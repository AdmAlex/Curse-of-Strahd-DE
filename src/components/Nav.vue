<template>
  <div class="nav">
    <div id="balken">
      <button v-on:click="x = 0">CoS</button>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Einführung</button>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Kapitel</button>
      <div class="dropdown-content">
        <button>Kapitel 1: In die Nebel</button>
        <button>Kapitel 2: Die Länder von Barovia</button>
        <button>Kapitel 3: Das Dorf Barovia</button>
        <button>Kapitel 4: Schloss Ravenloft</button>
        <button>Kapitel 5: Die Stadt Vallaki</button>
        <button>Kapitel 6: Alte Knochenmühle</button>
        <button>Kapitel 7: Argynvostholt</button>
        <button>Kapitel 8: Das Dorf Krezk</button>
        <button>Kapitel 9: Tsolenka-Pass</button>
        <button>Kapitel 10: Die Ruinen von Berez</button>
        <button>Kapitel 11: Van Richtens Turm</button>
        <button>Kapitel 12: Der Zauberer der Weine</button>
        <button>Kapitel 13: Der Bernsteintempel</button>
        <button>Kapitel 14: Yester Hill</button>
        <button>Kapitel 15: Werwolf Höhle</button>
      </div>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Nachwort</button>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Anhänge</button>
      <div class="dropdown-content">
        <button>Anhang A: Charakteroptionen</button>
        <button>Anhang B: Todeshaus</button>
        <button>Anhang C: Schätze</button>
        <button>Anhang D: Monster und NPCs</button>
        <button>Anhang E: Das Tarokka-Deck</button>
        <button>Anhang F: Handouts</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Nav",
  props: {
    x: Number
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* Style The Dropdown Button */
.dropbtn {
  background-color: #683913;
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

#balken {
  background-color: #683913;
  padding: 14.5px;
  border: none;
  cursor: pointer;
  position: relative;
  display: inline-block;
}

#balken button {
  border: none;
  background-color: #683913;
  color: white;
  font-size: 16px;
}

.nav {
  background-color: #683913;
}

/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: inline-block;
}

/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content button {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  border: none;
  background-color: white;
  min-width: 160px; 
}

/* Change color of dropdown links on hover */
.dropdown-content button:hover {
  background-color: #f1f1f1;
}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {
  display: block;
}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {
  background-color: #72441f;
}
</style>
