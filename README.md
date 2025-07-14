<h1 align="center">Datarisk Case – Junior Data Science</h1>

<p align="center">
  Solução para o desafio de Data Science Júnior da <strong>Datarisk</strong>, com análise, modelagem e predições.
</p>

<h2 id="estrutura">📁 Estrutura do Projeto</h2>
<ul>
  <li><code>data/</code>: arquivos <code>train.csv</code> e <code>test.csv</code></li>
  <li><code>notebooks/main.ipynb</code>: EDA, pré-processamento e modelagem</li>
  <li><code>src/</code>: scripts Python (opcional) para treino e predição</li>
  <li><code>outputs/</code>: modelo treinado e submissão gerada</li>
  <li><code>requirements.txt</code>: dependências do projeto</li>
</ul>

<h2 id="instalacao">🚀 Como Executar</h2>
<pre><code>pip install -r requirements.txt
jupyter notebook notebooks/main.ipynb
# Opcional:
python src/train.py      # treinar
python src/predict.py    # gerar submissões
</code></pre>

<h2 id="metodologia">⚙️ Metodologia</h2>
<ul>
  <li><strong>EDA:</strong> limpeza e visão dos dados (outliers, missing)</li>
  <li><strong>Engenharia de Features:</strong> criação/transformação de variáveis relevantes</li>
  <li><strong>Modelagem:</strong> testes com modelos como Logistic Regression, Random Forest, XGBoost</li>
  <li><strong>Validação:</strong> cross-validation e divisão treino/teste</li>
  <li><strong>Predição:</strong> aplicação do modelo e geração do arquivo final</li>
</ul>

<h2 id="resultados">📊 Resultados</h2>
<p>Desempenho do melhor modelo (exemplo):</p>
<ul>
  <li>Acurácia: <strong>0.84</strong></li>
  <li>F1‑Score: <strong>0.82</strong></li>
  <li>Features mais importantes: idade, renda, número de atrasos</li>
</ul>

<h2 id="proximos">🔭 Próximos Passos</h2>
<ul>
  <li>Refinar hiperparâmetros com <code>GridSearchCV</code></li>
  <li>Implementar validação temporal ou K-fold avançado</li>
  <li>Publicar API simples para inferência (FastAPI / Flask)</li>
  <li>Adicionar testes unitários e CI/CD</li>
</ul>

<h2 id="contato">✉️ Contato</h2>
<p>Seu Nome – <a href="mailto:seu.email@example.com">seu.email@example.com</a> – <a href="https://github.com/seu-usuario">GitHub</a></p>
