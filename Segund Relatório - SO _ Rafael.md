	Semana 3 \- Bootstrapping e Processos de Instalação

UNICID \- Universidade Cidade de São Paulo

Disciplina: Sistemas Operacionais

Professor: Clóvis José Ramos Ferraro

Grupo 13

					Introdução

Para começar o relatório do tema proposto, começaremos com a diferença entre UEFI e BIOS, a BIOS busca um HD no formato antigo com o formato MBR. Caso esteja configurado no UEFI, a busca é realizada no formato GPT, o formato atual com principais vantagens como a inicialização rápida da BIOS. Já o UEFI, é considerado o sucessor da BIOS com a mesma função mas com sua tecnologia mais avançada.

				Desenvolvimento

Neste desenvolvimento, vamos falar sobre o processo de instalação do Linux com o Inicializador GRUB e suas partições MBR, GPT e RAID. O computador é ligado com o carregamento do bootloader do MBR e carrega o kernel a partir do disco e gera o processo INIT no qual inicia os demais processos. O GRUB possui 3 estágios de inicialização que são a busca de um dispositivo executável, o menu de configurações e o carregamento na memória RAM com o controle do kernel. A sua configuração começa a partir do HD sem discriminação entre discos IDE ou SCSI ou entre as partições primárias ou lógicas. As principais partições utilizadas na instalação de um sistemas operacional são o MBR e GPT, o MBR sendo a BIOS e o GPT sendo o UEFI em que ambos solucionam o mesmo problema com a BIOS e o MBR sendo mais antigos ainda usados em diversos problemas e com o GPT e o UEFI sendo mais novos definindo o bootloader com a estrutura das partições em suas unidades de disco mostrando por onde começar e por onde terminar e se há algum sistema operacional instalado (Ex: Windows ou Linux). Em termos de comparação, a MBR nos permite criar até 4 partições primárias e criar novas partições lógicas com mais unidades de 32 bits para guardar informações além do tamanho máximo das partições de 2 terabytes, o GPT que possui 64 bits permite partições de até 10 terabytes com mais possibilidades de criar partições virtuais. Já o RAID, por exemplo, o RAID-1, junta-se dois HDs de forma espelhada sem junção do armazenamento de ambas as unidades. Porém, oferece mais segurança, com o outro disco assumindo o lugar do primeiro disco em caso de falhas onde ocorre a substituição de um dos discos para o uso dos arquivos.

Conclusão

Como conclusão deste relatório, nos aprofundamos mais na sobre os procedimentos de instalação de uma máquina virtual utilizando o Linux sem o risco de danificar o sistema do computador prejudicando não apenas a máquina, mas também o usuário, com o mal funcionamento e o custo de reparo. Para evitar o prejuízo, verifique se o seu hardware possui compatibilidade antes de qualquer configuração ao fazer a instalação do sistema operacional como o HD, o processador e verificar se sua partição é MBR ou GPT para não agravar os problemas de instalação no seu computador.

