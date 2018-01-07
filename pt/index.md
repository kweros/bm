---
layout: default
title: Tudo o que você precisa saber sobre a mineração Bitcoin
description: Tudo o que você precisa saber sobre a mineração Bitcoin
toc:
  hwc: Comparação entre Hardwares para Mineração
  wibm: O que  Mineração de Bitcoins?
  what-is-blockchain: O que é Blockchain?
  wipow: O que é Prova de Trabalho?
  md: Qual a dificuldade de minerar Bitcoins?
  tcdp: O problema de difícil computação
  difficulty: The Bitcoin Network Difficulty Metric
  bw: A Block-recompensa
---

<center>
  <p>A Portugese translation is coming soon. Check our GitHub to learn how to contribute!</p>
</center>

<center><iframe width="720" height="394" src="https://www.youtube.com/embed/GmOzih6I1zs" frameborder="0" allowfullscreen></iframe></center>

<div class="home-grid">
	<a href="/getting-started/" class="section">
		<img src="/images/icons/mining.png"> 
		<div class="section-title">Novo em mineração?</div> 
		<div class="section-view">Vamos começar ›</div> 
	</a>
	<a href="/bitcoin-mining-hardware/" class="section">
		<img src="/images/icons/mining2.png"> 
		<div class="section-title">Hardware de Mineração</div> 
		<div class="section-view">Aprenda mais ›</div> 
	</a>
	<a href="/best-bitcoin-cloud-mining-contract-reviews/" class="section">
		<img src="/images/icons/cloud.png"> 
		<div class="section-title">Mineração em nuvem</div> 
		<div class="section-view">Aprenda mais ›</div> 
	</a>
</div>

<img class="icon-home" alt="bitcoin mining" src="/images/icons/icon-big-bitcoinfrom.png">
<h2>Como a mineração de Bitcoins trabalha</h2>
<p>De onde vêm os bitcoins? Com dinheiro em papel, um governo decide quando imprimir e distribuir dinheiro. Bitcoin não tem um governo central.</p>

<p>With Bitcoin, mineradores usam um <a href="/bitcoin-mining-software/">software especial </a> para resolver problemas de matemática e receber um determinado número de bitcoins em troca. Isto provê uma forma inteligente para emitir a moeda e também criar um incentivo para pessoas minararem.</p>

<img class="icon-home" alt="bitcoin is secure" src="/images/icons/icon-big-secure.png">
<h2>Bitcoin é seguro</h2>

<p>Mineradores de Bitcoin miners ajudam a manter a rede Bitcoin segura aprovando transações. A mineração é a parte importante que assegura a lisura das transações e mantém a rede Bitcoins estável e segura.</p>

<img class="icon-home" alt="bitcoin is secure" src="/images/icons/icon-big-links.png">
<h2>Links</h2>
<ul>
	<li><a href="https://www.weusecoins.com/" target="_blank">We Use Coins</a> - Aprenda sobre criptomoedas.<br></li>
	<li><a href="https://www.reddit.com/r/Bitcoin/" target="_blank">Bitcoin News</a> - Onde a comunidade Bitcoin encontra novidades.<br></li>
	<li><a href="http://www.bitcoin.kn">Bitcoin Knowledge Podcast</a> - Intrevistas com as pessoas mais capacitadas do Mundo Bitcoin.</li>
</ul>

<hr id="hwc" style="width: 100%; margin: 20px 0; color: #eee;" />

<h2>Comparação entre Hardwares para Mineração de Bitcoin</h2>

<p>Atualmente, baseado no <b>(1)</b> preço por hash e <b>(2)</b> eficiência elétrica as melhores opções para mineração deBitcoin miner são:</p>

<div class="hardware-comparison">
{% for miner in site.data.hardware %}
{% if miner.cat contains 'featured' %}
{% include hardware-compare.html %}
{% endif %}
{% endfor %}
</div>

<hr style="width: 100%; margin: 20px 0; color: #eee;" />
<h2 id="wibm">What is Bitcoin Mining?</h2>
<center><img src="/images/what-is-bitcoin-mining.png" width="700" height="auto">
<a href="/images/what-is-bitcoin-mining-high-resolution.png" target="_blank">Visualize e Baixe o Infográfico em Alta Resolução</a></center>

{% include page-toc.html %}

