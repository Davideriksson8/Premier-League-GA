<script>

    import { Router, Link, Route } from "svelte-routing";
    import Mancityheader from "./Mancityheader.svelte";
    
    </script>
    
    
      
    
        <header class="Mancity">
    
            <Mancityheader/>
    
        </header>
    
        <main>
    
            <section class="sek1"> 
                <h1 class="rubrik">Manchester City</h1>
    
                <div class="text">
                <p>Manchester City Football Club är en engelsk professionell fotbollsklubb i Manchester, England som spelar i Premier League. Klubben grundades 1880 som St. Mark's (West Gorton). 1884 bytte klubben namn till Gorton AFC, 1887 till Ardwick AFC och 1894 fick klubben sitt nuvarande namn. Sedan 2003 spelar Manchester City sina hemmamatcher på City of Manchester Stadium (Etihad Stadium). 1897 till 1923 spelade man på Hyde Road och 1923 till 2003 var Maine Road klubbens hemmaarena.</p>
                <p> Manchester City har blivit engelska ligamästare sex gånger, FA-cupmästare sex gånger och ligacupmästare sju gånger. Man har även vunnit Community Shield sex gånger och cupvinnarcupen en gång.</p>
                <p></p>
                </div> 
    
            </section>
           
        <section class="sek2">
            <img src="https://www.thenationalnews.com/image/policy:1.906316:1567597962/sp05-Man-City-Trophy-Tour.jpg?f=16x9&w=1200&$p$f$w=56de256" alt="Mancity Champions Wall">
    
            <div>
                6 Ligasegrar: </div> <div>1936/37, 1967/68, 2011/12, 2013/14, 2017/18, 2018/19</div> 
    
            <div>
                6 FA-cuper: </div> <div>1903/04, 1933/34, 1955/56, 1968/69, 2010/11, 2018/19</div>
    
            <div>
                7 Ligacuper: </div> <div>1969/70, 1975/76, 2013/14, 2015/16, 2017/18, 2018/19, 2019/20</div>
    
            <div>
                1 UEFA Cupen: </div> <div>1969/70</div>
    
            <div>
                6 Charity/Community Shields: </div> <div>1937/38, 1968/69, 1972/73, 2012/13, 2018/19, 2019/20</div>
    
         
    
            <div>
                3 FA Youth Cup: </div> <div>1985/86, 2007/08, 2019/20</div>
    
            <div>
                1 Women's Super League: </div> <div>2016</div>

            <div>3 FA Women's Cup: </div> <div>2017, 2018/19, 2019/20</div>
            
            <div> 3 Continental Cup: </div> <div>2014, 2016, 2018/19</div>

                <div></div>
        </section>
    
    </main>
    
    <style>
    
    main {    
        background-color: #98C5E9;
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
        color: black;
        grid-row-start: 1;
        grid-row-end: 2;
        align-self: center;
        justify-self: center;
        grid-column-start: 2;
    }
    
    div.text {
        color: black;
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
        color: black;
        border-left: 1px solid black;
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
        border-bottom: solid 1px black;
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

    section div:nth-child(18) {
        grid-column-start: 2;
        grid-column-end: 3;
        grid-row-start: 10;
        border-bottom: none;
    }
    
    section div:nth-child(19) {
        grid-column-start: 3;
        grid-column-end: 6;
        grid-row-start: 10;
        border-bottom: none;
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