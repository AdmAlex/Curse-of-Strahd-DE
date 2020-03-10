<template>
  <div id="all">
    <div class="nav">
    <div id="balken">
      <button v-on:click="x = -10">CoS</button>
    </div>
    <div class="dropdown">
      <button class="dropbtn" v-on:click="x = -10">Menü</button>
    </div>
    <div class="dropdown">
      <button class="dropbtn" v-on:click="x = 0">Einführung</button>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Kapitel</button>
      <div class="dropdown-content">
        <button v-on:click="x = 1">Kapitel 1: In die Nebel</button>
        <button v-on:click="x = 2">Kapitel 2: Die Länder von Barovia</button>
        <button v-on:click="x = 3">Kapitel 3: Das Dorf Barovia</button>
        <button v-on:click="x = 4">Kapitel 4: Schloss Ravenloft</button>
        <button v-on:click="x = 5">Kapitel 5: Die Stadt Vallaki</button>
        <button v-on:click="x = 6">Kapitel 6: Alte Knochenmühle</button>
        <button v-on:click="x = 7">Kapitel 7: Argynvostholt</button>
        <button v-on:click="x = 8">Kapitel 8: Das Dorf Krezk</button>
        <button v-on:click="x = 9">Kapitel 9: Tsolenka-Pass</button>
        <button v-on:click="x = 10">Kapitel 10: Die Ruinen von Berez</button>
        <button v-on:click="x = 11">Kapitel 11: Van Richtens Turm</button>
        <button v-on:click="x = 12">Kapitel 12: Der Zauberer der Weine</button>
        <button v-on:click="x = 13">Kapitel 13: Der Bernsteintempel</button>
        <button v-on:click="x = 14">Kapitel 14: Yester Hill</button>
        <button v-on:click="x = 15">Kapitel 15: Werwolf Höhle</button>
      </div>
    </div>
    <div class="dropdown">
      <button class="dropbtn" v-on:click="x = 16">Nachwort</button>
    </div>
    <div class="dropdown">
      <button class="dropbtn">Anhänge</button>
      <div class="dropdown-content">
        <button v-on:click="x = 17">Anhang A: Charakteroptionen</button>
        <button v-on:click="x = 18">Anhang B: Todeshaus</button>
        <button v-on:click="x = 19">Anhang C: Schätze</button>
        <button v-on:click="x = 20">Anhang D: Monster und NPCs</button>
        <button v-on:click="x = 21">Anhang E: Das Tarokka-Deck</button>
        <button v-on:click="x = 22">Anhang F: Handouts</button>
      </div>
    </div>
  </div>
    <div id="app">
      <div id="links"></div>
      <div id="mitte">
        
        <div v-if="x === 0">
        <Einleitung />
        </div>
        <div v-else-if="x === 1">
        <Kap1 />
        </div>
        <div v-else-if="x === 2">
        <Kap2 />
        </div>
        <div v-else-if="x === 3">
        <Kap3 />
        </div>
        <div v-else-if="x === 4">
        <Kap4 />
        </div>
        <div v-else-if="x === 5">
        <Kap5 />
        </div>
        <div v-else-if="x === 6">
        <Kap6 />
        </div>
        <div v-else-if="x === 7">
        <Kap7 />
        </div>
        <div v-else-if="x === 8">
        <Kap8 />
        </div>
        <div v-else-if="x === 9">
        <Kap9 />
        </div>
        <div v-else-if="x === 10">
        <Kap10 />
        </div>
        <div v-else-if="x === 11">
        <Kap11 />
        </div>
        <div v-else-if="x === 12">
        <Kap12 />
        </div>
        <div v-else-if="x === 13">
        <Kap13 />
        </div>
        <div v-else-if="x === 14">
        <Kap14 />
        </div>
        <div v-else-if="x === 15">
        <Kap15 />
        </div>
        <div v-else-if="x === 16">
        <Nachwort />
        </div>
        <div v-else-if="x === 17">
        <AnhA />
        </div>
        <div v-else-if="x === 18">
        <AnhB />
        </div>
        <div v-else-if="x === 19">
        <AnhC />
        </div>
        <div v-else-if="x === 20">
        <AnhD />
        </div>
        <div v-else-if="x === 21">
        <AnhE />
        </div>
        <div v-else-if="x === 22">
        <AnhF />
        </div>
        <div v-else>
          <Home />
        </div>
      </div>
      <div id="rechts"></div>
    </div>
  </div>
</template>

<script>
import Home from "./components/Home.vue";
import Einleitung from "./components/Einleitung.vue";
import Kap1 from "./components/Kap1.vue";
import Kap2 from "./components/Kap2.vue";
import Kap3 from "./components/Kap3.vue";
import Kap4 from "./components/Kap4.vue";
import Kap5 from "./components/Kap5.vue";
import Kap6 from "./components/Kap6.vue";
import Kap7 from "./components/Kap7.vue";
import Kap8 from "./components/Kap8.vue";
import Kap9 from "./components/Kap9.vue";
import Kap10 from "./components/Kap10.vue";
import Kap11 from "./components/Kap11.vue";
import Kap12 from "./components/Kap12.vue";
import Kap13 from "./components/Kap13.vue";
import Kap14 from "./components/Kap14.vue";
import Kap15 from "./components/Kap15.vue";
import Nachwort from "./components/Nachwort.vue";
import AnhA from "./components/AnhA.vue";
import AnhB from "./components/AnhB.vue";
import AnhC from "./components/AnhC.vue";
import AnhD from "./components/AnhD.vue";
import AnhE from "./components/AnhE.vue";
import AnhF from "./components/AnhF.vue";


export default {
  name: "app",
  components: {
    Home,
    Einleitung,
    Kap1,
    Kap2,
    Kap3,
    Kap4,
    Kap5,
    Kap6,
    Kap7,
    Kap8,
    Kap9,
    Kap10,
    Kap11,
    Kap12,
    Kap13,
    Kap14,
    Kap15,
    Nachwort,
    AnhA,
    AnhB,
    AnhC,
    AnhD,
    AnhE,
    AnhF
  },
  props: {
    x: Number
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#links {
  width: 12em;
  float: left;
}

#mitte {
  margin-left: 12em;
  margin-right: 12em;
  background-color: rgb(235, 232, 232); 
  padding-left: 2em;
  padding-right: 2em;
  padding-top: 1em;
  padding-bottom: 1em;
  text-align: justify;
}

#rechts {
  width: 12em;
  float: right;
}

#all {
  background-color: #ad7344;
}
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
  cursor: pointer;
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
  margin-top: 53px;
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
