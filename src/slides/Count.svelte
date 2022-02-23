<script>
import Counter from 'svelte-counter';
export let counters = {

    'views' : 103624

}


</script>


<style>

@font-face {
  font-family: "Noto Sans";
  src: url("/fonts/Noto_Sans/NotoSans-Regular.ttf") format("ttf");
}

    .text {
        font-family: Noto Sans
    }
</style>



<section>

 	<Counter values={counters} duration="5000" random="false" minspeed="200" let:counterResult>
        <p class="text">{counterResult.views} animation views</p>
    </Counter> 
</section>
