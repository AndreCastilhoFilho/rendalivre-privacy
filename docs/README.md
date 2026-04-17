# Política de Privacidade (GitHub Pages)

Este diretório contém a página estática **`index.html`** usada como **Política de Privacidade** do app **Renda Livre**, para publicação na Google Play Console.

## Publicar com GitHub Pages

1. Envie este repositório para o GitHub (se ainda não estiver).
2. No repositório: **Settings → Pages**.
3. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
4. Selecione a branch principal (ex.: `main`) e a pasta **`/docs`**.
5. Salve. Em alguns minutos o site ficará disponível em:

   `https://<seu-usuario>.github.io/<nome-do-repositorio>/`

6. Abra essa URL no navegador e no celular para validar.
7. Na **Google Play Console**, em **Política de privacidade**, cole exatamente essa URL (HTTPS).

### Repositório só para a política (alternativa)

Se preferir um repositório separado (ex.: `rendalivre-privacy`), copie apenas o conteúdo de `docs/` para a **raiz** do novo repo, renomeando se necessário para ter `index.html` na raiz, e ative Pages com pasta **`/(root)`**.

## Antes de divulgar

- Revise o texto em **`index.html`** (especialmente data, descrição do app e alinhamento com o formulário **Segurança dos dados** da Play).
- Substitua ou complemente a secção de contato se quiser um e-mail explícito.
- Garanta que o que está escrito aqui é **verdadeiro** para a versão publicada do app.

## Checklist Play Console

- [ ] URL da política abre sem erro (HTTPS).
- [ ] Texto coerente com **Data safety / Segurança dos dados**.
- [ ] Mesmo app e pacote (`app.rendalivre`) referenciados na ficha.
