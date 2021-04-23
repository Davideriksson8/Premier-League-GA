<script>

    import { Router, Link, Route } from "svelte-routing";
    import Manutdheader from "./Manutdheader.svelte";
    
    </script>
    
    
      
    
        <header class="Manutd">
    
            <Manutdheader/>
    
        </header>
    
        <main>
    
            <section class="sek1"> 
                <h1 class="rubrik">Manchester United</h1>
    
                <div class="text">
                    <p>Manchester United Football Club är en fotbollsklubb från Stretford i Greater Manchester, England, som spelar i Premier League. Klubben ägs sedan maj 2005 av familjen Glazer.</p>
                    <p>Klubben grundades år 1878 under namnet Newton Heath LYR Football Club, men bytte 1902 namn till Manchester United och har spelat på Old Trafford sedan 1910. 1908 blev klubben engelska ligamästare för första gången och detta upprepades 1911. 1931 räddade James W. Gibson Manchester United från konkurs, då klubben under 1920- och 1930-talet var mindre framgångsrik och flyttades mellan den högsta och näst högsta divisionen. I flygolyckan i München 1958 dog åtta spelare i klubben, vid en tidpunkt då laget hade haft potential att göra Manchester United till ett av tidernas mästarlag i engelsk fotboll. 1968 var klubben, med Matt Busby som tränare, den första engelska klubben att vinna Europacupen och var under några år i slutet på 1960-talet också ett av Englands topplag. 1970- och 1980-talet präglades mestadels av degraderingar, tränarbyten och återavancemang – innan klubbens mest framgångsrike tränare, Alex Ferguson, tog över i november 1986 som skulle komma att vinna totalt 38 titlar under 26 säsonger med klubben (och Manchester United slutade som topp tre i Premier League samtliga år med Ferguson från grundandet av ligan, det vill säga 1992–2013). Efter Ferguson dröjde det tre år innan klubben lyckades bli någon form av mästare igen, och innan manager José Mourinho tillträdde 2016 hade klubben sparkat först David Moyes efter knappt en säsong och vidare Louis van Gaal efter sina två. Även Mourinho kom att sparkas i december 2018, och sedan dess leds laget av norrmannen Ole Gunnar Solskjær som tidigare haft en framgångsrik spelarkarriär i Manchester United.</p>
                    <p>Klubben har bland annat blivit engelsk mästare 20 gånger och vunnit Uefa Champions League tre gånger (1968, 1999 och 2008), och tävlar med rivalen Liverpool om att titulera sig Englands mest framgångsrika fotbollsklubb någonsin. Klubben rankas internationellt som ekonomiskt en av de mest värdefulla i fotbollsindustrin; 2019 rankade Forbes klubben som världens tredje rikaste till ett värde av drygt $3,8 miljarder. Klubben är även världens mest supporterstödda klubb, till supportrar sett också den mest världstäckande klubben, och hade totalt 659 miljoner fans 2011. Ryan Giggs, Bobby Charlton, Paul Scholes och Wayne Rooney hör till de spelare som spelat flest matcher och gjort flest mål för Manchester United.</p>
                </div> 
    
            </section>
           
        <section class="sek2">
            <img src="//assets.manutd.com/AssetPicker/images/0/0/10/73/674258/History-Trophy-Room51520075532648_xlarge.jpg" alt="Manutd Champions Wall">
    
            <div>
                20 Ligasegrar: </div> <div>1908, 1911, 1952, 1956, 1957, 1965, 1967, 1993, 1994, 1996, 1997, 1999, 2000, 2001, 2003, 2007, 2008, 2009, 2011, 2013</div> 
            
            <div>
                3 Europacuper: </div> <div>1968, 1999, 2008</div>
            
            <div>
                2 VM för Klubblag: </div> <div>1999, 2008</div>
    
            <div>
                12 FA-cuper: </div> <div>1909, 1948, 1963, 1977, 1983, 1985, 1990, 1994, 1996, 1999, 2004, 2016</div>
    
            <div>
                5 Ligacuper: </div> <div>1992, 2006, 2009, 2010, 2017</div>
    
            <div>
                2 UEFA Cupen: </div> <div>1991, 2017</div>
    
            <div>
                1 UEFA Supercuper: </div> <div>1991</div>
    
            <div>
                21 Charity/Community Shields: </div> <div>1908, 1911, 1952, 1956, 1957, 1965, 1967, 1977, 1983, 1990, 1993, 1994, 1996, 1997, 2003, 2007, 2008, 2010, 2011, 2013, 2016</div>
    
            <h2>Andra titlar:</h2>
    
            <div>
                10 FA Youth Cup: </div> <div>1953, 1954, 1955, 1956, 1957, 1964, 1992, 1995, 2003, 2011</div>
    
            <div></div> <div></div>
                <div></div>
        </section>
    
    </main>
    
    <style>
    
    main {    
        background-color: #DB1D24;
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
        color: white;
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
        color: white;
        border-left: 1px solid white;
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
        border-bottom: solid 1px white;
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
    }
    
    section div:nth-child(22) {
        grid-column-start: 3;
        grid-column-end: 6;
        grid-row-start: 13;
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