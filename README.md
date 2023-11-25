# Projeto-Classificador-Multilabel-NLP

<p>
<div style="text-align: justify; max-width: 800px; margin: 0;">
Este projeto propõe o uso de técnicas de <strong> processamento de linguagem natural </strong> através do desenvolvimento de um projeto de ciência de dados para a <strong> classificação das reclamações de clientes insatisfeitos com serviços financeiros </strong>, classificando a reclamação de acordo ao tipo de produto que se refere com o a utilização de um modelo preditivo de tipo <strong> classificador multirrótulo</strong>.
 </p>
Foram experimentados algoritmos de redes neurais como <strong> BERT, RoBerta e GPT2 </strong>, e modelos ensemble como o <strong> OneVSRest</strong> com base em <strong> regressão logística</strong>.
</p>
Depois da análise, conseguimos avaliar e escolher o modelo que teve a melhor performance com os dados fornecidos. Neste caso a escolha é pelo modelo de <strong> OneVSRest </strong>, que apesar da simplicidade do algoritmo em comparação às redes neurais apresentou um melhor desempenho com os dados, possivelmente porque foi utilizada a <strong> vetorização </strong> no lugar de utilizar a tokenização como foi para as redes neurais.
No último treinamento com toda a base utilizando o modelo OneVSRest utilizando a regressão logística obtivemos um resultado melhor nas <strong> metricas de hamming loss e acurácia </strong>.
</div>
<p>
</p>
<p align="center">
<img src= "image.png" alt="NLP"
width="500" height="300">
</p>