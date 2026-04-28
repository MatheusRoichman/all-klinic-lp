# ALL KLINIC — WEBSITE

## Conteúdo

- `index.html` — site completo (uma única página, totalmente standalone)
- `images/` — todos os ativos visuais
  - `logo.png` — logo (PNG transparente, 38×38 ideal)
  - `team.webp` — equipe médica
  - `team-entrance.webp` — equipe na entrada com letreiro
  - `facade.jpg` — fachada externa
  - `consulting-room.jpg` — consultório
  - `reception.jpg` — recepção

## Como visualizar

Basta abrir o arquivo `index.html` em qualquer navegador moderno.
Não há dependências de build — tudo está embutido no HTML.

## Como publicar

Faça upload de todo o conteúdo da pasta para qualquer serviço de
hospedagem estático (Vercel, Netlify, GitHub Pages, S3, etc.).
Não há servidor, banco de dados ou pipeline de build.

## Stack

- HTML5 + CSS3 + JavaScript vanilla
- Fontes: Cormorant Garamond + Manrope (Google Fonts)
- Mapa: Google Maps embed (carrega online)

## Paleta

| Cor       | Hex       | Uso                       |
| --------- | --------- | ------------------------- |
| Ouro      | `#C49C18` | principal (do logotipo)   |
| Tinta     | `#1B1A17` | texto e seções escuras    |
| Creme     | `#F8F4EC` | seções claras             |
| Papel     | `#FBF9F4` | fundo principal           |

## Editar conteúdo

Todos os textos estão diretamente no `index.html`, em português.
Procure pelos comentários `<!-- ===================== -->` para
navegar entre as seções (HERO, ABOUT, SPECIALTIES, etc.).
