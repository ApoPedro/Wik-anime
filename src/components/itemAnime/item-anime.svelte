<script>
    export let name;
    export let img;
</script>

<div class="item-anime">
    <div class="item-img">
        <img src="/src/assets/img/{img}.webp" alt="aled">
    </div>
    
    <div class="content">
        <p>{name}</p>
    </div>
</div>

<style>
    @import './itemAnime.css';
</style>