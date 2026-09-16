# TechDetail

Landing page da **TechDetail**, um serviço de limpeza, organização de cabos e montagem estética de computadores.

O site foi construído com HTML e CSS puro, sem frameworks ou dependências para instalar. Isso facilita a manutenção e permite publicar o projeto gratuitamente em serviços de hospedagem estática.

## Prévia

A página apresenta:

- limpeza interna e higienização de componentes;
- organização de cabos e melhoria visual do setup;
- auxílio na montagem e remontagem de PCs;
- planos e valores de referência;
- fluxo de atendimento em três etapas;
- chamadas para contato pelo WhatsApp e Instagram.

## Estrutura do projeto

```text
.
├── index.html
├── style.css
├── README.md
├── .gitignore
└── assets/
├── favicon.svg
└── TechDetail Logo on Dark Background.png
```

| Arquivo | Função |
| --- | --- |
| `index.html` | Estrutura e conteúdo da página principal |
| `style.css` | Layout, cores, tipografia e responsividade |
| `assets/favicon.svg` | Ícone TD exibido na aba do navegador |
| `assets/TechDetail Logo on Dark Background.png` | Logo exibida no cabeçalho |

## Como visualizar localmente

1. Abra a pasta do projeto no VS Code.
2. Abra o arquivo `index.html` no navegador.

Para uma experiência mais próxima da publicação, também é possível usar a extensão **Live Server** do VS Code e clicar em **Go Live**.

## Publicação

O projeto é estático e pode ser publicado no **GitHub Pages**, **Netlify** ou **Vercel**. O arquivo de entrada já está configurado como `index.html`.

### GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste projeto, incluindo a pasta `assets`.
3. Acesse **Settings > Pages**.
4. Em **Build and deployment**, selecione a branch principal e a pasta `/root`.
5. Salve e aguarde o GitHub gerar o endereço público.

## Personalização

Os principais dados comerciais ficam no arquivo `index.html`:

- número do WhatsApp;
- usuário e endereço do Instagram;
- nomes dos serviços;
- preços e descrições dos planos;
- textos da página.

Antes de publicar, revise esses links e valores para garantir que estejam atualizados.

## Tecnologias

- HTML5
- CSS3
- Google Fonts: Inter e Space Grotesk
- SVG para os elementos visuais e o favicon
