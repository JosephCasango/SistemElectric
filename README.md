<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

* {
  box-sizing: border-box;
}

.bg-image {
  /* Full height */
  height: 100%; 
  
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.img1 { 
  background-image: url("https://i.pinimg.com/736x/b2/b7/1a/b2b71a9a51ca1852a41df51a7f658c12.jpg"); 
}
.img2 { 
  background-image: url("https://i.pinimg.com/736x/9c/dc/ed/9cdced121b96194c6e52006ae6313b68.jpg"); 
  }
.img3 { 
  background-image: url("https://i.pinimg.com/736x/8b/a3/8e/8ba38e12ca47ceb1f1c269a8614f3947.jpg"); 
  }
.img4 { 
  background-image: url("https://i.pinimg.com/736x/29/c0/c4/29c0c41d913145f8a3d84c103127d123.jpg"); 
  }
.img5 { 
  background-image: url("https://i.pinimg.com/736x/8c/c4/b1/8cc4b1d0620b72b65b465f288db558e0.jpg"); 
  }
.img6 { 
  background-image: url("https://i.pinimg.com/736x/8e/64/7b/8e647bc8ae219eb6e325595c9c665fa1.jpg"); 
  }

/* Position text in the middle of the page/image */
.bg-text {
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
  color: white;
  font-weight: bold;
  font-size: 70px;
  border: 10px solid #f1f1f1;
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 500px;
  padding: 25px;
  text-align: center;
}













/* From Uiverse.io by satyamchaudharydev */ 
.Comenzar {
  padding: 0;
  margin: 0;
  border: none;
  background: none;
  cursor: pointer;
}

.Comenzar  {
  --primary-color: #f7ff00;
  --hovered-color: #00ff23;
  position: relative;
  display: flex;
  font-weight: 600;
  font-size: 20px;
  gap: 0.5rem;
  align-items: center;
}

.Comenzar p {
  margin: 0;
  position: relative;
  font-size: 20px;
  color: var(--primary-color);
}

.Comenzar::after {
  position: absolute;
  content: "";
  width: 0;
  left: 0;
  bottom: -7px;
  background: var(--hovered-color);
  height: 2px;
  transition: 0.3s ease-out;
}

.Comenzar p::before {
  position: absolute;
  /*   box-sizing: border-box; */
  content: "Comenzar";
  width: 0%;
  inset: 0;
  color: var(--hovered-color);
  overflow: hidden;
  transition: 0.3s ease-out;
}

.Comenzar:hover::after {
  width: 100%;
}

.Comenzar:hover p::before {
  width: 100%;
}

.Comenzar:hover svg {
  transform: translateX(4px);
  color: var(--hovered-color);
}

.Comenzar svg {
  color: var(--primary-color);
  transition: 0.2s;
  position: relative;
  width: 15px;
  transition-delay: 0.2s;
}
















/* Style tab links */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: white;
  display: none;
  padding: .1px .2px;
  height: 100%;

}

#Home {background-color: ;}
#Info {background-color: black;
}
#Fotos {background-color: white;}
#Creditos {background-color: black;}

























* {
  box-sizing: border-box;
}

body {
  background-color: #000000;

  font-family: Arial;
}

/* Center website */
.main {
  max-width: 1200px;
  margin: auto;
}

h1 {
  font-size: 50px;
  word-break: break-all;
}

.row {
  margin: 8px -16px;
}

/* Add padding BETWEEN each column */
.row,
.row > .column {
  padding: 8px;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
}

