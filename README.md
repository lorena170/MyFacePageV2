# Myfacepag 2.0

Este projeto é uma página web pessoal, desenvolvida em HTML e CSS, que apresenta informações sobre mim, meus interesses e minha formação. A seguir, está uma descrição dos componentes e estilos implementados.

## Estrutura do HTML

A página começa declarando o tipo de documento e define o elemento `<html>` com a linguagem configurada para português do Brasil. No `<head>`, as seguintes características são definidas:

- **Codificação**: UTF-8
- **Responsividade**: Meta tags adequadas para garantir que a página seja responsiva em diferentes dispositivos
- **Título**: "Myfacepag 2.0"
- **Estilos**: Link para um arquivo CSS para estilizar a página

No `<body>`, o conteúdo visível é organizado da seguinte forma:

- **Cabeçalho (`<header>`)**: Título principal "Myfacepag 2".
  
- **Principal (`<main>`)**: Contém uma `<div>` que organiza o conteúdo em seções:
  - **Apresentação pessoal**: Detalhes sobre mim.
  - **Bibliografia**: Informações sobre meu curso de Desenvolvimento de Sistemas Web.
  - **Interesses e hobbies**: Lista não ordenada dos meus interesses.
  - **Contato**: Meu e-mail.

- **Rodapé**: Inclui informações sobre direitos autorais.

## Estilos em CSS

Os estilos da página foram configurados com foco em clareza e estética:

- **Fonte**: "Times New Roman" para o corpo da página.
- **Espaçamento**: Linhas com espaçamento de 1.6 para facilitar a leitura.
- **Fundo**: Azul claro (#e6f2ff) para um visual agradável.
- **Margens e Padding**: Remoção de margens e padding padrão, com padding adicional na parte inferior para evitar que o conteúdo fique colado ao rodapé.

### Estilos Específicos

- **Cabeçalho**: Fundo roxo escuro (#8e0cab) com texto branco, centralizado e padding de 1 rem.
  
- **Barra de Navegação**: Também roxa, com texto branco, padding de 0.5 rem, usando flexbox para alinhamento horizontal. Marcadores removidos e margens entre itens para um visual limpo.

- **Container**: Utiliza flexbox para organizar itens em coluna, com padding de 20px. As colunas têm fundo branco, margens, padding, cantos arredondados e sombra suave para dar profundidade.

- **Seções**: Estilo semelhante ao das colunas, com fundo branco, margens, padding e sombra.

- **Rodapé**: Mantém o fundo roxo escuro, texto branco, centralizado e fixo na parte inferior da tela, ocupando toda a largura da página para garantir que esteja sempre visível.

## Conclusão

A página Myfacepag 2.0 é uma representação simples e clara de informações pessoais, combinando design responsivo com uma estética agradável. As escolhas de cores e tipografia foram feitas para proporcionar uma experiência de leitura confortável.

