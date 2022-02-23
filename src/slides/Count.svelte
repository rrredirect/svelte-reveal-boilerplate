<script>
import Counter from 'svelte-counter';
export let counters = {

    'views' : 103624

}


</script>


<style>
	p {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}
</style>



<section>

<p>Styled!</p>

   /* <Counter values={counters} duration="5000" random="false" minspeed="200" let:counterResult>
        <h1>{counterResult.views} animation views</h1>
    </Counter> */
</section>
