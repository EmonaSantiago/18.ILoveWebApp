<body>
<section id="header">
    <img class="logo" src="src/assets/logo.png" alt="logo" >
</section>
<section id="hero">
    <img class="hero-image" src="src/assets/hero.png" alt="hero" >
</section>
<section id="navigation">
<nav>
    <a href="/detail-page">detailpage</a> 
    <a href="/detail-page">detailpage</a> 
    <a href="/detail-page">detailpage</a> 
</nav>
</section>
</body>


<style>
* {
    margin: 0;
}
:root {
    --background-: #050542 ;
}
body {
    background-color: var(--background-);
}

#header {
    margin: 1em;
}

#hero {
    text-align: center;
}

/* #navigation {
    margin-top: 2em;
    margin-left: 1em;
    margin-right: 1em;
}
#navigation a {
   text-decoration: none;
   color: aqua;
   padding: 4px;
   border: solid 2px pink ;
   border-radius: 12em;
   margin-right: 2em;
} */

@media only screen and (max-width: 600px) {
.logo {
    width: auto;
    height: 2em;
}

.hero-image {
    width: auto;
    height: 16em;
}

}

</style>