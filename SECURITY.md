# Política de segurança

O Pauta é um aplicativo estático: roda inteiro no navegador, não tem servidor próprio e guarda os dados no
`localStorage` do aparelho.

## Sincronização pelo GitHub (opcional)

Se você ativar a sincronização, o app usa um **token do seu GitHub** para guardar uma cópia dos dados em um Gist.
Para usar com segurança:

- Crie o token com a **menor permissão possível**: apenas **`gist`**. Nunca marque `repo` ou outras permissões.
- Prefira um token com **data de validade** e apague-o se perder o aparelho.
- O token fica salvo **no navegador onde você o digitou**. Não ative a sincronização em computadores de outras pessoas ou públicos.
- **Nunca** cole o token em issues, prints ou no código.

## Encontrou um problema?

Abra uma [issue](../../issues) sem detalhes sensíveis ou use **Security → Report a vulnerability** neste repositório.
