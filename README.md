# Desarrollo-de-un-Prototipo-de-interfaz-de-un-sitio-web-de-portafolio
<! DOCTYPE html >
< html >
    < cabeza >
        < meta  charset = " UTF-8 " >
        < meta  name = " viewport " content = " width = device-width, initial-scale = 1.0 " >
        < meta  http-equiv = " X-UA-Compatible " content = " ie = edge " >
        < título > Portafolio Web de Pagina </ título >
        < link  rel = " stylesheet " href = " assets / Styles / styles.css " >
    <! - FUENTES DE GOOGLE ->
    < link  href = " https://fonts.googleapis.com/css?family=Quicksand " rel = " hoja de estilo " >
    <! - FUENTE IMPRESIONANTE ->
    < Enlace  rel = " hoja de estilo " href =" https://use.fontawesome.com/releases/v5.8.1/css/all.css " integridad =" sha384-50oBUHEmvpQ + 1lW4y57PTFmhCaXp0ML5d60M1M7uH2 + nqUivzIebhndOJK28anvf " crossorigin =" anónimo " >
    <! - CSS ANIMADO ->
    < link  rel = " stylesheet " href = " https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.0/animate.min.css " >
    </ cabeza >
    < cuerpo >
        < div  class = " contenedor1 " >
            < nav  id = " navegador " >
            < ul >
              < Li > < un  href = " #reperfil " > Acerca </ li >
              < Li > < un  href = " #studi " > Estudios </ una > </ li >
              < Li > < un  href = " #contac " > Contacto </ una > </ li >
            </ ul >
          </ nav >         
            < div  class = " lol " >
                  < svg  viewbox = " 0 0100 20 " >
                    < defs >
                      < linearGradient  id = " gradient " x1 = " 0 " x2 = " 0 " y1 = " 0 " y2 = " 1 " >
                        < stop  offset = " 5% " stop-color = " # FFFF00 " />
                        < stop  offset = " 95% " stop-color = " # F0FF00 " />
                      </ linearGradient >
                      < pattern  id = " wave " x = " 0 " y = " 0 " width = " 120 " height = " 20 " patternUnits = " userSpaceOnUse " >
                        < path  id = " wavePath " d = " M-40 9 Q-30 7-20 9 T0 9 T20 9 T40 9 T60 9 T80 9 T100 9 T120 9 V20 H-40z " mask = " url (#mask) " llenar = " url (#gradient) " > 
                          < animateTransform
                              atributoName = " transformar "
                              begin = " 0s "
                              dur = " 1,5 s "
                              type = " traducir "
                              from = " 0,0 "
                              to = " 40,0 "
                              repeatCount = " indefinido " />
                        </ ruta >
                      </ patrón >
                    </ defs >
                    < text  text-anchor = " middle " x = " 30 " y = " 10 " font-size = " 10 " fill = " url (#wave) "   fill-opacity = " 1 " > Bienvenido </ text >
                    < text  text-anchor = " middle " x = " 30 " y = " 10 " font-size = " 10 " fill = " url (#gradient) " fill-opacity = " 0.8 " > Bienvenido </ text >
                  </ svg >
                  
            </ div >
            < div  class = " titulo " >
                < h2 > Hola un gusto poder tenerte en nuestra pagina web </ h2 >     
            </ div >   

            < Div  clase = " Bot " >  < un  href =" #contac " clase =" botón de arco iris " alt =" Contacto " > </ a >  </ div >
        </ div >
        < div  class = " perfil " id = " reperfil " >
            < div  class = " foto " >
                < div  class = " avatar " style = " background-image: url (Perfiles / principal.jpg) " > </ div >
            </ div >
            < div  class = " texto " >
                < h1 > Somos Los Dragon-Black </ h1 >
            </ div >

            < div  class = " texto " >
                < h3 > Un grupo de estudiantes especiales en la creacion y desarrollo de paginas web y aplicaciones de tu dia a dia </ h3 >
            </ div >
            < div  class = " pos " >
            < div  class = " boton " >
                < Un  href = " #contac " ID =" CAS " clase =" boton " > Contacto </ una >
            </ div >
            </ div >
        </ div >
        < div  class = " Estudios " id = " studi " >
            < div  class = " izquierda " >
                < img  src = " assets / estudios-universidad.jpg " width = " 430 "   height = " 250 " >
            </ div >
            < div  class = textoizquierda >
                < div  class = " tituli " >
                    < h3 > Estudios Realizados </ h3 >
                </ div >
                < div  class = " tabla " >
                    < table  class = " estudes " border = " 1 " >
                        < tr >
                            < td > < fuerte > Primaria </ fuerte > </ td >
                            < td > < fuerte > Secundaria </ fuerte > </ td >
                            < td > < fuerte > Superior </ fuerte > </ td >
                
                        </ tr >
                        < tr >
                            < td > Escuela </ td >
                            < td > Informática </ td >
                            < td > Ingeniería en Software </ td >
                        </ tr >
                        < tr >
                            < td > Escuela Abdon Calderon </ td >
                            < td > Colegio Simón Bolívar </ td >
                            < td > Universidad Estatal de Milagro </ td >
                        </ tr >
                        < tr >
                            < td > Escuela </ td >
                            < td > Informática </ td >
                            < td > Ingeniería en Software </ td >
                        </ tr >
                        < tr >
                            < td > Escuela Hector Arregui </ td >
                            < td > Unidad educativa Alborada </ td >
                            < td > Universidad Estatal de Milagro </ td >
                            < td >             </ td >
                        </ tr >
                        < tr >
                            < td > Escuela </ td >
                            < td > Informática </ td >
                            < td > Ingeniería en Software </ td >
                        </ tr >
                        < tr >
                            < td > Escuela Simón Bolívar </ td >
                            < td > Colegio 17 de septiembre </ td >
                            < td > Universidad Estatal de Milagro </ td >
                        </ tr >
                    </ tabla >

                </ div >
            </ div >
        </ div >
        < div  class = " habilidades " >
            < div  class = " imagen2 " >
                < img  src = " assets / corto.jpg " width = " 430 "   height = " 250 " >
            </ div >
            < div  class = " textt " >
                < div  class = " tituli " >
                    < h3 > Habilidades y Especialidades </ h3 >
                </ div >
                < div  class = " sub " >
                    < h5 > Contamos con los conocimientos necesarios para la creación y diseño de una página web </ h5 >
                    < h5 > Conocimientos en la construccion de aplicativos para paginas web como moviles </ h5 >
                </ div >
            </ div >
        </ div >
        < div  class = " mitrabajo " >
            < div  class = " image1 " >
                < img  src = " assets / Art-245-Trabajo-en-casa-1.jpg " width = " 730 "   height = " 525 " >
            </ div >
            < div  class = " textto " >
                < div  class = " tituli " >
                    < h3 > Nuestro Trabajo </ h3 >
                </ div >
                < div  class = " sub " >
                    < p >
                    < h5 > Creacion y personalizacion de paginas web </ h5 >
                    < h5 > Creación de aplicativos en dispositivos móviles </ h5 >
                    < h5 > Desarrollo de aplicaciones en diferentes lenguajes </ h5 >
                    < h5 > ------------------------------ </ h5 >
                    < h5 > Analistas de problemas </ h5 >
                    </ p >
                </ div >
            </ div >
        </ div >
        < div  class = " comentarios " >
            < div  class = " contenedor-comentarios " >
           
                < div  class = " comentarios " >
                   
                    < div  class = " photo-perfil " >
                        < img  src = " Perfiles / portada.jpg " >
                    </ div >
                    < div  class = " info-comments " >
                        < div  class = " encabezado " >
                            < h4 > Orlando Perrazo </ h4 >
                            < h5 > 14 de diciembre de 2020 </ h5 >
                        </ div >
                        < p > Muy buena pagina, Excelente trabajo !!! </ p >
                        < div  class = " pie de página " >
                            < h5  class = " request " > Respondedor ..... </ h5 >
                            < label  class = " icon-heart " > </ label >
                            
                        </ div >
                    </ div >
                    
                </ div >
            </ div >
            < div  class = " contenedor-comentarios-solicitud " >
               
                < div  class = " solicitud de comentarios " >
                   
                    < div  class = " photo-perfil-request " >
                        < img  src = " Perfiles / IMG-20210126-WA0161.jpg " alt = "" >
                    </ div >
                    
                    < div  class = " info-comments-request " >
                        < div  class = " encabezado " >
                            < h4 > Djalmar Ronquillo </ h4 >
                            < h5 > 25 de diciembre de 2020 </ h5 >
                        </ div >
                        
                        < p > Formar parte de este gran grupo es fenomenal !!! </ p >
                        
                        < div  class = " pie de página " >
                           
                            < h5  class = " request " > Respondedor ..... </ h5 >
                            < label  class = " icon-heart " > </ label >
                            
                        </ div >
                    </ div >
                    
                </ div >
            </ div >
            < div  class = " contenedor-comentarios " >
               
                < div  class = " comentarios " >
                   
                    < div  class = " photo-perfil " >
                        < img  src = " Perfiles / 44648442_964212353752286_3921662594196176896_n.jpg " alt = "" >
                    </ div >
                    
                    < div  class = " info-comments " >
                       
                        < div  class = " encabezado " >
                            < h4 > Josua Vásquez </ h4 >
                            < h5 > 01 de enero de 2021 </ h5 >
                        </ div >
                        
                        < p > Buena informacion proporcionada en la pagina, Felicitaciones !!! </ p >
                        
                        < div  class = " pie de página " >
                           
                            < h5  class = " request " > Respondedor ..... </ h5 >
                            < label  class = " icon-heart " > </ label >
                            
                        </ div >
                    </ div >
                    
                </ div >
            </ div >
            
            < div  class = " contenedor-comentarios " >
               
                < div  class = " comentarios " >
                   
                    < div  class = " photo-perfil " >
                        < img  src = " Perfiles / portada.jpg " alt = "" >
                    </ div >
                    
                    < div  class = " info-comments " >
                       
                        < div  class = " encabezado " >
                            < h4 > Orlando Perrazo </ h4 >
                            < h5 > 01 de enero de 2021 </ h5 >
                        </ div >
                        
                        < p > Buen trabajo, esto es perfecto. </ p >
                        
                        < div  class = " pie de página " >
                           
                            < h5  class = " request " > Respondedor ..... </ h5 >
                            < label  class = " icon-heart " > </ label >
                            
                        </ div >
                    </ div >
                    
                </ div >
            </ div >
        </ main >
        
            </ div >
        </ div >
        < div  class = " content " id = " contac " >

            < h1  class = " logo " > Contactanos </ span > </ h1 >
    
            < div  class = " bounceInUp animado de envoltorio de contacto " >
                < div  class = " formulario de contacto " >
                    < h3 > Formulario </ h3 >
                    < acción de formulario  = "" >
                        < p >
                            < etiqueta > Nombres </ etiqueta >
                            < input  type = " text " name = " fullname " >
                        </ p >
                        < p >
                            < etiqueta > Correo </ etiqueta >
                            < input  type = " email " name = " email " >
                        </ p >
                        < p >
                            < etiqueta > Numero Telefonico </ etiqueta >
                            < input  type = " tel " name = " phone " >
                        </ p >
                        < p >
                            < etiqueta > Asunto </ etiqueta >
                            < input  type = " text " name = " affair " >
                        </ p >
                        < p  class = " bloquear " >
                           < etiqueta > Mensaje: </ etiqueta > 
                            < textarea  name = " message " rows = " 3 " > </ textarea >
                        </ p >
                        < p  class = " bloquear " >
                            < botón >
                                Enviar
                            </ botón >
                        </ p >
                    </ formulario >
                </ div >
                < div  class = " contact-info " >
                    < h4 > Más detalles </ h4 >
                    < ul >
                        < li > < i  class = " fas fa-map-marker-alt " > </ i > Milagro </ li >
                        < li > < i  class = " fas fa-phone " > </ i > +593 967323661 </ li >
                        < li > < i  class = " fas fa-sobre-open-text " > </ i > Jvasquezc@unemi.edu.ec </ li >
                        < li > < i  class = " fas fa-sobre-open-text " > </ i > Dronquillob@unemi.edu.ec </ li >
                        < li > < i  class = " fas fa-sobre-open-text " > </ i > Operrazoc@unemi.edu.ec </ li >

                    </ ul >
                    < p > "Si puedes pensarlo, podemos crearlo ...." </ p >
                    < p > Todos los derechos reservados © 2020/2021 </ p >
                </ div >
            </ div >

        </ div >
        < script  src = " jquery.js " > </ script >
        < script  src = " script.js " > </ script >
    </ cuerpo >
</ html >
