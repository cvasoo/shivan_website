# shivan_website

#this is where you can know what i do, what can i do :)

<canvas id="mtw-canvas" style="width:100vw;height:100vh;left:0;top:0;position:fixed;"></canvas>
<script src="https://cdn.jsdelivr.net/gh/mythemeway/mtw-canvas-disks@0.0.2/boilerplate-canvas/twgl/canvas.bundle.min.js"></script>
@keyframes color {
  0%   { background: #33CCCC; }
  20%  { background: #33CC36; }
  40%  { background: #B8CC33; }
  60%  { background: #FCCA00; }
  80%  { background: #33CC36; }
  100% { background: #33CCCC; }
}

body {
  background: #33CCCC; /* Fallback */
  animation: color 9s infinite linear;
  text-align: center;
  padding: 2em;
}
h1 {
  text-align: center;
  font-family: 'Kavoon', sans-serif;
  font-size: 2.5em;
  color: white;
}

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Website</title>
  </head>
  <body>
    <main>
        <h1>Welcome to My Website</h1>  
        <p>This is my new website which is hosted on GitHub Pages!</p>
    </main>
  </body>
</html>
