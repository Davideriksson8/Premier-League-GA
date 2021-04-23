<script>
    import Link from 'svelte-routing/src/Link.svelte';
</script>

<section>

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

    <div class="laget">    
        <Link to="/Liverpool"><img alt="Liverpool" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F1d12e6a6-a139-44eb-88f8-91959d6ab843.image.png?v=1600869512682"></Link>
    </div>

    <div class="laget">    
        <Link to="/Mancity"><img alt="ManCity" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F6c730e18-38f8-4999-adf4-2483cb8c4da0.image.png?v=1600869517276"></Link>
    </div>
    
    <div class="laget">    
        <Link to="/Manutd"><img alt="ManUtd" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fe1464486-118a-4605-81d8-73213f08a0fe.image.png?v=1600869523951"></Link>
    </div>
      
    <img alt="Newcastle" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F0369f104-0729-4b91-afb8-344eb1d2811a.image.png?v=1600869533618">
      
    <img alt="SheffieldUtd" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fde2fe11d-6be9-46f4-b792-c635f27e0208.image.png?v=1600869536329">
      
    <img alt="Southampton" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fc38ef005-b272-4ff3-b2d0-abb93f9c5140.image.png?v=1600869543657">
      
    <img alt="Spurs" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fea2a8f48-c246-4865-9263-9c094aee1634.image.png?v=1600869546423">
      
    <img alt="Westbrom" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F56e54a82-b155-4b97-82e3-ddc46d7e7739.image.png?v=1600869551609">
      
    <img alt="Westham" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2Fde2a81f5-7212-4bf4-a0a7-6a266b66d73b.image.png?v=1600869562614">
      
    <img alt="Wolves" class=" logo" src="https://cdn.glitch.com/7d5ea8d6-5674-46fb-b0f1-196915dca9a4%2F1bbd26f3-fb26-4e8e-b27c-aeafe8390691.image.png?v=1600869565070">


</section>

<style>

    section {
        background:  linear-gradient(120deg, #ff853e, #d43b3b);
        display: flex;
        flex-direction: column;
    }

    div.laget {
        height: 100px;
        width: 100px;
        margin: 10px 0;
        cursor: pointer;
    }

    img {
        height: 100px;
        width: 100px;
        margin: 10px;
        cursor: pointer;
    }

    img:nth-child(1) {
        margin-top: 15px;
    }

    img:nth-child(20) {
        margin-bottom: 20px;
    }
    
</style>