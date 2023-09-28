

<div class="box">
    <img src="images/IMG_4460.jpeg" style="width:100%;height:100%" alt="bio"/>
    <p class="bio">My name is Thomas</p>
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