<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive unit  </title>
    <style>
        .percent {width: 50%; background-color: aqua; padding: 10px;}
        .em {font-size: 5px;}
        .em span {font-size: 2em; color: chocolate;}
        .em {font-size: 1.5rem; color: blue;}
        .vw {font-size: 8vw; color: orangered;}
        .vh {font-size: 8vh; color: orchid;}
        .vmin {font-size: 5vmin;background-color: palevioletred;}
        .ch {width: 20ch; background-color: aquamarine;}
    </style>
</head>
<body>
    <div class="percent">80% width(percentage)</div>
    <p class="em">This is a default 16px font.
    <span>2em (relative to percent)</span> </p>
    <p class="rem">1.5rem (relative to root)</p>
    <h2 class="vw">8vw (viewreport width) </h2>
    <h2 class="vh">8vh (viewreport width) </h2>
    <p class="vmin">Sample text with 5vmin.(small scale)</p>
    <input class="ch" type="text" value="Input box 25ch wide>"
</body>
</html>
