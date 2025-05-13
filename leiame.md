TUTORIAL PARA CONSEGUIR ABRIR

1º instalar o jekyll e o ruby(O ruby de preferência usa o RBENV para baixar, melhor para gerenciar versões)
JEKYLL- https://jekyllrb.com/docs/- :

1ºInstall the jekyll and bundler gems.

gem install jekyll bundler

2ºCreate a new Jekyll site at ./myblog.

jekyll new myblog

3ºChange into your new directory.

cd myblog

4ºBuild the site and make it available on a local server.

bundle exec jekyll serve OU bundle exec jekyll serve --livereload (para atualizar automatico a pag após editar codigo)
_____________________________________________________________________

COMO EDITAR / ONDE

OBS: alguns arquivos estão com nomes meios estranhos para oq eles realmente fazem, a causa é que n quiz mexer em alguns nomes para não quebrar o codigo em algum ponto muito escondido. Vou listar esses arquivos seguindo o modelo NOME DO ARQUIVO - OQUE ELE É

portfoloio_grid - infraestrutura 
/img/portofolio - /imgs/infraestrutura
_____________________________________________________________________
ARQUIVOS CONTACT
os arquivos contact foram ocultados da pagina, não apaguei eles pois por algum motivo não roda o site se exluir
_____________________________________________________________________

OUTROS ARQUIVOS  

demais arquivos tem seus nomes corretos footer = controla parte baixa do site(localização, github etc...), modals = controla o modelo dos posts, header = controla parte alta do site(nome do lab etc...)
_____________________________________________________________________

COMANDOS DE TEXTOS NO MARKDONW(posts)

para escrever titulos se usa # , quanto mais # menor o titulo 

para escrever textos normais, apenas escrever, (caso o paragrofo ficar do lado da img de um enter para dar uma linha entre o codigo da img e o texto)

para colocar img é <img src="{{ site.baseurl }}/img/portfolio/nomedoarquivo.png" alt="Foto do drone em ação" style="width: 80%; max-width: 600px; height: auto; border: 1px solid #ddd;">

____________________________________________________________________

CSS E CONFIG GERAIS

quase todos os CSS estão no /includes/css/main

algumas cores estão setados como secundarias e primarias para configuar essas cores vá até _config.yml e ache o color

outras config como título principal etc... tbm estão em config.yml
