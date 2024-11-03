<div style = "text-align: center">
    
<img src = "https://i.gifer.com/9uhG.gif" width = 900 height = 400/>

# Desafio: Previsão da Média de Curtidas no Instagram

</div>

<p style="text-align: justify;">
    <strong>
        Vamos lá, máquinas! Este é o momento perfeito para colocar em prática tudo o que vocês têm aprendido sobre regressão linear e análise de dados. O Desafio de Previsão da Média de Curtidas no Instagram não é apenas um exercício técnico, mas uma oportunidade de mergulhar no mundo real dos dados, onde cada clique e cada linha de código fazem a diferença. Imagine a satisfação de ver seu modelo prever com precisão o engajamento das postagens! Isso é mais do que apenas números; é sobre entender padrões, tomar decisões baseadas em dados e aprimorar habilidades que são valiosas no mercado de trabalho. Não subestimem o poder do que vocês podem conquistar aqui. Então, respirem fundo, se organizem e aceitem o desafio com determinação. Vocês são totalmente capazes, e o conhecimento que vão ganhar agora é um investimento para o futuro.
    </strong>
</p>


## Objetvo:

<p style="text-align: justify;">
    Desenvolver um modelo preditivo utilizando Regressão Linear para estimar a Média de Curtidas em postagens no Instagram, explorando como diversos atributos dos perfis, como número de seguidores, quantidade de postagens e taxa de engajamento, influenciam o desempenho das publicações. Este modelo ajudará a entender quais fatores têm maior impacto na popularidade de um post, possibilitando a criação de estratégias direcionadas para maximizar o engajamento e, consequentemente, o alcance e influência do perfil na plataforma.
    Sobre este arquivo:
</p>

## Base dos Dados:
A base de dados contém informações sobre influenciadores no Instagram, com as seguintes colunas:
- **Classificação:** Ranking do influenciador.
- **Nome:** Nome do influenciador.
- **Pontuação:** Pontuação geral baseada em diversos fatores.
- **Postagens:** Número de postagens feitas pelo influenciador.
- **Seguidores:** Número de seguidores do influenciador.
- **Média de Curtidas:** Média de curtidas por postagem (variável target).
- **Taxa de Engajamento:** Percentual de engajamento em relação ao número de seguidores.
- **Média de Curtidas Novas:** Média de curtidas em postagens recentes.
- **Likes:** Número total de likes.
- **País:** Localização do influenciador.


## Dados:

Faça o Download: [Instagram influencers](https://mega.nz/file/XUk1xbqD#yHPS96ulvTbAnyw1ZTQ6kJ3UZWVP_PEpkRSvgfE2NQ8)

Lembre-se de que este é o mesmo notebook utilizado na unidade 4, então, aproveite-o com todas as adaptações realizadas. Antes de fazer qualquer edição, crie uma cópia do arquivo.

## Passos para a Solução:

**1. Carregue os Dados:** importe a base de dados do Instagram para o seu ambiente de desenvolvimento.
**2. Análise Exploratória dos Dados:** 
- Examine a estrutura dos dados e identifique variáveis relevantes para o modelo.
- Verifique a existência de valores ausentes e trate-os adequadamente.
- Analise a correlação entre as variáveis para identificar quais têm maior influência na Média de Curtidas.

**3. Pré-processamento dos Dados:**
- Selecione as features mais relevantes para o modelo, como Pontuação, Postagens, Seguidores, Taxa de Engajamento, e outras que possam influenciar na Média de Curtidas.
- Divida os dados em conjuntos de treino e teste.

**4. Treinamento do Modelo:**
- Aplique a Regressão Linear usando as variáveis selecionadas para prever a Média de Curtidas.
- Treine o modelo com o conjunto de dados de treino.

**5. Avaliação do Modelo:**
- Utilize métricas como Erro Médio Absoluto (MAE), Erro Quadrático Médio (MSE), Raiz do Erro Quadrático Médio (RMSE) e Coeficiente de Determinação (R²) para avaliar o desempenho do modelo.
- Interprete os resultados para entender o quão bem o modelo está prevendo a Média de Curtidas.

**6. Visualização dos Resultados:**
- Plote os resíduos (diferença entre valores reais e previstos) para verificar a adequação do modelo.
- Crie gráficos de dispersão que mostrem a relação entre as previsões e os valores reais.

**7. Análise dos Coeficientes:**
- Interprete os coeficientes do modelo para identificar quais variáveis têm maior impacto na previsão da Média de Curtidas.

**Extra:** Para aprimorar ainda mais sua análise, considere normalizar os dados, testar transformações logarítmicas, ou mesmo adicionar mais variáveis que possam ser relevantes, como o número de comentários ou a categoria do influenciador.

## Entrega:

<p style="text-align: justify;">
Envie um notebook contendo todo o procedimento de análise, desde a importação dos dados até a interpretação dos resultados. Inclua gráficos, tabelas e comentários minuciosos acerca das descobertas e possíveis recomendações a partir dos resultados do modelo. Essa abordagem guiará na construção de um modelo de Regressão Linear focado na previsão da Média de Curtidas, proporcionando uma prática real de análise de dados e modelagem preditiva com um contexto relevante e aplicável no mundo do Instagram.
</p>