# JPVargasss.github.io
The website to prove the knowledge obteined in the Course
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Lectura S11</title>
</head>
<header>
  <h1>Organizar info en tablas</h1>
</header>

<body>
  <!--Table complete-->
  <table>
    <caption><strong> Este es el título de la tabla</strong></caption>
    <thead>
      <tr>
        <th scope="col">Item</th>
        <th scope="col">Availability</th>
        <th scope="col">Qty</th>
        <th scope="col">Price</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Don&#8217;t Make Me Think by Steve Krug</td>
        <td>In Stock</td>
        <td>1</td>
        <td>$30.02</td>
      </tr>
      <tr>
        <td>A Project Guide to UX Design by Russ Unger &#38; Carolyn Chandler</td>
        <td>In Stock</td>
        <td>2</td>
        <td>$52.94 ($26.47 &#215; 2)</td>
      </tr>
      <tr>
        <td>Introducing HTML5 by Bruce Lawson &#38; Remy Sharp</td>
        <td>Out of Stock</td>
        <td>1</td>
        <td>$22.23</td>
      </tr>
      <tr>
        <td>Bulletproof Web Design by Dan Cederholm</td>
        <td>In Stock</td>
        <td>1</td>
        <td>$30.17</td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <!--Uso del colspan-->
        <td colspan="3">Subtotal</td>
        <td>$135.36</td>
      </tr>
      <tr>
        <td colspan="3">Tax</td>
        <td>$13.54</td>
      </tr>
      <tr>
        <td colspan="3">Total</td>
        <td>$148.90</td>
      </tr>
    </tfoot>
  </table>
  <hr>
  <div>
    <table>
      <thead>Marcas de dispositivos tecnológicos</thead>
      <tbody>
        <tr>
          <th>Portátiles</th>
          <td>MAC</td>
          <td>hp</td>
          <!--Uso del rowspan-->
          <td rowspan="2">Huawei</td>
        </tr>
        <tr>
          <th>Celulares</th>
          <td>Iphone</td>
          <td>Xiaomi</td>
        </tr>
      </tbody>
    </table>

  </div>
  <hr>
  <blockquote><i>"Ese comportamiento de pornstar me tiene loco"</i> Pablito</blockquote>
  <details>Quiero probar como funciona</details>
  <hr>
  
</body>
</html>
