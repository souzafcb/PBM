# Provas de Conceito — Apoio à Decisão em Hemoterapia

Site estático preparado para apresentação em congresso e publicação no GitHub Pages. Não exige instalação, compilação, servidor ou dependências externas.

## Estrutura

```text
.
├── index.html          # página inicial e acesso às demonstrações
├── assets/site.css     # estilos da página inicial
├── pbm/index.html      # decisão transfusional — hemácias
├── tpe/index.html      # solicitação de plasmaférese terapêutica
└── .nojekyll           # publicação direta de arquivos estáticos
```

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie **o conteúdo desta pasta** para a raiz do repositório. O arquivo `index.html` precisa ficar na raiz.
3. No repositório, acesse **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main`, a pasta `/(root)` e clique em **Save**.
6. Aguarde o endereço público aparecer na mesma tela.

As rotas publicadas serão:

- `/` — vitrine das provas de conceito;
- `/pbm/` — decisão transfusional de hemácias;
- `/tpe/` — solicitação de plasmaférese terapêutica.

## Antes da apresentação

- Teste o endereço publicado em computador e celular.
- Use apenas dados fictícios ou anonimizados.
- No protótipo PBM, o código demonstrativo de visitante informado na própria tela é `CHM2026`.
- O bloqueio de acesso do protótipo PBM é apenas uma simulação no navegador e **não constitui autenticação real**.

## Uso responsável

Este material é uma prova de conceito. Não substitui avaliação profissional, protocolos institucionais, validação clínica, governança de dados ou requisitos de segurança para uso assistencial.
