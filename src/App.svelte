<script>
	import { Router, Link, Route } from "svelte-routing";
	import PLHeader from './Routes/PLHeader.svelte'
	import Jamfor from './Routes/Jamfor.svelte'
	import PLMain from './Routes/PLMain.svelte'
	import Lag from './Routes/Lag.svelte'
	import PLFooter from './Routes/PLFooter.svelte'

	import Liverpool from './Routes/Liverpool/Liverpool.svelte'
	import Liverpoolinfo from './Routes/Liverpool/Liverpoolinfo.svelte'
	import Liverpooltrupp from './Routes/Liverpool/Liverpooltrupp.svelte'


	import Mancity from './Routes/ManCity/Mancity.svelte'
	import Mancityinfo from './Routes/ManCity/Mancityinfo.svelte'
	import Mancitytrupp from './Routes/ManCity/Mancitytrupp.svelte'
	
	import Manutd from './Routes/ManUtd/Manutd.svelte'
	import Manutdinfo from './Routes/ManUtd/Manutdinfo.svelte'
	import Manutdtrupp from './Routes/ManUtd/Manutdtrupp.svelte'
	


	import { FirebaseApp } from 'sveltefire'
	import firebase from 'firebase/app'
	import 'firebase/firestore'
	import 'firebase/auth' 

	// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
	apiKey: "AIzaSyCki97h1o7_oJ2uiioBBIM5tCbuSL7ObjY",
  	authDomain: "gymnasiearbete-99a71.firebaseapp.com",
  	databaseURL: "https://gymnasiearbete-99a71.firebaseio.com",
  	projectId: "gymnasiearbete-99a71",
  	storageBucket: "gymnasiearbete-99a71.appspot.com",
  	messagingSenderId: "130377051228",
  	appId: "1:130377051228:web:64019f7527ca9495fd4a99",
  	measurementId: "G-5K0QMRFLBF"
};

	firebase.initializeApp(firebaseConfig)

	async function useEmulator() {
		if (location.hostname === "localhost"){
			firebase.auth().useEmulator("http://localhost:9099")
			firebase.firestore().useEmulator("localhost", 8080)
		}
	}


</script>

<FirebaseApp firebase={firebase} on:initializeApp={useEmulator}>
	 <header class="PL">
    

              <Router> 
                    
							<PLHeader></PLHeader>

							
							
							<Route path="/Liverpool">
								<Liverpool />	

							

							

							</Route>
								<Route path='/Liverpoolinfo'>
									<Liverpoolinfo />
									
								
								</Route>

								<Route path='/Liverpooltrupp'>
									<Liverpooltrupp />
									
								
								</Route>

							
							<Route path='/Jamfor'>
								<Jamfor></Jamfor>
							</Route>

							<Route path='/Lag'>
								<Lag></Lag>
							</Route>
								
					 				
							

							<Route path="/Mancity">
								<Mancity />	

							

							</Route>
								<Route path='/Mancityinfo'>
									<Mancityinfo />
									
								
								</Route>

								<Route path='/Mancitytrupp'>
									<Mancitytrupp />
									
								
								</Route>





								<Route path="/Manutd">
									<Manutd />	
	
								
	
								</Route>
									<Route path='/Manutdinfo'>
										<Manutdinfo />
										
									
									</Route>
	
									<Route path='/Manutdtrupp'>
										<Manutdtrupp />
										
									
									</Route>
					 
              </Router>
    
  
    
    
  </header>
	
  
    
    
  <main class="Premier1">
    
	<Router>
		<Route path='/'>
			<PLMain></PLMain>
		</Route>
	</Router>
  
  </main>
    
    
    
    
  <footer class="Premierl">
	  <Router>
		<Route path='/'>
		  	<PLFooter></PLFooter>
		</Route>
	  </Router>
  </footer>

	
</FirebaseApp>





<style>


  
  
</style>