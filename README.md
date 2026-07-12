# A Casa Fora de Casa — site público

Esta pasta contém apenas a versão pública do livro de Miguel Pinto. Não inclui ficheiros de curadoria, folhas de cálculo, notas de trabalho nem os nomes originais das fotografias.

## Ver antes de publicar

Abra `index.html` no navegador. No computador, o livro aparece em duplas; num telemóvel em posição vertical, aparece página a página.

## Publicar gratuitamente no GitHub Pages

1. Entre em [github.com](https://github.com/) e escolha **New repository**.
2. Dê ao repositório um nome simples, por exemplo `a-casa-fora-de-casa`.
3. Escolha **Public** e crie o repositório. Não é necessário adicionar modelo, licença ou outro ficheiro nesta fase.
4. No repositório, escolha **Add file → Upload files**. Primeiro arraste a pasta `assets` completa e confirme em **Commit changes**. Ela contém exatamente 100 imagens, o limite de um carregamento feito pelo navegador.
5. Volte a **Add file → Upload files**, carregue `index.html` e `README.md`, e confirme novamente em **Commit changes**.
6. Abra **Settings → Pages**.
7. Em **Build and deployment**, escolha **Deploy from a branch**.
8. Selecione a branch `main`, a pasta `/(root)` e carregue em **Save**.
9. Aguarde a publicação. O endereço ficará normalmente no formato `https://SEU-UTILIZADOR.github.io/a-casa-fora-de-casa/` e também aparecerá em **Settings → Pages**.

Documentação oficial: [carregar ficheiros num repositório](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository) e [publicar a partir de uma branch no GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Atualizar uma fotografia mais tarde

As imagens públicas estão em `assets/fotos/` e usam o número da página: `001.jpg` a `100.jpg`. Para corrigir uma imagem sem alterar o livro, substitua o ficheiro com o mesmo número. Por exemplo, a fotografia corrigida desta versão está em `assets/fotos/044.jpg`.

## Importante

- Mantenha `index.html` e a pasta `assets` na raiz do repositório, exatamente com estes nomes.
- Um repositório público e o respetivo site podem ser vistos e os previews podem ser descarregados por qualquer pessoa com o endereço.
- Não é necessário instalar qualquer plugin, serviço ou sistema de construção.