/* Clear floats after rows */ 
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Content */
.content {
  background-color: white;
  padding: 10px;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 900px) {
  .column {
    width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}












/* From Uiverse.io by Galahhad */ 
.ui-bookmark {
  --icon-size: 24px;
  --icon-secondary-color: rgb(77, 77, 77);
  --icon-hover-color: rgb(97, 97, 97);
  --icon-primary-color: gold;
  --icon-circle-border: 1px solid var(--icon-primary-color);
  --icon-circle-size: 35px;
  --icon-anmt-duration: 0.3s;
}

.ui-bookmark input {
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  display: none;
}

.ui-bookmark .bookmark {
  width: var(--icon-size);
  height: auto;
  fill: var(--icon-secondary-color);
  cursor: pointer;
  -webkit-transition: 0.2s;
  -o-transition: 0.2s;
  transition: 0.2s;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
  -webkit-transform-origin: top;
  -ms-transform-origin: top;
  transform-origin: top;
}

.bookmark::after {
  content: "";
  position: absolute;
  width: 10px;
  height: 10px;
  -webkit-box-shadow: 0 30px 0 -4px var(--icon-primary-color),
    30px 0 0 -4px var(--icon-primary-color),
    0 -30px 0 -4px var(--icon-primary-color),
    -30px 0 0 -4px var(--icon-primary-color),
    -22px 22px 0 -4px var(--icon-primary-color),
    -22px -22px 0 -4px var(--icon-primary-color),
    22px -22px 0 -4px var(--icon-primary-color),
    22px 22px 0 -4px var(--icon-primary-color);
  box-shadow: 0 30px 0 -4px var(--icon-primary-color),
    30px 0 0 -4px var(--icon-primary-color),
    0 -30px 0 -4px var(--icon-primary-color),
    -30px 0 0 -4px var(--icon-primary-color),
    -22px 22px 0 -4px var(--icon-primary-color),
    -22px -22px 0 -4px var(--icon-primary-color),
    22px -22px 0 -4px var(--icon-primary-color),
    22px 22px 0 -4px var(--icon-primary-color);
  border-radius: 50%;
  -webkit-transform: scale(0);
  -ms-transform: scale(0);
  transform: scale(0);
}

.bookmark::before {
  content: "";
  position: absolute;
  border-radius: 50%;
  border: var(--icon-circle-border);
  opacity: 0;
}

/* actions */

.ui-bookmark:hover .bookmark {
  fill: var(--icon-hover-color);
}

.ui-bookmark input:checked + .bookmark::after {
  -webkit-animation: circles var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  animation: circles var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  -webkit-animation-delay: var(--icon-anmt-duration);
  animation-delay: var(--icon-anmt-duration);
}

.ui-bookmark input:checked + .bookmark {
  fill: var(--icon-primary-color);
  -webkit-animation: bookmark var(--icon-anmt-duration) forwards;
  animation: bookmark var(--icon-anmt-duration) forwards;
  -webkit-transition-delay: 0.3s;
  -o-transition-delay: 0.3s;
  transition-delay: 0.3s;
}

.ui-bookmark input:checked + .bookmark::before {
  -webkit-animation: circle var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  animation: circle var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  -webkit-animation-delay: var(--icon-anmt-duration);
  animation-delay: var(--icon-anmt-duration);
}

@-webkit-keyframes bookmark {
  50% {
    -webkit-transform: scaleY(0.6);
    transform: scaleY(0.6);
  }

  100% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
  }
}

@keyframes bookmark {
  50% {
    -webkit-transform: scaleY(0.6);
    transform: scaleY(0.6);
  }

  100% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
  }
}

@-webkit-keyframes circle {
  from {
    width: 0;
    height: 0;
    opacity: 0;
  }

  90% {
    width: var(--icon-circle-size);
    height: var(--icon-circle-size);
    opacity: 1;
  }

  to {
    opacity: 0;
  }
}

@keyframes circle {
  from {
    width: 0;
    height: 0;
    opacity: 0;
  }

  90% {
    width: var(--icon-circle-size);
    height: var(--icon-circle-size);
    opacity: 1;
  }

  to {
    opacity: 0;
  }
}

@-webkit-keyframes circles {
  from {
    -webkit-transform: scale(0);
    transform: scale(0);
  }

  40% {
    opacity: 1;
  }

  to {
    -webkit-transform: scale(0.8);
    transform: scale(0.8);
    opacity: 0;
  }
}

@keyframes circles {
  from {
    -webkit-transform: scale(0);
    transform: scale(0);
  }

  40% {
    opacity: 1;
  }

  to {
    -webkit-transform: scale(0.8);
    transform: scale(0.8);
    opacity: 0;
  }
}

















/* From Uiverse.io by Yaya12085 */ 
.ui-like {
  --icon-size: 40px;
  --icon-secondary-color: rgb(0, 0, 0);
  --icon-hover-color: rgb(211, 205, 205);
  --icon-primary-color: rgb(230, 26, 26);
  --icon-circle-border: 1px solid var(--icon-primary-color);
  --icon-circle-size: 35px;
  --icon-anmt-duration: 0.3s;
}

.ui-like input {
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  display: none;
}

.ui-like .like {
  width: var(--icon-size);
  height: auto;
  fill: var(--icon-secondary-color);
  cursor: pointer;
  -webkit-transition: 0.2s;
  -o-transition: 0.2s;
  transition: 0.2s;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  position: relative;
  -webkit-transform-origin: top;
  -ms-transform-origin: top;
  transform-origin: top;
}

.like::after {
  content: "";
  position: absolute;
  width: 10px;
  height: 10px;
  -webkit-box-shadow: 0 30px 0 -4px var(--icon-primary-color),
    30px 0 0 -4px var(--icon-primary-color),
    0 -30px 0 -4px var(--icon-primary-color),
    -30px 0 0 -4px var(--icon-primary-color),
    -22px 22px 0 -4px var(--icon-primary-color),
    -22px -22px 0 -4px var(--icon-primary-color),
    22px -22px 0 -4px var(--icon-primary-color),
    22px 22px 0 -4px var(--icon-primary-color);
  box-shadow: 0 30px 0 -4px var(--icon-primary-color),
    30px 0 0 -4px var(--icon-primary-color),
    0 -30px 0 -4px var(--icon-primary-color),
    -30px 0 0 -4px var(--icon-primary-color),
    -22px 22px 0 -4px var(--icon-primary-color),
    -22px -22px 0 -4px var(--icon-primary-color),
    22px -22px 0 -4px var(--icon-primary-color),
    22px 22px 0 -4px var(--icon-primary-color);
  border-radius: 50%;
  -webkit-transform: scale(0);
  -ms-transform: scale(0);
  transform: scale(0);
}

