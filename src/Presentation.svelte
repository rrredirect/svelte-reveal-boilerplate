<script>
    import Title          from './slides/Title.svelte';
    import Love           from './slides/Love.svelte';
    import GettingStarted from './slides/GettingStarted.svelte';
    import Count from './slides/Count.svelte';

    const partner = ['TFF', 'Animation'];
</script>

<Count/>
<Title/>
<Love {partner}/>
<GettingStarted/>

