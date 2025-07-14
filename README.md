<h1 align="center">Case – Junior Data Science</h1>

<p align="center">
  Solução para o desafio de Data Science Júnior da <strong>Datarisk</strong>, com análise, modelagem e predições.
</p>

<h2 id="estrutura">📁 Estrutura do Projeto</h2>
<ul>
  <li><code>data/</code>: arquivos <code>base_pagamentos_desenvolvimento.csv</code> e <code>base_pagamentos_teste.csv</code> para treino, teste e validação do modelo.</li>
  <li><code>data/</code>: arquivos <code>base_info.csv</code> e <code>base_cadastral.csv</code> com informações dos clientes.</li>
  <li><code>Probabilidade de inadimplência.ipynb</code>: EDA, pré-processamento, modelagem.</li>
  <li><code>requirements.txt</code>: dependências do projeto.</li>
</ul>

<h2 id="instalacao">🚀 Como Executar</h2>
<pre><code>pip install -r requirements.txt
jupyter notebook Probabilidade de inadimplência.ipynb
</code></pre>

<h2 id="metodologia">⚙️ Metodologia</h2>
<ul>
  <li><strong>EDA:</strong> limpeza e visão dos dados (outliers, missing)</li>
  <li><strong>Engenharia de Features:</strong> criação/transformação de variáveis relevantes</li>
  <li><strong>Modelagem:</strong> testes com modelos como Logistic Regression, Random Forest, Neural Network</li>
  <li><strong>Predição:</strong> aplicação do modelo e geração do arquivo final</li>
</ul>

<h2 id="resultados">📊 Resultados</h2>
<p>Desempenho do melhor modelo RandomForestClassifier:</p>
<ul>
  <li>Acurácia: <strong>0.87</strong></li>
  <li>F1‑Score: <strong>0.86</strong></li>
  <li>Features mais importantes: VALOR_A_PAGAR, PRAZO, HISTORICO_ATRASO</li>
</ul>


<h2 id="contato">✉️ Contato</h2>
<p>Seu Nome – <a href="mailto:wesleybritowx@gmail.com">wesleybritowx@gmail.com</a> – <a href="https://github.com/wbrito0">GitHub</a></p>
