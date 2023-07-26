<div align="center">
  <img height="150" src="https://camo.githubusercontent.com/62da68eb62b1e5f175f7d1f0191dd89a653d7908feb22d37d4a0ab07365d6791/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f4d3967624264396e6244724f5475314d71782f67697068792e676966"  />
</div>

###

<div align="center">
  <a href="https://www.linkedin.com/in/carlos-campanari/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
</div>

###

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=ccampa896.ccampa896&"  />
</div>

###

<h1 align="center">Modelagem de Banco de Dados Relacional</h1>

###

<h3 align="left">Normalização</h3>

###

<p align="justify">Após as três etapas iniciais (modelagem conceitual, lógica e física), podemos seguir para a etapa de normalização do banco de dados. Segunda a Escola Alura, chegou a hora de <i>"aprender a trabalhar com normalização de dados para reduzir a redundância, ganhar integridade e desempenho dos dados. Ainda sobre normalização, vamos conhecer a forma normal de Boyce-Codd, uma regra para tratar alguns tipos de anomalias no banco de dados"</i>.</p>

###

<p align="justify">O Professor Max Roberto Pereira, da Universidade Cesumar - Maringá/PR, define normalização como <i>"uma técnica de projeto de banco de dados que reduz a redundância de dados e elimina aspectos indesejáveis, como anomalias nas operações de inserção, alteração e eliminação."</i> Desta forma, as tabelas maiores são divididas em tabelas menores, relacionando-se através do tipos de relacionamentos estudados nos projetos conceitual e lógico.</p>

###

<p align="left">Conceitos importantes estudados durante o curso:</p>

###

<p align="left"><strong>Dependência Funcional</strong>:</p>
- A dependência funcional estabelece uma relação de atributos dentro da tabela. Exemplo: CPF -> nome;
- O atributo que determina o valor é chamado de Determinante. O outro atributo é chamado de Dependente.

###

<p align="left"><strong>Primeira Forma Normal - 1FN</strong></p>
<ul>
  <li>Evitar ter mais de um assunto em uma tabela;</li>
  <li>Possuir somente valores atômicos (indivisíveis);</li>
  <li>Não há grupos de atributos repetidos (há apenas um dado por coluna nas linhas);</li>
  <li>Existe uma chave primária;</li>
  <li>A relação não possui atributos multivalorados ou relações aninhadas.</li>
</ul>

###

<p align="left"><strong>Segunda Forma Normal - 2FN</strong></p>
<ul>
  <li>Estar na Primeira Forma Normal;</li>
  <li>Atributos não-chave dependem da chave composta em sua totalidade.</li>
</ul>

###

<p align="left"><strong>Terceira Forma Normal - 3FN</strong></p>
<ul>
  <li>Estar na Segunda Forma Normal;</li>
  <li>Se nenhuma coluna possui dependência transitiva em relação a outra coluna que não participe da chave primária.</li>
</ul>

###

<p align="left"><strong>Forma Normal de Boyce-Codd - FNBC</strong></p>
<ul>
  <li>Versão mais rigorosa da 3FN;</li>
  <li>Se e somente se todos os determinantes são chaves candidatas;</li>
  <li>Uma chave candidata é um conjunto de um ou mais atributos que podem identificar de forma única uma tupla (linha) em uma relação (tabela). Cada relação em um banco de dados deve ter pelo menos uma chave candidata.</li>
</ul>

###

<p align="left"><strong>Quarta Forma Normal - 4FN</strong></p>
<ul>
  <li>Estar na Terceira Forma Normal;</li>
  <li>Não ter mais de um atributo multivalorado.</li>
</ul>

###

<p align="left"><strong>Quinta Forma Normal - 5FN</strong></p>
<ul>
  <li>Estar na Quarta Forma Normal;</li>
  <li>Não possuir dependência de junção.</li>
</ul>

###

<p align="justify">A normalização estudada neste curso foi realizada através de representação gráfica em planilhas eletrônicas pelo <a href="https://docs.google.com/spreadsheets/u/0/" target="_blank">Google Sheets</a> e posteriormente aplicadas no projeto físico no SQL Power Architect.</p>

###

<p align="left">REFERÊNCIAS:</p>
<ul>
<li><i>PEREIRA, Max Roberto. Banco de Dados e Mineração. Maringá - PR: Unicesumar, 2021. 228 p.</i></li>
<li><i>SILBERSCHATZ, Abraham; KORTH, S.; SUDARSHAN, Henry F. Sistema de Banco de Dados. 7. ed. Rio de Janeiro: GEN LTC, 2020. 754 p.</i></li>
</ul>

###

<h3 align="left">🛠 Language and tools</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" height="40" alt="google logo"  />
  <img width="12" />
  <img src="./power.jpeg" height="40" alt="linux logo"  />
</div>

###

<h3 align="left">🔥   My Stats :</h3>

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=ccampa896&locale=en&mode=daily&theme=dark&hide_border=false&border_radius=5&order=3" height="220" alt="streak graph"  />
</div>

###
