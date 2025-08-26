# MuseuF1 – HTML & CSS simples

## Objetivo
Este projeto consiste em uma **página web institucional** desenvolvida com **HTML5 e CSS3 simples**, focando em **estética, semântica e experiência do usuário**. O site possui seções organizadas de forma clara: **Início, Sobre, Atrações e Contato**, com elementos visuais e interativos que valorizam a apresentação do conteúdo.

O projeto inclui:
- **Galeria de imagens** para exibição de conteúdos visuais.
- **Cartões** para informações destacadas.
- **Linha do tempo**.
- **Animações simples**, aplicando `scale` para dinamizar a navegação.
- Formulário de contato funcional e semântico.
- Uso de **BEM** na nomenclatura e boas práticas de CSS e HTML.

## Tecnologias Utilizadas
- **HTML5** – Estrutura semântica das páginas.
- **CSS3** – Estilização, animações e responsividade.

### Cores Utilizadas
```css
:root {
    /* Cor principal: utilizada em títulos, cabeçalhos e elementos de destaque */
    --cor-primaria: #002E12;

    /* Cor secundária: utilizada em botões, links e elementos interativos */
    --cor-secundaria: #FFB600;

    /* Cor de detalhe: para ícones, destaques e pequenos elementos gráficos */
    --cor-detalhe: #008C14;

    /* Cor de contraste: para fundos claros e suavizados */
    --cor-contraste: #EDEBD9;

    /* Cor de base/branco: textos, fundos secundários e elementos neutros */
    --cor-branco: #F3F3F3;
}
```
### Tipografia

- **Título Hero Section:** "Edu NSW ACT Cursive", cursive

- **Subtítulos:** "Cormorant Garamond", serif

- **Texto Geral:** "Open Sans", sans-serif

## Funcionalidades

- Botões com hover controlado para evitar alterações indesejadas em outros elementos.

- Caixa de texto no Hero Section com fundo em blur, posicionada na parte inferior lateral para melhor visual.

- Cards da linha do tempo com box-shadow para profundidade.

- Uso de clamp() nas fontes para adaptação em diferentes tamanhos de tela.

- Fundo padronizado #EDEBD9 para suavidade e equilíbrio visual.

## Como Rodar

### Clone este repositório:

git clone https://github.com/seu-usuario/nome-do-projeto.git

## Acesse o site: https://formula1-kappa-six.vercel.app/
