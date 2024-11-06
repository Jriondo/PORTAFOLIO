*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: "Oxygen", sans-serif;
}    


body{
    background: rgb(250,215,161);
    background: linear-gradient(90deg, rgba(250,215,161,1) 0%, rgba(233,109,113,1) 100%);; 
}

body {
    font-family: Arial, sans-serif;
}


///////////////////////////////////////////////////////////////////////////////////////////////////////////
.header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 85px;
    padding: 5px 10%;
}

.header .h2 {
    height: 70px;
    width: auto ;
}

.header .nav-links {
    list-style: none;
    font-size: 17px;
}

.header .nav-links li{
    display: inline-block;
    padding: 0 20px;
}
.header .nav-links li:hover{
    transform: scale(1.1);
}

.header .nav-links a {
    font-size: 700;
    color: #616161;
    text-decoration: none;
}

.header .nav-links a1 {
    color: #363636;
    font-weight: bold;
}

.header .nav-links li a:hover{
    color: #616161;
}

.header .btn button {
    font-weight: bold;
    color: #000000;
    padding: 9px 25px;
    background: #0ceca2;
    border: 3px solid black;
    border-radius: 50px;
    cursor: pointer;
    transition: all 0.3s ease 0s;
    font-size: 15px;
    box-shadow: 1px 1px 20px;
}

.header .btn button:hover {
    transform: scale(1.1);
}


////////////////////////////////////////////////////////////////////////


.Hola-Santiago {
    position: relative;
    max-width: 108%;
    display: flex;
    align-items: center;
}
.Hola-Santiago .Eclipse {
    width: 350px;

}
.Hola-Santiago .tituloBienvenida {
    position: relative;
    max-width: 600px;
}
.Hola-Santiago .tituloBienvenida h2 {
    font-size: 4.0em;
    color: black;
    line-height: 1.7;
}
.Hola-Santiago .tituloBienvenida h1 {
    font-size: 5em;
    color: black ;
    line-height: 1.6;
}
.Hola-Santiago .tituloBienvenida p {
    font-size: 20px;
    line-height: 1.6;
    margin-bottom: 20px
}
.Hola-Santiago .tituloBienvenida .btnRedes {
    display: flex;
    justify-content: space-between;
    width: 230px;
}
.Hola-Santiago .tituloBienvenida .btnRedes .btnTelefono:hover {
    transform: scale(1.1);

}
.Hola-Santiago .tituloBienvenida .btnRedes .btnEmail:hover {
    transform: scale(1.1);
}
.Hola-Santiago .tituloBienvenida .btnRedes .btnInstagram:hover {
    transform: scale(1.1);
}
.Hola-Santiago .tituloBienvenida .btnRedes .btnTwitter:hover {
    transform: scale(1.1);
}           


.Hola-Santiago .imgPersona img {
    width: 720px;
    height: 700px;
}


//////////////////////////////////////////////////////////////////////////////


.cuerpoSection1 {
    padding: 100px 0;
    display: flex;
    justify-content: space-around  ;
} 
.cuerpoSection1 .comentario {
    text-align: center;
}
.cuerpoSection1 .comentario p {
    font-size: 42px; 
    line-height: 1.6;
    color: #0F0A0A;
    font-weight: lighter; 
}
.cuerpoSection1 .comentario h5 {
    font-size: 27px;
    font-weight: bold;
    line-height: 4;
}

///////////////////////////////////////////////////////////////////////////////



