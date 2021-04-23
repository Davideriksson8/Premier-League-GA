<script>
    
    import { Router, Link, Route } from "svelte-routing";

    //import {PLKlubbar} from 'firebase/firestore'
    
</script>



<header class="mancity">

    
    <ul class="meny mancity">
    <li class="start">
       
        <nav class="start">
            <Link class="start" to="/Mancity">
                Start
            </Link>
        </nav>
        
        <nav>
            <Link to="/Mancityinfo">
                Klubben
            </Link>
        </nav>
        <nav class="manlogo">
            <img class="bild" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F6c730e18-38f8-4999-adf4-2483cb8c4da0.image.png?v=1600869517276" alt="Manchester City">
        </nav>
        <nav class="trupp">
            <Link to='/Mancitytrupp'>
                Truppen
            </Link>
        </nav>
        <nav>        
        <a href="https://shop.mancity.com/en/?_s=bm-FI-PSC-MCFC-ShopPageEng">Butik</a>
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