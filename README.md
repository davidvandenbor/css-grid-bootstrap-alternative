# CSS grid Bootstrap alternative

**Download** to your desktop? [Klik hier](https://github.com/davidvandenbor/css-grid-bootstrap-alternative/archive/refs/heads/master.zip)     
Preview in the browser? [Klik hier](https://davidvandenbor.github.io/css-grid-bootstrap-alternative)  
Play live with this code in **CodeSandbox** > [Klik hier!](https://codesandbox.io/s/github/davidvandenbor/css-grid-bootstrap-alternative) 

Example of how to clone the Bootstrap (or Foundation) grid behaviour by just using vanilla CSS grids! You can easily create your own grid system by just using a few lines of CSS code. Start by creating  a 12 column grid definition in your CSS file (it can be any amount of columns really!) 🙂

```CSS
display:grid;
grid-template-columns: repeat(12,1fr);
```

And then define the column spans for the columns in your lay-outs:

```CSS
header { grid-column:span 12;}
nav { grid-column: span 3;}
main { grid-column:span 9;}
footer { grid-column:span 12;}
```
Cheers,  
David!