.like::before {
  content: "";
  position: absolute;
  border-radius: 50%;
  border: var(--icon-circle-border);
  opacity: 0;
}

/* actions */

.ui-like:hover .like {
  fill: var(--icon-hover-color);
}

.ui-like input:checked + .like::after {
  -webkit-animation: circles var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  animation: circles var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  -webkit-animation-delay: var(--icon-anmt-duration);
  animation-delay: var(--icon-anmt-duration);
}

.ui-like input:checked + .like {
  fill: var(--icon-primary-color);
  -webkit-animation: like var(--icon-anmt-duration) forwards;
  animation: like var(--icon-anmt-duration) forwards;
  -webkit-transition-delay: 0.3s;
  -o-transition-delay: 0.3s;
  transition-delay: 0.3s;
}

.ui-like input:checked + .like::before {
  -webkit-animation: circle var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  animation: circle var(--icon-anmt-duration)
    cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards;
  -webkit-animation-delay: var(--icon-anmt-duration);
  animation-delay: var(--icon-anmt-duration);
}

@-webkit-keyframes like {
  50% {
    -webkit-transform: scaleY(0.6);
    transform: scaleY(0.6);
  }

  100% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
  }
}

@keyframes like {
  50% {
    -webkit-transform: scaleY(0.6);
    transform: scaleY(0.6);
  }

  100% {
    -webkit-transform: scaleY(1);
    transform: scaleY(1);
  }
}

@-webkit-keyframes circle {
  from {
    width: 0;
    height: 0;
    opacity: 0;
  }

  90% {
    width: var(--icon-circle-size);
    height: var(--icon-circle-size);
    opacity: 1;
  }

  to {
    opacity: 0;
  }
}

@keyframes circle {
  from {
    width: 0;
    height: 0;
    opacity: 0;
  }

  90% {
    width: var(--icon-circle-size);
    height: var(--icon-circle-size);
    opacity: 1;
  }

  to {
    opacity: 0;
  }
}

@-webkit-keyframes circles {
  from {
    -webkit-transform: scale(0);
    transform: scale(0);
  }

  40% {
    opacity: 1;
  }

  to {
    -webkit-transform: scale(0.8);
    transform: scale(0.8);
    opacity: 0;
  }
}

@keyframes circles {
  from {
    -webkit-transform: scale(0);
    transform: scale(0);
  }

  40% {
    opacity: 1;
  }

  to {
    -webkit-transform: scale(0.8);
    transform: scale(0.8);
    opacity: 0;
  }
}












.titulo {
  margin: 0;
  height: auto;
  background: transparent;
  padding: 0;
  border: none;
  cursor: pointer;
}

/* button styling */
.titulo {
  --border-right: 1px;
  --text-stroke-color: rgba(255,255,255,0.6);
  --animation-color: #37FF8B;
  --fs-size: 2em;
  letter-spacing: 3px;
  text-decoration: none;
  font-size: var(--fs-size);
  font-family: "Arial";
  position: relative;
  text-transform: uppercase;
  color: transparent;
  -webkit-text-stroke: 1px var(--text-stroke-color);
}
/* this is the text, when you hover on button */
.hover-text {
  position: absolute;
  box-sizing: border-box;
  content: attr(data-text);
  color: var(--animation-color);
  width: 0%;
  inset: 0;
  border-right: var(--border-right) solid var(--animation-color);
  overflow: hidden;
  transition: 0.5s;
  -webkit-text-stroke: 1px var(--animation-color);
}
/* hover */
.titulo:hover .hover-text {
  width: 101%;
  filter: drop-shadow( 0 0 53px var(--animation-color))
}














.Trans {
  padding: 1em 2em;
  border: none;
  border-radius: 5px;
  font-weight: bold;
  letter-spacing: 5px;
  text-transform: uppercase;
  cursor: pointer;
  color: #ff4900;
  transition: all 1000ms;
  font-size: 15px;
  position: relative;
  overflow: hidden;
  outline: 2px solid #ff4900;
}

.Trans:hover {
  color: #ffffff;
  transform: scale(1.1);
  outline: 2px solid #70bdca;
  box-shadow: 4px 5px 17px -4px #268391;
}

.Trans::before {
  content: "";
  position: absolute;
  left: -50px;
  top: 0;
  width: 0;
  height: 100%;
  background-color: #ff4900;
  transform: skewX(45deg);
  z-index: -1;
  transition: width 1000ms;
}

