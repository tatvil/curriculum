<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="curriculum de Tatiana Villa Ema con HTML5, CSS3 y javascript">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Curriculum Vitae - Tatiana Villa</title>
</head>
<body>
    <header>
        <div id="nombre">
            <h1 class='text-center'>TATIANA VILLA <small>Curriculum Vitae</small></h1>
        </div>
    </header>
    <div id='contenedor' class="container"> 
    <div class="accordion accordion-flush" id="accordionFlushExample">
        <div class="accordion-item">
          <h2 class="accordion-header cabecera-item" id="flush-headingOne">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#datosPersonales" aria-expanded="false" aria-controls="flush-collapseOne"><i class="fa fa-user"></i>DATOS PERSONALES<i class="fa fa-arrows-v pull-right"></i>
            </button>
          </h2>
          <div id="datosPersonales" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
                <div class="row">
                    <div class="celda col-md-5">
                        <dt>Domicilio </dt>
                        <address>
                            Las Rozas de Madrid<br>
                            28290 - Madrid<br>
                        </address>
                    </div>
                    <div class="celda col-md-5">
                        <dl class="dl-horizontal">
                                <strong>e-mail: </strong><a href="mailto:tatiana@tecnologia-facil.es">tatiana@tecnologia-facil.es</a><br>
                                <strong>Teléfono: </strong>
                                <a href="tel:639145826">639145826</a><br> 
                        </dl>
                    </div>
                    <div class="celda foto col-md-2">
                        <img class='thumbnail rounded' src='img/tatiana-villa.jpg'width="100px" alt='foto de Tatiana Villa'>
                    </div>
                </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingTwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
              FORMACION
            </button>
          </h2>
          <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
            <div class="accordion-body">
                <div class="table-responsive">
                    <table class="table">
                    <thead>
                      <tr>
                          <td>Fecha</td>
                          <td>Estudios</td>
                          <td>Institución</td>
                      </tr>
                      </thead>
                      <tr>
                        <td>2021</td>
                        <td><a href="https://sede.sepe.gob.es/especialidadesformativas/RXBuscadorEFRED/DetalleEspecialidadFormativa.do?metodo=verDetalle&codEspecialidad=IFCD0210&volver=true&idBusquedaFormacion=&volverUrl=">Certificado de Profesionalidad: IFCD0210 Desarrollo de Aplicaciones con Tecnologías WEB</a></td>
                        <td>Grupo Colón</td>
                    </tr>
                    <tr>
                        <td>2021</td>
                        <td><a href="https://www.comunidad.madrid/info/servicios/empleo/cursos/20-2387">Diseño WEB para comercio electrónico</a></td>
                        <td>Grupo Aspasia</td>
                    </tr>
                    <tr>
                        <td>2020-2021</td>
                        <td>Experto en Robótica y diseño 3D</td>
                        <td>UNIR</td>
                    </tr>
                    <tr>
                        <td>2013-2016</td>
                        <td>Fotografia digital y Adobe Photoshop</td>
                        <td>Ayuntamiento de Las Rozas</td>
                    </tr>
                    <tr>
                        <td>1995</td>
                        <td>Fundamentos y Administración de Sistemas Operativos UNIX (HP-UX)</td>
                        <td>Hewlett Packard</td>
                    </tr>
                    <tr>
                          <td>1990-1994</td>
                          <td>Informática</td>
                          <td>Escuela de Sistemas Informáticos</td>
                      </tr>  
                      <tr>
                        <td>1989-1990</td>
                        <td>Bachillerato</td>
                        <td><a href="https://richland.rsd.edu/">Richland High School</a> (Estados Unidos)</td>
                    </tr>                 
                    </table>
                  </div>
            </div>
          </div>
        </div>
        <div class="accordion-item">
          <h2 class="accordion-header" id="flush-headingThree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
              EXPERIENCIA PROFESIONAL
            </button>
          </h2>
          <div>
            <div class="accordion-body">
                <div class="table-responsive">
                    <table class="table">
                    <thead>
                      <tr>
                          <td>Fecha</td>
                          <td>Cargo</td>
                          <td>Empresa</td>
                          <td>Observaciones</td>
                      </tr>
                      </thead>
                      <tr>
                        <td>2016-2021</td>
                        <td>Diseño y desarrollo de páginas WEB</td>
                        <td>Freelance</td>
                        <td>
                            Clientes: 
                                <ul>
                                    <li><a href="http://www.ampaieselburgo.com">AMPA IES El Burgo</a></li>
                                    <li><a href="http://www.tecnologia-facil.es">Tecnología Fácil</a></li>
                                </ul>
                        </td>
                      </tr>

                      <tr>
                        <td>2003-2007</td>
                        <td>Administracion HPUX</td>
                        <td>Freelance</td>
                        <td>
                            Clientes administrados: 
                                <ul>
                                    <li>Realia</li>
                                    <li>Telefónica de España</li>
                                </ul>
                        </td>
                      </tr>
                      <tr>
                        <td>1999-2001</td>
                        <td>Formadora de Administracion de HPUX</td>
                        <td>Hewlett Packard</td>
                        <td></td>
                      </tr>
                      <tr>
                        <td>1995-1999</td>
                        <td>Administracion de HPUX (Unix propietario de HP)</td>
                        <td>Hewlett Packard</td>
                        <td>
                            Clientes administrados: 
                                <ul>
                                    <li>Caja Duero</li>
                                    <li>Telefónica I+D</li>
                                    <li>Telefónica de España</li>
                                </ul>
                        </td>
                      </tr>
                    <tr>
                        <td>1993-1995</td>
                        <td>Programadora (Power Builder y Oracle Forms)</td>
                        <td>Next Computers</td>
                        <td>
                            Clientes:
                            <ul>
                                <li>Air Liquide</li>
                                <li>Red de Hospitales de San Juan de Dios (Sevilla)</li>
                                <li>MUSAAT (Mutua de Seguros de Aparejadores y Arquitectos Técnicos)</li>
                            </ul>

                        </td>
                    </tr>               
                    </table>
                  </div>
            </div>
          </div>
        </div>
            <div class="accordion-item">
                <h2 class="accordion-header cabecera-item" id="flush-headingRedesSociales">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#redesSociales" aria-expanded="false" aria-controls="flush-collapseResesSociales"><i class="fa fa-user"></i>REDES SOCIALES<i class="fa fa-arrows-v pull-right"></i>
                    </button>
                </h2>
                <div id="redesSociales" class="accordion-collapse collapse" aria-labelledby="flush-headingRedesSociales" data-bs-parent="#accordionFlushRedesSociales">
                    <div class="accordion-body">
                        <div class="container">
                            <div class="row row-cols-auto">
                              <div class="col"> <a href="https://www.facebook.com/tatiana.villaema"><img src="img/facebook redondo.png" alt="Facebook" width="30" height="30"></a></div>
                              <div class="col"><a href="https://www.instagram.com/tatvil/"><img src="img/instagram color.png" alt="Instagram" width="30" height="30"></a></div>
                              <div class="col"><a href="https://twitter.com/tatvil"><img src="img/twitter azul.png" alt="Twitter" width="30" height="30"></a></div>
                              <div class="col"><a href="https://github.com/tatvil"><img src="img/github.png" alt="Github" width="30" height="30"></a></div>
                            </div>
                          </div>

                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</body>
</html>
