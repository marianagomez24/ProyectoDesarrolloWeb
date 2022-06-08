# ProyectoDesarrolloWeb
<html>
    <head>
        <title>Toyota</title>
        <link rel="stylesheet" href="css/home.css"/>
        <link rel="stylesheet" href="css/index.css" type="text/css">
        <link rel="stylesheet" href="css/toyota.css" type="text/css"/>
        <link rel="stylesheet" href="css/volkswagen.css" type="text/css">
        <link rel="stylesheet" href="css/login.css" type="text/css"/>




    </head>
    
    <body>
        <!-- Este Div es nuestro Container = contiene toda la página-->
        <div class = 'container'>
            <div class = 'compra3'>
              <p>Comprar</p>
              </div>
               <div class = 'compra4'>
                   
              <p>Comprar</p>
              </div>
        
            <!-- Este Div es nuestro NAVBAR = navigation bar -->
            <div class = 'navbar'>
                <img src="images/toyota.png" class = 'toyota' alt="Es mi logo"/>
              <nav>
                
                    <p>Toyota Corolla 2022, automatico, precio: 20.000 $</p>
                     <p>Comprar</p>
              </nav>
              <nav>
                  <p>Toyota Hilux 2022, automatico, precio: 50.000 $</p>
                   <p>Comprar</p>
              </nav>
            </div>
            
            <!-- Este DIV es nuestro contenido -->
            <!-- br = break = es crear un salto de linea -->
            <div class = 'content'>
            
                <img src="images/toyota1.jpg" class = 'toyota1' alt="alt"/>
                <img src="images/toyota2.jpg" class = 'toyota2' alt="alt"/>
            </div>
        
        </div>
    </body>
</html>

.......................................................................................................................................................................

@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Kaushan+Script&family=Roboto:wght@100&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Kaushan+Script&family=Monda&family=Roboto:wght@100&display=swap');


*{
    margin:0;
    padding:0;
    font-family:'Bebas Neue', cursive;
}

.compra3{
    position: initial;
    padding-left: 1%;
    border-radius: 10px;
    padding-right: -15%;
    background-color: #0F1A59;
    position:   absolute;
    color: white;
    top: 48%;
    height:4vh;
    width: 4%;
    cursor: pointer;
    text-decoration: underline;
    left: -20px;
    right: -600px;
    display:flex;
    margin: auto;
    align-items:  normal;
}

.compra4{
    position: initial;
    padding-left: 1%;
    border-radius: 10px;
    padding-right: -10%;
    background-color: #0F1A59;
    position:   absolute;
    color: white;
    top: 48%;
    height:4vh;
    width: 4%;
    cursor: pointer;
    text-decoration: underline;
    left: 20px;
    right: 400px;
    display:flex;
    margin: auto;
    align-items:  normal;

}
.container{
    height:100vh;
    width:100%;
    background-color: #ffffff;
    background-position:center;
    background-size: cover;
    padding-left: 10%;
    padding-right: 35%;
    box-sizing: border-box;
    position:relative;
    
}
/*Lo que hace el display el comportamiento de nuestros elementos en la cajita el flex hace que se acomoden en un nivel de bloque , align es que los queremos centrados
*/
.navbar{
    position: relative;
    height:35vh;
    width:100%;
    left: auto;
    margin:auto;
    display:flex;
    align-items: center;
}



/*Es que se aplica ese como tal*/
nav{
    /*El flex que tanto va crecer como de uno a uno*/
  top: 200px;
  position: relative;
  flex:1;
  padding-left: 60px;  
  right: -280px;
}

/*Lo que hace esque siempre esta sucesión que le aplique los datos que están adentro

/* el inline block que se desplque en una sola linea horizontal*/

/*none es no ponerle ningun estilo y el margin*/

nav ul li{
    display:inline-block;
    list-style: none;
    margin:0px 20px;
}

nav ul li a{
    /*Quitar la linea que está debajo*/
    text-decoration: none;
    /*Ponerle color*/
    color: black;
    font-size: 25px;
    font-family: 'Monda', sans-serif;
}

nav ul li a:hover{
    text-decoration: underline;
}

.content h1{
    font-size: 60px;
    font-weight: bold;
    margin-top:80px;
    margin: 200px;
    color:black;
}
.content p{
    position: relative;
    top:-180px;
    margin-left: 210px;
    font-size:20px;
    color:black;
    font-family: 'Kaushan Script', cursive;
}

.content h1 p{
    position: relative;
    left: 500px;
}

.toyota{
    height: 50%;
    position: absolute;
    bottom: 50px;
   left: 590px;
  
}

.toyota1{
    height: 40%;
    position: absolute;
    bottom: 50px;
    right: 250px;
   
}

.toyota2{
    height: 40%;
    position: absolute;
    bottom: 50px;
   
    left: 350px;
}
.
