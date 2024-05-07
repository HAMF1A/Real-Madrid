/* Barra de navegacion */
.navbar {
    background-color: white !important;
    font-size: 18px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight: lighter;
}

.navbar-collapse {
    align-items: center;
    justify-content: space-between;
}


/* Barra de navegacion */

.portada{
    background-image: url(Imagenes/cesped\ banner.jpg);
    background-size: cover;
    
}

.portada-imagen{
   width: auto;
   height: auto;
}


/* Estilos Generales */
section{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

h1 {
    font-size: 2.5rem;  
    font-weight: bold;
}

.seccion-oscura {
    color: white;
    background-color: black;
}

.seccion-clara {
    color: black;
    background-color: white;
}

.seccion-titulo {
    font-size: 2rem;
    padding: 15px 0;
    text-align: center;
    color:#ffd700;

}


.seccion-descripcion{
    font-size: 1.2rem;
    color: #584e4e;
}

.seccion-texto {
    font-size: 1.2rem;
    text-align: center justify;
}

.texto-negro {
    color: black;
}

.texto-blanco{
    color: white;
}

/* NOTICIAS */
.Noticias {
    background-color: #f8f9fa;
    padding: 0.5rem;
  }
  
  .Noticias h1 {
    color: #333;
  }
  
  .carousel-news .carousel-item img {
    width: 100%;
    height: auto;
  }
  
  .carousel-news .carousel-caption {
    background-color: rgba(0, 0, 0, 0.5);
    padding: 20px;
    border-radius: 10px;
    color: #fff;
  }
  
  .carousel-news .carousel-caption h2 {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 10px;
  }
  
  .carousel-news .carousel-caption p {
    font-size: 16px;
  }
  
  .carousel-control-prev,
  .carousel-control-next {
    background-color: transparent;
    border-radius: 25px;
  }
  
  .carousel-control-prev-icon,
  .carousel-control-next-icon {
    background-color: #fff;
    border-radius: 50%;
    color: #000;
  }
  
  .carousel-control-prev:hover,
  .carousel-control-next:hover {
    background-color: rgba(0, 0, 0, 0.7);
  }
  
  .carousel-control-prev-icon,
  .carousel-control-next-icon {
    background-color: #000;
  }

  /* Columnas Jugadores */
.Jugadores {
    padding: 0.5rem; 
  }
  
  .Jugadores h1 {
    color: #333;
    text-align: center;
    margin-bottom: 30px;
  }
  
  /* Estilos para hacer la tabla responsive */
  .table-responsive {
    overflow-x: auto;
  }
  
  /* Estilos personalizados para la tabla */
  .table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0 10px;
    border: 2px solid #dee2e6;
    border-radius: 10px;
    border-color: gold;
  }
  
  .table th,
  .table td {
    padding: 15px;
    text-align: center;
    border: 2px solid #dee2e6;
    border-color: gold;
    font-weight: bold;
  }
  
  .table th {
    background-color: #f8f9fa;
    color: #333;
    font-weight: bold;
    border-radius: 10px 10px 0 0;
    border-color: gold;
  }
  
  .table-striped tbody tr:nth-of-type(odd) {
    background-color: rgba(0, 0, 0, 0.05);
  }
  
  /* Estilos para las imágenes de los jugadores */
  .table img {
    max-width: 60px;
    height: auto;
    border-radius: 50%;
    transition: transform 0.3s ease, border-radius 0.3s ease;
  }
  
  .table img:hover {
    transform: scale(1.1);
    border-radius: 10%;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
  }


/* SECCION TROFEOS MEJORADO */


.trofeos {
  padding: 40px ;
}

.trofeos-titulo{
  font-size: 30px;
  font-weight: bold;
  margin: 10px 0;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  
}

.trofeos .columna {
  padding: 20px;
  border: 2px solid #8080804d;
  display: flexbox;
  flex-direction: column;
  justify-content: space-evenly;
  transition: all 0.2s ease-in;
  border-color: gold;
}

.trofeos .columna:hover {
  color: white;
  background-color: #1b1b32;
}

.trofeos-imagen {
  height: 200px;
  font-size: 2.5rem;
  color: gold;
  padding: 8px 19px;
  border-radius: 50%;
}

.badges-contenedor{
  font-size: 15px;
  font-weight: bold;
  margin: 10px 0;
}

.badge{
  margin: 5px;
  background-color: gold !important;
}

 
/* FOOTER */

.footer-principal{
  min-height: 100px;
}

.footer-texto {
    font-size: 1.5rem;
    padding: 5px;
    margin-bottom: 10px;
    
}

.iconos-redes-sociales a{
    width: 35px;
    height: 35px;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 2px;
    margin: 10px;
    border: 2px solid white;
    border-radius: 50%;
    transition: all 0.2s ease-in;
}

.iconos-redes-sociales i {
    color: white;
    font-size: 1.5rem;
    transition: all 0.2s ease-in;
}

.iconos-redes-sociales a:hover {
    background-color: white;
    border: 2px solid rgb(13, 110, 253);
}

.iconos-redes-sociales a:hover i {
    color: black;
}


/* Media query para ajustar el tamaño del banner en pantallas más pequeñas */
@media (max-width: 768px) {
    .portada-imagen {
      width: 100%; /* Ajusta el ancho al 100% en pantallas más pequeñas */
      height: auto; /* Permite que la altura se ajuste proporcionalmente al ancho */
    }
  }


  /* Color de fondo*/

  body{
    background-color: rgb(224,224,224);
  }

  #principal{
    background-color:white;
    text-align: justify;
    width:75%;
    height:auto;
    margin: 0px auto;
    box-shadow: -10px 10px 15px #888888,
                 10px 10px 15px #888888;

  }

 .content{
    padding: 30px;

    /*diseño del texto */ 
    
 }

 #titulo{
    color: goldenrod;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight: lighter;
 }

 .parrafo{
    text-align: center;
 }

 .content{
    border-top-style: solid;
    border-width: 2px ;
    border-color: silver;
 }

 .creador{
    text-align: center;
    
 }


 @media (max-width: 768px) {
    .creador {
      width: 100%; /* Ajusta el ancho al 100% en pantallas más pequeñas */
      height: auto; /* Permite que la altura se ajuste proporcionalmente al ancho */
    }
  }
