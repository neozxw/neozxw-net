<style>
    .button {
        background: white;
        font-weight: bold;
        color: var(--black-1);
        
        display: flex;
        width: fit-content;
        padding: 10px;
        border-radius: 30px;
        margin: 5px;
    }

    .clickable {
        background: var(--link-1);
    }
</style>

<script>
    export let clickable = false;
</script>

<div class='button {clickable ? 'clickable' : ''}'>
    <slot />
</div>