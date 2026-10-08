# Atividade Tailwind CSS

Projeto desenvolvido para a **Atividade 02 da Aula 07 — Frameworks CSS**.

Este projeto demonstra o uso de mais de **70 classes diferentes** do Tailwind CSS, incluindo cores, tipografia, espaçamentos, bordas, posicionamento, Flexbox, Grid e responsividade.

## Deploy

**[Acessar projeto](https://atividade-tailwind-css.vercel.app)**

## Capturas de tela

### Layout principal
![Screenshot do projeto](./docs/screenshot-main.png)

### Lista de classes

![Demonstração das classes utilizadas](./docs/screenshot-classes.png)

> As imagens podem ser adicionadas na pasta `docs/`.

## Tecnologias

- Tailwind CSS (via Play CDN)
- HTML5
- CSS3 customizado (configuração do tema)

## Classes utilizadas

O projeto utiliza mais de 70 classes do Tailwind CSS, organizadas em:

- **Cores:** `bg-gray-900`, `bg-gray-800`, `bg-gray-700`, `text-white`, `text-gray-300`, `text-gray-400`, `text-gray-500`, `bg-primary`, `bg-secondary`, `bg-accent`
- **Tipografia:** `font-bold`, `font-nunito`, `font-fredoka`, `text-sm`, `text-xl`, `text-2xl`, `text-3xl`
- **Layout Flexbox:** `flex`, `flex-col`, `flex-grow`, `justify-center`, `justify-between`, `items-center`, `items-start`, `space-x-4`
- **Layout Grid:** `grid`, `grid-cols-2`, `grid-cols-1`, `md:grid-cols-3`, `md:grid-cols-4`, `gap-6`, `gap-4`
- **Espaçamento:** `p-4`, `px-3`, `px-4`, `px-6`, `py-4`, `py-6`, `py-8`, `mb-4`, `mb-8`, `mx-auto`, `w-12`, `h-12`
- **Bordas:** `border`, `border-gray-700`, `border-t`, `rounded-lg`, `rounded-xl`, `rounded-full`
- **Sombras:** `shadow-md`, `shadow-lg`
- **Posicionamento:** `fixed`, `bottom-6`, `right-6`, `mt-8`
- **Transições:** `transition-colors`, `duration-200`, `transform`, `hover:scale-105`, `hover:bg-primary`
- **Responsividade:** `md:grid-cols-3`, `sm:grid-cols-3`, `sm:grid`
- **Background:** `bg-gradient-to-br`, `from-gray-900`, `to-dark`, `bg-opacity-10`

## Estrutura

```text
atividade-tailwind-css/
├── index.html      # Estrutura e classes do projeto
├── vercel.json     # Configuração do deploy
├── package.json    # Metadados do projeto
└── README.md       # Documentação
```

## Publicar alterações

1. Envie as alterações para o GitHub:
```bash
git add .
git commit -m "melhora o projeto"
git push origin main
```

2. O deploy na Vercel será atualizado automaticamente.
