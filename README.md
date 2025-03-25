# Sentiment Analysis with Python and NLTK

Este projeto utiliza a biblioteca NLTK para realizar análise de sentimento em frases em inglês. A análise é feita usando o **VaderSentiment**, que calcula a pontuação de sentimento baseado na polaridade das palavras.

## Função Utilizada

A análise de sentimento foi realizada com a seguinte linha de código:

score = sia.polarity_scores(sentence)


onde `sia` é uma instância de `SentimentIntensityAnalyzer` e `sentence` é a frase a ser analisada.

## Resultados

Aqui estão os resultados da análise de sentimento para as 25 frases:

| Frase                                                                 | Compound Score | Sentimento       |
|-----------------------------------------------------------------------|----------------|------------------|
| "This is the best day of my life! I feel ecstatic!"                   | 0.844          | Positive         |
| "I absolutely adore this movie, it's a masterpiece!"                 | 0.851          | Positive         |
| "Winning the award made me over the moon with joy!"                   | 0.900          | Positive         |
| "This cake is heavenly, I've never tasted anything better!"          | 0.438          | Positive         |
| "I love this product beyond words, it's perfect!"                     | 0.848          | Positive         |
| "The weather today is lovely and refreshing."                         | 0.586          | Positive         |
| "I really enjoy spending time with my friends."                       | 0.764          | Positive         |
| "This book is quite interesting and well-written."                    | 0.458          | Positive         |
| "The service at the restaurant was excellent."                        | 0.572          | Positive         |
| "Learning new skills makes me happy."                                 | 0.572          | Positive         |
| "The meeting starts at 3 PM in the conference room."                  | 0.000          | Neutral          |
| "This pencil is made of wood and graphite."                           | 0.000          | Neutral          |
| "The train arrives at platform 2."                                    | 0.000          | Neutral          |
| "Water boils at 100 degrees Celsius."                                 | 0.000          | Neutral          |
| "The document has 15 pages."                                          | 0.000          | Neutral          |
| "The delay in the flight was frustrating."                            | -0.637         | Negative         |
| "I dislike the cold weather in winter."                               | -0.382         | Negative         |
| "The coffee tasted bitter and unpleasant."                            | -0.710         | Negative         |
| "The traffic today is unbearable."                                    | 0.000          | Neutral          |
| "The movie had a disappointing ending."                               | -0.494         | Negative         |
| "This is the worst experience I've ever had!"                         | -0.659         | Negative         |
| "I hate this place, it's disgusting and filthy!"                      | -0.812         | Negative         |
| "The customer service was a nightmare!"                               | 0.000          | Neutral          |
| "This food tastes like garbage, I’m horrified!"                       | -0.316         | Negative         |
| "I’m devastated by the terrible news."                                | -0.796         | Negative         |

## Como Executar
1. Instale o NLTK:
pip install nltk

2. Baixe o corpus necessário:
nltk.download('vader_lexicon')

3. Execute o script Python para realizar a análise.

Este projeto demonstra como utilizar a biblioteca NLTK para análise de sentimento em frases em inglês.
