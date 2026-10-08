# Eva Flow · Fluxos operacionais

Página de apresentação do **Eva Flow**, sistema de separação de pedidos da **Eva Connect**, com uma demonstração completa que roda no navegador, sem servidor e sem banco de dados.

## Arquivos

| Arquivo | O que é |
|---|---|
| `index.html` | Página de apresentação do produto |
| `demo.html` | O sistema completo em modo demonstração, com dados de exemplo |
| `assets/` | Logo e imagens das telas |

## Publicar no GitHub Pages

1. Crie um repositório (por exemplo `eva-flow`) e envie estes arquivos para a raiz.
2. No repositório, abra **Settings › Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em um ou dois minutos o site fica disponível em `https://SEU-USUARIO.github.io/eva-flow/`.

## Acessos da demonstração

| Área | Usuário | Senha |
|---|---|---|
| Vendas | Ana ou Bruno | `demo123` |
| Estoque | Carla ou Diego | `demo123` |
| Administração | — | `admin123` |
| Painel da TV | `demo.html#tv` | — |

Os dados da demonstração ficam só no navegador de quem está testando (localStorage). Abas abertas no mesmo navegador se atualizam juntas: dá para deixar o Estoque numa aba, a TV em outra e simular vendas. O botão **Restaurar dados** volta tudo ao exemplo original.

## Observações

- A demonstração não envia nada para servidor nenhum e não contém dados reais de clientes.
- Para trocar o e-mail de contato, procure `adm@evaconnect.com.br` no `index.html`.
- Visual nas cores da Eva Connect (roxo, lilás e branco), fonte Plus Jakarta Sans (Google Fonts).
