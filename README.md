Olá, o objetivo era transformar o layout do Figma em uma página WEB, para tal, foram usados:

- HTML: Esqueleto da página
- CSS: Estilização, dividida em micro arquivos
- Javascript vanilla(puro): Para dar vida a uma ou outra funcionalidade

Não foram utilizados frameworks, apenas essas tecnologia.

-------------

No início da estrutura HTML, verá um série de imports de CSS, começando por:

- Reset.css: Usado para resetar algumas configurações específicas de tags, para facilitar o trabalho. É o primeiro a ser carregado e pode ser sobrecrito por outros arquivos, que vierem posteriormente.
- Uma série de arquivos css, que vão desde componentes e partes específicas do layout, como profile (referente a foto de perfil, profissão e botão meu perfil), até a seção de new post (toda a estilização de um post, igual ao do Cazé)...
- O último arquivo CSS sempre será o da estrutura da página, sendo 'courses-page.css' o arquivo para página de layout e 'rede.css' o arquivo para página de posts/redes. É importante que este seja o último pois terá poder de sobrescrever todos os anteriores, adaptando por exemplo, componentes... caso necessário. 
É nele que você encontrará como o esqueleto da página foi desenhado.


Para facilitar a manutenção no código, inseri comentários sobre o quando um novo arquivo de CSS começa a interferir na página, assim, saberá exatamente em qual arquivo mexer... Fiquem a vontade caso queiram alterar a organização das pastas, basta alterar no index o novo diretório e tudo funcionará normalmente...

Uma segestão: o projeto não possui um título principal da página (h1), ao menos não destacado no Figma. Semanticamente é importante inserir, por conta de mecanismos de busca, ferramentas de leitura do navegador e acessibilidade... 

Um abraço!