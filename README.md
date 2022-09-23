
<!DOCTYPE html>
<html>
<head>
    <title>Texto na aba 4-HTML s13</title>
    <meta name="author" content="Claudio Ganança" />
    <meta name="keywords" content="html, tags, design" />
    <meta name="description" content="Todos os exemplos de programação HTML" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<details>
  <summary><h4> 4-HTML s19</h4></summary>
	<div>Uma tag ‘DIV’ é semelhante à ‘P’.</div>
	<h1>h1 é bem usada pra colocar nomes de capítulos no documento.</h1>
	<h2>h2 pode ser um título para parte do texto.</h2>
	<p>Aqui um parágrafo.</p>
	<h3>h3 pode ser um subtítulo.</h3>
	<h4>h4 pode ser o subtítulo do subtítulo.</h4>
	<h5>h5 pode ser um subítem.</h5>
	<h6>h6 é o último nível desta hierarquia.</h6>
	<p>Aqui outro parágrafo.</p>
</details><hr />

<details>
  <summary><h4> 4-HTML s21</h4></summary>
		<div>O elemento 'hr' produz uma quebra de linha,<hr /> mas desenha uma linha horizontal.</div>
		<div>O elemento 'i' muda o texto para o formato <i>itálico</i>, o 'b' coloca o texto contido nele em formato <b>negrito</b>.</div>
		<div>O elemento 'big' <big>aumenta o texto</big>, e pode ser usado repetido até 6 vezes para <big><big><big><big><big><big>aumentar muito o texto </big></big></big></big></big></big>.</div>
		<div>O elemento 'small' <small>diminui o texto</small>, e pode ser usado repetido até 6 vezes para <small><small><small><small><small><small>diminuir muito o texto</small></small></small></small></small></small>.</div>
</details><hr />

<details>
  <summary><h4> 4-HTML s23</h4></summary>
		<div>O elemento <i>‘sup’ = ‘superscript’</i> ajuda a escrever exponenciação, por exemplo: <b>2<sup>3</sup> = 8</b>, ou ainda em textos, por exemplo: <b>Prof<sup>as</sup></b>.</div>
		<div>O elemento <i>‘sub’ = ‘subscript’</i> ajuda a escrever fórmula química, por exemplo: <b>H<sub>2</sub>O</b> ou uma mais complexa, como da serotonina <b>C<sub>10</sub>H<sub>12</sub></b>.</div>
</details><hr />
 
<details>
  <summary><h4> 4-HTML s27</h4></summary>
   <figure>
      <img src="Addo_CrocodileRanch_AddoLion_a06f01.jpg" alt="Leão Addo" width="70%" />
      <figcaption>
        Fig.1 - Leão Addo, do Addo Crocodile Ranch, na cidade Addo, em Eastern Cape, South Africa.
      </figcaption>
    </figure>
</details><hr />

<details>
  <summary><h4> 4-HTML s31</h4></summary>
	<svg width="400" height="100">
		<rect width="400" height="100" stroke="darkblue" stroke-width="6" fill="cyan" />
	</svg>
	<svg width="400" height="180">
		<rect width="150" height="150" x="50" y="20" rx="20" ry="20" stroke="maroon" stroke-width="8" fill="antiquewhite" />
	</svg>
	<svg width="200" height="200">
		<circle cx="100" cy="100" r="95" stroke="olive" stroke-width="4" fill="darkgreen" />
	</svg>
	<svg width="300" height="200">
	  <polygon points="100,10 40,198 190,78 10,78 160,198" stroke="purple" stroke-width="5" fill="lime" />
	</svg>
</details><hr />

<details>
  <summary><h4> 4-HTML s38</h4></summary>
<svg height="120" width="400">
  <defs>
    <linearGradient id="meuGradual_01" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" style="stop-color:#0078ff;stop-opacity:1" />
<stop offset="100%" style="stop-color:#0044aa;stop-opacity:1" />
    </linearGradient>
  </defs>

  <ellipse cx="190" cy="60" rx="180" ry="50" fill="url(#meuGradual_01)" />

  <text fill="white" font-size="45" font-family="Verdana" x="80" y="76">USCS</text>
</svg>
</details><hr />

