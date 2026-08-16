# Haja Luz

Site institucional da **Haja Luz**, empresa de instalações e manutenções elétricas residenciais, comerciais e industriais.

🔗 **Site publicado:** https://SEU-USUARIO.github.io/haja-luz/

## Sobre

Página única (landing page) apresentando os serviços da empresa, processo de atendimento e canais de contato — com tema escuro inspirado em um quadro de disjuntores.

## Tecnologias

- HTML5
- CSS3 (arquivo separado, sem frameworks)
- Fontes: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter) e [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), via Google Fonts

## Estrutura

```
haja-luz/
├── index.html      # Estrutura e conteúdo da página
├── styles.css       # Estilos (cores, tipografia, layout, animações)
└── README.md         # Este arquivo
```

## Como rodar localmente

Não é necessário nenhuma instalação. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
git clone https://github.com/SEU-USUARIO/haja-luz.git
cd haja-luz
```

Depois é só dar duplo clique em `index.html`, ou abrir com a extensão **Live Server** no VS Code para recarregamento automático.

## Guia rápido de manutenção

Quer mudar algo? Veja onde mexer:

| Quero mudar... | Onde editar |
|---|---|
| Telefone / WhatsApp | `index.html` — busque `(21) 99999-0000` (aparece 2x) |
| E-mail | `index.html` — busque `contato@hajaluz.com.br` |
| Título principal / texto do topo | `index.html` — dentro de `<section class="hero">` |
| Adicionar ou remover um serviço | `index.html` — dentro de `<section id="servicos">`, copie ou apague um bloco `<div class="breaker">...</div>` inteiro |
| Texto "Sobre a empresa" | `index.html` — dentro de `<section id="sobre">` |
| Números (anos de atuação, instalações, etc.) | `index.html` — dentro de `<div class="stats">` |
| Etapas do processo de atendimento | `index.html` — dentro de `<section id="processo">` |
| Horário de atendimento | `index.html` — dentro de `<section id="contato">` |
| Cores do site (tudo de uma vez) | `styles.css` — bloco `:root{ }` no topo do arquivo, cada cor tem comentário explicando o que controla |
| Fontes | `styles.css` — busque `font-family` |

Todos os pontos editáveis em `index.html` têm um comentário `<!-- EDITAR: ... -->` logo acima, para facilitar achar rápido.

Depois de editar, salve e suba a alteração:
```bash
git add .
git commit -m "descreva o que mudou"
git push
```
O site atualiza sozinho em 1-2 minutos.

## Publicação

O site está hospedado gratuitamente via **GitHub Pages**, publicado direto a partir da branch `main`.

Para atualizar o site: edite os arquivos, faça commit e push — o GitHub Pages atualiza a versão publicada automaticamente em alguns minutos.

## Contato

- **E-mail:** contato@hajaluz.com.br
- **Telefone / WhatsApp:** (21) 99999-0000

---

© 2026 Haja Luz. Todos os direitos reservados.