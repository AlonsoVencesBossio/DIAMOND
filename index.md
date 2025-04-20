---
layout: default
---

<h1>¡Bienvenidos a mi repositorio sobre los cambios de forma Pokémon!</h1>

![Image](https://github.com/user-attachments/assets/90a6bf1e-c12f-4725-be02-8f9887bde60d)

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

En este sitio encontrarás una recopilación completa de los cambios de forma en Pokémon, organizados por región y tipo. Desde las primeras formas regionales introducidas en Alola, hasta las nuevas variantes Paradoja de Pasado y Futuro en Paldea, pasando por formas únicas como las Convergentes y las exclusivas de Hisui y Galar.

Cada sección te llevará a una categoría específica, explicando los Pokémon que cambian su tipo, forma, habilidad o incluso su historia en el lore. También incluimos una sección de Referencias con las fuentes consultadas para asegurar la precisión del contenido.

---

## <a id="alola"></a>☀️ALOLA

Las formas de Alola fueron introducidas en Pokémon Sol y Luna...

---

## <a id="galar"></a>🏰GALAR

Las formas Galar aparecieron en Pokémon Espada y Escudo...

---

## <a id="hisui"></a>🏛️HISUI

Las formas de Hisui surgieron en Leyendas Pokémon: Arceus...

---

## <a id="paldea"></a>🔥PALDEA

La región de Paldea nos trajo nuevos Pokémon y formas regionales...

---

## <a id="convergente"></a>🔄CONVERGENTE

Los Pokémon convergentes son similares a otros, pero no están relacionados evolutivamente...

---

## <a id="paradox-pasado"></a>⏳PARADOX PASADO

Pokémon de apariencia antigua, como Colmilargo y Pelarena...

---

## <a id="paradox-futuro"></a>⏳PARADOX FUTURO

Pokémon de apariencia futurista como Ferropalmas y Ferropúas...

---

## <a id="referencias"></a>🤝REFERENCIAS

- Bulbapedia
- Pokémon Database
- Sitio oficial de Pokémon

