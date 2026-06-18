<h1>🪐 AstroMesh AI</h1>
<p><strong>A Rede Inteligente do Espaço Profundo</strong></p>

<p>Projeto de arquitetura, modelagem de dados e design de solução desenvolvido para o <strong>Global Solution 2026 (FIAP)</strong>. 

<hr />

<h2>🛸 O Desafio da Comunicação Interplanetária</h2>
<p>Atualmente, as comunicações espaciais enfrentam desafios críticos como distâncias enormes (com latência entre Terra e Marte variando de 3 a 22 minutos), perda massiva de pacotes de dados por conta de tempestades solares e risco de falhas críticas em satélites retransmissores que podem comprometer missões inteiras.</p>

<h2>🚀 A Solução: AstroMesh AI</h2>
<p>O <strong>AstroMesh AI</strong> é o conceito de uma plataforma WEB centralizada de última geração projetada para monitorar, gerenciar e otimizar as comunicações em malha (mesh network) entre operadores na Terra, bases na Lua, Marte e as redes de satélites orbitais.</p>

<h3>🛠️ Módulos Projetados</h3>
<ul>
  <li><strong>Dashboard Central:</strong> Monitoramento de indicadores críticos (latência média geral, taxa de perda de pacotes e tráfego de dados).</li>
  <li><strong>Mapa Espacial Dinâmico:</strong> Visualização em malha das rotas de transmissão (ativas, congestionadas ou fora de operação).</li>
  <li><strong>Central de Alertas Automatizada:</strong> Triagem de incidentes categorizados por gravidade através de notificações em tempo real.</li>
  <li><strong>Assistente de IA Cognitivo:</strong> Terminal integrado em linguagem natural para consultas rápidas e execução de comandos de roteamento.</li>
</ul>

<hr />

<h2>💾 Arquitetura e Modelagem de Dados</h2>
<p>O projeto conta com a estruturação completa de um Banco de Dados Relacional para suportar a telemetria e o gerenciamento do ecossistema espacial:</p>

<h3>Entidades Mapeadas:</h3>
<ul>
  <li><code>USUARIOS</code>: Operadores de missão espacial.</li>
  <li><code>SATELITES</code>: Nós repetidores da malha orbital.</li>
  <li><code>TRANSMISSOES</code>: Registro detalhado do tráfego de dados e tamanhos de arquivos enviados.</li>
  <li><code>ALERTAS</code>: Incidentes e oscilações críticas detectadas na rede.</li>
  <li><code>INTERACOES_CHAT</code>: Histórico do suporte cognitivo por IA.</li>
</ul>

<h3>Script DDL (Geração do Banco):</h3>
<pre>
CREATE TABLE usuarios (
    id_usuario INT PRIMARY KEY,
    nome VARCHAR(100) NOT NULL,
    email VARCHAR(100) UNIQUE NOT NULL,
    cargo VARCHAR(50)
);

CREATE TABLE satelites (
    id_satelite INT PRIMARY KEY,
    nome VARCHAR(50) NOT NULL,
    localizacao_orbita VARCHAR(50) NOT NULL,
    status VARCHAR(20) NOT NULL
);
</pre>
<p><em>*O script estrutural completo com chaves estrangeiras e relacionamentos está documentado no escopo do projeto.</em></p>

<hr />

<h2>🧠 O Motor de Inteligência Artificial</h2>
<ol>
  <li><strong>Análise Preditiva de Falhas (ML):</strong> Algoritmos de Machine Learning analisam variações sutis de telemetria de hardware (energia, temperatura) antes que falhas interrompam a missão.</li>
  <li><strong>Roteamento Dinâmico Inteligente:</strong> Em caso de blackout parcial, a IA recalcula as rotas instantaneamente utilizando caminhos alternativos com a menor perda possível.</li>
</ol>

<hr />

<h2>🎥 Vídeo Pitch</h2>
<p>Assista à apresentação completa do conceito e impacto da solução no YouTube: <a href="https://youtu.be/nbPMrCwwsD4" target="_blank">AstroMesh AI - Pitch</a></p>

<h2>👥 Integrantes</h2>
<ul>
  <li><strong>Pedro Henrique Ferreira Borges</strong></li>
  <li>Evelyn Oliveira Costa</li>
</ul>
