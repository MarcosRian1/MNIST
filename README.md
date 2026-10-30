<h1 align="center">
  Previsão de classificador MNIST
</h1>

<h2 id="objetivo">🎯 Objetivo</h2>

<p>
Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever números escritos a mão de diferentes formatos, com base nas features (pixels) do dataset.
</p>

<h2 id="fonte">🗃️ Dataset</h2>

<p>
Os dados utilizados neste projeto foram obtidos da biblioteca Scikit-Learn, denominada <i>mnist_784</i>.
</p>

<p>
Inicialmente, foram identificadas:
</p>

<ul>
  <li>70.000 registros de números escritos a mão.</li>
</ul>

<p>Neste projeto foi utilizado o SGDClassifier como modelo para treinamento dos dados. Também se utilizou o Cross Validation Predict para verificar a generalização durante o treinamento.</p>

<h2 id="resultados">📊 Resultados</h2>

<p>
Por fim, o modelo final foi treinado e avaliado sobre o conjunto de teste. Utilizado a matriz de confusão e normalizado os dados para entender melhor a taxa de erro em cada label.
</p>

| Métrica | Resultado |
|---|---:|
| Acurácia | `0.87` |