<div style="text-align:center">
	<table style="border: 1px solid darkgray;display: inline-block;" >
	  <caption>População dos municípios:</caption>
	  <tr>
		<td style="border: 3px solid green;" >São Paulo</td>
		<td style="border: 3px solid yellow;" >Rio de Janeiro</td>
		<td style="border: 3px solid orange;" >Belo Horizonte</td>
	  </tr>
	  <tr>
		<td style="border: 2px solid darkblue;" >12.332.000</td>
		<td style="border: 2px solid darkblue;" > 6.748.000</td>
		<td style="border: 2px solid darkblue;" > 2.722.000</td>
	  </tr>
	</table>
</div>

<hr />

	<details>
	<summary><h4> 5-HTML s06</h4></summary>
	<table style="border: 1px solid darkgray;" >
	  <caption>População dos municípios:</caption>
	  <tr>
		<td style="border: 3px solid green;" >São Paulo</td>
		<td style="border: 3px solid yellow;" >Rio de Janeiro</td>
		<td style="border: 3px solid orange;" >Belo Horizonte</td>
	  </tr>
	  <tr>
		<td style="border: 2px solid darkblue;" >12.332.000</td>
		<td style="border: 2px solid darkblue;" > 6.748.000</td>
		<td style="border: 2px solid darkblue;" > 2.722.000</td>
	  </tr>
	</table>
	</details>


<details>
  <summary><h4> 5-HTML s09</h4></summary>
<table style="border: 1px solid teal;" >
 <caption>População dos municípios:</caption>
  <tr>
    <th style="border: 3px solid tan;" >Cidade</th>
    <th style="border: 3px solid antiquewhite;" >População</th>
    <th style="border: 3px solid teal;" >PIB</th>
  </tr>
  <tr>
    <td style="border: 3px solid tan;" >São Paulo</td>
    <td style="border: 3px solid antiquewhite;" >12.332.000</td>
    <td style="border: 3px solid teal;" >699.288.352.000</td>
  </tr>
  <tr>
    <td style="border: 2px solid tan;" >Rio de Janeiro</td>
    <td style="border: 2px solid antiquewhite;" > 6.748.000</td>
    <td style="border: 2px solid darkblue;" >337.594.462.000</td>
  </tr>
  <tr>
    <td style="border: 2px solid tan;" >Belo Horizonte</td>
    <td style="border: 2px solid antiquewhite;" >2.722.000</td>
    <td style="border: 2px solid darkblue;" >88.951.168.000</td>
  </tr>
</table>
</details><hr />

<details>
  <summary><h4> 5-HTML s14</h4></summary>
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
</details><hr />

<details>
  <summary><h4> 5-HTML s16</h4></summary>
<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>
</details><hr />

<details>
  <summary><h4> 5-HTML s19</h4></summary>
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ol start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
</details><hr />

<details>
  <summary><h4> 5-HTML s21</h4></summary>
<dl>
  <dt>Coffee</dt>
  <dd>Café com opções de preparo quente ou frio.</dd>
  <dt>Milk</dt>
  <dd>Leite puro,com açúcar 
      ou achocolatado.</dd>
  <dt>Tea</dt>
  <dd>Chá com vários sabores, 
      servidos quentes ou frios.</dd>
</dl>
</details><hr />

<details>
  <summary><h4> 5-HTML s26</h4></summary>
<main>
  <h1>Navegadores mais Populares</h1>
  <p>Chrome, Firefox, e Edge são os navegadores mais usados atualmente.</p>

  <article>
    <h2>Google Chrome</h2>
    <p>Google Chrome é um navegador web desenvolvido pela empresa Google, lançado em 2008. Chrome é o navegador mais popular do mundo nos dias de hoje!</p>
  </article>

  <article>
    <h2>Mozilla Firefox</h2>
    <p>Mozilla Firefox é um navegador web de código aberto (<i>open-source<>) desenvolvido pela empresa Mozilla. Firefox é o segundo navegador mais popular do mundo desde Janeiro de 2018.</p>
  </article>

  <article>
    <h2>Microsoft Edge</h2>
    <p>Microsoft Edge é um navegador web browser desenvolvido pela Microsoft, lançado em 2015. Microsoft Edge substituiu o Internet Explorer e é extremamente aderente às funcionalidades disponíveis para HTML5 e CSS3.</p>
  </article>
