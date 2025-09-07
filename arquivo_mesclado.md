RELATÓRIO DO PROJETO

MÓDULO 2  
 VIRTUALBOX E VMWARE

Disciplina: Sistemas Operacionais  
Professor: Clóvis Ferraro  
Grupo: 13  
**Sumário**  
1\. Introdução  
2\. Metodologia  
3\. Comparação entre os Sistemas Operacionais  
   3.1 Windows  
   3.2 Linux  
   3.3 Android  
   3.4 Comparação Crítica  
4\. Análise Crítica  
5\. Conclusão  
6\. Autoavaliação  
7\. Referências

**1\. Introdução**  
Em nosso meio se torna comum estarmos cercados por sistemas operacionais e no geral nem mesmo percebemos que eles estão ali, tão pouco tamanha importância de cada um deles. Neste módulo iremos ver em primeira mão qual a diferença de cada um deles em suas pequenas configurações e desenvolvimentos ao pedirmos para subir comandos específicos, suas funções e principalmente a resposta de cada um deles.

**2\. Metodologia**

Primeiro devemos fazer a instalação da nossa máquina virtual onde iremos realizar nossos testes, o modelo utilizado foi o VMware workstation pro bastando apenas procurar em seu navegador VMware workstation download lembrando que para baixar o VMware o computador precisará ter: um hardware compatível processador de 64 bits com, 4GB de RAM e 1.2GB de espaço livre.
A configuração de hardware virtual para VM foi ajustada para um desempenho razoável, tipo 2GB de RAM e 20GB de disco, mas isso pode variar.

Depois de tudo instalado, comecei a testar os prompts de comando. No Windows, pesquisei por “Prompt de Comando” e testamos os comandos *tasklist, date /t, time /t, e ipconfig*. 

Já no Ubuntu, para testar os comandos precisamos ir no botão de menu inicial e clicar em “Terminal”, e então testei os mesmos comandos do Windows, mas no Ubunto eles são: *top, date* e *ip a*.

Por fim, no Android, para testar os comandos é preciso apertar *alt \+ f1* para ativar o prompt de comando, pois não tem um botão para acessá-lo. E então testei os mesmos comandos, *top, date* e *ip addr*.

