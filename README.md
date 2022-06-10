# Biblioteca-Online

https://user-images.githubusercontent.com/102496892/172972166-d534254f-6277-4da5-be5b-47487a933c04.mov

Site de apresentação de livros literários focado em responsividade para os principais tamanhos de tela (mobile, tablet e desktop).
Utilizei medidas relativas como vw para definir não somente a largura de algumas imagens como também o font-size dos títulos das sections para que eles ficassem proporcionais ao tamanho da largura da tela.
No mobile as imagens ocupam 100% da largura da tela, fazer isso foi um pouco problemático com os paddings da classe "container", e a solução que encontrei foi não usar essa classe nas sections "autores" e "destaques", e fazer os ajustes de espaçamento pelas classes específicas dessas partes. As imagens podem ter uma largura máxima de 465px;
Em uma tela de 1024px de largura são exibidas duas imagens lado a lado, e em telas maiores podem ser exibidas todas as imagens horizontalmente por section.
A apresentação do cabeçalho é alterada em telas de 374px ou menores para poupar o espaço horizontalmente, deixando o menu de navegação abaixo do título do site.
A biblioteca AOS foi utilizada para gerar as animações exibidas pelas imagens tanto dos livros como dos autores.

Utilizei também tags semânticas como figure, cite e address, além de aplicar as funções tel: e mailto: ao número e email de contato na última section do site;

https://user-images.githubusercontent.com/102496892/172972762-a2878481-2998-43f9-871f-95e3734bc361.mov
