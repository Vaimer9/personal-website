<script lang="ts">

import NavBar from '../components/navbar.svelte';

</script>

<NavBar/>

<main>
    <h1>Vaimer9's Homepage</h1>
    <div class="content">
        <div>A programmer and linux enthusiast</div>
    </div>
</main>

<style>

:global(body) {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.content {
    padding-left: 6em;
}

.content div {
    margin-bottom: 0.5em;
}

a:visited {
    color: white;
}

</style>
