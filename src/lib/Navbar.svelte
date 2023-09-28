
<div class="navbar">
    <div class=""><a href="/"><img src="/images/navbar_logo.png" class="logo" alt="SO@VT Logo"><a/></div>
    <div class="buttons">
        <a href="/about" class="button">About Us</a>
        <a href="google.com" class="button">Contact</a>
        <a href="google.com" class="button">Hello</a>
        <a href="/tournament-info" class="button">Tournament Info</a>
    </div>

</div>


<style>
    .navbar {
        position: absolute;
        width: 100vw;
        top: 0;
        right: 0;
        display:flex;
        align-items: center;

        justify-content: space-between;
        
        background-color: rgba(0,0,0,.8);
        z-index: 10;

        margin: auto;

        /* padding: 2rem; */

    }

    .button {
        color: white;
        opacity: .8;
        height: 100%;
        width: 10rem;
        line-height: 45px;
        text-align: center;
        font-size: 1rem;
        font-family: 'Montserrat', sans-serif;
        padding: 1rem;

        transition: 0.3s;
    }

    .button:hover {
        color: orange;

    }

    a {
        text-decoration: none;
        display: block;
        margin:auto;
    }

    .logo {
        width: 5rem;
        padding: 1rem;
    }

    .buttons {
        display: flex;
        align-items: center;
    }

</style>

