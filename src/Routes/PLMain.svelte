<script>
import Tabell from "./Tabellen.svelte"





</script>

<main class="Premier1">
    
    <aside class="tabell">
      
      <h1 class="tabell">
        Tabell: 
        <Tabell></Tabell>
      </h1>
    
    </aside>

      <h1 class="pl premierleaguerubrik">
        Premier League
      </h1>

    <section class="informationpl">
    


      <div class="iframe">

        <div class="imgsbl"></div>
        <a class="sblogo" href="https://www.aftonbladet.se/tagg/premier-league"><img class="sblogo" src="https://gfx.aftonbladet-cdn.se/hyper-assets/1de50b9ac3ce6d421c32572b3d250e99.jpg" alt="Sport Bladet logo"></a> 
        
        
        <div class="inf1">
          <img src="bildgasb2.jpg" alt="Bild" class="sbbild">
          <div class="sbinfo"> I dag släcker de sina sociala medier
          <a class="länksb" href="https://www.aftonbladet.se/sportbladet/fotboll/a/pA87bw/i-dag-slacker-de-sina-sociala-medier">Läs mer här.</a>
        </div></div>

        <div class="inf2">
          <img class="sbbild" src="BildGASB.jpg" alt="Bild">
        <div class="sbinfo"> Uppgifter: Ville ta över Arsenal redan innan Super League
        <a class="länksb" href="https://www.aftonbladet.se/sportbladet/fotboll/a/41kaWe/uppgifter-ville-ta-over-arsenal-innan-super-league-planerna">Läs mer här.</a>
        </div></div>

        <div class="inf3">
          <img class="sbbild" src="sportbladet1.jpg" alt="Bild">
         <div class="sbinfo">Panel: "Megastjärnan hade passat perfekt i Liverpools offensiv"
         <a class="länksb" href="https://www.aftonbladet.se/sportbladet/fotboll/a/dlEEoj/liverpool-panelen-salah-out--och-har-ar-dromvarvningarna">Läs mer här.</a> 
        </div></div>

      </div>

     <!--<iframe title="news" src="https://www.aftonbladet.se/tagg/premier-league0264613" frameborder="0"></iframe>--> 

    </section>
    
    <aside class="mästerskapslista">
      
    <h1 class="vinnarerubrik">
      Mästerskapslistan:
      </h1>
    <ul>
		<li>92/93: <em>Manchester United</em></li>
		<li>93/94: <em>Manchester United</em></li>
		<li>94/95: <em>Blackburn Rovers</em></li>
		<li>95/96: <em>Manchester United</em></li>
		<li>96/97: <em>Manchester United</em></li>
		<li>97/98: <em>Arsenal</em></li>
		<li>98/99: <em>Manchester United</em></li>
		<li>99/00: <em>Manchester United</em></li>
		<li>00/01: <em>Manchester United</em></li>
		<li>01/02: <em>Arsenal</em></li>
		<li>02/03: <em>Manchester United</em></li>
		<li>03/04: <em>Arsenal</em></li>
		<li>04/05: <em>Chelsea</em></li>
		<li>05/06: <em>Chelsea</em></li>
		<li>06/07: <em>Manchester United</em></li>
		<li>07/08: <em>Manchester United</em></li>
		<li>08/09: <em>Manchester United</em></li>
		<li>09/10: <em>Chelsea</em></li>
		<li>10/11: <em>Manchester United</em></li>
		<li>11/12: <em>Manchester City</em></li>
		<li>12/13: <em>Manchester United</em></li>
		<li>13/14: <em>Manchester City</em></li>
		<li>14/15: <em>Chelsea</em></li>
		<li>15/16: <em>Leicester City</em></li>
		<li>16/17: <em>Chelsea</em></li>
		<li>17/18: <em>Manchester City</em></li>
		<li>18/19: <em>Manchester City</em></li>
		<li>19/20: <em>Liverpool</em></li>
		

	</ul>
    </aside>
   
  </main>

  <style>

