# Conexão Missionária Global

Site estático pronto para GitHub Pages.

## Publicar
1. Crie um repositório no GitHub.
2. Envie `index.html` e a pasta `assets`.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione `main` e `/ (root)` e salve.

## Personalizar capas e leitura
O catálogo já contém os títulos mostrados na referência do site. Para inserir as capas reais:
- coloque os arquivos de capa em `assets/`;
- no array `books`, preencha `cover` com caminhos como `assets/criacao.jpg`;
- preencha `url` com o PDF ou página de leitura, por exemplo `livros/criacao.pdf`.

O banner inferior enviado foi incluído sem alterar sua composição, em `assets/banner-inferior.jpg`.

As mini logos originais e a ilustração PNG do personagem não estavam disponíveis como arquivos nesta solicitação. O cabeçalho e o personagem animado têm versões provisórias em CSS/emoji; substitua pelo arquivo da logo e do personagem quando os tiver na pasta `assets`.
