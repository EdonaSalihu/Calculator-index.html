# Calculator-index.html
<!DOCTYPE html>

<head>
  <title>Calculator</title>
  <meta charset="utf-8" name="viewport" content="width=device-width, initial-scale=1" />
  <link href="styles.css" rel="stylesheet" type="text/css">
</head>


<body>

  <section id="calculator-body">

    <div class="header">
      <h2>Standard Calculator</h2>
    </div>

    <div id="calculator-screen">
      <h1 id="screen">0</h1>
    </div>

    <div class="calculator-grid-buttons">

      <div class="non-number-buttons">
        <button id="clear"><h1 class="text">CE</h1></button>
      </div>

      <div class="non-number-buttons">
        <button id="clear-all"><h1 class="text">C</h1></button>
      </div>

      <div class="non-number-buttons">
        <button id="undo"><h1 class="text">Undo</h1></button>
      </div>

      <div class="non-number-buttons">
        <button class="operand" value="divide"><h1>÷</h1></button>
      </div>

      <div class="number">
        <button id="seven" class="number-button" value="7">7</button>
      </div>

      <div class="number">
        <button id="eight" class="number-button" value="8">8</button>
      </div>

      <div class="number">
        <button id="nine" class="number-button" value="9">9</button>
      </div>

      <div class="non-number-buttons">
        <button class="operand" value="multiply"><h1>x</h1></button>
      </div>

      <div class="number">
        <button id="four" class="number-button" value="4">4</button>
      </div>

      <div class="number" >
        <button id="five" class="number-button" value="5">5</button>
      </div>

      <div class="number">
        <button id="six" class="number-button" value="6">6</button>
      </div>

      <div class="non-number-buttons">
        <button class="operand" value="subtract"><h1>-</h1></button>
      </div>

      <div class="number">
        <button id="one" class="number-button" value="1">1</button>
      </div>

      <div class="number">
        <button id="two" class="number-button" value="2">2</button>
      </div>

      <div class="number">
        <button id="three" class="number-button" value="3">3</button>
      </div>

      <div class="non-number-buttons">
        <button class="operand" value="add">+</button>
      </div>

      <div class="number" id="zero">
        <button  class="number-button" value="0">0</button>
      </div>

      <div class="non-number-buttons">
        <button id="decimal" value=".">.</button>
      </div>

      <div class="non-number-buttons">
        <button value="equals" id="equals">=</button>
      </div>

    </div>


  </section>

  <script src="jquery.js"></script>
  <script src="script.js"></script>

</body>
