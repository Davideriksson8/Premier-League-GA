<script>
    import { Router, Link, Route } from "svelte-routing";
    import Tabellen from "../Tabellen.svelte";
    import Mancityheader from "./Mancityheader.svelte";
    
    
    
    
    </script>
    
    <header class="mancity">
    
        <Mancityheader/>
    
        <!--{link}-->
    
    </header>
    
    <main class="mancity">
        <section>Tabell:<Tabellen/></section>
    
        <section>
            <img src="est1894.png" alt="estsign">
    
            <img src="mancityrattlineup.png" alt="lineup">
        </section>
    
        <section>
            <div class="mal">
                <h2>Skytteligan:</h2>
                    <div>
                        <img src="https://resources.premierleague.com/premierleague/photos/players/250x250/p59859.png" alt="Spelare 1">
                        <h3>17 Mål</h3>
                    </div>
                    <div>
                        <img src="https://resources.premierleague.com/premierleague/photos/players/250x250/p209244.png" alt="Spelare 2">
                        <h3>16 Mål</h3>
                    </div>
                    <div>
                        <img src="https://resources.premierleague.com/premierleague/photos/players/250x250/p103955.png" alt="spelare 3">
                        <h3>14 Mål</h3>
                    </div>
            </div>
            <div class="assist">
                <h2>Assistligan:</h2>
                    <div class="A1">
                        <img class="A1" src="https://resources.premierleague.com/premierleague/photos/players/250x250/p61366.png" alt="Spelare 1">
                        <h3>18 Assist</h3>
                    </div>
                    <div class="A2">
                        <img class="A2" src="https://resources.premierleague.com/premierleague/photos/players/250x250/p209244.png" alt="Spelare 2">
                        <h3>10 Assist</h3>
                    </div>
                    <div class="A3">
                        <img class="A3" src="https://resources.premierleague.com/premierleague/photos/players/250x250/p103955.png" alt="spelare 3">
                        <h3>10 Assist</h3>
                    </div>
            </div>
        </section>
    </main>
    
    <footer class="mancity">
    
    </footer>
    
    <style>
    
    main {
        background-color: #98C5E9;
        height: 1000px;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-rows: 35px auto;
        gap: 10px;
    }
    
    section:nth-child(1) {
        grid-row-start: 2;
        height: 20px;
        font-family: 'Poppins', sans-serif;
        font-size: 20px;
        color: Black;
    }
    
    section:nth-child(2) {
        display: grid;
        grid-template-rows: 150px auto;
        grid-row-start: 2;
        grid-column-start: 2;
        color: white;
        font-size: 40px;
        
    }
    
    img:nth-child(1) {
        grid-row-start: 1;
        height: 100px;
        width: 395px;
    }
    
    
    
    
    img:nth-child(2) {
        height: 500px;    
        grid-row-start: 2;
        width: 395px;
    }
    
    section:nth-child(3) {
        display: grid;
        grid-template-rows: 1fr 1fr;
        grid-column-start: 3;
        grid-row-start: 2;
        font-family: 'Poppins', sans-serif;
        font-size: 20px;
        color: white;
        gap: 10px;
        margin-right: 10px;
    }
    
    section div:nth-child(1) {
        grid-row-start: 1;
        background-color: grey;
        border-radius: 25px;
        display: grid;
        grid-template-rows: 40px 1fr 1fr 1fr;
        gap: 10px;
        border: white 1px solid;
    }
    
    section div h2 {
        grid-column-start: 1;
        font-size: 25px;
        margin: 15px;
    }
    
    section div:nth-child(2) {
        grid-row-end: 3;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        border-top: white 1px solid;
        border-bottom: white 1px solid;
    
    }
    
    section div:nth-child(3) {
        grid-row-start: 3;
        grid-row-end: 4;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        border-top: white 1px solid;
        border-bottom: white 1px solid;
    }
    
    section div:nth-child(4) {
        grid-row-start: 4;
        grid-row-end: 5;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        border-top: white 1px solid;
    }
    
    section div img:nth-child(1) {
        grid-column-start: 1;
        grid-column-end: 2;
        width: 100px;
        background-color: #98C5E9;
        border-radius: 100px;
        align-self: center;
        justify-self: center;
        margin-left: 10px;
    }
    
    h3 {
        color: white;
        font-size: 30px;
        grid-column-start: 2;
        grid-column-end: 4;
        align-self: center;
        justify-self: center;
    }
    
    section div.assist {
        grid-row-start: 2;
        background-color: grey;
        border-radius: 25px;
        display: grid;
        grid-template-rows: 40px 1fr 1fr 1fr;
        grid-template-columns: 1fr;
        gap: 10px;
        border: white 1px solid;

    }
    
    div.A1 {
        grid-row-end: 3;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        border-top: white 1px solid;
        border-bottom: white 1px solid;
        width: 100%;
    }
    
    div.A2 {
        grid-row-start: 3;
        grid-row-end: 4;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        border-top: white 1px solid;
        border-bottom: white 1px solid;
    }
    
    div.A3 {
        grid-row-start: 4;
        grid-row-end: 5;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        border-top: white 1px solid;
    }
    



    

@media screen and (max-width: 970px) {

main {
    height: auto;
}

section:nth-child(3) {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 3;
    justify-self: center;
    margin-top: 20px;
}

section div.assist {
    grid-column-start: 2;
    grid-row-start: 1;
    grid-row-end: 2;
}




}

@media screen and (max-width: 750px) {
main {
    height: auto;
}

section:nth-child(2) {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 2;
    grid-row-end: 3;
    justify-self: center;

}

section:nth-child(1)  {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 3;
    grid-row-end: 4;
    justify-self: center;
    height: 600px;
}

section:nth-child(3) {
    grid-column-start: 1;
    grid-column-end: 4;
    grid-row-start: 4;
    justify-self: center;
}

section div.assist {
    grid-column-start: 1;
    grid-row-start: 2;
    grid-row-end: 3;
    margin-bottom: 30px;
}
}

    
     
    
    </style>