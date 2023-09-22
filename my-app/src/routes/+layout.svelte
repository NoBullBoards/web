<script>
    import Nav from "$lib/Nav.svelte"
    import {main_color} from "$lib/colors.ts"

    console.log(main_color)
</script>

<main style="background-color: {main_color};">
    <Nav />
    <slot />
</main> 
<style>
    main {
        display: flex;
    }
</style>