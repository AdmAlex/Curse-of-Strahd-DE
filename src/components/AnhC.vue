<template>
  <div class="einl">
    <div>
      <h1>Kapitel 12: Der Zauberer der Weine</h1>
      <hr />

      <h2></h2>
      <hr />
      <div></div>
      <h2></h2>
      <hr />
      <div></div>
      <h2></h2>
      <hr />
      <div></div>
      <h2></h2>
      <hr />
      <div></div>
      
    </div>

    <h1>Einleitung</h1>
    <hr />

    <h2>Ausführen des Abenteuers</h2>
    <hr />

    <div class="box">
      <h4>EIN KLASSISCHER NACHERZÄHLUNG</h4>
    </div>

    <div class="flavor"></div>

    <h3>Story Übersicht</h3>
    <hr />

    <p class="bold">Bereiche nach Ebenen</p>
    <br />

    <table>
      <tr>
        <th>Durchschnittliches Level</th>
        <th>Area</th>
        <th>Kapitel</th>
      </tr>
      <tr>
        <td>1 bis 3</td>
        <td>Dorf von Barovia</td>
        <td>3</td>
      </tr>
      <tr>
        <td>4</td>
        <td>Stadt Vallaki</td>
        <td>5</td>
      </tr>
    </table>
    <ul>
      <li>Wenn es so aussieht, als hätten die Charaktere alles unter Kontrolle, kann man eine Windböe haben, die plötzlich ihre Fackeln ausbläst und sie in die Dunkelheit stürzt.</li>
      <li>Bevor ein Monster erscheint, nimm dir einen Moment Zeit, um den Geruch zu beschreiben, der ihm vorausgeht, den unheimlichen Klang, den es macht, oder den seltsamen Schatten, den es wirft.</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Kap12",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-size: 30px;
  font-weight: bold;
}

ul {
  list-style-type: circle;
  margin-left: 15px;
  margin-right: 15px;
}

table {
  width: 100%;
}

td {
  padding-right: 15px;
  padding-left: 15px;
  border: 1px black solid;
}

.text {
  padding-right: 5px;
  padding-left: 0px;
  border: 0px;
}

#bcos03-01 {
  width: 1800px;
  height: 350px;
}

.bunter {
  text-align: center;
  font-weight: bold;
  font-style: italic;
}

th {
  padding-right: 15px;
  padding-left: 15px;
  border: 1px black solid;
}

h2 {
  font-size: 23px;
  font-weight: bold;
}

h3 {
  font-size: 18px;
  font-weight: bold;
}

h4 {
  font-weight: bold;
}

hr {
  background-color: green;
}

.box {
  font-size: 14px;
}

.flavor {
  border: 1px solid black;
  padding: 15px;
  font-size: 14px;
  background-color: lightgrey;
}

.bold {
  font-weight: bold;
}
</style>
