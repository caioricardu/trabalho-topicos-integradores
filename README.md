# OSBoys Jornal - Acessibilidade e Boas Práticas de Web

Este é um projeto simples de jornal online chamado **OSBoys Jornal**, que exibe notícias relacionadas à economia do Brasil. A principal preocupação deste projeto é garantir que ele seja acessível, seguindo as diretrizes de **WAI-ARIA** e **COGA (Cognitive and Learning Disabilities Accessibility Task Force)**.

## Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **WAI-ARIA** para acessibilidade
- **COGA** para garantir melhor experiência para usuários com dificuldades cognitivas e de aprendizado.

## Objetivo

O objetivo deste projeto é criar uma **página** para o público em geral, com foco em:

- Leitores de tela (para deficientes visuais);
- Usuários com **deficiência cognitiva** (a exemplo de dislexia, dificuldades de memória ou de foco);
- Navegação clara e intuitiva em dispositivos móveis e desktop.


# Como Rodar o Projeto

Apenas abrir o arquivo HTML em seu navegador


## Acessibilidade com WAI-ARIA e COGA

Este projeto utiliza as seguintes tags e atributos WAI-ARIA para melhorar a acessibilidade, especialmente para atender diretrizes COGA (Cognitive and Learning Disabilities Accessibility Task Force):

- **`role="banner"`**  
  Define a região do cabeçalho principal do site.

- **`aria-label="Cabeçalho do site"`**  
  Descreve o propósito do banner de forma clara para tecnologias assistivas.

- **`role="main"`**  
  Indica a região principal do conteúdo da página.

- **`aria-label="Conteúdo principal"`**  
  Dá uma descrição clara da área principal para usuários de leitores de tela.

- **`aria-labelledby="noticias-economia"`**  
  Relaciona a seção de notícias ao título correspondente, ajudando na navegação.

- **`aria-labelledby="pib-2025"`**, **`aria-labelledby="inflacao-2025"`**,  
  **`aria-labelledby="economia-gastos"`**, **`aria-labelledby="salario-minimo"`**  
  Cada artigo é relacionado ao seu título, permitindo que leitores de tela apresentem um resumo útil.

- **`role="contentinfo"`**  
  Marca a região do rodapé do site.

- **`aria-label="Rodapé"`**  
  Fornece uma descrição clara do conteúdo do rodapé.

