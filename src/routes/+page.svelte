<script>
    import Wrapper from '$lib/comp/Wrapper.svelte';
    import Button from '$lib/comp/Button.svelte';
    import Project from '$lib/comp/Project.svelte';
</script>

<style>
    .bold {
        font-weight: bold;
        color: var(--white-1);
        font-size: max(2vw,1.5rem);
        margin: 5px;
    }

    p {
        text-align: center;
    }

    a {
        text-decoration: none;
        color: var(--black-3);
    }

    .hwrap {
        display: flex;
    }

    .main {
        width: 100px;
    }
</style>

<Wrapper>
    <p class='bold'>neozxw</p>

    <img class='main' src='/neozxw.svg' alt='neozxw Logo'>

    <p>Web developer planning to enter the professional space</p>

    <div class='hwrap'>
        <Button>
            Arch Linux
        </Button>
        <Button>
            SvelteKit
        </Button>
    </div>

    <div class='hwrap'>
        <Button>
            <a href='https://github.com/neozxw'>Github</a>
        </Button>
    </div>
</Wrapper>

<h2>Contributions</h2>
<div class='hwrap'>
    <Project name='neozxw.net' url='#' img='/neozxw.svg' >
        Personal information and contacts.
    </Project>
</div>