.Trans:hover::before {
  width: 250%;
}


.Trans2 {
  padding: 1em 2em;
  border: none;
  border-radius: 5px;
  font-weight: bold;
  letter-spacing: 5px;
  text-transform: uppercase;
  cursor: pointer;
  color: #2c9caf;
  transition: all 1000ms;
  font-size: 15px;
  position: relative;
  overflow: hidden;
  outline: 2px solid #2c9caf;
}

.Trans2:hover {
  color: #ffffff;
  transform: scale(1.1);
  outline: 2px solid #70bdca;
  box-shadow: 4px 5px 17px -4px #2c9caf;
}

.Trans2::before {
  content: "";
  position: absolute;
  left: -50px;
  top: 0;
  width: 0;
  height: 100%;
  background-color: #2c9caf;
  transform: skewX(45deg);
  z-index: -1;
  transition: width 1000ms;
}

.Trans2:hover::before {
  width: 250%;
}







.Trans3 {
  padding: 1em 2em;
  border: none;
  border-radius: 5px;
  font-weight: bold;
  letter-spacing: 5px;
  text-transform: uppercase;
  cursor: pointer;
  color: #05bd6f;
  transition: all 1000ms;
  font-size: 15px;
  position: relative;
  overflow: hidden;
  outline: 2px solid #2c9caf;
}

.Trans3:hover {
  color: #ffffff;
  transform: scale(1.1);
  outline: 2px solid #05bd6f;
  box-shadow: 4px 5px 17px -4px #05bd6f;
}

.Trans3::before {
  content: "";
  position: absolute;
  left: -50px;
  top: 0;
  width: 0;
  height: 100%;
  background-color: #05bd6f;
  transform: skewX(45deg);
  z-index: -1;
  transition: width 1000ms;
}

.Trans3:hover::before {
  width: 250%;
}






















.headering {
  text-align: center;
  padding: 32px;
}

