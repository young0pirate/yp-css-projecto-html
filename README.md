/*Formatações gerais*/
*{box-sizing: border-box;
font-size: 12pt;
font-family: "times new roman";
margin: 0 0 0 0;
color: black;
}

p,section{
text-indent: 10px;
text-align: justify;
font-family: 'Times New Roman';
font-size: 10pt;
}
p::first-letter{
font-size: 12pt;
font-weight: 500;
font-style: italic;
font-family: arial;
}

a{
text-decoration: none;
color: darkblue;
font-size: 10pt;
}

img{
width: 300px;
height: 200px;
margin: 0 auto;
}

.corpo-rodape{
background-color: black;
}
footer{
margin-top: 9%;
padding: 13px;
box-shadow: 1px 1px 3px 2px gray;
}

footer p{
color: white;
}
.unico{
width: 20px;
height: 20px;
}

.cont-img{
display: flex;
justify-content: flex-end;
margin-top: -2%;
}

.voa{
background-color: white;
}
/*Fim... */

/*Formatação do cabeçalho da página HOME VIEW MORE*/
header{
margin-top: 10px;
margin-bottom: 4px;
background-color: darkorange;
padding: 10%;
box-shadow: 2px 2px 1px 1px gray;

}

header nav{
display: flex;
}
nav a{
font-size: 10pt;
border-bottom: dashed 1px blue;
border-top: solid 1px blue;
margin-bottom: 5px;
}

nav{
width: 85%;
margin: 0 auto;
margin-top: 8px;
margin-bottom: 2px;
}
form{
text-align: center;
}
.btn{
background: gray;
opacity: 0.5;
font-family: georgia;
font-size: 10pt;
color: white;
font-style: italic;
font-weight: bolder;
}
.btn, .pesq{
border: 0px;
}
form .pesq{
width: 150px;
}
nav{
justify-content: space-around;
flex-wrap: wrap;
align-items: center;
background-color: black;
}
.n-1
{margin-left: 0px;}
.M
{margin-right: 0px;}

.n-1, .n-2, .n-3, .n-4, .n-5{
font-style: oblique;
font-weight: bold;
text-transform: uppercase;
}
.n-1{
color: green;
}
.n-2{
color: darkred;
}
.n-3{
color: orange;
}
.n-4{
color: darkcyan;
}
.vazio2{
padding: 1%;
margin-bottom: 1%;
}

.vazio{
background-color: lightblue;
padding: 3px;
}
/*Fim...*/

/*Formatação do corpo da página HOME*/
.p-dif{
background-color: orange;
}

.tam{
font-size: 9pt;
}

ol li{
font-size: 7pt;
color: purple;
font-style: oblique;
font-variant: bolder;
text-transform: uppercase;
}

dt{
color: green;
text-align: center;
font-size: 7pt;
background-color: cyan;
}
.css{
max-width: 50%;
float: left;
clear: right;
border: solid 1px gray;
font-size: 6px;
}

.html{
max-width: 50%;
float: left;
clear: right;
font-size: 6px;
}
#exp-tec
{
color: gray;
font-family: helvetica;
margin-top: 4%;
margin-bottom: 6%;
}
article h6 p
{
font-size: 3pt;
}

h6{
color: red;
font-size: 8pt;
font-style: italic;
text-align: right;
}
#borda
{
border: 2px solid gray;
box-shadow: 2px 2px 1px 1px gray;
background-color: darkgreen;
}
h4{
font-family: impact;
font-style: italic;
color: gray;
text-align: center;
}
h5{
color: purple;
font-style: oblique;
text-decoration: underline
}
.h5{
text-align: center;
}
h3{
margin-bottom: 6px;
text-align: center;
font-familiy: Serif;
}
.fQ
{
text-align: center;
font-style: italic;
font-size: 11px;
font-weight: bolder;
text-transform: lowercase;
text-shadow: gray 1px 1px;
box-shadow: black 7px 3px;
}
ul li{
font-style: bliquo;
font-size: 10pt;
font-family: Verdana, Helvetica, Calibri, 'Times New Roman';
}
hr{
margin-top: 4px;
margin-bottom: 3px;
background-color: red;
}
.branco li{
color: white;
}
/*Fim...*/

/*Formatação da página VIEW MORE*/
section > h2{
background-color: gray;
font-variant: small-caps;
text-align: center;
font-weight: medium;
color: white;
}
.dif{
background-color: yellow;
color: blue;
}


#pai
{
background-color: rgba(7,2,0,0.1);
}

figcaption{
font-size: 10px;
font-family: serif;
font-style: italic;
color: white;
margin-top: -3px;
background-color: green;
text-align: center;
text-transform: capitalize;
}

#mb
{
margin-top: 2%;
text-transform: uppercase;
text-align: center;
font-style: italic;
font-family: California;
font-size: 10px;
color: brown;
opacity: 0.9;
background-color: lightblue;
width: 50%;
}

address{
font-size: 9pt;
font-family: calibri;
color: gray;
text-align: center;
}
/*Fim...*/


/*Formatação da página commuty*/

#tab-html
{
border: solid 1px gray;
}
/*Fim*/


/*Versão variável -formatação*/
@media (min-width: 480px){
img{
width: 450px;
height: 300px;
m
}
figcaption{
font-size: 10pt;
text-align: center;
width: 450px;
margin: 0 auto;
}

.n-1
{margin-left: 0px;}
.n-5
{margin-right: 0px;}

#mb
{
width: 70%;
}

.vazio2{
width: 400px;
}
}

/*Fim...*/
@media print{
font-family: 'Times New Roman';
font-size: 12pt;
color: black;
}
@page{
size: A4 portrait;
}
