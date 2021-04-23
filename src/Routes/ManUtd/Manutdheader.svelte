<script>
    
    import { Router, Link, Route } from "svelte-routing";

    //import {PLKlubbar} from 'firebase/firestore'
    
</script>



<header class="Manutd">

    
    <ul class="meny Manutd">
    <li class="start">
       
        <nav class="start">
            <Link class="start" to="/Manutd">
                Start
            </Link>
        </nav>
        
        <nav>
            <Link to="/Manutdinfo">
                Klubben
            </Link>
        </nav>
        <nav class="livlogo">
            <img class="bild" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fe1464486-118a-4605-81d8-73213f08a0fe.image.png?v=1600869523951" alt="Manchester United">
        </nav>
        <nav class="trupp">
            <Link to='/Manutdtrupp'>
                Truppen
            </Link>
        </nav>
        <nav>        
        <a href="https://store.manutd.com/en/?_s=bm-FI-PSC-MUFC-ShopNav">Butik</a>
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