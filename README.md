# Teste das cadeias de substituição do D2L (sandbox)

Página estática só para testar se o Brightspace (D2L) substitui cadeias como `{UserId}` e `{FirstName}`
quando abre uma URL externa (widget com iframe ou link da barra de navegação).

- Endereço: `https://danillo-vidal.github.io/teste-cadeias-d2l/`
- Os valores chegam depois do `#` na URL, que não é enviado ao servidor do GitHub.
- A página não faz chamadas de rede, não salva nada e apaga os valores da barra de endereço depois de ler.

Uso apenas em sandbox. Não coloque aqui dados de alunos, tokens ou credenciais.

## Publicar

Settings › Pages › Build and deployment › Source: **Deploy from a branch** › Branch: **main** / **(root)**.

## Testar no D2L

A própria página mostra o código do iframe (widget) e a URL do link personalizado, já com o endereço certo.
