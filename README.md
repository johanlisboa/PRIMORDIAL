# PRIMORDIAL
<!-- Menu lateral com apenas 2 botões -->
<nav>
  <button onclick="mostrarOcultar('aps')">APS</button>

  <button onclick="mostrarOcultar('plantao')">Plantão</button>
</nav>

<!-- Seção APS oculta inicialmente -->
<section id="aps" style="display:none">

  <button onclick="mostrarOcultar('idoso')">Idoso</button>

  <button onclick="mostrarOcultar('cronicos')">Crônicos</button>

  <!-- outros subitens da APS -->

</section>

<!-- Seção Plantão oculta inicialmente -->  
<section id="plantao" style="display:none">

  <button onclick="mostrarOcultar('atestados')">Atestados</button>

  <button onclick="mostrarOcultar('exames')">Exames</button>

  <!-- outros subitens do Plantão -->

</section>

<!-- Subseções compartilhadas -->
<section id="mulher" style="display:none">
  <!-- conteúdo mulher -->
</section>

<section id="crianca" style="display:none">
  <!-- conteúdo criança --> 
</section>
