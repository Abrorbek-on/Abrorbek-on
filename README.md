## Hi there 👋 Abrorbek


<p align="center">
  <img src="https://camo.githubusercontent.com/6809322d6b9d5248e22f4b76a2e8970eab151dca0a4f98dd86ba8a7babb4e5c8/68747470733a2f2f6d65646961312e67697068792e636f6d2f6d656469612f674d3571466b73554c7735344e4d577972792f67697068792e6769663f6369643d6563663035653437727a677661717a3033636165347567617770766f306768736334763263713475347a776434307461267269643d67697068792e6769662663743d73" width="150" alt="Sticker GIF">
</p>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Typewriter Effect</title>
<style>
  p {
    color: blue;
    font-weight: bold;
    font-size: 24px;
    text-align: center;
    font-family: monospace;
  }
</style>
</head>
<body>

<p id="fullname"></p>

<script>
  const text = "Fullname: Karimov Abrorbek";
  let index = 0;
  const p = document.getElementById("fullname");

  function typeWriter() {
    if (index < text.length) {
      p.innerHTML += text.charAt(index);
      index++;
      setTimeout(typeWriter, 150);
    } else {
      setTimeout(() => {
        p.innerHTML = "";
        index = 0;
        typeWriter();
      }, 2000);
    }
  }

  typeWriter();
</script>

</body>
</html>


<a href="https://github.com/Abrorbek09">
  <img src="https://camo.githubusercontent.com/2eedf25c65a9269ed2097998da5fded175a37ee0997c3d2c83dfde65eb6d88a4/68747470733a2f2f6d656469612e74656e6f722e636f6d2f4e4f594633663832625f6741414141432f70726f6772616d6d65722e676966" width="400" alt="GitHub">
</a>
