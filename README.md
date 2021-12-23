@import url('https://fonts.googleapis.com/css?family=Roboto');
@font-face {font-family: Pusab; src: url('../../assets/Pusab.ttf')}

.gdButton {
  cursor: pointer;
  z-index: 1;
  user-select: none;
  transition-duration: 0.07s;
  transition-timing-function: ease-in-out;
}

.gdButton:active {
  animation: bounceButton 0.25s ease-in-out forwards;
}

body {
  background-color: 555555;
}

p {
  font-family: aller, helvetica, arial;
  font-size: 18px;
}

h1 {
  font-weight: normal;
  margin: 0 0;
  font-size: 60px;
  font-family: Pusab;
  color: white;
  letter-spacing: -0.01em;
  overflow: hidden;
  white-space: nowrap;
  -webkit-text-stroke-width: 2.2px;
  -webkit-text-stroke-color: black;
  text-shadow: 3px 3px 0.5px rgba(0, 0, 0, 0.3);
}

h2 {
  font-weight: normal;
  margin: 0 0;
  font-size: 35px;
  font-family: Pusab;
  width: fit-content;
  color: white;
  letter-spacing: -0.01em;
  -webkit-text-stroke-width: 1.6px;
  -webkit-text-stroke-color: black;
  text-shadow: 2px 2px 0px rgba(0, 0, 0, 0.3);
}

.hidden {
  display: none;
}

.inline, .help {
  display: inline-block;
}

.help {
  cursor: help;
}

.small {
  font-size: 16px
}

.smaller {
  font-size: 14px;
}

.bigger {
  font-size: 25px;
}

.noMargin {
  margin-bottom: 0px;
}

.blankButton {
  padding: 0 0 0 0;
  margin: 0 0 0 0;
  background: none;
  cursor: pointer;
  border: none;
}

input:focus, select:focus, textarea:focus, button:focus {
  outline: none;
 }

 input:not([type='checkbox']), select {
  padding: 7 7 7 7;
  font-size: 14px;
  width: 15%;
  border-style: 1px inset black;
 }

 input:-webkit-autofill, input:-webkit-autofill:hover, input:-webkit-autofill:focus, input:-webkit-autofill:active {
  box-shadow: 0 0 0px 1000px #764F1A inset !important;
  -webkit-box-shadow: 0 0 0px 1000px #764F1A inset !important;
  -webkit-text-fill-color: white !important;
}

 textarea {
  border-radius: 5px;
  padding: 7 7 7 7;
  width: 600px;
  height: 10%;
  max-width: 80%;
  min-width: 30%;
  min-height: 5%;
  max-height: 30%;
  text-align: left;
  font-size: 18px;
  font-family: "Roboto";
}

#textbox {
  text-transform: uppercase;
  font-size: 22px;
}

.oxygene {
  font-family: Oxygene2;
}

.buttonLink {
  border: none;
  outline: none;
  background: none;
  font-family: "Roboto";
  cursor: pointer;
  color: rgb(85, 26, 139);
}

.center {
  text-align: center;
}

.supercenter {
  position: absolute; 
  top: 50%; 
  left: 50%; 
  transform: translate(-50%,-50%);
}

.iconimage {
  height: 60px;
}

.generate {
  width: 75vw;
  display: block;
  padding: 5px 0 30px 0;
  margin: 10px auto 30px auto;
  background-color: rgb(235, 235, 235);
  border-radius: 8px;
}

.configbox {
  width: 250px;
  display: inline-block;
}

.configbox input {
  width: 95%;
}

.configbox select {
  width: 95%;
  text-transform: capitalize;
}

.squareIcon {
  background-color: rgba(0, 0, 0, 0.2);
  padding: 5px 5px;
  border-radius: 10px;
}

#url {
  width: 500px;
  max-width: 90%;
}

#resize {
  width: 250px;
  max-width: 90%;
}

