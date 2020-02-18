# sryan5966.github.io
<html>
<head>
    <style>
        #one {
            width: 100px;
            height: 100px;
            background-color: gray;
            margin-left: 250px;
            margin-top:250px;
            transition: background-color 1s, margin-left 1s ;
        }
            #one:hover {
                margin-left: 350px;
                background-color: white;
            }

              #two {
            width: 100px;
            height: 100px;
            background-color: gray;
            margin-left: 250px;
            margin-top:250px;
            transition: background-color 1s, margin-left 0.1s ;
        }

            #two:hover {
   transform: rotateX(30deg)  rotateY(30deg) rotateZ(30deg);
}

 #three {
            width: 100px;
            height: 100px;
            background-color: gray;
            margin-left: 250px;
            margin-top:250px;
            transition: background-color 1s, margin-left 0.1s ;
        }

            #three:hover {
  transform: rotate3d(1,1,1, 30deg);
}

.element {
  display: inline-block;
  background: linear-gradient(180deg,#ff8a00,#e52e71);
  height: 100px;
  width: 100px;
  font-size: 1px;
  padding: 1px;
  color: white;
  margin-right: 5px;
  margin-left: 5px;
  animation: skew 3s infinite;
  transform: skew(20deg);
  animation-direction: alternate;
  opacity: .7;
 
  align-items: center;
  justify-content: center;
}

@keyframes skew {
  0% {
    transform: skew(20deg, 20deg);
  }
  100% {
    transform: skew(-20deg, -20deg);
  }
}

.reactor-container {
  width: 300px;
  height: 300px;
  margin: auto;
  border: 1px dashed #888;
  position: relative;
  border-radius: 50%;
  background-color: #384c50;
  border: 1px solid rgb(18, 20, 20);
  box-shadow: 0px 0px 32px 8px rgb(18, 20, 20), 0px 0px 4px 1px rgb(18, 20, 20) inset;
}
.reactor-container-inner {
  height: 238px;
  width: 238px;
  background-color: rgb(22, 26, 27);;
  box-shadow: 0px 0px 4px 1px #52FEFE;
}

.circle {
  border-radius: 50%;
}
.abs-center {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto;
}
.core-inner {
  width: 70px;
  height: 70px;
  border: 5px solid #1B4E5F;
  background-color: #FFFFFF;
  box-shadow: 0px 0px 7px 5px #52FEFE, 0px 0px 10px 10px #52FEFE inset;
}
.core-outer {
  width: 120px;
  height: 120px;
  border: 1px solid #52FEFE;
  background-color: #FFFFFF;
  box-shadow: 0px 0px 2px 1px #52FEFE, 0px 0px 10px 5px #52FEFE inset;
}
.core-wrapper {
  width: 180px;
  height: 180px;
  background-color: #073c4b;
  box-shadow: 0px 0px 5px 4px #52FEFE, 0px 0px 6px 2px #52FEFE inset;
}
.tunnel {
  width: 220px;
  height: 220px;
  background-color: #FFFFFF;
  box-shadow: 0px 0px 5px 1px #52FEFE, 0px 0px 5px 4px #52FEFE inset;
}
.coil-container {
  position: relative;
  width: 100%;
  height: 100%;
  animation: 3s infinite linear reactor-anim;
}
.coil {
  position: absolute;
  width: 30px;
  height: 20px;
  top: calc(50% - 110px);
  left: calc(50% - 15px);
  transform-origin: 15px 110px;
  background-color:#073c4b;
  box-shadow: 0px 0px 5px #52FEFE inset;
}
.coil-1 {
  transform: rotate(0deg);
}
.coil-2 {
  transform: rotate(45deg);
}
.coil-3 {
  transform: rotate(90deg);
}
.coil-4 {
  transform: rotate(135deg);
}
.coil-5 {
  transform: rotate(180deg);
}
.coil-6 {
  transform: rotate(225deg);
}
.coil-7 {
  transform: rotate(270deg);
}
.coil-8 {
  transform: rotate(315deg);
}
@keyframes reactor-anim {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}


    </style>
</head>
<body>
    <div id="one">
        
    </div>

    <div id="two">
        
    </div>
    <div id="three">
        
    </div>
    <br>
<div class="element">
</div>
<div class="element">
</div>
<div class="element">
</div>

<div class="fullpage-wrapper">
  <div class="reactor-container">
    <div class="reactor-container-inner circle abs-center"></div>
    <div class="tunnel circle abs-center"></div>
    <div class="core-wrapper circle abs-center"></div>
    <div class="core-outer circle abs-center"></div>
    <div class="core-inner circle abs-center"></div>
    <div class="coil-container">
      <div class="coil coil-1"></div>
      <div class="coil coil-2"></div>
      <div class="coil coil-3"></div>
      <div class="coil coil-4"></div>
      <div class="coil coil-5"></div>
      <div class="coil coil-6"></div>
      <div class="coil coil-7"></div>
      <div class="coil coil-8"></div>
    </div>
  </div>
</div>


</body>
</html>
