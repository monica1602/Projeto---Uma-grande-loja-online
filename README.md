# Projeto de Análise de Dados - Uma grande Loja Online

## Descrição do Projeto
Este projeto tem como objetivo realizar uma análise de dados em uma grande loja online com o intuito de identificar e validar hipóteses que podem aumentar a receita. Em colaboração com o departamento de marketing, foi compilada uma lista de hipóteses sobre possíveis ações que poderiam impactar diretamente os resultados da loja.
A abordagem adotada para testar essas hipóteses foi por meio de um teste A/B, no qual as hipóteses foram divididas entre dois grupos: o grupo A (controle), que representou a condição original, sem alterações, e o grupo B (teste), que recebeu a alteração proposta pela hipótese. O desempenho de ambos os grupos foi monitorado, analisando diferenças nas métricas de receita, taxas de conversão e comportamento dos consumidores.
Após a execução do teste A/B, os resultados foram analisados para verificar se as mudanças implementadas no grupo B geraram resultados significativos, confirmando ou refutando as hipóteses. Com base nessas análises, as hipóteses mais promissoras foram priorizadas para futuras implementações, ajudando o departamento de marketing a tomar decisões mais assertivas. Esse processo de validação não só permitiu otimizar as estratégias de marketing, mas também criou uma base sólida para o crescimento contínuo da loja online, fundamentando decisões com dados reais e melhorando o impacto nas receitas.

## As tarefas são:
- Calcular o ICE e RICE das hipóteses e identificar as hipóteses prioritárias: O primeiro passo na análise das hipóteses foi a aplicação das métricas ICE (Impacto, Confiança e Facilidade) e RICE (Impacto, Confiança, Facilidade e Alcance) para cada hipótese. Essas métricas permitiram priorizar as hipóteses, destacando aquelas com maior potencial de impacto para a loja online, considerando não apenas o impacto esperado, mas também a confiança na estimativa e a facilidade de implementação. Isso ajudou a identificar as hipóteses mais relevantes e com maior possibilidade de sucesso.
- Teste A/B: As hipóteses priorizadas foram então testadas utilizando um teste A/B, no qual os usuários foram divididos entre dois grupos: o grupo de controle (A), que manteve a condição original, e o grupo de teste (B), que foi exposto à alteração proposta pela hipótese. Esse processo permitiu comparar o comportamento dos usuários entre os dois grupos e identificar se a alteração teve um efeito significativo.
- Análise dos gráficos: Durante o processo de análise, gráficos foram utilizados para visualizar o desempenho de cada grupo (A e B) em relação a diferentes métricas, como taxas de conversão, receita, tempo de permanência no site e outros KPIs relevantes. A análise gráfica facilitou a compreensão do impacto das mudanças implementadas.
- Tomar decisões com base nos resultados dos testes: Com os resultados obtidos nos testes A/B e a análise dos gráficos, as decisões foram tomadas de forma estratégica, focando naquelas hipóteses que apresentaram resultados significativos e positivos. As alterações que tiveram um impacto positivo nas métricas de sucesso foram priorizadas para serem implementadas de forma definitiva na plataforma, enquanto hipóteses com resultados negativos ou sem impacto significativo foram descartadas ou repensadas.

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
- Python: Linguagem de programação principal utilizada para análise de dados, permitindo a execução de scripts e manipulação de grandes volumes de informações.
- Pandas: Biblioteca utilizada para manipulação, limpeza e análise de dados, especialmente para trabalhar com estruturas de dados como DataFrames, permitindo fácil leitura e processamento de dados em formatos como CSV e Excel.
- Matplotlib: Biblioteca para visualização de dados, permitindo a criação de gráficos e visualizações estáticas, interativas ou animadas.
- NumPy: Biblioteca que simplifica o manuseio de vetores e matrizes, acelerando cálculos matemáticos e estatísticos nos dados.
- Math: Biblioteca que disponibiliza várias funções matemáticas básicas, como operações aritméticas, trigonométricas, logaritmos, entre outras.
- Seaborn: Biblioteca de visualização de dados baseada no Matplotlib, que facilita a criação de gráficos estatísticos bonitos e informativos, com alta customização e integração com Pandas.
- Scipy: Biblioteca que complementa o Numpy, oferecendo funções adicionais para otimização, integração, interpolação e estatísticas, sendo útil para cálculos científicos e técnicos.
- Plotly Express: Biblioteca para criação de visualizações interativas e eficientes, permitindo que gráficos sejam facilmente manipulados e explorados em tempo real, ideal para dashboards interativos.
- Datetime: Biblioteca para manipulação de datas e horas, permitindo a análise de períodos, intervalos de tempo e conversão de diferentes formatos de data de forma eficiente.

## Imagens

### Tabela hipóteses
<img src="https://github.com/user-attachments/assets/60132568-ff30-4f3f-8202-b7c18f44220e" alt="Projeto 9" width="1000"/>

### Tabela - Hipótese ICE
<img src="https://github.com/user-attachments/assets/7ee8a939-7935-4458-b28b-c9655848a888" alt="Projeto 9" width="1000"/>

### Tabela - Hipótese RICE
<img src="https://github.com/user-attachments/assets/806d0643-542d-4321-8bb2-01085a14f0dc" alt="Projeto 9" width="1000"/>

### Tabela - Pedidos
<img src="https://github.com/user-attachments/assets/8b8f77d9-34be-465f-b094-ea656ad8f278" alt="Projeto 9" width="1000"/>

### Tabela - Visitas
<img src="https://github.com/user-attachments/assets/c327d0f4-41c2-4c01-996b-fdb4176f34a9" alt="Projeto 9" width="1000"/>

### Gráfico - Receita acumulada
<img src="https://github.com/user-attachments/assets/7f12ab53-3f27-4c9a-b329-e7b36556f086" alt="Projeto 9" width="800"/>

### Gráfico - Receita por data
<img src="https://github.com/user-attachments/assets/1184b002-fe43-4bbe-8a79-9e81ecf1bf37" alt="Projeto 9" width="800"/>

## Resultados
- A análise dos resultados dos testes evidenciou uma diferença estatisticamente significativa entre os grupos A e B.
- Observou-se que o grupo B apresentou um desempenho superior ao grupo A, indicando que a alteração testada foi eficaz.
- Diante desses achados, conclui-se que o teste A/B gerou um impacto positivo, o que justifica a adoção e a continuidade da estratégia avaliada, corroborando a eficácia das modificações implementadas.

## Aprendizados
- Análise de dados: Avaliação dos dados para identificar padrões e insights.
- Tratar os dados: Modificação dos tipos de dados, ajustes nos nomes das colunas, tratamento de valores ausentes e remoção de duplicatas.
- Construção e análise de gráficos: Criação de visualizações para representar os dados e identificar tendências.
- Manipulação de tabelas: Organização e transformação dos dados para facilitar a análise.
- Teste A/B: Realização de testes controlados para comparar diferentes grupos e identificar a eficácia das mudanças implementadas.
- Testes estatísticos: Aplicação de métodos estatísticos para validar as hipóteses e garantir a confiabilidade dos resultados.

## Contexto real
- Empresas que desejam testar mudanças em seus produtos para avaliar o impacto dessas alterações no comportamento dos consumidores e nos resultados comerciais.
- Empresas de marketing interessadas em entender como as modificações em seus produtos influenciam as interações dos usuários e as métricas de desempenho após a implementação das mudanças.
  
## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
  