#symbols, .subdiv {
  background-color: rgb(219, 219, 219);
  margin: 10px auto 10px auto;
  width: 65%;
  padding: 10 10 10 10;
  overflow: auto;
  white-space: nowrap;
  border-radius: 8px; 
}

#symbols p {
  font-size: 230%;
  font-family: Oxygene2;
  margin: 0 0 0 0;
  padding: 0 0 0 0;
}

#accountInfo {
  width: 50%;
}

#accountInfo p {
  text-align: left;
  line-height: 23px;
  margin-left: 10px;
  font-size: 18px;
}

.char {
  border: 1px solid black;
  background-color: white;
  border-radius: 2px;
  color: black;
  width: 55;
  height: 55;
  margin: 3px 10px 3px 10px;
  cursor: pointer;
}

.char:hover {
  background-color: rgb(223, 223, 223);
  transition: background-color 0.15s;
}

.char:active {
  background-color: rgb(200, 200, 200);
}

#generate {
  font-family: "Roboto";
  border: transparent;
  background-color: #88FF33;
  box-shadow: 2px 2px 3px #66AA22;
  border-radius: 10px;
  color: black;
  padding: 10px 15px 10px 15px;
  cursor: pointer;
  font-size: 18px;
}

#generate:hover {
  background-color: rgb(133, 230, 65);
  transition: background-color 0.15s;
}

#generate:active {
  background-color: rgb(117, 211, 50);
}

.miniButton {
  font-family: "Roboto";
  border: transparent;
  background-color: #88FF33;
  box-shadow: 1.5px 1.5px 2px #66AA22;
  border-radius: 10px;
  color: black;
  padding: 7px 9px 7px 9px;
  cursor: pointer;
  font-size: 14px;
}

.miniButton:hover {
  background-color: rgb(133, 230, 65);
  transition: background-color 0.15s;
}

.miniButton:active {
  background-color: rgb(117, 211, 50);
}

.iconKit {
  width: 800px;
  overflow-x: hidden;
  display: block;
  padding-bottom: 20px;
  margin: 0 auto 0 auto;
  background-color: rgba(0, 0, 0, 0.3);
  border-radius: 8px;
}

.iconKit button, .colTypes button {
  margin: 0 0 0 0;
  padding: 0 0 0 0;
  border: 5px solid transparent;
}

.iconSelected {
  border-image: url('../../assets/select.png') 10 stretch !important;
}

.iconTabButton, .glowToggle, .copyForm {
  margin: 0 5 0 5;
  transition: transform .1s ease-in-out;
}

.colorPicker {
  width: 0.01px !important;
  height: 0.01px !important;
  padding: 0 0 0 0 !important;
  visibility: hidden;
  position: absolute;
}

.colorLabel {
  transition-duration: 0.05s;
  transition-timing-function: ease-in-out;
}

.colorLabel:hover {
  transform: scale(1.08)
}

.colorLabel img {
  display: none;
  width: 45px;
  border: 2.5px solid black;
  border-radius: 420px;
  transition-duration: 0.25s;
}

.customMode {
  border: 2.5px solid white;
}

.copyForm {
  margin: 18 10 0 10 !important;
}

.iconTabButton:active, .glowToggle:active, .copyForm:active {
  transform:scale(1.05)
}

#colors {
  width: 1000px;
  overflow-x: auto;
  padding: 10 10 10 10;
  background-color: rgba(0, 0, 0, 0.7);
}

#colors::-webkit-scrollbar, #iconKitParent::-webkit-scrollbar {
  width: 9px;
  height: 9px;
  background: rgba(0, 0, 0, 0.5); 
}

#colors::-webkit-scrollbar-thumb, #iconKitParent::-webkit-scrollbar-thumb {
  background: rgb(185, 185, 185); 
}

#iconKitParent {
  max-height: 210px;
  box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.5);
}

#iconKitParent div {
  margin-top: -5;
}

#colors div {
  display: flex;
}

#gdfloor {
  margin-bottom: 15px;
  margin-top: 0px;
  border: 0;
  height: 3px;
  width: 80%;
  background-image: linear-gradient(to right, rgba(255, 255, 255, 0), rgba(255, 255, 255, 1), rgba(255, 255, 255, 0));
}

