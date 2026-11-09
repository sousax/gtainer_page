# Gtainer — Landing page

Landing page da Gtainer, empresa de Santos (SP) que aluga containers Reefer e Dry, geradores a diesel e quadros de tomadas.

**Demo:** https://sousax.github.io/gtainer_page/

## Funcionalidades

- Seções: início, quem somos, serviços, quando usar um container frigorífico, ficha técnica do Reefer, tipos de container (Reefer, Standard, High Cube, Open Top, Flat Rack, Plataforma), clientes, perguntas frequentes e contato
- FAQ com `<details>`/`<summary>`, sem JavaScript
- Contato por telefone e e-mail com links `tel:` e `mailto:`
- SEO: título e URL canônica, dados estruturados JSON-LD (`LocalBusiness`, `Service`, `FAQPage`), `robots.txt` e `sitemap.xml`
- Layout responsivo, imagens com `loading="lazy"`, pré-carregamento da imagem principal e suporte a `prefers-reduced-motion`

## Tecnologias

- HTML e CSS puros, em um único `index.html`
- Google Fonts (Oswald e Source Sans 3)

## Como rodar

Abra o `index.html` no navegador. Se preferir um servidor local:

```bash
python3 -m http.server
```

## Estrutura

```
index.html    página completa (HTML + CSS inline)
img/          fotos, logo e logos de clientes
robots.txt
sitemap.xml
```
