# Projeto de Prospeção de Clientes com base no CNAE

Este projeto tem como objetivo criar uma ferramenta em Python para a geração de uma planilha de clientes em Excel, visando a prospecção assertiva de clientes através da utilização da Classificação Nacional de Atividades Econômicas (CNAE). A proposta é proporcionar mais foco e precisão na prospecção, segmentando os potenciais clientes por setor e categoria.

## Motivação

A prospecção de clientes é uma etapa fundamental para o crescimento e desenvolvimento de qualquer negócio. No entanto, a abordagem genérica pode resultar em baixas taxas de conversão e desperdício de recursos. Com base na compreensão de que diferentes setores e categorias têm necessidades e características específicas, a utilização da CNAE como critério de segmentação permite direcionar os esforços de prospecção de forma mais eficiente.

## Funcionalidades

- Captura de Dados: O projeto utiliza informações disponíveis em um site de dados abertos, acessando a API fornecida por [Compras Públicas](https://compras.dados.gov.br/docs/home.html).
- Processamento de Dados: Os dados obtidos são em formato JSON, sendo necessário transformá-los em um DataFrame utilizando a biblioteca pandas em Python.
- Geração de Planilha: A partir do DataFrame, é gerada uma planilha em Excel que pode ser facilmente editada e utilizada para a prospecção de clientes.

## Como Utilizar

1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las executando `pip install -r requirements.txt`.
3. Após a execução bem-sucedida, a planilha de clientes será gerada no diretório especificado.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues relatando problemas ou sugerindo melhorias. Pull requests também são encorajados.

## Agradecimentos

Este projeto foi desenvolvido com base na necessidade de otimização dos processos de prospecção de clientes. Agradeço a todos que contribuíram direta ou indiretamente para tornar este projeto possível.



