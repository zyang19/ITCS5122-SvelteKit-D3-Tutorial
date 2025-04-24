<script>

    /**
        * Assignment name: Inclass Svelte + D3
        * First name: 
        * Last name:
        * Student ID:
    */

    import * as d3 from 'd3';

    import { config } from '$lib/state/state.svelte';

    const containerWidth = $derived(
        config.scatterplot.containerWidth
    );
    const containerHeight = $derived(
        config.scatterplot.containerHeight
    );
    const margin = $derived(
        config.scatterplot.margin
    );

    const width = $derived(
        containerWidth - margin.left - margin.right
    );
    const height = $derived(
        containerHeight - margin.top - margin.bottom
    );

</script>

<svg id="scatterplot">
    
</svg>