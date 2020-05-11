Tarea 1. 11 may 2020 Fer Vera

A.	<label></label>
El Elemento HTML <label> representa una etiqueta para un elemento en una interfaz de usuario. Este puede estar asociado con un control ya sea mediante la utilizacion del atributo for, o ubicando el control dentro del elemento label. Tal control es llamado "el control etiquetado" del elemento label.
<form action="/action_page.php">
  <label for="male">Male</label>
  <input type="radio" name="gender" id="male" value="male"><br>
  <label for="female">Female</label>
  <input type="radio" name="gender" id="female" value="female"><br>
  <label for="other">Other</label>
  <input type="radio" name="gender" id="other" value="other"><br><br>
  <input type="submit" value="Submit">
</form>

B. <pre></pre>
El Elemento HTML <pre> (o Texto HTML Preformateado) representa texto preformateado. El texto en este elemento típicamente se muestra en una fuente fija, no proporcional, exactamente como es mostrado en el archivo. Los espacios dentro de este elemento también son mostrados como están escritos.
<pre>
body{  color:  red;}
a   {  color:green;}
</pre>
C. <br/>

El elemento HTML line break <br> produce un salto de línea en el texto (retorno de carro). Es útil para escribir un poema o una dirección, donde la división de las líneas es significante.
No utilices <br> para incrementar el espacio entre líneas de texto; para ello utiliza la propiedad margin de CSS o el elemento <p>.

<p>To force<br> line breaks<br> in a text,<br> use the br<br> element.</p>
D. <table></table>
El Elemento de Tabla HTML (<table>) representa datos en dos o más dimensiones. Al igual que otros elementos HTML, este elemento también soporta atributos globales.
<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
</table>


