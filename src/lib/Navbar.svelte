
<script>

    let on = false;


</script>

<div class="navbar">
    <div class=""><a href="/" on:click={() => {on = false;}}><img src="/images/navbar_logo.png" class="logo" alt="SO@VT Logo"></a></div>
    <div class="buttons">
        <a href="/tournament-info" class="button">Tournament Info</a>
        <!-- <a href="/about" class="button">About Us</a> -->
        <a href="/about" class="button">About Us</a>
        <a href="/volunteer" class="button">Volunteer</a>
        <a href="/past-tournaments" class="button">Past Tournaments</a>
        <a href="/contact" class="button">Contact</a>
        
    </div>

    <a href="#" on:click={() => {on = !on}} id="hamburger"><img src="images/hamburger.png" class="hamburger" alt="Hamburger Menu"></a>

</div>

<div class="menu" style={on ? "display:block":"display:none"}>

    <div class="buttons2">
        <a href="/tournament-info" on:click={() => {on = false}} class="button">Tournament Info</a>
        <!-- <a href="/about" class="button">About Us</a> -->
        <a href="/about" on:click={() => {on = false}} class="button">About Us</a>
        <a href="/volunteer" on:click={() => {on = false}} class="button">Volunteer</a>
        <a href="/past-tournaments" on:click={() => {on = false}} class="button">Past Tournaments</a>
        <a href="/contact" on:click={() => {on = false}} class="button">Contact</a>
        
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

    .hamburger {
        width: 0rem;
        height: 3rem;
        display: none;
    }

    #hamburger {
        display: none;
    }

    .menu {
        position: absolute;
        top: 0;
        left: 0;
        width: 100vw;
        background-color: rgba(0,0,0,1);
        z-index: 1;
        text-align: center;

        height: 22rem;
    }

    .button:hover {
        color: orange;

    }

    .button {
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

    .buttons2 {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        position: absolute;
        margin-top: 5rem;
        left: 50%;
        transform: translate(-50%, 0);

    }

    @media (max-width: 1000px) {
        .buttons {
            display: none;
        }   

        .button {
            height: 1rem;
            width: 100vw;
            line-height: 1rem;
        }

        .hamburger {
            width: 3rem;
            margin-right: 2rem;
            display: block;
        }

        #hamburger {
            display: inline;
        }

        .menu {
            display: none;
        }
        
    }

</style>