.rolls {
  display: -ms-flexbox; /* IE 10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE 10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create two equal columns that sits next to each other */
.columbia {
  -ms-flex: 50%; /* IE 10 */
  flex: 50%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
}

/* Style the buttons */
.btn {
  border: none;
  outline: none;
  padding: 10px 16px;
  background-color: #f1f1f1;
  cursor: pointer;
  font-size: 18px;
}

.btn:hover {
  background-color: #ddd;
}

.btn.active {
  background-color: #666;
  color: white;
}




























/* From Uiverse.io by Yaya12085 */ 
.card {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 350px;
  background-color: #fff;
  color: #212121;
}

.image {
  height: 18rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.content {
  padding: 1rem;
  text-align: center;
}

.text-1 {
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.text-2 {
  margin-top: 1rem;
  font-weight: 900;
  text-transform: uppercase;
}

.text-2 span:first-child {
  font-size: 2.25rem;
  line-height: 2.5rem;
  font-weight: 900;
}

.text-2 span:last-child {
  margin-top: 0.5rem;
  display: block;
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.action {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}

.date {
  margin-top: 1rem;
  font-size: 0.75rem;
  line-height: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  color: rgba(156, 163, 175, 1);
}

























body {font-family: Arial, Helvetica, sans-serif;}

#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}




#myImg2 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg2:hover {opacity: 0.7;}




#myImg3 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg3:hover {opacity: 0.7;}




#myImg4 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg4:hover {opacity: 0.7;}




#myImg5 {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg5:hover {opacity: 0.7;}


/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation */
.modal-content, #caption {  
  -webkit-animation-name: zoom;
  -webkit-animation-duration: 0.6s;
  animation-name: zoom;
  animation-duration: 0.6s;
}

@-webkit-keyframes zoom {
  from {-webkit-transform:scale(0)} 
  to {-webkit-transform:scale(1)}
}

@keyframes zoom {
  from {transform:scale(0)} 
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}
</style>
</head>
<body>















<div id="Home" class="tabcontent">


<div class="bg-image img1"><img src="https://i.pinimg.com/736x/b2/b7/1a/b2b71a9a51ca1852a41df51a7f658c12.jpg" style="width:100%"></div>
<div class="bg-image img2"><img src="https://i.pinimg.com/736x/9c/dc/ed/9cdced121b96194c6e52006ae6313b68.jpg" style="width:100%"></div>
<div class="bg-image img3"><img src="https://i.pinimg.com/736x/8b/a3/8e/8ba38e12ca47ceb1f1c269a8614f3947.jpg" style="width:100%"></div>
<div class="bg-image img4"><img src="https://i.pinimg.com/736x/29/c0/c4/29c0c41d913145f8a3d84c103127d123.jpg" style="width:100%"></div>
<div class="bg-image img5"><img src="https://i.pinimg.com/736x/8c/c4/b1/8cc4b1d0620b72b65b465f288db558e0.jpg" style="width:100%"></div>
<div class="bg-image img6"><img src="https://i.pinimg.com/736x/8e/64/7b/8e647bc8ae219eb6e325595c9c665fa1.jpg" style="width:100%"></div>

<div class="bg-text">Sistemas Electricos De Las Aeronaves

<br>
    <center>
<button class="Comenzar" onclick="openPage('Info', this,)">
  <p>Comenzar</p>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    class="h-6 w-6"
    fill="none"
    viewBox="0 0 24 24"
    stroke="currentColor"
    stroke-width="4"
  >
    <path
      stroke-linecap="round"
      stroke-linejoin="round"
      d="M14 5l7 7m0 0l-7 7m7-7H3"
    ></path>
  </svg>
</button>
</center>
</div>


</div>











<div id="Info" class="tabcontent">





<!-- MAIN (Center website) -->
<div class="main">
<center>
<button class="titulo" data-text="Awesome">
    <span class="actual-text">&nbsp;Sistemas Electricos De La Aeronaves&nbsp;</span>
    
  <span aria-hidden="true" class="hover-text">&nbsp;Sistemas Electricos De La Aeronaves&nbsp;</span>
</button></center>

<hr>

<h2>Aeronaves</h2>
<p>Hoy en día, los aviones están equipados con un sistema eléctrico cuya energía alimenta a otros sistemas y dispositivos. No obstante, para el encendido del motor se sigue utilizando un sistema de magnetos independiente, es decir que las magnetos no necesitan del sistema eléctrico para su operación. Gracias a esta característica, el corte del sistema eléctrico en vuelo no afecta para nada al funcionamiento normal del motor.</p>

<!-- Portfolio Gallery Grid -->
<div class="row">
  <div class="column">
    <div class="content">
      <img src="https://i.pinimg.com/736x/67/6d/a1/676da1ce7a7bb8ebb7004808cdcdffab.jpg" alt="Mountains" style="width:100%">
    <FONT COLOR="black"> 

<table>
  <tr>
    <td>
     <h3>Cota</h3>
     </td>


  <td>
     </td>
     <td>
<label class="ui-bookmark">
    <input type="checkbox">
    <div class="bookmark">
      <svg viewBox="0 0 32 32">
        <g>
          <path d="M27 4v27a1 1 0 0 1-1.625.781L16 24.281l-9.375 7.5A1 1 0 0 1 5 31V4a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4z"></path>
        </g>
      </svg>
    </div>
  </label>
     </td>
     <td>
<label class="ui-like">
    <input type="checkbox">
    <div class="like">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill=""><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"><path d="M20.808,11.079C19.829,16.132,12,20.5,12,20.5s-7.829-4.368-8.808-9.421C2.227,6.1,5.066,3.5,8,3.5a4.444,4.444,0,0,1,4,2,4.444,4.444,0,0,1,4-2C18.934,3.5,21.773,6.1,20.808,11.079Z"></path></g></svg>
       </div>
  </label>
     </td>
     </tr>      
</table>


  </label>
      <p>La energía eléctrica es necesaria para el funcionamiento de muchos sistemas e instrumentos del aeroplano: arranque del motor, radios, luces, instrumentos de navegación, y otros dispositivos que necesitan esta energía para su funcionamiento (bomba de combustible, en algunos casos accionamiento de flaps, subida o bajada del tren de aterrizaje, calefacción del pitot, avisador de pérdida, etc...)​
Antiguamente, muchos aeroplanos no contaban con un sistema eléctrico sino que tenían un sistema de magnetos que proporcionaban energía eléctrica exclusivamente al sistema de encendido (bujías) del motor; debido a esta carencia, el arranque del motor debía realizarse moviendo la hélice a mano. más tarde, se utilizó la electricidad para accionar el arranque del motor eliminando la necesidad de mover la hélice manualmente.
</p></FONT>

 


  </div>
  </div>


  <div class="column">
    <div class="content">
    <img src="https://i.pinimg.com/736x/7a/41/6e/7a416eac9e07232e8a0f8c2d35951cf5.jpg" alt="Lights" style="width:100%">


  <table>
  <tr>
    <td>
               <FONT COLOR="black"> <h3>Diego</h3></FONT>
    </td>

  <td>
<label class="ui-bookmark">
    <input type="checkbox">
    <div class="bookmark">
      <svg viewBox="0 0 32 32">
        <g>
          <path d="M27 4v27a1 1 0 0 1-1.625.781L16 24.281l-9.375 7.5A1 1 0 0 1 5 31V4a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4z"></path>
        </g>
      </svg>
    </div>
  </label>
     </td>
     <td>
<label class="ui-like">
    <input type="checkbox">
    <div class="like">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill=""><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"><path d="M20.808,11.079C19.829,16.132,12,20.5,12,20.5s-7.829-4.368-8.808-9.421C2.227,6.1,5.066,3.5,8,3.5a4.444,4.444,0,0,1,4,2,4.444,4.444,0,0,1,4-2C18.934,3.5,21.773,6.1,20.808,11.079Z"></path></g></svg>
       </div>
  </label>
     </td>
     </tr>      
</table>
     <FONT COLOR="black"> <p>
La mayoría de los aviones ligeros están equipados con un sistema de corriente continua de 12 voltios, mientras que aviones mayores suelen estar dotados de sistemas de 24 voltios, dado que necesitan de mayor capacidad para sus sistemas más complejos, incluyendo la energía adicional para arrancar motores más pesados.​
La batería o acumulador, como su propio nombre indica, transforma y almacena la energía eléctrica en forma química. Esta energía almacenada se utiliza para arrancar el motor, y como fuente de reserva limitada para uso en caso de fallo del alternador o generador.
</p></FONT>


   </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="https://i.pinimg.com/736x/4f/05/62/4f0562f6e354c0c39954e1230a3b295c.jpg" alt="Nature" style="width:100%">
          

 <table>
  <tr>
    <td>
               <FONT COLOR="black"> <h3>Casango</h3></FONT>
    </td>

  
  <td>
     </td>
     <td>
<label class="ui-bookmark">
    <input type="checkbox">
    <div class="bookmark">
      <svg viewBox="0 0 32 32">
        <g>
          <path d="M27 4v27a1 1 0 0 1-1.625.781L16 24.281l-9.375 7.5A1 1 0 0 1 5 31V4a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4z"></path>
        </g>
      </svg>
    </div>
  </label>
     </td>
     <td>
<label class="ui-like">
    <input type="checkbox">
    <div class="like">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill=""><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"><path d="M20.808,11.079C19.829,16.132,12,20.5,12,20.5s-7.829-4.368-8.808-9.421C2.227,6.1,5.066,3.5,8,3.5a4.444,4.444,0,0,1,4,2,4.444,4.444,0,0,1,4-2C18.934,3.5,21.773,6.1,20.808,11.079Z"></path></g></svg>
       </div>
  </label>
     </td>
     </tr>      
</table>





  <FONT COLOR="black">
      <p>Es el instrumento utilizado para monitorizar el rendimiento del sistema eléctrico. 
<br>
        Un valor positivo en el amperímetro indica que el generador/alternador esta aportando carga eléctrica al sistema y a la batería. Un valor negativo indica que el alternador/generador no aporta nada y el sistema se está nutriendo de la batería. Si el indicador fluctua rápidamente indica un mal funcionamiento del alternador/generador.
</p></FONT>
    </div>
  </div>
  <div class="column">
    <div class="content">
    <img src="https://i.pinimg.com/736x/f1/37/dc/f137dc8205201778b2a7f6d1aa903eac.jpg" alt="Mountains" style="width:100%">
          
 <table>
  <tr>
    <td>
               <FONT COLOR="black"> <h3>Ale</h3></FONT>
    </td>

  
  <td>
     </td>
     <td>
<label class="ui-bookmark">
    <input type="checkbox">
    <div class="bookmark">
      <svg viewBox="0 0 32 32">
        <g>
          <path d="M27 4v27a1 1 0 0 1-1.625.781L16 24.281l-9.375 7.5A1 1 0 0 1 5 31V4a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4z"></path>
        </g>
      </svg>
    </div>
  </label>
     </td>
     <td>
<label class="ui-like">
    <input type="checkbox">
    <div class="like">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill=""><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"><path d="M20.808,11.079C19.829,16.132,12,20.5,12,20.5s-7.829-4.368-8.808-9.421C2.227,6.1,5.066,3.5,8,3.5a4.444,4.444,0,0,1,4,2,4.444,4.444,0,0,1,4-2C18.934,3.5,21.773,6.1,20.808,11.079Z"></path></g></svg>
       </div>
  </label>
     </td>
     </tr>      
</table>




  <FONT COLOR="black">
      <p>Los equipos eléctricos están protegidos de sobrecargas eléctricas por medio de fusibles o breakers (interruptores de circuito). Los breakers hacen la misma función que los fusibles, con la ventaja que pueden ser restaurados manualmente en lugar de tener que ser reemplazados. Los breakers tienen forma de botón, que salta hacia afuera cuando se ve sometido a una sobrecarga; el piloto solo tiene que pulsar sobre el breaker ("botón") para volver a resta
</p></FONT>
    </div>
  </div>
<!-- END GRID -->
</div>

<div class="content">
  <img src="https://i.pinimg.com/736x/38/4e/ec/384eec32b988ed5157cbba2a318801df.jpg" alt="Bear" style="width:100%">
      
 <table>
  <tr>
    <td>
               <FONT COLOR="black"> <h3>Dani</h3></FONT>
    </td>

   <td>
     </td>
     <td>
<label class="ui-bookmark">
    <input type="checkbox">
    <div class="bookmark">
      <svg viewBox="0 0 32 32">
        <g>
          <path d="M27 4v27a1 1 0 0 1-1.625.781L16 24.281l-9.375 7.5A1 1 0 0 1 5 31V4a4 4 0 0 1 4-4h14a4 4 0 0 1 4 4z"></path>
        </g>
      </svg>
    </div>
  </label>
     </td>
     <td>
<label class="ui-like">
    <input type="checkbox">
    <div class="like">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill=""><g stroke-width="0" id="SVGRepo_bgCarrier"></g><g stroke-linejoin="round" stroke-linecap="round" id="SVGRepo_tracerCarrier"></g><g id="SVGRepo_iconCarrier"><path d="M20.808,11.079C19.829,16.132,12,20.5,12,20.5s-7.829-4.368-8.808-9.421C2.227,6.1,5.066,3.5,8,3.5a4.444,4.444,0,0,1,4,2,4.444,4.444,0,0,1,4-2C18.934,3.5,21.773,6.1,20.808,11.079Z"></path></g></svg>
       </div>
  </label>
     </td>
     </tr>      
</table>




  <FONT COLOR="black">
  <p>En el panel de instrumentos, hay un interruptor de encendido/starter accionado por llave, el cual tiene cinco posiciones:​

OFF (Apagado).​

R (Right=Derecha) en la cual solo una magneto suministra corriente a su juego de bujías.​

L (Left=Izquierda) lo mismo con la otra magneto y su juego de bujías.​

BOTH (Ambos), ambas magnetos suministran corriente, cada una a su juego de bujías, y​

START (Arranque) que acciona el starter que arranca el motor.​

​

Para generar electricidad las magnetos deben girar, así que para poner en marcha el motor el piloto acciona el arranque (llave en START), alimentado por la batería, con lo cual se hace girar al cigüeñal y este a su vez las magnetos. Una vez comienzan a girar, las magnetos producen corriente y hacen saltar en las bujías la chispa que inflama la mezcla de aire y combustible en los cilindros. En el momento en que el motor comienza a girar por su propios medios (explosiones en los cilindros), el piloto suelta la llave, la cual vuelve automauticamente a su posición de BOTH quedando desactivado el sistema de arranque. El motor sigue su ciclo de trabajo, con el sistema de encendido alimentado por la corriente generada por las magnetos gracias al giro del motor, así que la batería ya no juega ning​
  </p>
 </FONT>
</div>



<!-- END MAIN -->
<br>
<br>


<center>

<button class="Trans" onclick="openPage('Home', this,)" id="defaultOpen">Regresar</button>
<br>
<br>
<button class="Trans2" onclick="openPage('Fotos', this,)">Siguiente</button>

<br>
<br>
<br>


</div>
</div>
























<div id="Fotos" class="tabcontent">




<!-- Header -->
<div class="headering" id="myHeader">
  <FONT COLOR="black"><h1>Imagenes de Aviones</h1></FONT>
  <br>
  <br>


<button class="Trans3" onclick="openPage('Creditos', this,)" id="defaultOpen">Siguiente</button>
  <br>
  <br>



  <button class="btn" onclick="one()">1</button>
  <button class="btn active" onclick="two()">2</button>
  <button class="btn" onclick="four()">4</button>
</div>

<!-- Photo Grid -->
<div class="rolls"> 
  <div class="columbia">
    <img src="https://i.pinimg.com/736x/2d/c9/94/2dc994dec24b21ad8333966c0663d464.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/fb/31/0a/fb310a8c05271eb04e4bc4d885ed9667.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/2b/52/b5/2b52b5a84e015aa85d63e8963f21790b.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/b2/3b/db/b23bdb5e8ef48d9e9beff180456aadb6.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/a8/2d/ef/a82def64a05e1716f2cbac9abf2703cc.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/93/f3/e6/93f3e6a5126a589b7d5bfb950277efd0.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/28/c7/dd/28c7dd2b4d5f0f4486992e1ae02434cb.jpg" style="width:100%">
  </div>
  <div class="column">
    <img src="https://i.pinimg.com/736x/82/a7/20/82a7206266143b263051d20734f4c31f.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/e8/83/ae/e883ae99593262d2f07bc9273033f5c9.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/8e/64/6a/8e646aa3943a57194fb93a6fe8318569.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/4c/54/0e/4c540ea3435572e076007efd6bb44320.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/41/2e/7d/412e7d86765f210a35abc0551aec2569.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/0b/ba/38/0bba3886cc33462a93ecbbbefa52d355.jpg" style="width:100%">
  </div>  
  <div class="columbia">
    <img src="https://i.pinimg.com/736x/25/a5/51/25a5512104b5e6a7467d21eb4114cd69.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/de/41/ed/de41ed90ae64af086f8d86000f4c315d.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/d5/f8/e9/d5f8e9d90e138c23b09f4fb30ef7f413.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/30/c3/54/30c354e892121a1089c841392565f8c2.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/23/20/9c/23209cf5d78228d93394ff0a6edf3edb.jpg" style="width:100%">

  </div>
  <div class="columbia">
    <img src="https://i.pinimg.com/736x/b8/d1/9c/b8d19c16fa6d2e9f96af31931fa31a01.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/87/3c/b2/873cb24018a07ba2de0ec54807aa9afb.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/8b/92/9b/8b929bd024e31519527bcb2c33860498.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/1a/fe/eb/1afeebdbbbb5be7f991ea5b8db4e9cc1.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/e9/8d/d7/e98dd7175ecfb459f3e86d821c4e7d89.jpg" style="width:100%">
    <img src="https://i.pinimg.com/736x/14/3f/62/143f62e8f8e2a3653b90a8c55adbd269.jpg" style="width:100%">
  </div>
</div>




</div>








<div id="Creditos" class="tabcontent">













<br>
<br>
<center>

<table>
  <tr>


<td>
<div class="card">
  <div class="image"><img id="myImg" src="https://i.pinimg.com/736x/c7/c9/92/c7c992f263101c6af899a747ec3e1ab4.jpg" alt="Casango" width="350" height=" 290"></div>
  <div class="content">
    <p class="text-1">
      Jose Casango
    </p>

  <p class="date">
      Tecnico en Programacion
    </p>
     <p class="date">
      Ing. Aeronautico
    </p>
 <div class="text-2">
      <span>
      
  </span>
      <span>jose405378@gmail.com</span>
    </div>
</div>





<td>
<div class="card">
  <div class="image"><img id="myImg2" src="https://i.pinimg.com/736x/34/cd/df/34cddf5c044cc4f8fa6333ee4479b866.jpg" alt="Cota" width="350" height=" 290"></div>
  <div class="content">
    <p class="text-1">
      Jose Cota
    </p>

  <p class="date">
      DOWNHILL
    </p>
     <p class="date">
      Ing. Aeronautico
    </p>
 <div class="text-2">
      <span>
      
  </span>
      <span>cota35125@gmail.com</span>
    </div>
</div>


<td>
<div class="card">
  <div class="image"><img id="myImg3" src="https://i.pinimg.com/736x/a4/f4/e4/a4f4e4ea81f742af9e90d056e324218c.jpg" alt="Luna" width="350" height=" 290"></div>
  <div class="content">
    <p class="text-1">
      Diego Luna
    </p>

  <p class="date">
      GYM
    </p>
     <p class="date">
      Ing. Aeronautico
    </p>
 <div class="text-2">
      <span>
      
  </span>
      <span>luna7674@gmail.com</span>
    </div>
</div>




<center>
<tr>
  <td>
<div class="card">
  <div class="image"><img id="myImg4" src="https://i.pinimg.com/736x/35/8d/73/358d739cae62183f50e78c1faefb9a8e.jpg" alt="Alexa" width="350" height=" 290"></div>
  <div class="content">
    <p class="text-1">
      Perla Alexa
    </p>

  <p class="date">
      GYM
    </p>
     <p class="date">
      Ing. Aeronautico
    </p>
 <div class="text-2">
      <span>
      
  </span>
      <span>Perla001@gmail.com</span>
    </div>
</div>

  <td>
<div class="card">
  <div class="image"><img id="myImg5" src="https://i.pinimg.com/736x/b5/1f/b7/b51fb760aef4c3907d5947f3d49db0c0.jpg" alt="Luis" width="350" height=" 290"></div>
  <div class="content">
    <p class="text-1">
      Daniel Fuentes
    </p>

  <p class="date">
      GYM
    </p>
     <p class="date">
      Ing. Aeronautico
    </p>
 <div class="text-2">
      <span>
      
  </span>
      <span>fuentesluis@gmail.com</span>
    </div>
</div>






<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>
















</div>


















<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

document.getElementById("defaultOpen").click();


















var elements = document.getElementsByClassName("column");


var i;

// Full-width images
function one() {
    for (i = 0; i < elements.length; i++) {
    elements[i].style.msFlex = "100%";  // IE10
    elements[i].style.flex = "100%";
  }
}

// Two images side by side
function two() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.msFlex = "50%";  // IE10
    elements[i].style.flex = "50%";
  }
}

// Four images side by side
function four() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.msFlex = "25%";  // IE10
    elements[i].style.flex = "25%";
  }
}

// Add active class to the current button (highlight it)
var header = document.getElementById("myHeader");
var btns = header.getElementsByClassName("btn");
for (var i = 0; i < btns.length; i++) {
  btns[i].addEventListener("click", function() {
    var current = document.getElementsByClassName("active");
    current[0].className = current[0].className.replace(" active", "");
    this.className += " active";
  });
}















// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}






// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg2");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}







// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg3");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}








// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg4");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}




// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg5");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}






// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg6");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}
</script>

</body>
</html>
