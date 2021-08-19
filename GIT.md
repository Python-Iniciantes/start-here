## O que é Git?  
Em termos simples, ele é o que chamamos de Sistema de Controle de Versão Distribuído. Isso significa que você pode registrar alterações em um arquivo ou conjunto de arquivos ao longo do tempo para que você possa recuperar versões específicas posteriormente. Deixando mais claro: caso você estrague um arquivo, perca dados ou queira reverter uma alteração qualquer, pode facilmente fazer isso usando o Git.    
<br>
Além do que foi dito, existe a vantagem de que várias pessoas podem trabalhar em partes diferentes do mesmo sistema sem a preocupação de uma prejudicar o trabalho da outra. Algo que é extremamente importante quando falamos de projetos grandes e com muitas áreas envolvidas.

## Como funciona?  
O controle de versão é composto por duas partes: o **repositório** e a **área de trabalho**. O repositório armazena todo o histórico de evolução do projeto, registrando toda e qualquer alteração feita em cada item versionado.  
<br>
O desenvolvedor não trabalha diretamente com os arquivos do repositório, mas sim em uma área de trabalho onde se encontra a cópia do projeto. Ela é monitorada para identificar mudanças realizadas.   
<br>
No caso particular do Git as coisas são um pouco mais complexas, afinal, como já foi citado, ele é distribuído. Isso quer dizer que cada um no projeto vai ter seu próprio repositório e sua própria área de trabalho. E sim, isso pode ser tão complicado quanto parece.  
<br>
Imagine a seguinte cena: três pessoas estão criando um site, cada uma atuando em uma área, mas vez ou outra precisando mexer no arquivo dos outros. O problema é que cada desenvolvedor tem seu repositório único, na sua máquina, e seria no mínimo inconveniente ter que ficar trocando de computador cada vez que precisasse alterar um arquivo. Isso sem contar no que fariam para juntar todas as peças no final.   
<br>
Para resolver esse problema, todas as máquinas e seus repositórios (também chamado de **repositórios locais**) devem estar conectados a um repositório principal (chamado de **repositório remoto**). Sempre que fazemos alterações substanciais no local enviamos para o remoto, logo todos os outros que estão envolvidos no projeto podem baixá-las.    
<br>
A principal ferramenta hospedagem e gerenciamento de repositório remoto que temos hoje é o **GitHub**.   

***
#### Fontes:
https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control  
https://github.com/xdvrx1/what-is-github  
https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/  
https://blog.pronus.io/posts/controle-de-versao/conceitos-basicos-de-controle-de-versao-de-software-centralizado-e-distribuido/  
<br>
#### Créditos:
 - Pesquisa: Daniel Neto
 - Tradução e Adaptação: Smith

