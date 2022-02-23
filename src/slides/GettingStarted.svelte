<script>
    import { onMount } from 'svelte';

    onMount(() => console.log('md'));
</script>

<style>
	p {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}
</style>


<section>
    <p>Peas</p>
    <h2>Getting started</h2>
    <ul>
        <li class="fragment fade-up">Configure your Presentation in <code>config.js</code></li>
        <li class="fragment fade-up">Create your Slides in <code>Presentation.svelte</code></li>
    </ul>
</section>
