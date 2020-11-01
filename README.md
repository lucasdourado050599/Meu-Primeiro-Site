# Meu-Primeiro-Site
body, div, h1, h2, h3, h4, h5, h6, p, ul, ol, li, dl, dt, dd, img, form, fieldset, input, textarea, blockquote {
	margin: 0; padding: 0; border: 0;
}

body {
	background: #ffe743;
	font: 16px Helvetica, Arial, Sans-Serif; color: #000000	; line-height: 24px;
	
}

#menu {
	margin: 0px auto; 
	text-align: center;
}

#menu ul ul {
	display: none;
}

	#menu ul li:hover > ul {
		display: block;
	}


#menu ul {
	background: #ff1d0b; 
	padding: 0 20px;
	list-style: none;
	position: relative;
	display: inline-table;
	}
	#menu ul:after {
		content: ""; clear: both; display: block;
	}

	#menu ul li {
		float: left;
	}
		#menu ul li:hover {
			background: #CD5555;
		}
			#menu ul li:hover a {
				color: #ffffab;
			}
		
		#menu ul li a {
			display: block; padding: 25px 40px;
			color: #ffffab; text-decoration: none; text-align: left;
		}
			
		
	#menu ul ul {
		background: #ff0000; border-radius: 0px; padding: 0;
		position: absolute; top: 100%;
	}
		#menu ul ul li {
			float: none;
			position: relative;
		}
			#menu ul ul li a {
				padding: 15px 40px;
				color: #fff;
			}	
				#menu ul ul li a:hover {
					background: #CD5555;
				}
					#menu ul ul li {
						float: none;
						position: relative;
					}

	
			
		
	#menu ul ul ul {
		position: absolute; left: 100%; top:0;
	}

#whats {

    position: fixed;
    top: 76%;
    left: 7%;
    padding: 100px;
    z-index: 10000000;

}


#container {
	width: 960px; margin: 0 auto;
}

	#footer {
	padding: 40px 0 0 0;
	overflow: hidden; margin: 0 0 30px 0;
}
	#footer p#copyright {
		font-size: 12px; float: left; margin: 0 0 0 30px; color: #000000	;
	}
	#footer p#loja {
		
		font-size: 12px; float: left; margin: 0 0 0 30px; color: #000000; font-weight: bold	;
	}
	#footer p#back-top {
		float: right;
	}
		#footer a {
		color: #EE6363; text-decoration: none;
	}
		#footer a:hover {
			color: #CD5555;
		}

#header {
	height: 224px; padding: 52px 10px 0 57px;
	background: url(../imagens/capa.gif);
}

	#header h1 {
		font: 38px Georgia, Serif; color: #000000; letter-spacing: 2px; margin: 0 0 20px 0;
		text-shadow: 0px 3px 3px #494949;
	}
	#header h2 {
		width: 510px; font: 30px Georgia, Serif; color: #000000; letter-spacing: 2px; margin: 0 0 20px 0;
		text-shadow: 0px 3px 3px #494949;
	}

#content {
	background: url(../imagens/fundo.png) repeat-y;
	padding: 57px 69px 50px 69px; overflow: hidden;
}
	#content h2 {
		font: 30px Georgia, Serif; letter-spacing: 2px; margin: 0 0 20px 0;
	}

	#content h3 {
		font: 26px Georgia, Serif; letter-spacing: 2px; margin: 0 0 20px 0;
	}
	
	#content p {
		margin: 0 0 30px 0;
	}
	
	#content a {
		color: #000000; text-decoration: none;
	}
		#content a:hover {
			color: #000000;
		}

div.figura {
  background-color: #f2f0eb;
  float: center;
  width: auto;
  border: none;
  margin: 1em;
  padding: 0;
}
div.figura span {
  text-align: left;
  font-style: italic;
  font-size: smaller;
  text-indent: 0;
}
img.escala {
  width: 100%;
}

#content .resumo-item {
	width: 182px; padding: 4px; background: #eee; text-align: center;
	float: left; margin: 0 7px 14px 7px;
}
	#content .resumo-item p.btn {
		margin: 0;
	}
	#content .resumo-item p.btn a {
		display: block; width: 183px; height: 29px; padding: 7px 0 0 0;
		background: url(../imagens/fu.jpg);
		font-weight: bold; text-align: center; text-transform: uppercase;
		text-decoration: none;
	}

#content #contact {
	width: 411px; float: left; margin: 0 40px 0 0;
}

#content #contact label {
	float: left; clear: left; margin: 11px 20px 0 0; width: 95px;
	text-align: right; font-size: 16px; 
	text-transform: uppercase;
}
	
#content #contact input {
	width: 256px; height: 35px; padding: 5px 20px 0px 20px; margin: 0 0 20px 0;
	background: #ffe743;
	font-family: sans-serif; font-size: 16px; color: #000000; text-shadow: 0px -1px 0px #000000;
}
	
#content #contact textarea {
	width: 256px; height: 170px; padding: 12px 20px 0px 20px; margin: 0 0 20px 0;
	background: #ffe743;
	font-family: sans-serif; font-size: 16px; color: #000000; text-shadow: 0px -1px 0px #000000;
}
	
#content #contact input:focus, #content #contact textarea:focus {
	background: #ffe743;
}
	
#content #contact input[type=submit] {
	width: 185px; height: 52px; float: right; padding: 10px 15px; 
	border: 1px solid #000000;
	cursor: pointer;
}

#content #social {
	width: 371px; float: left; 
}		
	#content #social ul {
		list-style: none;
	}
		#content #social ul li {
			float: left; margin: 0 20px 20px 0;
		}
			#content #social ul li a {
				display: block; width: 100px; padding: 20px 0 5px 45px;
			}

#header.page {
	height: 91px; padding: 52px 0 0 57px;
	background: url(../imagens/header.png);
}


/*Galeria de fotos*/

.galeria {
	width:680px;
	height: 375px;
	margin:30px auto;
	text-align:left; 
	}
ul.fotos {
	position:relative;
	list-style:none;  
	width:162px;
	padding:0px;
	background:#999;
	margin:0; 
	padding:0; 
}
.fotos:after {
	display: block;
	content: ".";
	height: 0;
	font-size:0; 
	visibility: hidden;
	clear: both;
	}
ul.fotos li {
	width:75px;
	height:50px;
	float:left; 
	border:2px solid #444;
	margin:1px; 
}
ul.fotos li img {
	border:none; 
	width:75px;
	height:50px;
}
ul.fotos li span img {
	border:none;
	width:500px;
	height:375px;
}
ul.fotos a {
	display: block;
	} 
ul.fotos a span {
	display: none;
}
ul.fotos a:hover span {
	display: block;
	text-align:center; 
	width:500px;
	position:absolute;
	top:375px;
	left:-2px;
}
ul.fotos a:hover span {
	display: block;
    position: absolute; 
	top:-5px; 
	left: 177px; 
	background:#fff;
   }
ul.fotos a:hover span {
	padding:5px 0;
	color:#333; 
}

#tabela
{
font-family:Georgia, Arial, Helvetica, sans-serif;
width:100%;
border-collapse:collapse;
}
#tabela td, #tabela th 
{
font-size:1em;
border:1px solid  #000000;
padding:3px 7px 2px 7px;
}
#tabela th 
{
font-size:1.1em;
text-align:left;
padding-top:5px;
padding-bottom:4px;
background-color:#000000;
color:#ffffff;
}
#tabela tr.alt td 
{
color:#000000;
background-color:#ffffab;
}
Meu primeiro site no ar, feito em HTML e CSS
