<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CALCULATOR</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 <div class="container"> 
 <div class="CALCULATOR">
 <input type="text" id="display" id="inputBox" >
 <div class="button">
 <div>
 <button onclick="display.value =''" class="operator">AC</button>
 <button onclick="display.value =display.value.toString().slice(0,-1)"class="operator">D</button>
 <button onclick="display.value +='%'" class="operator">%</button>
 <button onclick="display.value +='.'" class="operator">.</button>
 </div>
 <div> 
 <button onclick="display.value += 1">1</button> 
  <button onclick="display.value +=2 ">2</button>
  <button onclick="display.value +=3">3</button>
  <button onclick="display.value += '+' " class="operator" >+</button>
  </div>
  <div>
  <button onclick="display.value +=4">4</button>
  <button onclick="display.value += 5">5</button>
  <button onclick="display.value += 6">6</button>
  <button onclick="display.value +='-' " class="operator">-</button>
  </div>
  <div>
  <button onclick="display.value += 7">7</button>
  <button onclick="display.value += 8">8</button>
  <button onclick="display.value +=9">9</button>
  <button onclick="display.value += '*'" class="operator" >*</button>
  </div>
  <div>
  <button onclick="display.value +=0">0</button>
  <button onclick="display.value +='00'">00</button>
  <button onclick="display.value +='/'">/</button>
  <button id="equals" onclick="display.value=eval(display.value)">=</button>
  </div>
  </div>
  </div>
  
  </body>
</html>
<style>.container{
           background-color:#ffffff;
         }
.calculator{
                 width:260px;
                 height:400px;
                 margin:40px;
                 padding:18px;
                 border:1px solid #ccc;
                 border-radius:8px;
                 rgba:(0,0,0,0.5);
                 box-shadow:(0,0,10px);
                 background-color:black;
               }
#display{
              width:100%;
              height:60px;
              margin-bottom:18px;
              padding:10px;
              font-size:45px;
              text-align:right;
              border:none;
              border-radius:10px;
              box-shadow:(0,0,10px);
              rgba:(0,0,0,0.5);
              background-color:grey;
              color:black;
            }

button{
            padding:30px;
            font-size:16px;
            height:50px;
            width:50px;
            margin:1px;
            border:none;
            border-radius:50px;
            background-color:grey;
            cursor:pointer;
            color:white;
   
          }  
button:hover{
                background-color:none;
              }
 #equals{ 
              background-color:orange;
              color:white;
            }
#equals:hover{
                   background-color:none;
                 }
  
  .operator{
         background-color:orange;
       }

       
  
  </style># codealpha_tasks