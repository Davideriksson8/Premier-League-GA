<script>
	
import Link from 'svelte-routing/src/Link.svelte';

 
 let sidmeny = { listaIn: false };

 function toggle() {
  sidmeny.listaIn = !sidmeny.listaIn;
 }

 //function myfunction () {
  //  document.getElementById("mymeny").style.visibility = "visible";
 //}

 //function minfunction () {
   // document.getElementById("meny").style.visibility = "hidden";
 //}
</script>


  
<div class="plheader">
    
    <section class="plloga">
			
    <Link to="/">  <img class="pl" alt="PL" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fe77ec073-a557-4529-92fb-515aa59ead4f.image.png?v=1600869350663"></Link>
   
		
		
			<ul>
      
      
          <li>          <img alt="Arsenal" class=" logo" src="Arsenal.png"></li>

          <li>          <img alt="Villa" class=" logo" src="Villa.png"></li>
          
          <li>           <img alt="Brighton" class=" logo" src="Brighton.png"></li>
           
          <li>        <img alt="Burnley" class=" logo" src="Burnley.png"></li>
        
          <li>       <img alt="Chelsea" class=" logo" src="Chelsea.png"></li>
       
          <li>              <img alt="Palace" class=" logo" src="Palace.png"></li>
              
          <li>           <img alt="Everton" class=" logo" src="Everton.png"></li>
           
          <li>   <img alt="Fulham" class=" logo" src="Fulham.png"></li>
   
          <li>    <img alt="Leeds" class=" logo" src="Leeds.png"></li>

          <li>          <img alt="Leicester" class=" logo" src="Leic.png"></li>

          <li>          <Link to="/Liverpool"><img alt="Liverpool" class=" logo" src="Liverpool.png"></Link></li>

          <li>          <Link to="/Mancity"><img alt="ManCity" class=" logo" src="Mancity.png"></Link></li>
			
          <li>          <Link to="/Manutd"><img alt="ManUtd" class=" logo" src="Manutd.png"></Link></li>
			
          <li>          <img alt="Newcastle" class=" logo" src="New.png"></li>
			
          <li>          <img alt="SheffieldUtd" class=" logo" src="Sheffield.png"></li>
			
          <li>          <img alt="Southampton" class=" logo" src="South.png"></li>
			
          <li>          <img alt="Spurs" class=" logo" src="Spurs.png"></li>
			
          <li>          <img alt="Westbrom" class=" logo" src="Westbrom.png"></li>
			
          <li>          <img alt="Westham" class=" logo" src="Westham.png"></li>
			
          <li>          <img alt="Wolves" class=" logo" src="Wolves.png"></li>

      

 </ul>

  </section>

  <section class="Menysök">

    <Link to="/"><img class="PLLOGGA" src="Premier-League-symbol-2.png" alt="PL Loga"></Link>

    
  {#if sidmeny.listaIn}
    <nav class="mymeny">
      <div class="nerkryssning" on:click={toggle}>x</div>
      <div class="menytext">
     <!-- <li class="punkt1 p">
        Rekord
      </li>-->
      <li class="punkt2 p">
        <Link to="/Jamfor">
          <p>Jämför</p>
        </Link>
      <!--</li>
      <li class="punkt3 p">
        Statistik
      </li>
      <li class="punkt4 p">
        Managers
      </li>-->
      <li class="punkt5 p">
        <Link to="/Lag">
        <p>Lag</p>
        </Link>
      </li>
      </div>
    </nav>
  {/if}
  
  
  
  {#if !sidmeny.listaIn}
  <img alt="menyknapp" src="menyn.jpg" id="meny" class="fas fa-bars" on:click={toggle}>

  {/if}

 <!--<script>-->
   

 <!--</script>-->
    
    
  <input class="sökruta" type="text" placeholder="Sök...">
  </section>
</div>

  <style> 

       *{
              margin: 0;
              padding: 0;
              box-sizing: border-box;
              list-style: none;
              
       }

           section.plloga {
		display: grid;
		grid-template-columns: 50px, auto; 
    margin: 25px 0;
    background-color: white;  
    line-height: 45px;
  
  }
		
		img.pl {
			grid-column-start: 1;
      height: 50px;
      width: 100px;
		}

		
  ul {
		grid-column-start: 2; 
    display: flex;
    justify-content: space-evenly; 
    /*display: grid; 
    grid-template-columns: (1fr * 20);*/
    
  
  
  }




  
  img.logo {
    height: 45px;
    width: 45px;
    cursor: pointer;
  }
  
 
  
 
 section.Menysök {
   display: flex;
   flex-direction: row;
   
 }

  
  
  .fas {
    margin: 10px 20px 0 20px;
    height: 80px;
    width: 80px;
    font-size: 40px;
    color: white;
    cursor: pointer;
    text-align: center;
  }

  p {
    color: white;
    
  }

  nav.mymeny {
    display: flex;
    flex-direction: row;
    background-color: #37003c;
    height: 100px;
    margin-right: 10px;
    border-right: 1px solid white
  }

  div.menytext {
    display: flex;
    flex-direction: row;
    align-items: center;
  }

  div.nerkryssning {
    cursor: pointer;
    font-size: 40px;
    height: 50px;
    width: 40px;
    margin-left: 10px;
    color: #fff;
  }

  
  
  li.p {
    margin: 10px;
    font-size: 25px;
    text-align: center;
    color: #fff;
  }

  p:hover {
    text-decoration: underline;
   text-decoration-color: #fff;
  }

    
  input.sökruta {
    position: center;
    font-size: 20px;
    border-radius: 25px; 
    background: white;
    outline: none;
    padding: 7px 10px;
    border-color: #37003c;
    height: 40px;
    margin-top: 30px;
  }
	
    @media screen and (min-width: 1020px) {
      img.PLLOGGA {
        display: none;
      }
    }

		@media only screen and (max-width: 1020px) {
			
      section.plloga {
        display: none;
      }
    }

    nav.mymeny {
      border-left: 1px solid white;
    }
      
    section.Menysök {
     background-color: #37003c;
      height: 100px;
              
    }

   img.PLLOGGA {
      background-color: white;
      height: 60px;
      width: 102px;
      margin-top: 20px;
      margin-right: 10px;
    }

    @media only screen and (max-width: 560px) {
      input.sökruta {
        display: none;
      }
    }

    </style>
  
