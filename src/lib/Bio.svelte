

<div class="box">
    <img src="http://placehold.it/257x200.jpg" alt="bio"/>
    <p class="bio">I am super cool.</p>
  </div>



<style>

    .bio {
        position: absolute;
    }

    * {
        margin: 0;
        padding: 0;
        border: 0;
    }

    /* relevant styles */
    .box {
        position: relative;
        height: 200px;
        width: 257px;
        border-radius: 1rem;
    }

    .bio {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background: rgba(0, 0, 0, 0.5);
        color: #fff;
        visibility: hidden;
        opacity: 0;

        /* transition effect. not necessary */
        transition: opacity .2s, visibility .2s;
    }

    .box:hover .bio {
    visibility: visible;
    opacity: 1;
    }


</style>