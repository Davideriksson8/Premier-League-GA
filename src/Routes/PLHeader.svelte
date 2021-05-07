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
      
      
           <img alt="Arsenal" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F1f019f9e-d6af-4b50-9168-a094a5166130.image.png?v=1600869415819">

          <img alt="Villa" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F55b14ad6-200f-42a6-9b87-6cbf3f0a91e1.image.png?v=1600869447962">

           <img alt="Brighton" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F21562cab-b5d8-48d8-87cc-3af9b1a3d743.image.png?v=1600869456611">

        <img alt="Burnley" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F29aed67d-3b3f-4cd7-9543-14a190e9e45b.image.png?v=1600869463601">

       <img alt="Chelsea" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fd2bd68db-4fad-4a63-94c2-e0496ed69d9c.image.png?v=1600869468283">

              <img alt="Palace" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Ff1f7cdb9-1698-4c1a-984f-ffc0723a939f.image.png?v=1600869477375">

           <img alt="Everton" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fc0c6daa7-da53-4109-989e-2e5c1ff29e19.image.png?v=1600869489957">
			
   <img alt="Fulham" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Ff1b6750d-4585-49df-b739-1d9e55ba982e.image.png?v=1600869492960">

    <img alt="Leeds" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F736ae433-e566-4525-a6d0-8b469031e809.image.png?v=1600869503718">

          <img alt="Leicester" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fc3f8c15d-81cc-4a5d-9f00-f62f49f9fbf6.image.png?v=1600869507409">

      <Link to="/Liverpool"><img alt="Liverpool" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F1d12e6a6-a139-44eb-88f8-91959d6ab843.image.png?v=1600869512682"></Link>

      <Link to="/Mancity"><img alt="ManCity" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F6c730e18-38f8-4999-adf4-2483cb8c4da0.image.png?v=1600869517276"></Link>
			
    <Link to="/Manutd"><img alt="ManUtd" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fe1464486-118a-4605-81d8-73213f08a0fe.image.png?v=1600869523951"></Link>
			
    <img alt="Newcastle" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F0369f104-0729-4b91-afb8-344eb1d2811a.image.png?v=1600869533618">
			
     <img alt="SheffieldUtd" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fde2fe11d-6be9-46f4-b792-c635f27e0208.image.png?v=1600869536329">
			
      <img alt="Southampton" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fc38ef005-b272-4ff3-b2d0-abb93f9c5140.image.png?v=1600869543657">
			
   <img alt="Spurs" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fea2a8f48-c246-4865-9263-9c094aee1634.image.png?v=1600869546423">
			
   <img alt="Westbrom" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F56e54a82-b155-4b97-82e3-ddc46d7e7739.image.png?v=1600869551609">
			
   <img alt="Westham" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fde2a81f5-7212-4bf4-a0a7-6a266b66d73b.image.png?v=1600869562614">
			
   <img alt="Wolves" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F1bbd26f3-fb26-4e8e-b27c-aeafe8390691.image.png?v=1600869565070">

      

 </ul>

  </section>

  <section class="Menysök">

    <Link to="/"><img class="PLLOGGA" src="https://assets.turbologo.com/blog/en/2020/01/19084653/Premier-League-symbol.png" alt="PL Loga"></Link>

    
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
    cursor: pointer;
  }
  
  .pl {
    height: 50px;
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
    background-color: #3F1052;
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
    border-color: #3F1052;
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
     background-color: #3F1052;
      height: 100px;
              
    }

   img.PLLOGGA {
      background-color: white;
      height: 60px;
      margin-top: 20px;
      margin-right: 10px;
    }

    @media only screen and (max-width: 560px) {
      input.sökruta {
        display: none;
      }
    }

    </style>
  
