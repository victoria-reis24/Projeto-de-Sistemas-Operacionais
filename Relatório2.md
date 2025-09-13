

UNICID \- Universidade Cidade de São Paulo

Disciplina: Sistemas Operacionais

Professor: Clóvis José Ramos Ferraro

Grupo 13

**Introdução:**

Neste relatório temos como foco discutir e aprofundar mais sobre as diferenças entre UEFI, BIOS, MBR e GPT. Para iniciarmos a definição de cada um deles, precisamos deixar claro que MBR e GPT são formatos e formas que iremos armazenar nosso disco (HD ou SSD). O formato MBR seria o formato mais antigo, sendo possível trabalharmos em cima dele com no máximo um HD de até  2 teras, já por outro lado no formato GPT podendo proporcionar um limite extremamente maior de HD. É importante lembrar que dependendo da formatação que for utilizado seja ela GPT ou MBR só será possível trocar entre elas se formatamos o HD outra vez para o novo formato, podendo ser conferido o formato do disco atual através do prompt de comandos do windows por exemplo executando o comando “list disk”. Agora quando falamos sobre BIOS e UEFI estamos falando sobre como vamos configurar cada modelo sendo o BIOS representado pelo formato MBR e UEFI representado pelo formato GPT sendo possível trabalhar com BIOS no formato 8 bits e UEFI no formato 64 bits.

**Desenvolvimento:**

Para que possamos aprofundar ainda mais no assunto iremos retratar o processo de bootloader ou só boot que são os carregadores de inicialização que de maneira resumida o processo de boot acontece em etapas sendo elas: quando ligamos o computador a BIOS inicializa o hardware e carrega o bootloader do MBR, após isso o bootloader carrega o kernel do sistema operacional (modelo retratado seria o linux) a partir do disco e o sistema operacional gera um processo INIT que inicializa os demais processos. Agora iremos citar o bootloader mais conhecido o GNU GRUB conseguindo suportar todos os sistemas Unix e até sistemas windows. A sequência de inicialização do GRUB começa quando o MBR assume o controle dos processos, e dentro do MBR está localizado o primeiro estágio do GRUB que tem como função carregar o próximo estágio do grub, pois é um arquivo muito pequeno e simples cabendo apenas 512 bits, já no estágio 2 recebe o controle e disponibilizará um menu com opções dos sistemas que já estão instalados no computador, após esse passo o grub carregará na memória RAM o kernel do sistema selecionado do usuário. O GRUB pode ser configurado para oferecer ao usuário opções como: opções de carregamento do SO, alguns programas como testadores de memória etc..

**Conclusão:**

Para que podemos concatenar tudo que vimos podemos fazer um recap: vimos que existem alguns tipos de formatos que podemos utilizar para armazenarmos nossos dados, entre eles estão o MBR e o GPT e suas partições BIOS e UEFI respectivamente sendo o formato MBR um modelo mais antigo e com uma memória ou HD reduzida de apenas 2 teras já seu formato BIOS apresentando uma capacidade de 8 bits. E tendo como sua versão aprimorada o GPT que apresenta uma capacidade muito maior de armazenamento e seu formato UEFI com capacidade de 64 bits. Podemos também alterar e modificar tanto nossa capacidade e memória como escolher nosso SÓ através do GRUB que nada mais é que um programa capaz de escolher o sistema que o usuário irá utilizar seja ele qual for. Deve ser levado em consideração também a utilização de uma VM para realizar os testes de maneira segura sem prejudicar a máquina original.