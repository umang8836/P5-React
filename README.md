# How to embed a p5.js sketch in a React page

### To run:

Clone this repo and then run the following commands in the terminal:
```
npm i
npm start
```
![](https://miro.medium.com/max/1400/1*wdMMfT2Zb4nbBlWI3bnRtw.png)

Making p5.js sketches is incredibly fun and is an amazing tool for creative coding. However, while p5.js themselves show how to embed a sketch in pure html, it’s not clear how to embed one in a React app since the <script> tag doesn’t work the same way in a React component. Here’s how I figured out to do it:

### Make a p5.js sketch
I use their [online editor](https://editor.p5js.org/) to develop and run mine. Put the sketch in a file in the same directory as index.html, I named the file sketch.js.


