<h1>🍷 Previsão da Qualidade de Vinhos Tintos com Regressão Linear Múltipla</h1>

<p>
Este projeto tem como objetivo aplicar técnicas de <strong>ciência de dados</strong> e <strong>regressão linear múltipla</strong> para prever a <strong>qualidade de vinhos tintos</strong> com base em suas propriedades físico-químicas.
</p>

<p>
Utilizando o <a href="https://archive.ics.uci.edu/dataset/186/wine+quality" target="_blank">Wine Quality Dataset</a>, disponibilizado pela <strong>UCI Machine Learning Repository</strong>, desenvolvemos uma abordagem prática que envolve etapas clássicas da análise preditiva: exploração dos dados, visualização, modelagem estatística e avaliação de desempenho.
</p>

<p>
A variável alvo <code>quality</code> é uma nota sensorial atribuída por especialistas, variando de 0 a 10. As variáveis preditoras incluem características como acidez, teor alcoólico, pH, entre outras.
</p>

<hr />

<h2>🔍 Etapas do projeto</h2>
<ul>
  <li>Importação dos dados com <code>ucimlrepo</code></li>
  <li>Análise exploratória (distribuições, correlações)</li>
  <li>Divisão dos dados em treino e teste</li>
  <li>Treinamento de modelo de regressão linear múltipla</li>
  <li>Avaliação com métricas como MAE, RMSE e R²</li>
  <li>Análise gráfica dos resultados (valores previstos vs. reais, distribuição dos resíduos)</li>
</ul>

<hr />

<h2>📊 Principais resultados</h2>
<ul>
  <li><strong>MAE:</strong> 0.57</li>
  <li><strong>RMSE:</strong> 0.74</li>
  <li><strong>R²:</strong> 0.26</li>
</ul>

<p>
Esses resultados indicam que, embora o modelo capture parte da variabilidade da qualidade, há espaço para melhorias com modelos mais robustos.
</p>

<hr />

<h2>💡 Próximos passos</h2>
<ul>
  <li>Testar algoritmos não lineares como Random Forest ou XGBoost</li>
  <li>Aplicar regularização (Ridge, Lasso)</li>
  <li>Ajustar hiperparâmetros e explorar técnicas de engenharia de atributos</li>
</ul>

<hr />

<h2>📁 Dataset</h2>
<ul>
  <li><strong>Fonte:</strong> <a href="https://archive.ics.uci.edu/dataset/186/wine+quality" target="_blank">Wine Quality – UCI Machine Learning Repository</a></li>
  <li><strong>Tipo:</strong> Vinho tinto</li>
  <li><strong>Registros:</strong> 1.599 amostras</li>
  <li><strong>Variáveis:</strong> 11 preditoras + 1 alvo (<code>quality</code>)</li>
</ul>
