<table>
  <tbody>
   <tr>
   <td><img src="./imagenes/epis.png" alt="EPIS"></td>
   <th>
   <p>UNIVERSIDAD NACIONAL DE SAN AGUSTIN</p>
   <p>FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</p>
   <p>ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</p>
   </th>
   <td><img src="./imagenes/abet.png" alt="ABET"></td>
   </tr>
  </tbody>
</table>
<div align="center" dir="auto"><table>    
   <tbody>
   <tr><td colspan="3">Formato: Guía de Práctica de Laboratorio / Talleres / Centros de Simulación</td></tr>
   <tr><td>Aprobación:  2022/03/01</td><td>Código: GUIA-PRLD-001</td><td>Página: 1</td></tr>
   </tbody>
</table></div>
<div align="center" dir="auto">
   <span>INFORME DE LABORATORIO</span><br>
   <span>(formato estudiante)</span>
</div>
<div align="center" dir="auto"><table>
   <tbody><tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
   </tbody><tbody>
   <tr><td>ASIGNATURA:</td><td colspan="5">Programación Web 2</td></tr>
   <tr><td>TÍTULO DE LA PRÁCTICA:</td><td colspan="5">Javascript</td></tr>
   <tr>
   <td>NÚMERO DE PRÁCTICA:</td><td>02</td><td>AÑO LECTIVO:</td><td>2022 A</td><td>NRO. SEMESTRE:</td><td>III</td>
   </tr>
   <tr>
   <td>FECHA Presentacion:</td><td>08-May-2022</td><td>Hora de Presentacion:</td><td colspan="3">23:55</td>
   </tr>
   <tr><td colspan="3">Integrantes:
   <ul dir="auto">
   <li>Kevin Jheeremy Alvarez Astete</li>
   </ul>
   </td>
   <td> NOTA: </td>
   <td colspan="2"> </td>
   </tr><tr><td colspan="6">DOCENTES:
   <ul dir="auto">
   <li>Richart Smith Escobedo Quispe (rescobedoq@unsa.edu.pe)</li>
   </ul>
   </td>
</tr></tbody></table></div>
   <h1>SOLUCION Y RESULTADOS</h1>
   <h2>I. SOLUCION DE EJERCICIOS/PROBLEMAS</h2>
   <ul>
    <li><h3>EJERCICIO 01</h3></li>
    <img src="https://i.ibb.co/6NG5LWL/Ejercicio01.png">
    <li><h3>EJERCICIO 02</h3></li>
    <img src="https://i.ibb.co/qjgQ7c3/Ejercicio02.png">
    <li><h3>EJERCICIO 03</h3></li>
    <img src="https://i.ibb.co/FxzFgbK/Ejercicio03.png">
    <li><h3>EJERCICIO 04</h3></li>
    <img src="https://i.ibb.co/PFXkPwk/Ejercicio04.png">
    <li><h3>EJERCICIO 05</h3></li>
    <img src="https://i.ibb.co/74H15YR/Ejercicio05.png">
    <li><h3>EJERCICIO 06: link del video : </h3></li>
   </ul>
   <h2>II. SOLUCION DE CUESTIONARIO</h2>
   <ul>
      <li>Pruebe este código de arrayGenerator() en la página <a href="https://jslint.com/">https://jslint.com/</a></li>
      <li>Revisar esta discusión en stackoverflow - <a href="https://stackoverflow.com/questions/4852017/how-to-initialize-an-arrays-length-in-javascript">https://stackoverflow.com/questions/4852017/how-to-initialize-an-arrays-length-in-javascript</a></li>
      <ul>
         <li>¿Cómo se pueden resolver los warnings?</li>
         <ul>
           <p>Ejercicio analizado en JSLint: </p>
           <img src="https://i.ibb.co/NnNyhRy/Captura-de-pantalla-2022-05-09-083849.png">
           <p>Warnings obtenidos: </p>
           <img src="https://i.ibb.co/PMG0HKC/img02.png">
           <p>Se puede observar que dos warnings se disparan. El primero se soluciona declarando la variable antes que el bucle, sin embargo el bucle
           for requiere un cambio a for each un poco mas complejo. Para ello primero se debe tener un array con elementos y segundo se debe establecer
           la funcion que se ejecutara para cada elementos, como se muestra en la siguiente imagen:</p>
           <img src="https://i.ibb.co/TRrnfjq/img03.png">
           <img src="https://i.ibb.co/nj56RKs/img04.png">
           <p>Como se puede observar: al final solo nos presenta un unico warnings que nos indica que la variable "e" no se usa, sin embargo este 
           algoritmo esta diseñado para evitar usar otro array, por lo que no es posible evitar ese error ya que es necesario el uso del segundo index
           de la funcion dentro de for each para poder modificar los elementos del array</p>
         </ul>
         <li>¿Se puede modificar la solución usando map? ¿Cómo?</li>
         <ul>
           <p>Map es un herramienta mas util que for each ya que la funcion(callback) que utiliza modifica cada uno de los elementos del array sin
           necesidad de crear otro array</p>
           <img src="https://i.ibb.co/944Sjvd/img05.png">
         </ul>
      </ul>
   </ul>
   <h2>III. CONCLUSIONES</h2>
   <ul>
      <li></li>
      <li></li>
   </ul>
   <h1>RETROALIMENTACION GENERAL</h1>
   <h1>REFERENCIA Y BIBLIOGRAFIA</h1>
   <b><i></i></b>
