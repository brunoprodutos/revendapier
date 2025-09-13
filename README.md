# Guia Rápido: Parceria Darede & Pier Cloud

Este projeto contém um guia rápido sobre a parceria estratégica entre Darede e Pier Cloud, destacando os produtos e diferenciais da plataforma FinOps.

## Sobre o Projeto

Website responsivo com informações sobre:

- Introdução à parceria Darede & Pier Cloud
- Produtos da plataforma FinOps (Lighthouse, CCA, Autofix, Spot, SP Manager, Space)
- Diferenciais técnicos e argumentos de venda
- Benefícios da parceria para clientes

## Estrutura do Projeto

```
├── index.html          # Página principal
├── style.css           # Estilos CSS
├── assets/             # Recursos visuais
│   ├── autofix.svg     # Ícone do produto Autofix
│   ├── cca.svg         # Ícone do produto CCA
│   ├── lighthouse.svg  # Ícone do produto Lighthouse
│   ├── space.svg       # Ícone do produto Space
│   ├── spot.svg        # Ícone do produto Spot
│   ├── sp_manager.svg  # Ícone do produto SP Manager
│   └── logo-darede-white.png # Logo Darede
└── README.md           # Este arquivo
```

## Como Executar

1. Clone o repositório
2. Abra o arquivo `index.html` em um navegador
3. Ou use um servidor local (ex: Live Server no VS Code)

## Troubleshooting - Git Push

Se você encontrar problemas com `git push` relacionados a permissões ou usuários incorretos:

### Problema Comum

```
remote: Permission to brunoprodutos/revendapier.git denied to <user>.
fatal: unable to access 'https://github.com/brunoprodutos/revendapier.git/': The requested URL returned error: 403
```

### Solução

1. **Configure o usuário local correto:**

   ```bash
   git config user.name "seuuser"
   git config user.email "seu.email@exemplo.com"
   ```
2. **Gere um Personal Access Token no GitHub:**

   - Acesse GitHub.com → Settings → Developer settings → Personal access tokens
   - Clique em "Generate new token (classic)"
   - Selecione as permissões: `repo` e `workflow`
   - Copie o token gerado
3. **Use o comando de push com credenciais explícitas:**

   ```bash
   git push https://<seuuser>:TOKEN@github.com/brunoprodutos/revendapier.git master
   ```

### Dicas Importantes

- Use **token clássico** (não fine-grained)
- Certifique-se de marcar as permissões `repo` e `workflow`
- Se você tem múltiplas contas GitHub, use o usuário correto na URL
- O token substitui sua senha nos comandos git

### Configuração Permanente (Opcional)

Para evitar digitar credenciais toda vez:

```bash
git remote set-url origin https://seuuser:SEU_TOKEN@github.com/brunoprodutos/revendapier.git
```

## Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Design responsivo
- SVG Icons

## Autor

Darede @ 2025
