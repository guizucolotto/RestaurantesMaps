# Classificação de Restaurantes por Tipo de Culinária

## Descrição

Este projeto visa classificar uma lista de restaurantes com base em seus nomes e informações disponíveis, utilizando fontes confiáveis como o Guia Michelin e avaliações especializadas. Os dados utilizados foram extraídos de uma lista de salvos do Google Maps, utilizando a funcionalidade de exportação do Google Takeout.

## Objetivo

Desenvolver um sistema que categorize restaurantes de acordo com o tipo de culinária oferecida, facilitando a identificação e seleção por parte dos usuários.

## Funcionalidades

- **Análise de Nomes**: Identificação de palavras-chave nos nomes dos restaurantes para inferir o tipo de culinária.
- **Consulta a Fontes Externas**: Utilização de informações de fontes confiáveis para aprimorar a classificação.
- **Geração de Arquivo Atualizado**: Criação de um arquivo CSV com as classificações atribuídas a cada restaurante.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal para desenvolvimento do sistema.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Requests**: Biblioteca para requisições HTTP, utilizada na consulta a fontes externas.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```
2. **Instale as dependências**:
   ```bash
   pip install pandas requests
   ```
3. **Execute o script principal**:
   ```bash
   python classificar_restaurantes.py
   ```

## Estrutura do Projeto

- `classificar_restaurantes.py`: Script principal que realiza a classificação.
- `restaurantes.csv`: Arquivo CSV contendo a lista de restaurantes a serem classificados.
- `restaurantes_classificados.csv`: Arquivo gerado com as classificações atribuídas.

## Fonte dos Dados

Os dados foram exportados diretamente da lista de salvos do Google Maps utilizando a funcionalidade do Google Takeout. Esta abordagem garante que as informações dos restaurantes estejam atualizadas e reflitam os locais de interesse.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

## Contato

Para mais informações, entre em contato pelo e-mail: guilherme.sori@gmail.com

---

*Este projeto foi desenvolvido com base em informações disponíveis e fontes confiáveis, visando fornecer uma classificação precisa dos restaurantes listados.*
