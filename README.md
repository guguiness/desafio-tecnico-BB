# Desafio Técnico - Blue Bear
## Requisitos
O projeto foi desenvolvido seguindo os seguintes requisitos:
  - Conter ao menos 2 páginas;
  - Uma página contendo uma tabela de itens clicáveis que levam para a segunda página;
  - Uma página contendo um cabeçalho e cartões com detalhes sobre o item atual;
  - Todo o projeto deve usar o Salesforce Lightning Design System (SLDS).
 
## Como usar
A página inicial do projeto está no arquivo "index.html". Para que os estilos sejam aplicados, a pasta "salesforce-lightning-design-system-2.16.2" deve ser descompactada e deve estar na mesma pasta em que se encontram os arquivos HTML.

## Conteúdo
O tema escolhido para os itens do projeto foi "Frutas". Na tabela da página de itens há diversas informações sobre cada fruta, como:
  - Nome;
  - Categoria da receita (na página de detalhes);
  - Nome científico;
  - Nome da planta/árvore que origina a fruta;
  - Cores comuns da fruta;
  - Presença de sementes;
  - Período de floração da planta/árvore.

Já na página de detalhes de cada item, há informações como:
  - Descrição da fruta;
  - Curiosidades;
  - Receitas;
  - Informações nutricionais.

Há também uma página de referências, que pode ser acessada pela barra de navegação.

## Bugs
- Há um problema na importação de alguns arquivos do SLDS, o que faz com que as páginas quebrem quando acessadas direto do arquivo. Entretanto, quando os arquivos são abertos pelo Visual Studio Code usando a extensão "Live Server", os arquivos do SLDS são importados normalmente;
- A tabela da página de itens (arquivo "index.html") não é responsiva devido à tabela, que dificulta esse processo.
