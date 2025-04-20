---
layout: default
---

<h1>¡Bienvenidos a mi repositorio sobre los cambios de forma Pokémon!</h1>

<input type="text" id="buscador" placeholder="Buscar sección..." onkeyup="buscarSeccion()">
<ul id="lista-secciones">
  <li><a href="#principal">PRINCIPAL</a></li>
  <li><a href="#alola">ALOLA</a></li>
  <li><a href="#galar">GALAR</a></li>
  <li><a href="#hisui">HISUI</a></li>
  <li><a href="#paldea">PALDEA</a></li>
  <li><a href="#convergente">CONVERGENTE</a></li>
  <li><a href="#paradox-pasado">PARADOX PASADO</a></li>
  <li><a href="#paradox-futuro">PARADOX FUTURO</a></li>
  <li><a href="#referencias">REFERENCIAS</a></li>
</ul>

<script>
function buscarSeccion() {
  let input = document.getElementById('buscador').value.toUpperCase();
  let ul = document.getElementById('lista-secciones');
  let li = ul.getElementsByTagName('li');
  for (let i = 0; i < li.length; i++) {
    let a = li[i].getElementsByTagName("a")[0];
    let txt = a.textContent || a.innerText;
    li[i].style.display = txt.toUpperCase().indexOf(input) > -1 ? "" : "none";
  }
}
</script>

---

## <a id="principal"></a>PRINCIPAL

![Image](https://github.com/user-attachments/assets/90a6bf1e-c12f-4725-be02-8f9887bde60d)
Bienvenido a mi portafolio, soy Alonso Vences. En este proyecto, exploramos cómo los Pokémon cambian su apariencia, tipo y habilidades al adaptarse a diferentes regiones, climas y situaciones.
---

## <a id="alola"></a>ALOLA

Las formas de Alola fueron introducidas en Pokémon Sol y Luna...

---

## <a id="galar"></a>GALAR

Las formas Galar aparecieron en Pokémon Espada y Escudo...

---

## <a id="hisui"></a>HISUI

Las formas de Hisui surgieron en Leyendas Pokémon: Arceus...

---

## <a id="paldea"></a>PALDEA

La región de Paldea nos trajo nuevos Pokémon y formas regionales...

---

## <a id="convergente"></a>CONVERGENTE

Los Pokémon convergentes son similares a otros, pero no están relacionados evolutivamente...

---

## <a id="paradox-pasado"></a>PARADOX PASADO

Pokémon de apariencia antigua, como Colmilargo y Pelarena...

---

## <a id="paradox-futuro"></a>PARADOX FUTURO

Pokémon de apariencia futurista como Ferropalmas y Ferropúas...

---

## <a id="referencias"></a>REFERENCIAS

- Bulbapedia
- Pokémon Database
- Sitio oficial de Pokémon
