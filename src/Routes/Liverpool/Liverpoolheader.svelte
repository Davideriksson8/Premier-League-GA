<script>
    
    import { Router, Link, Route } from "svelte-routing";

    //import {PLKlubbar} from 'firebase/firestore'
    
</script>



<header class="liverpool">

    
    <ul class="meny Liverpool">
    <li class="start">
       
        <nav class="start">
            <Link class="start" to="/Liverpool">
                Start
            </Link>
        </nav>
        
        <nav>
            <Link to="/Liverpoolinfo">
                Klubben
            </Link>
        </nav>
        <nav class="livlogo">
            <img class="bild" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F1d12e6a6-a139-44eb-88f8-91959d6ab843.image.png?v=1600869512682" alt="Liverpool FC">
        </nav>
        <nav class="trupp">
            <Link to='/Liverpooltrupp'>
                Truppen
            </Link>
        </nav>
        <nav>        
        <a href="https://www.samdodds.com/sv-se">Butik</a>
        </nav>
    </li>
    </ul>

</header>



<style>

    ul li {
        display: flex;
        flex-direction: row;
        border-bottom: solid 1px black;
        justify-content: space-evenly;
        
    }

    ul li nav:nth-child(1){
        display: flex;
        align-items: center;
        margin: 5px;
    }

    ul li nav:nth-child(2){
        display: flex;
        align-items: center;
        margin: 5px;
    }

    img {
        height: 60px;
        align-self: center center;
        margin: 5px auto;
    }

    ul li nav:nth-child(4){
        display: flex;
        align-items: center;
        margin: 5px;
    }  
    
    ul li nav:nth-child(5){
        display: flex;
        align-items: center;
        margin: 5px;
    }

    



</style>