**3\. Comparação entre os Sistemas Operacionais**  
**3.1 Windows**
* date /t: mostra a data;  
* time /t: mostra a hora;  
* whoami: mostra informação do usuário da conta;  
* hostname: Mostra o nome do computador;  
* tasklist: mostra todos os arquivos em funcionamento naquele determinado momento no computador;  
* dir: mostra todas as pastas do diretório que o cmd esta;   
* ipconfig:mostra o ip e a configuração da rede em que seu computador está;  
* ping [google.com](http://google.com): envia dados pro servidor da Google para medir tempo de resposta e qualidade da rede.

        

**Imagens dos códigos e funcionamento:**

![][image1]

![][image2]

![][image3]

**3.2 Linux**

Comando *top* para mostrar os processos:

![][image4]

Comando *date* para mostrar data e hora:

![][image5]

Comando *ip a* para mostrar as configurações de rede do computador:

![][image6]

**Android** 

No sistema android x86 para acessarmos o prompt de comandos precisamos pressionar a tecla alt \+ f1 logo em seguida já temos algumas similaridades pois para vermos nossa lista de arquivos utilizamos o comando **ls** igual no linux. 

![][image5]

Já para vermos a versão do sistema atual temos o comando igual linux também chamado **uname \-a**  e **ps** para mostrar os processos. 

**![][image6]**

**3.4 Comparação Crítica**
Em grande parte todos os sistemas tiveram uma rápida resposta ao colocarmos os programas, porém, o android é o mais complicado para se entender a cadeia do comando, mesmo os mais básicos, podemos dizer que em grande parte, consegui enxergar comandos iguais mas entre o windows com relação ao linux e o android com relação ao linux o'que deixa evidente a presença de linux nos outros sistemas operacionais mesmo que minimamente. Poderia dizer que o linux foi o único a apresentar algo quase gráfico em seu terminal de comando, o que chamou minha atenção.

**Linux**

podemos pontuar que o linux é um sistema estável, possui uma gama de variedades de personalização e ambiente agradável, mas por outro lado apresenta um grau de aprendizagem não tão amigável para aquelas pessoas que não estão familiarizados com o sistema é mais recomendado para pessoas já experientes em manusear diversos sistemas operacionais diferentes. podendo ser visualmente representado abaixo;

![][image7]
**Preço:** o sistema Linux é uma ferramenta Gratuita;

**Vantagens:** 
Está disponível gratuitamente para uso pessoal e profissional;
O processo de configuração no Ubuntu, especialmente para testes é fácil;
O Ubuntu fornece uma interface de usuário fácil;
Na maioria das vezes, os usuários podem evitar o incômodo da instalação de drivers com este Sistema Operacional.
Quando o Sistema Operacional Ubuntu precisa ser atualizado, os usuários não precisam reiniciar a máquina, pois as atualizações podem ser facilmente executadas em segundo plano. Isso, por sua vez, faz com que o Ubuntu seja a escolha preferida para serviços como o Server.
**Desvantagens:** 
Os usuários precisam ter conhecimento técnico para usar o Ubuntu. Usuários que não estão familiarizados com a linha de comando encontrarão dificuldades para usar o Ubuntu;
A outra desvantagem do Ubuntu é que o suporte para alguns dos componentes de hardware e aplicativos de software não corresponde ao padrão fornecido pelo Windows;
Ubuntu também não suporta alguns dos softwares populares como Photoshop ou MS Office. No entanto, existem alternativas disponíveis para este software no Ubuntu, mas a experiência para o usuário não é a mesma do Windows.



**Windows** 

O sistema windows possui uma compatibilidade com ampla variedade de software e hardware, é um sistema mais fácil de ser utilizado se compararmos com o linux tem interfaces amigáveis, porém apresenta também menos estabilidade e segurança comparado ao linux e um consumo alto de recursos do sistema. podendo ser visualmente representado abaixo. 

![][image8] 
**Preço:** O sistema operacional Windows tem por sua vez um tempo de ultilzação gratuito limitado e apos esse tempo eles te cobram uma licença.

![alt text](image.png)

**Vantagens**
O Windows fornece uma interface suave, fácil e fácil de usar;
O Windows é conhecido por sua compatibilidade como Sistema Operacional e é capaz de suportar a maioria dos aplicativos;
No caso de um usuário encontrar um erro no Windows, os detalhes do erro não são completamente vistos para o usuário. Se um usuário não é tecnicamente sólido, o erro ainda será compreendido, ao contrário de outros sistemas operacionais onde os detalhes do erro parecem estranhos para o usuário se eles não são bem versados com essas palavras e códigos de erro;
O processo de instalação do Sistema Operacional Windows é simples e fácil de acompanhar.
**Desvantagens**
Uma das grandes desvantagens do Windows é que ele é não é livre para usar;
Os usuários precisam pagar um preço, mesmo que queiram atualizar para a versão mais recente do Windows;
O Windows tem a alto índice de consumo (quase o dobro) de recursos de máquinas de computador como RAM quando comparado ao Ubuntu;
A experiência do usuário pode ser impactada se o computador tiver uma RAM baixa e usar o sistema operacional Windows;
As opções de personalização no Windows são muito poucos e se limitam a wallpaper, fundo, sons de notificação, ícones, temas, etc.

**Android**

Por sua vez o android já é um sistema amplamente adaptável e mais estável se comparado ao windows  interface bem amigável e possui um controle maior de permissões aumentando por consequência sua segurança, mas por outro lado possui uma dependência maior dos serviços do Google e possui atualizações lentas em diversos dispositivos. podendo ser visualmente representado abaixo.

![][image9]

**Preço:** O sistema Android tambem é um sistema gratuito assim como o Linux.

**Vantagens:**
Código aberto;
Variedade de dispositivos;
Liberdade de customização;
Grande variedade de aplicativos;
Maior integração com os serviços do Google.

**Desvantagens:**
Falta de padronização;
Falta de otimização;
Fragmentação de versões do sistema;
Aplicativos desnecessários;
Desvalorização dos dispositivos.


**4\. Análise Crítica**
 **Segurança entre os sistemas:** A segurança entre os sistemas é uma preocupação crescente entre varios setores de tecnologia com tantas vulnerabilidades crescentes no mundo da computação, seja ela um erro dado pelo hardware do computador como o Meltdawn ou o Spectre ou o do proprio sistema com a frequente tentativa de mals elementos tentando conseguir nossos dados mais sigilosos temos a preocupação de pensar "será que nossos aparelhos informaticos estão seguros com nossos supostos sistemas operacionais ?", bem o IBSEC, (Instituto Brasileiro de Cibersegurança), nos da uma resposta um tanto preocupante:

![tabela de vulnerabolidades dos sistemas operacionais](<tabela de segurança.png>)

Como vemos na tabela, o sistema Android é oque mais possui vulnerabilidades mesmo que de todos eles p sistema seja por si so o que mais tem acessibilidade a arquivos pessoais e de maior importancia como sistemas de banco, documentos digitais e entre outros.
Vale lembrar que o sistema Linux Ubuntu ao qual estamos analisando nesse projeto não se encontra no rank porem suas taxas de vulnerabilidade analisadas no mesmoo periodo desse rank é de 1047 sendo o segundo mais vulneravel entre nossos tres sistemas estudados e por fim o windows 10 ficando com uma taxa de 490.
Tanto o Ubuntu quanto o Windows 10 possuem uma integração de antivirus, porem o sistema de antivirus do wondows 10 é frequentemente atualizado, sendo atualizado 3 vezes apenas esse ano!


**Vantagens de valores:** Entre os tres sistemas operacionais o windows 10 é o unico pago entre todos, uma licenca do windows 10 pode vir a custar R$1599,00.

**Privacidade:** Segundo o site https://www.softwaretestinghelp.com/ubuntu-vs-windows :"Em comparação com o Windows, o Ubuntu está muito à frente em termos de estar centrado na privacidade. Os dados confidenciais dos usuários não são coletados pela maioria das distribuições baseadas em Linux e os usuários têm a opção de desativar qualquer recurso desse tipo com qualquer grau de risco que seja. O Windows, por outro lado, não é tão centrado na privacidade.

A maioria dos recursos que podem ser considerados como violando a privacidade dos usuários, não podem ser desativados. No entanto, existem muitas outras opções que podem ser habilitadas ou desabilitadas a critério do usuário."

Já o sistema android tem um sistema de limites de privacidade ao qual você decide quais tipos de dados quer ou não compartilhar, um controle de acesso a localização, configuração de acesso aos aplicativos fora de uso e entre outras ferramentas facilmente encontradas nas configurações do seu aparelho.

**Interface:** As Interfaces de todos os Sistemas operacionais são bem diferentes uma da outra, isso é um visualizado facimente na tela principal de qualquer sistema oeracional, na sua tela de instação e ao decorrer de cada ação feita por nos no sistema. 
 - Windows 10: Se tratando do Windows, vemos a facilidade em que eles distribuem os botões dando a qualquer um mesmo com pouca familharidade em computação um acesso mais pratico ao aplicativos e funcionalidades, deixando tudo muito otimizado;
 - Ubuntu: Mesmo sua interface sendo mais veloz e mais divertida com suas bordas arredondadas, um contraste visivel de diferenciação com o windows, ainda é um pouco complicado encontrar certos recursos, tem um estilo semelhante ao Mec IOS com relação a alguns icones, suas cores quentes dão um apelo a atenção em certos detalhes do sistema.
 -Android: ao entrar no sistema temos uma visão clara de sua integração ao Google.com, um facil acesso aos aplicativos e a instalação dele, é interativo mesmo que a dificuldade para pessoas com mais idade seja maior em comparação ao publico mais jovem.

**Acessibilidade:** Falando de recursos de acessibilidade para pessoas com deficiencia, é importante ter em mente que a inclusão com pessoas com deficiencias e de suma importancia sejá em sites, aplicativos e principalmente nos sitemas operacionais.
 - Windows: o sistema windows conta com alguns sistemas de acessibilidade, podendo ser acessado pela tecla Windows+u, esses sistemas são:
    leitor de tela;
    Foco;
    Ferramentas de destreza e mobilidade;
    Sistemas de texto para pessoas com problemas auditivos;
    Facilitadores visuais;
    Entre outras.
 - Linux: Para o Linux, não temos muita diferença do comum, mas a abrangencia ainda é impressionante, como esta colocado em seu site prorpio, tais ferramentas são:
    Deficiências visuais;
    Lendo a tela em Braille;
    Lendo a tela em voz alta;
    Ajustando o contraste; 
    Alterando o tamanho do texto na tela;
    Ampliando uma área da tela; 
    Fazendo o cursor de teclado piscar; 
    Piscando a tela para sons de alerta; 
    Ajustando a velocidade do mouse e do touchpad; 
    Clicando e movendo o cursor do mouse usando o teclado; 
    Ajustando a velocidade do clique duplo; 
    Simulando cliques por flutuação; 
    Simulando o clique com o botão direito do mouse; 
    Ativando as teclas lentas; 
    Ativando teclas de aderência; 
    Ativando teclas de repercussão; 
    Gerenciando pressionamentos repetidos de teclas; 
    Navegação do teclado; 
    Usando um teclado em tela. 

 -Android: Já no sistema android temos uma interação não tão abrangente quanto o sistema ubuntu, porem, com focos importantes em cada uma das ferramentas:
    Usar um leitor de tela com o TalkBack;
    Mudar tela;
    Controles de interação para usar no dispositivo;
    Usar uma linha braille;
    Usar a Lupa do Pixel;
    Legendas;
    Áudio;
    Explorar apps e serviços de acessibilidade do Android;
    Projetar e desenvolver apps mais acessíveis;
    Mais ajuda.

**5\. Conclusão** 
Para podermos finalizar as comparações  vale a pena mencionar que para realizar esse processo todo o uso das VM se mostrou de extrema importância, pois proporcionou um ambiente de teste seguro sem afetar a máquina principal, falando agora do desempenho dos sistemas pode-se dizer que o linux é mais recomendado para aqueles que já estão familiarizados com seu funcionamento, já o android e windows é mais recomendado para diversos tipos de pessoas seja elas experientes ou não por justamente serem sistemas com maior facilidade de acesso.

**6\. Autoavaliação de cada integrante**
    **Primeiro integrante:**"Durante o projeto, enfrentei algumas dificuldades e imprevistos, principalmente devido à pouca experiência com determinados comandos e processos de instalação, para os meus colegas teve também problemas com instalação. Para superar os desafios, consultei fontes externas e procurei absorver o máximo possível do conteúdo proposto. Apesar dos obstáculos, reconheço que ainda há muito a ser estudado e explorado."

**Segundo integrante:**"Posso dizer que não fui o melhor fazendo esses testes mas tentei me esforçar para entregar um trabalho digno, tive bastante dificuldade em baixar os sistemas operacionais e a VM propriamente dita por ser minha primeira vez mexendo com esse tipo de coisa  mas fui atrás de ajuda, seja por meio de amigos que me ajudaram ou por meio de video aulas que ajudaram a configurar tudo, de maneira geral acho que eu me daria uma nota por volta de 7/10"

**Terceiro integrante:**"As principais dificuldades foram na parte da instalação e da
 configuração do Ubuntu por conta da falta de requisitos que meu
 computador atende para o uso do Linux Ubuntu, tirando estes problemas de
 configuração"

 **Quarto integrante:**"As dificuldades apresentadas a mim por meus colegas e algumas vividas por mim foram em instalações, nem todos conseguiram baixar os sistemas ou travar muito antes de realmente fazer conseguir concluir.  
Na minha avaliação, não tive dificuldades até o presente módulo do projeto."

 **Quinto integrante:**"Eu tive bastante dificuldade com as instalações, meu notebook não ajudou pois ele é muito antigo e muito lento, com isso precisei usar o computador do meu irmão. Para instalar os programas precisei pesquisar bastante, assisti aos vídeos no YouTube e precisei da ajuda de meus colegas. Demorou algumas horas para a conclusão da instalação do sistema Ubuntu."

 **7\. Referências**

https://www.hostmidia.com.br/blog/ubuntu-pode-substituir-o-windows-10/

https://www.reddit.com/r/Ubuntu/comments/z2a9jh/ubuntu_is_way_way_better_than_windows_10/?tl=pt-br

[https://www.youtube.com/watch?v=6PCx0lp3lMA](https://www.youtube.com/watch?v=6PCx0lp3lMA)

[https://www.youtube.com/watch?v=-53VraH-Otc](https://www.youtube.com/watch?v=-53VraH-Otc)

[https://www.youtube.com/watch?v=M-TTEVVNoXA](https://www.youtube.com/watch?v=M-TTEVVNoXA)

[https://www.youtube.com/watch?v=RGtoeZ1vof8](https://www.youtube.com/watch?v=RGtoeZ1vof8)

https://www.youtube.com/watch?v=wf_rjTrbBpw&t=466s

https://www.youtube.com/watch?v=YFzVQ7KLPvE&t=8s

https://www.youtube.com/watch?v=CT6BZBzbpWA&t=19s

https://www.youtube.com/watch?v=7cMItENCXkw&t=427s

https://www.ibm.com/br-pt/think/topics/linux

[https://www.hostinger.com/br/tutoriais/comandos-linux](https://www.hostinger.com/br/tutoriais/comandos-linux) 

[https://youtu.be/JEhVB4VHsTI?si=cecf3w9eCjamk2\_L](https://youtu.be/JEhVB4VHsTI?si=cecf3w9eCjamk2_L)

[https://youtu.be/RGtoeZ1vof8?si=1PLow16mv9CnDBfh](https://youtu.be/RGtoeZ1vof8?si=1PLow16mv9CnDBfh)

[https://4linux.com.br/o-que-e-linux/](https://4linux.com.br/o-que-e-linux/)

[https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-a-virtual-machine/](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-a-virtual-machine/)  

[https://www.hostinger.com/br/tutoriais/comandos-linux](https://www.hostinger.com/br/tutoriais/comandos-linux)  

https://dtnetwork.com.br/comandos-basicos-do-cmd  

[https://plus.diolinux.com.br/t/usando-terminal-no-android-termux/42225](https://plus.diolinux.com.br/t/usando-terminal-no-android-termux/42225)  

[https://pt.scribd.com/document/502780683/Google-Hacking-1-1](https://pt.scribd.com/document/502780683/Google-Hacking-1-1)  

[https://www.tudocelular.com/google/noticias/n233845/google-muda-requisitos-minimos-android.html](https://www.tudocelular.com/google/noticias/n233845/google-muda-requisitos-minimos-android.html)  

[https://help.involves.com/hc/pt-br/articles/360007453371-Requisitos-técnicos-para-smartphones-e-tablets](https://help.involves.com/hc/pt-br/articles/360007453371-Requisitos-técnicos-para-smartphones-e-tablets)  

[https://support.microsoft.com/pt-br/windows/requisitos-do-sistema-do-windows-10-6d4e9a79-66bf-7950-467c-795cf0386715](https://support.microsoft.com/pt-br/windows/requisitos-do-sistema-do-windows-10-6d4e9a79-66bf-7950-467c-795cf0386715)  

[https://help-ubuntu-com.translate.goog/community/Installation/SystemRequirements?\_x\_tr\_sl=en&\_x\_tr\_tl=pt&\_x\_tr\_hl=pt&\_x\_tr\_pto=tc](https://help-ubuntu-com.translate.goog/community/Installation/SystemRequirements?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc)

https://www.softwaretestinghelp.com/ubuntu-vs-windows

https://www.tudocelular.com/google/noticias/n36150/confira-5-vantagens-e-desvantagens-do-android.html

https://www.tudocelular.com/seguranca/noticias/n153436/android-recordista-em-falhas-de-seguranca-brecha-hackers-em-2019.html

https://ibsec.com.br/10-sistemas-operacionais-com-mais-cves

https://learn.microsoft.com/pt-br/defender-endpoint/msda-updates-previous-versions-technical-upgrade-support

https://www.android.com/intl/pt_br/safety/privacy

https://support.microsoft.com/pt-br/windows/descobrir-funcionalidades-de-acessibilidade-do-windows-8b1068e6-d3b8-4ba8-b027-133dd8911df9
https://help.ubuntu.com/stable/ubuntu-help/a11y.html.pt-BR

https://support.google.com/accessibility/android/answer/6006564?hl=pt-BR