<html>
  <body>
    <dv>
      <h1>Hello World!</h1>
    </dv>
  </body>
</html>

body {
  text-align:center;
  font-family:sans-serif;
  font-size:3em;
  color:red;
}
h1 {
  text-shadow: 
    1px -3px 6px #666,
    2px 0px 5px #555,
    3px 0px 4px #444,
    4px 0px 3px #333,
    5px 0px 2px #222,
    6px 0px 1px #111;
}
dv {
   border: 1px solid rgba(0,0,0,3);
  box-shadow: 
    1px 0px 6px #666,
    2px 0px 5px #555,
    3px 0px 4px #444,
    4px 0px 3px #333,
    5px 0px 2px #222,
    6px 0px 1px #111;
}
h1 dv {
  transition: all .2s;
}
h1:hover{
  animation:scalelt 2s alternate 4;
}
@keyframes scalelt{
  to{
    transform:scale(1,2) rotate(10deg);
    color:blue;
  }
}
