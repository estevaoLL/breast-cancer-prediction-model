Predição de Câncer de Mama

Sobre o Projeto
Este foi um trabalho acadêmico em que exploramos o uso de Redes Neurais para auxiliar no diagnóstico de câncer de mama. Utilizamos dados derivados da digitalização de imagens de tumores (massa mamária) obtidos do estado de Wisconsin, Estados Unidos. O nosso objetivo foi entender profundamente os dados e treinar um modelo capaz de distinguir padrões entre tumores benignos e malignos.

O que desenvolvemos e aprendemos:

Análise Exploratória: O dataset original contava com 30 características extraídas (como raio, suavidade e dimensão fractal). Construímos histogramas e boxplots e percebemos, por exemplo, que tumores malignos tendem a apresentar raios maiores, enquanto características como a dimensão fractal tinham pouca variação entre os diagnósticos.

Otimização e Redução de Dados: Um dos maiores aprendizados foi lidar com dados redundantes que poderiam causar overfitting ou lentidão no aprendizado do modelo. Utilizamos uma Matriz de Correlação e descobrimos variáveis com 100% de semelhança (como radius_mean e perimeter_mean). Fizemos uma seleção criteriosa e reduzimos o dataset de 30 para 18 atributos essenciais, deixando a base muito mais "limpa" e eficiente.

Modelagem e Resultados: Com os dados refinados, aplicamos um modelo de Rede Neural (Multilayer Perceptron) utilizando Python e a biblioteca TensorFlow/Keras. Graças a esse forte tratamento prévio dos dados, nosso modelo alcançou uma acurácia de 97% e 0,99 de AUC na classificação final, demonstrando alta confiabilidade na distinção dos tumores.

Um grande ponto que levamos desse trabalho é que, no campo da inteligência artificial e saúde, o pré-processamento e a interpretação correta das variáveis são tão importantes quanto a escolha do modelo preditivo em si.

Membros do grupo:

Estevão dos Santos Mello

Arthur Tavares Lindolpho

Cauã Gomes

Guilherme Alves

Marcelo Ângelo

Nicolas Ouverney

Dataset utilizado no trabalho:

Breast Cancer Wisconsin Data Set. Disponível em: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

Tecnologias: Python, TensorFlow, Keras, Scikit-learn, Pandas, Jupyter Notebook, Git.
