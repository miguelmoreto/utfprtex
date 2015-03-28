O UTFPRtex é um projeto de código aberto que visa desenvolver um modelo consistente e adequado para a elaboração de trabalhos acadêmicos da Universidade Tecnológica Federal do Paraná.

Este projeto vem sendo desenvolvido pelo prof. Miguel Moreto da UTFPR campus Pato Branco.


Características:

  * Geração automática dos elementos pré-textuais;
  * Numeração automática de páginas, figuras, tabelas, equações, etc.;
  * Geração automática de listas de siglas e símbolos;
  * Formatação das referências bibliográficas.

## Release Notes ##

**Versão 1.3.3**
  * Corrigido alinhamento dos títulos de seções até o nível 6.
  * No sumário agora aparece só até o nível 4.
  * Atualizado exemplo de resumo e abstract.
  * Corrigida a dedicatória.
  * Footnotes são exibidas em negrito.
  * Atualizados exemplos de proposta e TCC.
  * Inseridos exemplos com fontes nas figuras e tabelas.
  * Correção do termo de aprovação de TCC. O mesmo é atualizado automaticamente conforme tenha um ou dois autores.

Versão 1.3.2
  * Configuração da bibliografia no modelo de TCC foi mudada para não mais abreviar automaticamente os nomes dos autores. Todos os nomes são colocados por extenso na lista de bibliografias. Cabe ao usuário abreviar os nomes de forma adequada, mantendo por extenso apenas sobrenome e prenome, abreviando nomes do meio.

Versão 1.3.1:
  * Atualizada capa da proposta de TCC (corigido espaçamento desigual).
  * Atualizado o termo de aprovação de TCC.
  * Corrigidas as strings default dos comandos `\orientador` e `\coorientador`.

Versão 1.3:
  * Atualizado exemplo de TCC.
  * Modificado pacote de configuração de TCCs (utfprtexTCC.sty)
    * Incluido nele os comandos para montagem da folha de rosto e termo de aprovação.
  * Modificado modelo para inserir mais espaço entre o título do capítulo e o texto.    Por padrão esse espaço é de 2cm, mas pode ser modificado redefinindo o comando    `\espacoAfterChapter`. Por exemplo, para mudar para 3cm: `\renewcommand{\espacoAfterChapter}{3cm}`
  * Incluidos novos comandos para fornecer informações para montagem do termo de aprovação: `\bancaA`, `\bancaB`, `\bancaC`, `\bancaD` e `\atanumero`

## Downloads ##

Infelizmente o Google Code não permite mais hospedagem de arquivos para download. Então, baixe a última versão do Utfprtex na pasta do Google Drive através do seguinte link:

https://drive.google.com/folderview?id=0BywsLHa6z6DzWTYyQkxhcGplZU0&usp=sharing

## Instalação ##

Veja as instruções de instalação na página wiki:
https://code.google.com/p/utfprtex/wiki/getstarted

## Documentação ##




## Em desenvolvimento, aguarde! ##