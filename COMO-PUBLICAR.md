# Como publicar no GitHub Pages (grátis, ~10 min)

1. Crie uma conta em github.com com o usuário **iberajunior** (o endereço final fica `https://iberajunior.github.io`).
2. Clique em **New repository** e dê o nome exato: `iberajunior.github.io`. Marque **Public** e crie.
3. Na página do repositório, clique em **uploading an existing file** e arraste tudo desta pasta, mantendo a estrutura:
   - `index.html`
   - `cv-iberajunior.pdf` (seu currículo; ao atualizar o CV, suba com esse mesmo nome)
   - a pasta `assets/` inteira (sua foto, o vídeo de fundo em MP4 e WebM e a imagem de capa do vídeo)

   Dica: arraste a pasta `assets` de uma vez, o GitHub mantém o nome da pasta.
4. Clique em **Commit changes**.
5. Vá em **Settings > Pages**, confira se a origem está em **Deploy from a branch / main / root**.
6. Em 1 ou 2 minutos o site estará no ar em `https://iberajunior.github.io`.

## Links úteis para candidaturas

- Versão em português: `https://iberajunior.github.io/?lang=pt`
- Versão em inglês: `https://iberajunior.github.io/?lang=en`
  (sem o parâmetro, o site escolhe o idioma pelo navegador do visitante)

## Para editar depois

No GitHub, abra `index.html`, clique no lápis (Edit), altere e salve com **Commit changes**. O site atualiza sozinho.

Cada texto tem as duas versões nos atributos `data-pt` e `data-en`. Ao editar um texto, altere os dois.

## Sobre as imagens

As imagens dos cases são carregadas direto do site da KROMA (agenciakroma.com.br/assets/img/...). Se um dia quiser deixar o portfólio independente, suba as imagens numa pasta `img/` do repositório e troque os endereços no `index.html`.
