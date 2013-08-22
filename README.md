Github
======

Trabalho 1ºB
Modo de operação

   O RCS funciona apenas em arquivos individuais. Não há maneira de trabalhar com um projeto inteiro. Embora ele forneça ramificação para arquivos individuais, a sintaxe da versão é complicada. Em vez de usar ramos, muitas equipes usam apenas o mecanismo interno de bloqueio e trabalham em um único ramo cabeça (head).

 

Sucessores

CVS : Um sistema simples, chamado CVS, foi desenvolvido com a capacidade de lidar com arquivos RCS em massa, e este era o próximo passo natural da evolução deste conceito, uma vez que "transcende mas inclui" elementos de seu antecessor. CVS era originalmente um conjunto de scripts que utilizaram programas RCS para gerenciar os arquivos. Ele não faz mais isso, porém, atua diretamente nos arquivos.

PRCS : Um sistema posterior de nível mais alto, o PRCS,3 utiliza arquivos semelhante ao RCS mas nunca foi simplesmente um empacotador. Em contraste com o CVS, o PRCS melhora a compressão delta dos arquivos RCS usando Xdelta.

 

Vantagens

Em cenários monousuário, como arquivos de configuração do servidor ou scripts de automação, o RCS ainda pode ser a ferramenta de controle de revisão preferida, pois é simples e não há necessidade de repositório central para ser acessível para salvar revisões. Isto a torna uma ferramenta mais confiável quando o sistema está em condições de manutenção terríveis. Além disso, os arquivos de backup salvos são facilmente visíveis para a administração, desta forma a operação é simples. No entanto, não existem mecanismos internos de proteção contra adulterações (ou seja, os usuários que podem usar as ferramentas do RCS para a versão de um arquivo também, pelo projeto, são capazes de manipular diretamente o arquivo de controle de versão correspondente) e isso está levando alguns administradores conscientes à segurança a considerar os sistemas de controle de versão cliente/servidor que restringem a capacidade dos usuários para alterar arquivos de controle de versão.

 

Aplicação

Alguns mecanismos de wiki, incluindo TWiki e Foswiki, utilizam RCS para armazenar revisões de páginas.
