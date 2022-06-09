<script lang="ts">

import NavBar from '../components/navbar.svelte';

</script>

<NavBar/>

<main>
    <h1>Contacts</h1>
    <p> ~ </p>
    <div class="links">
        <a href="https://github.com/Vaimer9">Github</a><br>
    </div>
    <p class="links">
        <a href="https://twitter.com/vaimer9">Twitter</a>
    </p>
</main>

<style>

main {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    padding: 2em;
}

.links {
    margin: 10px;
    text-align: center;
}

h1 {
    font-size: 3rem;
}

a:visited, a {
    font-size: 2rem;
    color: white;
    text-decoration: none;
}
</style>
