<script>
</script>

<template>
    <header>
        <div class="jumbotron text-center">
            <h1> My Ranking</h1>
            <p class="frase"> Projeto criado para praticar Vue JS</p> 
        </div>
        <nav class="navbar navbar-expand-sm navbar-dark text-center">
            
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse container" id="collapsibleNavbar">
                <a class="nav-name" href="HomeView.vue">MR</a>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="https://github.com/CaioCozendey"><i class="bi bi-github"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://www.linkedin.com/in/caio-dias-cozendey-502a1418a/"><i class="bi bi-linkedin"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="mailto:caiocozendey@hotmail.com"><i class="bi bi-whatsapp"></i></a>
                    </li>  
                </ul>   
            </div>  
        </nav>
    </header>
</template>

<style>
h1{
    margin-bottom: 2rem;
    color: #ffffff;
    font-size: 80px;
}

.frase{
    color: #ffffff;
}

.navbar-dark{
    background-color: #070707;
}


.jumbotron{
    background-color: #050505;
    margin: 0rem;
}


.bi{
    font-size: 1.5rem;
    margin-left: 1rem;
    color: #ffffff;
    transition: 0.5s;
}


.bi-github:hover{
    color: #c4c4c4;
}

.bi-linkedin:hover{
    color: #0964bf;
}

.bi-whatsapp:hover{
    color: #50bb5b;
}

.nav-name{
    color: #ffffff;
    font-size: 2rem;
    transition: 0.6s;
}

.nav-name:hover{
    color: #5dcbb3;
    text-decoration: none;
}

</style>