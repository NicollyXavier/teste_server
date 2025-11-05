<h1>🧠 Sistema de Triagem Inicial para TEA com IA</h1>
<h3>Projeto de TCC — Triagem do Transtorno do Espectro Autista utilizando M-CHAT-R/F e Modelo de IA</h3>

<p>
Este repositório contém o código-fonte do protótipo desenvolvido para o Trabalho de Conclusão de Curso cujo objetivo é investigar e demonstrar o uso de Inteligência Artificial aplicada ao apoio no diagnóstico precoce do Transtorno do Espectro Autista (TEA).
</p>

<p>
O sistema implementa uma versão digital simplificada do instrumento <b>M-CHAT-R/F</b>, permitindo que respostas sejam processadas por um modelo de Machine Learning baseado em <b>Regressão Logística</b>, que classifica o risco de TEA em:
</p>

<ul>
<li>✅ Risco Baixo</li>
<li>⚠️ Risco Moderado</li>
<li>❗ Risco Alto</li>
</ul>

<p><b>⚠️ Aviso importante:</b> Este projeto é acadêmico e <b>não substitui avaliação clínica profissional</b>.</p>

<hr>

<h2>📁 Estrutura do Projeto</h2>

<pre>
📂 questionario_tea_tcc
 ├─ index.html                 # Interface do questionário
 ├─ styles.css                 # Estilização do front-end
 ├─ script.js                  # Lógica do questionário e chamada à API
 ├─ modelo_mchat.py            # Treinamento do modelo de IA
 ├─ server_mchat.py            # API Flask para servir o modelo
 ├─ modelo_mchat.pkl           # Modelo treinado
 └─ dataset_simulado*.csv      # Base sintética utilizada
</pre>

<hr>

<h2>🚀 Funcionalidades</h2>

<ul>
<li>✅ Formulário digital baseado no M-CHAT-R/F</li>
<li>✅ Processamento com IA via API Flask</li>
<li>✅ Treinamento com dados sintéticos</li>
<li>✅ Deploy no <b>Vercel</b> (front-end)</li>
<li>✅ Deploy no <b>Render</b> (API)</li>
<li>✅ Cálculo local como fallback</li>
</ul>

<hr>

<h2>🌐 Demonstração</h2>

<table>
<tr><td>Interface Web (Vercel)</td><td><a href="https://questionarioservidor.vercel.app">https://questionarioservidor.vercel.app</a></td></tr>
<tr><td>API Flask (Render)</td><td><a href="https://mchat-backend-bg0s.onrender.com">https://mchat-backend-bg0s.onrender.com</a></td></tr>
</table>

<hr>

<h2>⚙️ Tecnologias Utilizadas</h2>

<table>
<tr><td>Front-end</td><td>HTML5, CSS3, JavaScript</td></tr>
<tr><td>Back-end</td><td>Python, Flask</td></tr>
<tr><td>Machine Learning</td><td>Scikit-Learn, Pandas, Joblib</td></tr>
<tr><td>Hospedagem</td><td>GitHub, Vercel, Render</td></tr>
</table>

<hr>

<h2>🧪 Como Executar Localmente</h2>

<h3>1️⃣ Clonar repositório</h3>
<pre>git clone https://github.com/NicollyXavier/questionario_tea_tcc.git
cd questionario_tea_tcc</pre>

<h3>2️⃣ Instalar dependências</h3>
<pre>pip install flask scikit-learn pandas joblib</pre>

<h3>3️⃣ Treinar o modelo (opcional)</h3>
<pre>python modelo_mchat.py</pre>

<h3>4️⃣ Executar o servidor</h3>
<pre>python server_mchat.py</pre>

<code>http://127.0.0.1:5000/</code>

<h3>5️⃣ Executar o front-end</h3>
<p>Abrir <code>index.html</code> no navegador</p>

<hr>

<h2>📊 Funcionamento</h2>

<ol>
<li>Usuário responde M-CHAT-R/F online</li>
<li>Script envia respostas à API</li>
<li>Modelo classifica risco</li>
<li>Interface exibe resultado</li>
<li>Fallback local caso API falhe</li>
</ol>

<hr>

<h2>🛑 Disclaimer</h2>

<p>Este protótipo possui <b>caráter exclusivamente acadêmico</b> e não deve ser utilizado para diagnóstico real.</p>

<hr>

<h2>👩‍💻 Autoria</h2>

<p><b>Daniella Morais Justino - GitHub: @daniiiiella</b> <br><b>Nicolly Mayara Xavier Lima - GitHub: @NicollyXavier</b></br> </br><br>Curso de Engenharia da Computação - UNINASSAU</p>

<hr>

<h2>📚 Referências principais</h2>

<ul>
<li>Robins et al. — M-CHAT-R/F (2014)</li>
<li>Losapio et al. — Validação brasileira (2022)</li>
<li>OMS (2023)</li>
<li>Documentação Scikit-Learn</li>
</ul>

<hr>

<h2>⭐ Contribuições</h2>

<p>Contribuições e sugestões são bem-vindas! Abra uma issue ou pull request 🤝</p>

