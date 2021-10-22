# Batatabit
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link 
      href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Inter:wght@300;500&display=swap" rel="stylesheet"
    />
    <link rel="stylesheet" href="./mobile.css">
    <link rel="stylesheet" href="./ipad.css" media="screen and (min-width:600px)"/> 
    <link rel="stylesheet" href="./desktop.css" media="screen and (min-width:800px)"/> 
</head>
<body>

    <header>
        <img src="./Assets/img/Group 19 (1).svg" alt="">
        <div class="header--title-container">
            <h1>La proxima revolución en el cambio de cripto monedas</h1>
            <p>Batatabit te ayuda a navegar entre los diferentes precios y tendencias</p>
            <a href="#plans" class="header--button">Conoce nuestros planes <span></span>
            </a>
        </div>
    </header>

        <main class="container">

            <section class="main-exchange-container">

                <div class="backgroundImg"></div>

                <div class="main-exchange-container--title">
                    <h2>Visibilizamos todas las tazas de cambio</h2>
                    <p>Traemos información en tiempo real de las casas de cambio y las monedas más importantes del mundo</p>
                </div>

                <section class="main-tables-container">

                    <div class="comisiones">
                        <a href="http://127.0.0.1:5501/comisiones/index.html"><span class="next"></span></a>
                    </div>

                    <div class="main-currency-table">
                        <p class="currency-table--title">Monedas</p>
                      <div class="currency-table--container">
                        <table>
                            <tr>
                                <td class="table__top-left">Bitcon</td>
                                <td class="table__top table__rigth">$1.96 <span class="down"></span></td>
                            </tr>
                            <tr>
                                <td>Ethereum</td>
                                <td class="table__rigth">$0.07 <span class="over"></span</td>
                            </tr>
                            <tr>
                                <td>Ripple</td>
                                <td class="table__rigth">$2.15 <span class="down"></span</td>
                            </tr>
                            <tr>
                                <td class="table__bottom-left">Stellar</td>
                                <td class="table__bottom-rigth table__rigth">$4.96 <span class="down"></span</td>
                            </tr>
                        </table>
                      </div>

                      <div>
                        <div class="currency-table--date">
                            <p><b>Actualizado:</b> 02 de Octubre 14:50</p>
                        </div>

                     </div>

                  </div>
               </section>
            </section>

        <section class="main-product-detail">

                <span class="product-detail-batata-logo"></span>
                <div class="product-detail--title">
                    <h2>Creamos un producto sin comparación</h2>
                    <p>Confiable y diseñado para su uso diario</p>
                </div>

                <section class="product-cards-container">
                    <article class="product-detail--card">
                        <span class="clock"></span>
                        <p class="product--card-title">Tiempo Real</p>
                        <p class="product--card-body">Nuestro API toma información minuto a minuto sobre las tazas que más determinan el comportamiento.</p>
                    </article>
                    <article class="product-detail--card">
                        <span class="eye"></span>
                        <p class="product--card-title">No hay tazas escondidas</p>
                        <p class="product--card-body">Ni en la compra o al momento del exit, 
                            Batatabit siempre te muestra el costo real de lo que estás adquiriendo.
                        </p>
                    </article>
                    <article class="product-detail--card">
                        <span class="dollar"></span>
                        <p class="product--card-title">Compara monedas</p>
                        <p class="product--card-body">No más rumores, con Batatabit sabras el valor real de cada moneda en el mercado actual</p>
                    </article>
                    <article class="product-detail--card">
                        <span class="check-circle"></span>
                        <p class="product--card-title">Información confiable</p>
                        <p class="product--card-body">Nuestras fuentes están 100% verificadas y continuamos auditando su contenido mientras se actualizan.</p>
                    </article>
                </section>
            </section>

            <section class="bitcoin-img-container">
                <h2>Conocelo hoy.</h2>
            </section>

            <section id="plans" class="main-plans-container">
                <div class="plans--title">
                    <h2>Escoje el plan que mejor se ajuste a ti</h2>
                    <p>Cualquier plan te da acceso directo a nuestra plataforma</p>
                </div>
                <section class="plans-container--slider">
                    <article class="plans-container--card">
                        <p class="recomended">Recomendado</p>
                        <div class="plan-info-container">
                            <h3 class="plan-card--title">Pago Anual</h3>
                            <p class="plan-card--price"><span>$</span>99</p>
                            <p class="plan-card--saving">*Ahorras $129 comparado al plan mensual</p>
                            <button class="plan-card--ca">Escoger este <span></span></button>
                        </div>
                    </article>
                    <article class="plans-container--card">
                        <p class="recomended">Mes</p>
                        <div class="plan-info-container">
                            <h3 class="plan-card--title">Pago mensual</h3>
                            <p class="plan-card--price"><span>$</span>19</p>
                            <p class="plan-card--saving">*Gestiona tu pago automatico mensual</p>
                            <button class="plan-card--ca">Escoger este <span></span></button>
                        </div>
                    </article>
                    <article class="plans-container--card">
                        <p class="recomended">Diario</p>
                        <div class="plan-info-container">
                            <h3 class="plan-card--title">Pago x día</h3>
                            <p class="plan-card--price"><span>$</span>1.95</p>
                            <p class="plan-card--saving">*Pagas los días que quieras</p>
                            <button class="plan-card--ca">Escoger este <span></span></button>
                        </div>
                    </article>
                    <article class="plans-container--card">
                        <p class="recomended">Prime</p>
                        <div class="plan-info-container">
                            <h3 class="plan-card--title">Más beneficios</h3>
                            <p class="plan-card--price"><span>$</span>130</p>
                            <p class="plan-card--saving">*muchos beneficios adicionales</p>
                            <button class="plan-card--ca">Escoger este <span></span></button>
                        </div>
                    </article>
                    <article class="plans-container--card">
                        <p class="recomended">Prueba Gratis</p>
                        <div class="plan-info-container">
                            <h3 class="plan-card--title">30 días Gratis</h3>
                            <p class="plan-card--price"><span>$</span>0</p>
                            <p class="plan-card--saving">*Finalizado el periodo de prueba se cobra el pago anual de $99</p>
                            <button class="plan-card--ca">Escoger este <span></span></button>
                        </div>
                    </article>
                </section>
            </section>
        </main>

<footer>

    <section class="left">
        <ul>
            <li><a href="#">Linkedin</a></li>
            <li><a href="#">Crunchbase</a></li>
            <li><a href="#">Hackernews</a></li>
        </ul>
    </section>

    <section class="rigth">
        <img src="./Assets/img/logo-footer.svg" alt="Logo de Batatabit 2020">
    </section>

</footer>
</body>
</html>
