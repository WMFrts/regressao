<h3> <center> REGRESSÃO</center> </h3>
<hr size="1" width="100%" align="center" noshade> 



<h3> SOBRE </h3>


<p align = 'JUSTIFY'>Regressão é uma técnica que permite quantificar e inferir a relação de uma variável dependente (variável de resposta, objetivo) com variáveis independentes (variáveis explicativas, previsoras). A análise da regressão pode ser usada como um método descritivo da análise de dados (por exemplo, o ajustamento de curvas). </p>

<p align = 'JUSTIFY'>Existem mais de 10 tipos de regressão, nesse estudo serão abordadas a regressão linear simples, regressão linear múltipla, regressão polinomial. Além disso, regressão com árvores de decisão, random forest, vetores de suporte e com redes neurais </p>


<p align = 'JUSTIFY'>Em relação aos dados, foram utilizados uma base de dados ilustrativa sobre plano de saúde para responder o questionamento: "quanto poderia custar o plano saúde dependendo da idade da pessoa?". Em outro momento, foi usado um banco de dados sobre preço de casas com a pergunta "De acordo com os dados apresentados, baseado na metragem, qual seria o preço da casa?" </p>

<p align = "JUSTIFY"> Logo abaixo, segue heatmap sobre a correlação entre os atributos referentes à base de dados que informa o preço das casas. Quanto mais claro o retângulo, maior a correlação entre o atributo da linha com a correspondente da coluna</p>


<img src="https://github.com/WMFrts/regressao/blob/main/grafico-correlacao.png">

<h3>BIBLIOTECAS/IMPORTAÇÕES</h3>


* pandas

* numpy 

* seaborn


* matplotlib.pyplot


* plotly.express

* plotly.graph_objects





<h3>ÍNDICE</h3>

<dl>
  
<dt>1 REGRESSÃO</dt>
<dt>1.1 BASE PLANO DE SAÚDE - EXPLORAÇÃO DE DADOS</dt>
<dt>1.2 PERGUNTA SOBRE O CONTEXTO</dt>
<dt>1.3 COEFICIENTE DE CORRELAÇÃO</dt>
<dt>1.4 BASE PREÇO DAS CASAS - EXPLORAÇÃO DE DADOS</dt>
<dt>1.5 PERGUNTA SOBRE O CONTEXTO</dt>
<dt>1.6 CRIAÇÃO DO MODELO DE REGRESSÃO LINEAR</dt>
<dt>1.7 MÉTRICAS DE AVALIAÇÃO</dt>
<dt>2 REGRESSÃO LINEAR MÚLTIPLA</dt>
<dt>3 REGRESSÃO POLINOMIAL</dt>
<dt>3.1 BANCO PLANO DE SAÚDE 2 - EXPLORAÇÃO DE DADOS</dt>
<dt>3.2 CRIAÇÃO DO MODELO DE REGRESSÃO POLINOMIAL</dt>
<dt>3.3 TESTE DO ALGORITMO</dt>
<dt>3.4 PREVISÕES</dt>
<dt>3.5 BASE PREÇO DAS CASAS</dt>
<dt>3.6 CRIAÇÃO DO MODELO DE REGRESSÃO POLINOMIAL</dt>
<dt>3.7 MÉTRICAS DE AVALIAÇÃO</dt>
<dt>4 REGRESSÃO COM ÁRVORES DE DECISÃO</dt>
<dt>4.1 BASE PLANO DE SAÚDE</dt>
<dt>4.2 BASE PREÇO DAS CASAS</dt>
<dt>4.3 CRIAÇÃO DA REGRESSÃO COM ÁRVORES DE DECISÃO</dt>
<dt>5 REGRESSÃO COM RANDOM FOREST</dt>
<dt>5.1 BASE PLANO DE SAÚDE 2</dt>
<dt>5.2 BASE PREÇO DAS CASAS</dt>
<dt>6 REGRESSÃO COM VETORES DE SUPORTET</dt>
<dt>6.1 BASE PLANO DE SAÚDE</dt>
<dt>6.2 SUPPORT VECTOR REGRESSIONE</dt>
<dt>6.3 KERNELS</dt>
<dt>6.4 PREVISÃO</dt>
<dt>6.5 BASE PREÇO DAS CASAS  </dt>
<dt>6.6 CRIAÇÃO DO ALGORITMO SVM, TESTE E PREVISÕES</dt>
<dt>7 REGRESSÃO COM REDES NEURAIS</dt>
<dt>7.1 BASE PLANO DE SAÚDE 2 </dt>
<dt>7.2 CRIAÇÃO DA REDE NEURAL </dt>
  
  
  
  
  
</dl>


<h3>REFERÊNCIAS</h3>


<p align = 'JUSTIFY'>REGRESSÃO (ESTATÍSTICA). In: WIKIPÉDIA, a enciclopédia livre. Flórida: Wikimedia Foundation, 2021. Disponível em: <a href= "https://pt.wikipedia.org/w/index.php?title=Regress%C3%A3o_(estat%C3%ADstica)&oldid=62175676">Regressão</a>. Acesso em: 28 fev. 2022.


<p align = 'JUSTIFY'> BHALLA, Deepanshu. 15 Types of Regression in Data Science.Listen Data, Delhi, 25, março, 2018. Disponível em:<a href= "https://www.listendata.com/2018/03/regression-analysis.html"> 15 Types of Regression in Data Science</a>. Acesso em: 28 fev. 2022.
