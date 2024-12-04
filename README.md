# Análise de Exercícios de Membros de Academia

Este projeto contém uma análise de dados de membros de academia, com foco em explorar e entender a relação entre variáveis como tempo de exercício, calorias queimadas, tipos de exercícios, frequência de treino e outros fatores relacionados à saúde, como o índice de massa corporal (BMI) e percentual de gordura.

O objetivo deste projeto é analisar os dados dos membros da academia para encontrar correlações e padrões que possam fornecer insights sobre o comportamento dos participantes, incluindo: a correlação entre o tempo de exercício e as calorias queimadas, análise das diferenças no gasto calórico entre os tipos de exercício, a relação entre a frequência de atividade física e o BMI, e análise do percentual de gordura em relação à frequência de exercício.

O dataset utilizado neste projeto é um arquivo CSV chamado `gym_members_exercise_tracking.csv`, que contém informações sobre as sessões de treino dos membros da academia. As colunas do dataset incluem:

- `Session_Duration (hours)`: Duração da sessão de exercício em horas.
- `Calories_Burned`: Quantidade de calorias queimadas durante o exercício.
- `Workout_Type`: Tipo de exercício realizado (por exemplo, Yoga, HIIT, Cardio, etc.).
- `Workout_Frequency (days/week)`: Frequência semanal de exercícios (em dias).
- `BMI`: Índice de Massa Corporal dos membros.
- `Fat_Percentage`: Percentual de gordura corporal dos membros.
- `Gender`: Gênero do membro.

No decorrer da análise, realizamos as seguintes abordagens:

1. **Correlação entre Tempo de Exercício e Calorias Queimadas**: Calculamos a correlação de Pearson entre a duração da sessão de exercício e as calorias queimadas, interpretando o resultado para determinar se existe uma relação estatisticamente significativa.

2. **Análise de Calorias Queimadas por Tipo de Exercício**: Realizamos uma análise para verificar a média de calorias queimadas para diferentes tipos de exercício (Yoga, HIIT, Cardio, Strength), seguida de um gráfico de barras para visualização.

3. **Teste ANOVA para Comparar as Médias de Calorias Queimadas**: Aplicamos o teste ANOVA para verificar se há diferenças estatisticamente significativas no gasto calórico entre os tipos de exercício. O resultado foi interpretado com base no p-valor.

4. **Correlação entre Frequência de Exercício e BMI**: Analisamos a correlação entre a frequência de exercício (dias por semana) e o índice de massa corporal (BMI) dos membros.

5. **Correlação de Spearman entre Frequência de Exercício e Percentual de Gordura**: Calculamos a correlação de Spearman entre a frequência de exercício e o percentual de gordura corporal dos membros, seguido de uma interpretação do p-valor.

6. **Distribuições e Visualizações**: Geramos gráficos para visualizar a distribuição do percentual de gordura e do BMI dos membros, além de uma análise de como a atividade física se distribui por gênero.

O projeto inclui diversas visualizações, como gráficos de dispersão (para correlações), histogramas (para distribuições) e gráficos de barras (para comparações entre grupos). Essas visualizações ajudam a compreender melhor os padrões e insights presentes nos dados.

### Como Rodar o Projeto

Para rodar este projeto, você precisará ter os seguintes pacotes Python instalados:

- pandas
- numpy
- matplotlib
- seaborn
- scipy

Se ainda não tiver essas bibliotecas instaladas, você pode instalá-las utilizando o seguinte comando:

```bash
pip install pandas numpy matplotlib seaborn scipy