</main>
</details><hr />

<details>
  <summary><h4> 5-HTML s29</h4></summary>
<main>
	<article>
	  <header>
		<h1>Treinamento InovaNEX</h1>
		<p><small>Postado por Vinícius</small></p>
		<p>Passando pelos elementos com significado semântico em HTML.</p>
	  </header>
	  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Hac habitasse platea dictumst quisque sagittis purus sit amet volutpat. Scelerisque felis imperdiet proin fermentum leo vel orci porta. Scelerisque felis imperdiet proin fermentum leo. Blandit turpis cursus in hac habitasse platea dictumst.</p>
	  <footer>
		<h3>HTML</h3>
		<p>Material desenvolvido exclusivamente para treinamento de futuros desenvolvedores.</p>
	  </footer>
	</article>
</main>
</details><hr />

<details>
  <summary><h4> 5-HTML s32</h4></summary>
<main>
  <aside style="width:20%;float:left;margin-right:15px;background-color:lightgray;">
<h4>Epcot Center</h4>
<p>O Epcot é um parque temático no Walt Disney World Resort com atrações emocionantes, pavilhões internacionais, fogos de artifício premiados e eventos especiais sazonais.</p>
  </aside>
  <section>
<h2>Histórico do WWF</h2>
<p>O World Wide Fund for Nature (WWF) é uma organização internacional que trabalha em questões relacionadas à conservação, pesquisa e restauração do meio ambiente, anteriormente denominada World Wildlife Fund. O WWF foi fundado em 1961.</p>
  </section>
  <section>
<h2>Símbolo da WWF</h2>
<p>O Panda tornou-se o símbolo da WWF. O conhecido logotipo do panda da WWF originou-se de um panda chamado Chi Chi que foi transferido do Zoológico de Pequim para o Zoológico de Londres no mesmo ano do estabelecimento do WWF.</p>
  </section>
</main>
</details><hr />

<details>
  <summary><h4> 5-HTML s35</h4></summary>
<dialog style="display:block;width:35%;position:absolute;z-index:1;float:left; margin-left:30%;background-color:yellow;" >
  <h5>ATENÇÃO</h5>
  <p>Aqui uma mensagem de erro de exemplo para o pessoal em treinamento.</p>
</dialog>
<main>
  <article>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Hac habitasse platea dictumst quisque sagittis purus sit amet volutpat. Scelerisque felis imperdiet proin fermentum leo vel orci porta. Scelerisque felis imperdiet proin fermentum leo. Blandit turpis cursus in hac habitasse platea dictumst. Vitae aliquet nec ullamcorper sit amet risus nullam eget. Enim blandit volutpat maecenas volutpat blandit. Sed arcu non odio euismod lacinia at quis. Magna sit amet purus gravida. Pulvinar pellentesque habitant morbi tristique senectus et netus et malesuada. Odio pellentesque diam volutpat commodo. Porta lorem mollis aliquam ut porttitor leo a diam sollicitudin. Ornare arcu dui vivamus arcu felis bibendum.
  </article>
</main>
</details><hr />


<details>
  <summary><h4> 5-HTML s38</h4></summary>
<div>Lista de <span id="tp_titulo" style="background-color:lightgreen;"> produtos </span></div>

<ul>
  <li><data value="A1053">Arroz Número Um</data></li>
  <li><data value="A1122">Macarrão Tagliarini</data></li>
  <li><data value="A1055">Feijão Ribeirão</data></li>
</ul>
</details><hr />

<details>
  <summary><h4> 5-HTML s41</h4></summary>
	<h1>Bem vindo à USCS</h1>
	<details>
		  <summary>Campus situado em São Caetano do Sul</summary>
		  <img src="USCS.png" alt="USCS" width="10%" />
		  <p>Rua Conceição, 321<br />Bairro Santo Antônio</p>
	</details><hr />
</details><hr />
<br /><br /><br /><br /><br /><br /><br /><br /><br />

</body>
</html>
exemplao.html
Exibindo exemplao.html…
