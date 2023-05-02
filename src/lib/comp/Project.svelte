<script>
    export let img = '/img/favicon.svg';
    export let name = 'Placeholder';
    export let url = '#';
</script>

<style>
    .project {
        width: 300px;
        height: 150px;
        display: flex;
        flex-direction: column;
        box-shadow: var(--shadow-1);
        overflow: hidden;
        margin: 10px;
        padding: 10px;
    }

    h2 {
        display: flex;
        flex-direction: row;
        align-items: center;
        margin: 0;
    }

    h2 a {
        text-decoration: none;
        color: var(--dark-1);
    }

    img {
        height: 30px;
        width: 30px;

        margin: 5px;

        border-radius: 100%;
    }
</style>

<div class='project'>
    <h2>
        <img src={img} alt=''>
        <a href={url}>{name}</a>
    </h2>
    <slot />
</div>