.git-contenedor {
    height: 550px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.git-contenedor .textos-botones {
    position: relative ;
    max-width: 500px;
    padding-left: 100px;
    margin: 0 0 0 25px;  
}
.git-contenedor .textos-botones h3 {
    font-size: 42px;
    color:#0ceca2;
    background-color: #000000;
    box-shadow: -6px 5px 0px 0px rgba(255,255,255,1);
    line-height: 1.5;
    padding-left: 10px;
}
.git-contenedor .textos-botones p {
    font-size: 16px;
    padding-top: 30px;
    line-height: 1.5;
}
.git-contenedor .textos-botones .btnsgitHub {
    display: flex;
    justify-content: space-between;
    width: 230px;
    padding-top: 16px;
    margin-inline: -18px;

}

.git-contenedor .textos-botones .btnsgitHub .btnVerProyecto:hover {
    transform: scale(1.1);
}
.git-contenedor .textos-botones .btnsgitHub .btngit:hover {
    transform: scale(1.1);
}
.git-contenedor .vistaPrevia img { 
    width: 800px; 
    height: 450px;
    margin: 0 0 0 80px;
}

////////////////////////////////////////////////////////////////////////////////////

.testimonio {
    position: relative;
    display: flex;
    justify-content: center;
    padding: 80px 0;
}
.testimonio .contenedorTestimonio {
    width: 1366px; 
    height: 603px; 
}
.testimonio .contenedorTestimonio img {
    width: 1366px;
    height: 603px;
}


/////////////////////////////////////////////////////////////////////////////////////////////////


.marvel {
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 16px 0;
}
.marvel .tablet{
    width: 518px;
    height: 588px;
    align-items: center;
}
.marvel .tablet img{
    width: 508px;
    height: 555px;
}
.marvel {
    padding-left: 10px;
}
.marvel .textoMarvel .letra {
    display: inline-block;
    font-size: 38px;
    color:#0ceca2;
    background-color: #000000;
    box-shadow: -6px 5px 0px 0px rgba(255,255,255,1);
    line-height: 1.5;
    padding-left: 10px;
    padding-right: 10px;
}
.marvel .textoMarvel p {
    font-size: 16px;
    padding-top: 25px;
    line-height: 1.3;
}
.marvel .textoMarvel .btnsgitHub {
    display: flex;
    justify-content: space-between;
    width: 230px;
    padding-top: 16px;
    margin-inline: -18px;
}
.marvel .textoMarvel .btnsgitHub .btnSeeProyecto:hover {
    transform: scale(1.1);
}
.marvel .textoMarvel .btnsgitHub .btngitHub:hover{
    transform: scale(1.1);
}


///////////////////////////////////////////////////////////////////////////////////

.testimonio2 {
    position: relative;
    display: flex;
    justify-content: center;
    padding: 80px 0;
}
.testimonio2 .contenedorTestimonio2 {
    width: 1366px; 
    height: 523px; 
}
.testimonio2 .contenedorTestimonio2 img {
    width: 1366px;
    height: 523px;
}

////////////////////////////////////////////////////////////////////////////////////////////

.sectionNet {
    position: relative;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 16px 0px;
}
.sectionNet .textosNet {
    position: relative ;
    max-width: 500px;
    margin: 0 0 0 0px;  
}
.sectionNet .textosNet .letra2 {
    display: inline-block;
    font-size: 38px;
    color:#0ceca2;
    background-color: #000000;
    box-shadow: -6px 5px 0px 0px rgba(255,255,255,1);
    line-height: 1.5;
    padding-left: 10px;
    padding-right: 10px;
}
.sectionNet .textosNet p {
    font-size: 16px;
    padding-top: 30px;
    line-height: 1.5;
}
.sectionNet .textosNet .btnsgitHub3 {
    display: flex;
    justify-content: space-between;
    padding-top: 16px;
    margin-inline: -18px;
}
.sectionNet .textosNet .btnsgitHub3 .btngit3{
    padding-right: 10px;
}

.sectionNet .textosNet .btnsgitHub3 .btnVerProyecto3:hover {
    transform: scale(1.1);
}
.sectionNet .textosNet .btnsgitHub3 .btngit3:hover{
    transform: scale(1.1);
}
.sectionNet .vistaCelular{
    width:610px;
    height: 636px;
    align-items: center;
}
.sectionNet .vistaCelular img{
    width: 380px;
    height: 636px;
}


////////////////////////////////////////////////////////////////////////////////////////////////

.testimonio3 {
    position: relative;
    display: flex;
    justify-content: center;
    padding: 80px 0;
}
.testimonio3 .contenedorTestimonio3 {
    width: 1366px; 
    height: 573px; 
}
.testimonio3 .contenedorTestimonio3 img {
    width: 1366px;
    height: 573px;
}


///////////////////////////////////////////////////////////////////////////////////////////////////////////

.hablemos {
    position: relative;
    display: flex;
    justify-content: center;
    text-align: center;
    padding: 75px 15px;
}
.hablemos .textosHablemos .letra3 {
    text-align: center;
    font-size: 30px;
    color:#0ceca2;
    background-color: #000000;
    box-shadow: -5px 4px 0px 1px rgba(255,255,255,1);
    line-height: 1.5;
    padding: 5px;
}
.hablemos .textosHablemos p {
    font-size: 16px;
    padding-top: 20px;
    line-height: 1.5;
    font-weight: 500px;
}
form {
    display: inline;
    justify-content: left;
}
.input-group {
    display: flex;
    flex-direction: column;
    text-align: left;
    padding-top: 25px;
}
label {
    color:#000000;
    font-size: 15px;
    font-weight: 600;
    margin-bottom: 10px;
    padding-left: 12px;
}
input, textarea {
    padding: 13px 12px;
    border-radius: 8px;
    background-color: white;
    margin-bottom: 15px;
    border: 2px solid #b3b3b3;
    color: #000000;
}
.btnFinal {
    font-weight: 600;
    color: #000000;
    padding: 9px 25px;
    background: #0ceca2;
    border: 2px solid black;
    border-radius: 50px;
    cursor: pointer;
    transition: all 0.3s ease 0s;
    font-size: 15px;
    box-shadow: 1px 1px 10px;
}
.btnFinal:hover {
    transform: scale(1.1);
}


////////////////////////////////////////////////////////////////////////////////////////////////////

.piePagina {
    padding: 25px 0;
    overflow: hidden;
    display: flex;
    justify-content: space-evenly;
    margin: auto;
    align-items: center;
}
.piePagina .logoPie h1{
    font-weight: 700;
    font-size: 25px;
    
}
.piePagina .mensajePie {
    padding-bottom: 20px;
    align-items: center;
    text-align: center;
    font-size: 20px;
}
.piePagina .redesIcons {
    display: flex;
    justify-content: space-between;
    width: 230px;
}
.piePagina .redesIcons .btnTelefonoPie:hover {
    transform: scale(1.1);
}
.piePagina .redesIcons .btnEmailPie:hover {
    transform: scale(1.1);
}
.piePagina .redesIcons .btnInstagramPie:hover {
    transform: scale(1.1);
}
.piePagina .redesIcons .btnTwitterPie:hover {
    transform: scale(1.1);
