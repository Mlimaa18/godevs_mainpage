<template>
    <div class="container">
        <!-- Row ¿Que hacemos? -->
        <div class="row">
            <div class="col-12">
                <h1 class="text-center mt-3">¿Qu&eacute; hacemos?</h1>
                <hr>
            </div>
            <div class="row">
                <div class="col-12 col-md-4">
                    <h3 class="text-center">Paginas Web</h3>
                    <img src="~/assets/web-pages-logo.png" alt="páginas web" class="img-thumbnail">
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione voluptas sint tempore dolore soluta ea doloribus quia quae. Voluptate iste esse molestiae temporibus nam accusamus ducimus quidem incidunt explicabo iure! Lorem ipsum,
                        dolor sit amet consectetur adipisicing elit. Eaque eum nobis ea assumenda repellat dolorum pariatur ipsum animi expedita optio. Corporis necessitatibus et reiciendis rerum vitae nisi possimus. Voluptates, animi.</p>
                </div>
                <div class="col-12 col-md-4">
                    <h3 class="text-center">E-Commerce</h3>
                    <img src="~/assets/ecommerce-logo.png" alt="E-Commerce" class="img-thumbnail">
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione voluptas sint tempore dolore soluta ea doloribus quia quae. Voluptate iste esse molestiae temporibus nam accusamus ducimus quidem incidunt explicabo iure! Lorem ipsum,
                        dolor sit amet consectetur adipisicing elit. Eaque eum nobis ea assumenda repellat dolorum pariatur ipsum animi expedita optio. Corporis necessitatibus et reiciendis rerum vitae nisi possimus. Voluptates, animi.</p>
                </div>
                <div class="col-12 col-md-4">
                    <h3 class="text-center">Aplicaciones iOS y Android</h3>
                    <img src="~/assets/android-ios-logo.png" alt="Aplicaciones móviles" class="img-thumbnail">
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ratione voluptas sint tempore dolore soluta ea doloribus quia quae. Voluptate iste esse molestiae temporibus nam accusamus ducimus quidem incidunt explicabo iure! Lorem ipsum,
                        dolor sit amet consectetur adipisicing elit. Eaque eum nobis ea assumenda repellat dolorum pariatur ipsum animi expedita optio. Corporis necessitatibus et reiciendis rerum vitae nisi possimus. Voluptates, animi.</p>
                </div>
            </div>
        </div>
        <!-- Row Tecnologías -->
        <div class="row">
            <div class="col-12">
                <h1 class="text-center mt-3">Tecnologías</h1>
                <hr>
            </div>
            <div class="row">
                <div class="col-12 col-md-6">
                    <h1 class="subtitle">Tecnologías</h1>
                    <hr>
                    <p>
                        Realizamos proyectos inovadores y de calidad utilizando las tecnologías principales para
                        desarrollo de páginas web y aplicaciones a la medida de tus necesidades.
                    </p>
                </div>
                <div class="col-12 col-md-6">
                    <!--
                    <img src="~/assets/nodejs-logo.png" alt="NodeJS" class="img-thumbnail">
                    <img src="~/assets/vuejs-logo.png" alt="Vue" class="img-thumbnail">
                    <img src="~/assets/html5-logo.png" alt="HTML5" class="img-thumbnail">
                    <img src="~/assets/css-logo.png" alt="CSS" class="img-thumbnail">
                    <img src="~/assets/javascript-logo.png" alt="Javascript" class="img-thumbnail">
                    <img src="~/assets/laravel-logo.png" alt="Laravel" class="img-thumbnail">
                    <img src="~/assets/php-logo.svg" alt="PHP" class="img-thumbnail">
                    -->
                    <b-carousel
                        id="carousel-fade"
                        style="text-shadow: 0px 0px 2px #000"
                        v-model="slide"
                        :interval="2000"
                        fade
                    >
                        <b-carousel-slide img-src="~/assets/nodejs-logo.png"></b-carousel-slide>
                        <b-carousel-slide img-src="~/assets/css-logo.png"></b-carousel-slide>
                        <b-carousel-slide img-src="~/assets/vuejs-logo.png"></b-carousel-slide>
                        <b-carousel-slide img-src="~/assets/html5-logo.png"></b-carousel-slide>
                        <b-carousel-slide img-src="~/assets/javascript-logo.png"></b-carousel-slide>
                        <b-carousel-slide img-src="~/assets/php-logo.png"></b-carousel-slide>
                        <b-carousel-slide img-src="~/assets/laravel-logo.png"></b-carousel-slide>
                    </b-carousel>
                </div>
            </div>
        </div>
        <!-- Row Futuro -->
        <div class="row">
            <div class="col-12 col-md-6">
                <h1 class="subtitle">Tecnologías a futuro</h1>
                <hr>
                <p>
                    Nos movemos al ritmo de la tecnología, de esta forma continuamos implementando nuevas
                    tecnologías para poder ofrecer un amplio catalogo al cliente.
                </p>
            </div>
            <div class="col-12 col-md-6">
                <b-carousel
                    id="carousel-fade"
                    style="text-shadow: 0px 0px 2px #000"
                    v-model="slide"
                    :interval="2000"
                    fade
                >
                    <b-carousel-slide img-src="~/assets/gatsby-logo.png"></b-carousel-slide>
                    <b-carousel-slide img-src="~/assets/flutter-logo.png"></b-carousel-slide>
                </b-carousel>
            </div>
            <!--
            <div class="row">
                <div class="col-12 col-md-2"></div>
                <div class="col-12 col-md-2">
                    <img src="~/assets/gatsby-logo.jpeg" alt="Gatsby" class="img-thumbnail">
                </div>
                <div class="col-12 col-md-1"></div>
                <div class="col-12 col-md-2">
                    <img src="~/assets/flutter-logo.png" alt="Flutter" class="img-thumbnail">
                </div>
                <div class="col-12 col-md-1"></div>
                <div class="col-12 col-md-2">
                </div>
                <div class="col-12 col-md-2"></div>
            </div>
            -->
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    html div {
        color: white;
        background-color: #355e93;
    }
    .subtitle {
        padding: 0.5em 2em;
    }
    .carousel {
        max-width: 400px;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        -webkit-transform: translate(-50%, -50%);
    }
    .carousel .img-fluid {
        padding: 2em;
    }
    .img-thumbnail {
        border: none;
        padding: 2em;
    }
</style>
