# Instalação #

## Antes de mais nada: ##

Antes de instalar o UTFPRtex certifique-se de você tem uma distribuição LaTeX instalada e funcionando em seu ambiente de trabalho.

Você pode instalar o UTFPRTeX de duas maneiras, veja abaixo:

### A partir do download do arquivo compactado ###

  * Baixe na página inicial deste projeto o arquivo .zip com a versão mais recente do UTFPRTeX;
  * Uma vez baixado o arquivo, descompacte-o em uma pasta exclusiva;
  * Entre no menu de configurações (_settings_) do MiKTeX (Menu iniciar/programas/MiKTeX 2.X/Maintenance (Admin)/Settings (Admin));
  * Na aba _Roots_ clique no botão _Add_ e adicione a pasta onde você descompactou o UTFPRTeX;
  * Volte para a aba _General_ e clique nos botões _Refresh FNDB_ e _Update Formats_.

Pronto, o MiKTeX já sabe onde está o UTFPRTeX.


### A partir do SVN ###

Você pode também baixar o UTFPRTeX a partir do repositório [SVN](http://pt.wikipedia.org/wiki/Subversion) deste projeto. A vantagem deste método é que você sempre baixará a versão mais recente do UTFPRTeX. Além disso, com um [sistema de controle de versões](http://pt.wikipedia.org/wiki/Sistema_de_controle_de_vers%C3%A3o) você pode facilmente atualizar o UTFPRTeX. O procedimento básico é o seguinte:

  * Baixe e instale um programa cliente SVN. É recomendado o [Tortoise SVN](http://tortoisesvn.tigris.org/);
  * Crie uma pasta para o UTFPRTeX no seu computador;
  * Instalado o Tortoise SVN, abra o windows explorer e clique com o botão direito do mouse dentro desta pasta e selecione _SVN Checkout_;
  * Na janela que abriu, cole o seguinte endereço no campo _URL of reposiroty_:

> `http://utfprtex.googlecode.com/svn/trunk/`

  * Clique em _OK_ e espere o Tortoise conectar e baixar os diretórios e arquivos mais atuais do servidor;
  * Pronto, agora você já tem a versão mais atual do UTFPRTeX;
  * Entre no menu de configurações (_settings_) do MiKTeX (Menu iniciar/programas/MiKTeX 2.X/Maintenance (Admin)/Settings (Admin));
  * Na aba _Roots_ clique no botão _Add_ e adicione a pasta que você criou anteriormente e agora contem o UTFPRTeX;
  * Volte para a aba _General_ e clique nos botões _Refresh FNDB_ e _Update Formats_.

Pronto, o MiKTeX já sabe onde está o UTFPRTeX.

Se você quiser usar um cliente SVN na linha de comando do Windows (ou Linux), baixe os binários do SVN no site http://subversion.tigris.org/ e após instalar, utilize a seguinte linha de comando:

`svn checkout http://utfprtex.googlecode.com/svn/trunk/ utfprtex-read-only `


# Testando ou Criando Seu Primeiro Documento #

Atenção: os exemplos de TCC e proposta de TCC estão na pasta docs do UTFPRTeX. Para que os exemplos funcionem corretamente, não os edite diretamente na pasta do modelo. Copie os arquivos para outra pasta específica para seu documento, sendo essa não localizada na pasta do modelo.

# Obtendo Ajuda #

Consulte o google, por enquanto.