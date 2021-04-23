<script>

import { Router, Link, Route } from "svelte-routing";
import Liverpoolheader from "./Liverpoolheader.svelte";

</script>


  

    <header class="liverpool">

        <Liverpoolheader/>

    </header>

    <main>

        <section class="sek1"> 
            <h1 class="rubrik">Liverpool FC</h1>

            <div class="text">
            <p>Liverpool FC (The Reds) är en engelsk professionell fotbollsklubb i Liverpool som spelar i Premier League. Klubben grundades den 3 juni 1892 och har Anfield som sin hemmaarena.</p>
            <p>Klubben har stått som engelska mästare totalt 19 gånger, varav en Premier League-titel (2019/20), och har därtill vunnit sex Europacup-/Champions League-titlar (senast 2019) vilket är tre fler än rivalen Manchester United (som dock har 20 engelska mästartitlar, merparten i Premier League) i kampen om att titulera sig Englands mest framgångsrika klubb någonsin.</p>
            <p>Liverpool FC hade sin mest framgångsrika tid under 1970- och 1980-talet, och vann år 1984 den så kallade trippeln: engelska ligan, Europacupen för mästarlag (nuvarande Champions League) och Ligacupen.</p>
            </div> 

        </section>
       
    <section class="sek2">
        <img src="https://d3j2s6hdd6a7rg.cloudfront.net/v2/uploads/media/default/0002/09/thumb_108252_default_news_size_5.jpeg" alt="Liverpool Champions Wall">

        <div>
            19 Ligasegrar: </div> <div>1900-01, 1905-06, 1921-22, 1922-23, 1946-47, 1963-64, 1965-66, 1972-73, 1975-76, 1976-77, 1978-79, 1979-80, 1981-82, 1982-83, 1983-84, 1985-86, 1987-88, 1989-90, 2019-20</div> 
        
        <div>
            6 Europacuper: </div> <div>1976-77, 1977-78, 1980-81, 1983-84, 2004-05, 2018-19</div>
        
        <div>
            1 VM för Klubblag: </div> <div>2019</div>

        <div>
            7 FA-cuper: </div> <div>1964-65, 1973-74, 1985-86, 1988-89, 1991-92, 2000-01, 2005-06</div>

        <div>
            8 Ligacuper: </div> <div>1980-81, 1981-82, 1982-83, 1983-84, 1994-95, 2000-01, 2002-03, 2011-12</div>

        <div>
            3 UEFA Cupen: </div> <div>1972-73, 1975-76, 2000-01</div>

        <div>
            4 UEFA Supercuper: </div> <div>1977, 2001, 2005, 2019</div>

        <div>
            15 Charity/Community Shields: </div> <div>1964*, 1965*, 1966, 1974, 1976, 1977*, 1979, 1980, 1982, 1986*, 1988, 1989, 1990*, 2001, 2006 ( * Delad)</div>

        <h2>Andra titlar:</h2>

        <div>
            4 FA Youth Cup: </div> <div>1996, 2006, 2007, 2019</div>

        <div>
            2 Women's Super League: </div> <div>2013, 2014</div>
            <div></div>
    </section>

</main>

<style>

main {    
    background-color: #a91c30;
    height: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
}


section.sek1 {
    display: grid;
    grid-column-start: 1;
    grid-column-end: 2;
    grid-template-rows: 100px auto;
    justify-self: center;
}

h1.rubrik {
    color: silver;
    grid-row-start: 1;
    grid-row-end: 2;
    align-self: center;
    justify-self: center;
    grid-column-start: 2;

}

div.text {
    color: white;
    grid-row-start: 2;
    grid-row-end: 3;
    justify-self: center;
    grid-column-start: 2;
    grid-column-end: 3;
}

p {
    justify-self: center;
    margin-right: 20px;
    margin-left: 20px;
    margin-bottom: 10px;
}

section.sek2 {
    grid-column-start: 2;
    grid-column-end: 3;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
    grid-template-rows: auto auto auto auto;
    color: silver;
    border-left: 1px solid silver;
}

img:nth-child(1) {
    justify-content: center;
    grid-column-start: 1;
    grid-column-end: 8;
    width: 100%;
}

div {
    margin-top: 15px;
    margin-bottom: 15px;
    border-bottom: solid 1px silver;
    font-size: 20px;
}

section div:nth-child(2) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 2;
    
}

section div:nth-child(3) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 2;

}

section div:nth-child(4) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 3;
}

section div:nth-child(5) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 3;
}

section div:nth-child(6) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 4;
}

section div:nth-child(7) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 4;
}

section div:nth-child(8) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 5;
}

section div:nth-child(9) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 5;
}

section div:nth-child(10) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 6;
}

section div:nth-child(11) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 6;
}

section div:nth-child(12) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 7;
}

section div:nth-child(13) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 7;
}

section div:nth-child(14) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 8;
}

section div:nth-child(15) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 8;
}

section div:nth-child(16) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 9;
}

section div:nth-child(17) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 9;
}

section div:nth-child(23) {
    grid-column-start: 2;
    grid-column-end: 6;
    grid-row-start: 10;
    border-bottom: none;
}

section h2:nth-child(18) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 11;
    border-bottom: solid 1px white;  
}

section div:nth-child(19) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 12;
}

section div:nth-child(20) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 12;
}

section div:nth-child(21) {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 13;
    margin-bottom: 30px;
}

section div:nth-child(22) {
    grid-column-start: 3;
    grid-column-end: 6;
    grid-row-start: 13;
    margin-bottom: 30px;
}





@media screen and (max-width: 562px) {
    main {
        display: grid;
        grid-template-rows: auto auto;
    }

    section.sek1 {
        grid-row-start: 1;
        grid-row-end: 2;
        grid-column-start: 1;
        grid-column-end: 3;
    }

    section.sek2 {
        grid-row-start: 2;
        grid-row-end: 3;
        grid-column-start: 1;
        grid-column-end: 3;
    }
}




</style>