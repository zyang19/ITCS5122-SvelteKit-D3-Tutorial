<script>

    /**
        * Assignment name: Inclass Svelte + D3
        * First name: 
        * Last name:
        * Student ID:
    */

    import { tooltip } from "$lib/state/state.svelte";
    
</script>

<div id="tooltip">

</div>

<style>
    #tooltip {
        position: absolute;
        display: none;
        background: #fff;
        box-shadow: 3px 3px 3px 0px rgb(92 92 92 / 0.5);
        border: 1px solid #ddd;
        font-size: 12px;
        font-weight: 500;
        padding: 8px;
        min-width: 160px;
        color: #333;
    }
    .tooltip-title {
        color: #000;
        font-size: 14px;
        font-weight: 600;
    }
    #tooltip ul {
        margin: 5px 0 0 0;
        padding-left: 20px;
    }
</style>