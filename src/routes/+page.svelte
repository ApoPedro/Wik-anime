<script>
    import Navbar from "../components/navbar/navbar.svelte";
    import ItemAnime from "../components/itemAnime/item-anime.svelte";
</script>
<Navbar/>
<div class="container">
    <h1>Recent anime</h1> 

    <div class="recent">
        <ItemAnime name={"Mashle"} img={"mashle"}/>
        <ItemAnime name={"Mashle"} img={"mashle"}/>
        <ItemAnime name={"Mashle"} img={"mashle"}/>
        <ItemAnime name={"Mashle"} img={"mashle"}/>
        <ItemAnime name={"Mashle"} img={"mashle"}/>
        <ItemAnime name={"Mashle"} img={"mashle"}/>
        <ItemAnime name={"Mashle"} img={"mashle"}/>
        <ItemAnime name={"Mashle"} img={"mashle"}/>
    </div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Anime+Ace&display=swap');
    .recent {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        padding: 3rem;
    }

</style>