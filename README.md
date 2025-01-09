# Projeto de Análise de Dados Uma grande Loja Online

## Descrição do Projeto
Este projeto consiste em uma análise em uma grande loja online. Para isso, junto com o departamento de marketing, foi compilado uma lista de hipóteses que podem ajudar a aumentar a receita. Foi necessário priorizar essas hipóteses, através de um teste A/B, sendo o grupo A de controle e o grupo B de teste e analisar os resultados.

## As tarefas são:
- Calcular o ICE e RICE das hipóteses e identificar as hipóteses prioritárias
- Teste A/B
- Análise dos gráficos
- Tomar decisões com base nos resultados dos testes

## Dicionário de dados
- hypotheses_us.csv
  - 'Hypotheses': breves descrições das hipóteses
  - 'Reach': alcance do usuário, em uma escala de um a dez
  - 'Impact': impacto nos usuários, em uma escala de um a dez
  - 'Confidence': confiança na hipótese, em uma escola de um a dez
  - 'Effort': os recursos necessários para testar uma hipótese, em uma escala de um a dez. Quanto maior o valor, mais recursos são necessários para o teste
  - 'transactionId': identificador do pedido
  - 'visitorId': identificador do usuário que fez o pedido
  - 'date': data do pedido
  - 'revenue': receita do pedido
  - 'group': o grupo de testes A/B ao qual o usuário pertence
- visits.csv
  - 'date': data
  - 'group': grupo de teste A/B
  - 'visits': o número de visitas na data especificada de teste A/B especificado

## Ferramentas e Bibliotecas utilizadas
- Pyhton:  Linguagem principal utilziada para a análise
- Pandas: Biblioteca para manipulação e análise de dados
- Matplotlib: Biblioteca para gerar gráficos
- Numpy: Biblioteca que permite trabalhar com objetos multidimensionais, como matrizes e sequências
- Math: Biblioteca que permite usar funções matemáticas
- Seaborn: Biblioteca de visualização de dados
- Scipy: Biblioteca que fornece uma manipulação conveniente e rápida de um array N-dimensional
- Ploty.express: Biblioteca que permite criar visualizações rápidas e eficientes
- Datetime: Biblioteca para manipulação de datas e horas

## Imagens

### Tabela hipóteses
<img src="https://github.com/user-attachments/assets/60132568-ff30-4f3f-8202-b7c18f44220e" alt="Projeto 9" width="200"/>

### Hipótese ICE
<img src="https://github.com/user-attachments/assets/7ee8a939-7935-4458-b28b-c9655848a888" alt="Projeto 9" width="200"/>

### Hipótese RICE
<img src="https://github.com/user-attachments/assets/806d0643-542d-4321-8bb2-01085a14f0dc" alt="Projeto 9" width="200"/>

### Pedidos
<img src="https://github.com/user-attachments/assets/8b8f77d9-34be-465f-b094-ea656ad8f278" alt="Projeto 9" width="200"/>

### Visitas
<img src="https://github.com/user-attachments/assets/c327d0f4-41c2-4c01-996b-fdb4176f34a9" alt="Projeto 9" width="200"/>

### Receita acumulada
<img src="https://github.com/user-attachments/assets/7f12ab53-3f27-4c9a-b329-e7b36556f086" alt="Projeto 9" width="200"/>

### Receita por data
<img src="https://github.com/user-attachments/assets/1184b002-fe43-4bbe-8a79-9e81ecf1bf37" alt="Projeto 9" width="200"/>

## Resultados
- Com os resultados dos testes é possível ver que existe diferença entre os grupos
- O grupo B aparentemente está melhor que o grupo A
- Concluindo, o teste A/B teve efeito e pode continuar

## Aprendizados
- Análise de dados
- Tratar os dados modificando os tipos de dados, nome das colunas, valores ausentes, valores duplicados
- Construção e análise de gráficos
- Manipulação de tabelas
- Teste A/B
- Testes estatísticos

## Contexto real
- Empresas que desejam testar algumas mudanças em seus produtos
- Empresas de marketing que desejam sbaer mais sobre o comportamento dos usuários depois de alguma mudança
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
  
