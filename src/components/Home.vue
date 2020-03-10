<template>
  <div class="home">
    <h2>Inhaltsverzeichnis</h2><br>
    <table>
      <tr>
        <td>
          <h1>Einführung</h1>
          <hr>
          Ausführen des Abenteuers<br>
          Zeichen des Schreckens<br><br>
          <h1>Kap. 1: In den Nebel hinein</h1>
          <hr>
          Strahd von Zarovich<br>
          Das Schicksal von Ravenloft<br>
          Abenteuer-Haken<br><br>
          <h1>Kap. 2: Die Länder von Barovia</h1>
          <hr>
          Die Lage des Landes<br>
          Barovianer<br>
          Vistani<br>
          Zufällige Begegnungen<br>
          Gebiete von Barovia<br><br>
          <h1>Kap. 3: Das Dorf Barovia</h1>
          <hr>
          Anfahrt zum Dorf<br>
          Bereiche des Dorfes<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 4: Schloss Ravenloft</h1>
          <hr>
          Zufällige Begegnungen<br>
          Mauern von Ravenloft<br>
          Hauptgeschoss<br>
          Gericht des Grafen<br>
          Räume des Weinens<br>
          Türme von Ravenloft<br>
          Vorratsschränke von Ill Omen<br>
          Verlies und Katakomben<br>
        </td>
        <td>
          <h1>Kap. 5: Die Stadt Vallaki</h1>
          <hr>
          Annäherung an die Stadt<br>
          Gebiete von Vallaki<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 6: Alte Knochenmühle</h1>
          <hr>
          Annäherung an die Windmühle<br>
          Bereiche der Windmühle<br>
          Die Megalithen<br><br>
          <h1>Kap. 7: Argynvostholtholt</h1>
          <hr>
          Der Orden des silbernen Drachens<br>
          Annäherung an die Villa<br>
          Gebiete von Argynvostholtholt<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 8: Das Dorf Krezk</h1>
          <hr>
          Krezker Gebiete<br>
          Bereiche der Abtei<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 9: Tsolenka-Pass</h1>
          <hr>
          Bereiche des Passes<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 10: Die Ruinen von Berez</h1>
          <hr>
          Auf dem Weg zu den Ruinen<br>
          Gebiete von Berez<br>
          Besondere Ereignisse<br><br>
        </td>
        <td>
          <h1>Kap. 11: Van Richtens Turm</h1>
          <hr>
          Annäherung an den Turm<br>
          Bereiche des Turms<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 12: Der Zauberer der Weine</h1>
          <hr>
          Auf dem Weg zum Weingut<br>
          Anfahrt zum Weingut<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 13: Der Bernsteintempel</h1>
          <hr>
          Bereiche des Tempels<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 14: Yester Hill: Yester Hill</h1>
          <hr>
          Gebiete des Hügels<br>
          Besondere Ereignisse<br><br>
          <h1>Kap. 15: Werwolf Dens</h1>
          <hr>
          Bereiche der Höhle<br>
          Besondere Ereignisse<br><br>
          <h1>Nachwort</h1>
          <hr>
          Strahd Überwiegt<br>
          Strahd Stirbt<br><br>
          <h1>Anhänge</h1>
          <hr>
          Anhang A: Zeichenoptionen<br>
          Anhang B: Todeshaus<br>
          Anhang C: Schätze<br>
          Anhang D: Monster und NSCs<br>
          Anhang E: Das Tarokka-Deck<br>
          Anhang F: Handzettel<br><br>
        </td>
      </tr>
    </table>
</div>
</template>

<script>
export default {
  name: 'Home',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  text-align: justify;
}
h2 {
 font-size: 30px;
 font-weight: bold;
 text-align: center;
}
table {
  width: 100%;
}
h1 {
  font-weight: bold;
}
hr {
  background-color: black;
}
td {
  padding-right: 10px;
}
</style>
