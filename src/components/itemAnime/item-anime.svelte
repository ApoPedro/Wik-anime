<script>
    export let name;
    export let img;
    // Récupération de l'élément img et mise à jour de l'attribut src
    import { onMount } from 'svelte';

    let imgElement;

    onMount(() => {
        imgElement.src = `/src/assets/img/${img}.webp`;
    });
</script>

<div class="item-anime">
    <!-- Utilisation d'une expression JavaScript pour mettre à jour l'attribut src -->
    <img bind:this={imgElement} alt="aled">
    <div class="content">
        <p>{name}</p>
    </div>
</div>



<style>
    @import './itemAnime.css';
</style>