.menuButton {
  margin: 0 5 0 5;
  transition: transform .15s ease-in-out;
}

.menuButton:hover {
  transform:scale(1.07)
}

.menuButton:active {
  transform:scale(1.15)
}

#iconprogressbar {
  background: rgba(0, 0, 0, 0.5); 
  height: 12px;
}

#iconloading {
  background: rgba(255, 255, 255, 0.5); 
  height: 12px;
  width: 0%;
}

.iconScroll::-webkit-scrollbar  {
  width: 0;
  background: transparent;
}

.iconHover {
  transform: scale(1.075);
  background-color: rgb(255, 255, 255, 0.2);
  border-radius: 10px;
}

.popup {
  position: fixed; 
  display: none; 
  width: 100%;
  height: 100%;
  top: 0; left: 0; right: 0; bottom: 0;
  background-color: rgba(0,0,0,0.4);
  z-index: 2;
}

.brownBox {
  border: 17px solid transparent;
  border-radius: 25px;
  background-color: #995533;
  border-image: url('../../assets/brownbox.png') 10% round;
}

.xButton {
  position: absolute;
  top: -35px;
  left: -40px;
  text-align: left;
}

input[type=text] {
  font-weight: normal;
  margin: 0 0;
  font-size: 45px;
  font-family: Pusab;
  color: white;
  letter-spacing: 0.02em;
  text-shadow: -0.2vh -0.2vh 0vh #000, 0.2vh -0.2vh 0vh #000, -0.2vh 0.2vh 0vh #000, 0.2vh 0.2vh 0vh #000;
  border: 0 solid transparent;
  border-radius: 15px;
  background-color: rgba(0, 0, 0, 0.3);
  white-space: nowrap;
}

input[type=text]::placeholder {
  color: #6F98D8;
  font-size: 40px;
  text-shadow: -0.15vh -0.15vh 0vh #000, 0.15vh -0.15vh 0vh #000, -0.15vh 0.15vh 0vh #000, 0.15vh 0.15vh 0vh #000;
}

input[type=checkbox] {
  display: none;
}

.gdcheckbox {
  vertical-align: middle;
  display: inline-block;
  background-image: url(../../assets/check-off.png);
  background-repeat: no-repeat;
  background-size: contain;
  padding-right: 40px;
  height: 42px;
  text-align: left;
  margin: 0 15 0 35;
}

input[type=checkbox]:checked + label.gdcheckbox {
  background-image: url(../../assets/check-on.png);
}

.bounce {
  animation: boxAnimator 0.25s;
}

.grayscale {
  filter: grayscale(100%) brightness(0.7);
}

.gold {
  color: rgb(255, 200, 0);
}

.blue {
  color: blue;
 }

 .white {
  color: white;
 }

.inline {
  display: inline-block;
}

.spin {
  -webkit-animation: spin 2s linear infinite;
  -moz-animation: spin 2s linear infinite;
   animation: spin 2s linear infinite;
   mix-blend-mode: luminosity;
}

@keyframes boxAnimator {
  0% {
      transform: scale(0) translate(-50%, -50%);
      transform-origin:left top
  }
  75% {
      transform: scale(1.075) translate(-50%, -50%);
      transform-origin:left top
  }
  100% {
      transform: scale(1) translate(-50%, -50%);
      transform-origin:left top
  }
}

@keyframes bounceButton {
  0% {
      transform: scale(1);
  }
  50% {
      transform: scale(1.12);
  }
  75% {
      transform: scale(1.06);
  }
  100% {
      transform: scale(1.1);
  }
}

@-moz-keyframes spin { 100% { -moz-transform: rotate(360deg); } }
@-webkit-keyframes spin { 100% { -webkit-transform: rotate(360deg); } }
@keyframes spin { 100% { -webkit-transform: rotate(360deg); transform:rotate(360deg); } }