<p>Mineração de Bitcoin é o processo de adicionar registros de transação ao livro contábil público do Bitcoin que contém todas as transações passadas ou <b>blockchain</b>. Este livro contábil de transsações realizadas é chamado de blockchain por ser como um encadeamento de blocos. A cadeia de blocos serve para confirmar transações para o resto da rede tome conhecimento.
<p>Nós Bitcoin usam a <b>cadeia de blocos</b> para distinguir legítimas transações de tentativas de re-gastar dinheiro que já tenha sido gasto em outra ocasião (problema do gasto duplo).
<h3 id="what-is-blockchain">O que é Blockchain?</h3>
<center><iframe width="700" height="394" src="https://www.youtube.com/embed/YIVAluSL9SU" frameborder="0" allowfullscreen></iframe></center>
<p><a href="http://bitcoinminer.com/">Mineração de Bitcoin </a> é intencionalmente projetada para ser intensiva em recursos e difícil, de modo que o número de blocos encontrados todos os dias pelos mineiros permaneça estável. Blocos individuais  Individual blocks devem conter uma <a href="/what-is-proof-of-work/">prova de trabalho</a> para serem considerados válidos. Esta prova de trabalho é verificada por outros nós da rede Bitcoin cada vez que eles recebem um bloco. Bitcoin utiliza a função prova de trabalho <a href="/what-is-hashcash/">hashcash</a>.
<p>O propósito primordial de minerar é propocionar condições para que os nós Bitcoin alcancem um consenso em termos de segurança e anti-adulteração. Mineração é também o mecanismo usado para colocar Bitcoins em circulação: Mineradores recebem todas as taxas de transação, bem como um subsídio de novas moedas.
<p>Isto serve como propósito de disseminação de novas moedas de uma maneira descentralizada e também como motivação para pessoas proverem a segurança do sistema.
<p>A mineração de Bitcoin é assim chamada porque se assemelha à mineração de outras comodities: requer esforço e lentamente torna novas moedas disponíveis ao sistema a uma taxa que se assemelha à taxa em que mercadorias como o ouro são extraídas do solo.
<h2 id="wipow">O que é prova de trabalho?</h2>
<center><img src="/images/what-is-proof-of-work.png" width="700" height="auto">
<a href="/images/what-is-proof-of-work-high-resolution.png" target="_blank">Visualize e Baixe o Infográfico em Alta Resolução</a></center></center>
<p>Uma <a href="/what-is-proof-of-work/">prova de trabalho</a> é um pedaço de dado que foi difícil de calcular (em termos de custo e tempo computacional) a fim de satisfazer certos requisitos. Deve ser trivial verificar se os dados atendem aos referidos requisitos.
<p>Producing a proof of work can be a random process with low probability, so that a lot of trial and error is required on average before a valid proof of work is generated. Bitcoin uses the Hashcash proof of work.
<h2 id="md">What is Bitcoin Mining Difficulty?</h2>
<center><img src="/images/what-is-bitcoin-mining-difficulty.png" width="700" height="auto">
<a href="/images/what-is-bitcoin-mining-difficulty-high-resolution.png" target="_blank">Visualize and Download High-Resolution Infographic</a></center>
<h3 id="tcdp">The Computationally-Difficult Problem</h3>
<p>Bitcoin mining a block is difficult because the SHA-256 hash of a block's header must be lower than or equal to the target in order for the block to be accepted by the network.
<p>This problem can be simplified for explanation purposes: The hash of a block must start with a certain number of zeros. The probability of calculating a hash that starts with many zeros is very low, therefore many attempts must be made. In order to generate a new hash each round, a nonce is incremented. See Proof of work for more information.
<h3 id="difficulty">The Bitcoin Network Difficulty Metric</h3>
<p>The <a href="/what-is-bitcoin-mining-difficulty/">Bitcoin mining network difficulty</a> is the measure of how difficult it is to find a new block compared to the easiest it can ever be. It is recalculated every 2016 blocks to a value such that the previous 2016 blocks would have been generated in exactly two weeks had everyone been mining at this difficulty. This will yield, on average, one block every ten minutes.
<p>As more miners join, the rate of block creation will go up. As the rate of block generation goes up, the difficulty rises to compensate which will push the rate of block creation back down. Any blocks released by malicious miners that do not meet the required difficulty target will simply be rejected by everyone on the network and thus will be worthless.
<h3 id="bw">The Block Reward</h3>
<p>When a block is discovered, the discoverer may award themselves a certain number of bitcoins, which is agreed-upon by everyone in the network. Currently this bounty is 25 bitcoins; this value will halve every 210,000 blocks. See Controlled Currency Supply.
<p>Additionally, the miner is awarded the fees paid by users sending transactions. The fee is an incentive for the miner to include the transaction in their block. In the future, as the number of new bitcoins miners are allowed to create in each block dwindles, the fees will make up a much more important percentage of mining income.