*{
    margin: 0;
              padding: 0;
              box-sizing: border-box;
              list-style: none;
              text-decoration: none;
       

}



      	  main.Premier1 {
    display:grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 20px; 
    grid-template-rows: 2.6em auto auto auto;
    /*grid-template-areas: "aside section aside";*/
    background-image: url(https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fe77ec073-a557-4529-92fb-515aa59ead4f.image.png?v=1600869350663);
    background: linear-gradient(120deg, #ff853e, #d43b3b);
    height: 100%;
    width: 100%;
  }

  aside.tabell {
    /*border-right: 1px solid black;*/
    justify-self: center; 
    grid-row-start: 2;
    grid-column-start: 1;
    grid-column-end: 2;
    height: 700px;
  }
  
  h1.tabell {
    margin-top: 80px; 
    height: 20px;
    font-family: 'Open Sans', sans-serif;
    font-size: 20px;
  }
  
  section.informationpl {
    grid-column-start: 2; 
    grid-column-end: 3;
    justify-self: center; 
    grid-row-start: 2;
  }
  
  .premierleaguerubrik {
    height: 45px;
    font-family: 'Open Sans', sans-serif;
    font-size: 60px;
    /*font-family: 'Roboto', sans-serif;*/
  }
  
  h1.pl {
    font-size: 2.5em;
    justify-self: center;
    grid-column-start: 1;
    grid-column-end: 4;
  }
  
  .iframe {
    display: grid;
    grid-template-rows: 1fr 1fr 1fr 1fr;
    grid-template-columns: 1fr;
    height: 400px;
    margin-top: 80px;
    background-color: #fde3e6;
  }

  .imgsbl {
    grid-row-start: 1;
    grid-row-end: 2;
    grid-column-start: 1;
    background-color: #a11014;
  }

  .sblogo {    
    width: 200px;
    height: 100px;
    grid-row-start: 1;
    grid-row-end: 2;
    grid-column-start: 1;
    justify-self: center;
  }

  a.sblogo {
    border-top: 3px solid #a11014;
  }

  img.sbbild {
    grid-column-start: 1;
    grid-column-end: 2;
    width: 150px;
    align-self: center;
    justify-self: center;
  }

  .inf1 {
    grid-row-start: 2;
    grid-row-end: 3;   
    display: grid;
    grid-template-columns: 1fr 1fr;
    border: 3px solid #a11014;
    height: 100px; 
  }

  .inf2 {
    grid-row-start: 3;
    grid-row-end: 4;
    display: grid;
    grid-template-columns: 1fr 1fr;
    border: 3px solid #a11014;
    height: 100px; 
  }

  .inf3 {    
    grid-row-start: 4;
    grid-row-end: 5; 
    display: grid;
    grid-template-columns: 1fr 1fr;
    border: 3px solid #a11014;
    height: 100px;   
  }

  div.sbinfo {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 2;
    font-size: 20px;
    align-self: center;
    justify-self: center;
  }

  a.länksb {
    font-size: 15px;
    justify-self: end;
  }


  
  aside.mästerskapslista {
    grid-column-start: 3;
    grid-column-end: 4; 
    /*border-left: 1px solid black;*/
    justify-self: center; 
    /*background-color: #3F1052;*/
    color: white;
    margin-bottom: 20px;
    grid-row-start: 2;
  }
  
  .vinnarerubrik {
    margin-top: 80px; 
    height: 20px;
    font-family: 'Open Sans', sans-serif;
    font-size: 20px;
    
  }

  ul {
    margin-top: 20px;
  }

  ul li {
    font-size: 20px;
  }


  
  @media screen and (max-width: 1020px) {
    aside.mästerskapslista {
      grid-row-start: 3;
      grid-column-start: 1;
      grid-column-end: 4;
      justify-self: center;
    }

    section.informationpl {
    grid-column-start: 2; 
    grid-column-end: 4;
    justify-self: center; 
    grid-row-start: 2;
  }
  

  }




  @media screen and (max-width: 650px) {
    aside.mästerskapslista {
      grid-row-start: 4;
      grid-column-start: 1;
      grid-column-end: 4;
      justify-self: center;
    }

    section.informationpl {
    grid-column-start: 1; 
    grid-column-end: 4;
    justify-self: center; 
    grid-row-start: 3;
  }
 

  
  
 
  }

  </style>