<script>
    import Wrapper from '$lib/comp/Wrapper.svelte';
    import Button from '$lib/comp/Button.svelte';
    import Project from '$lib/comp/Project.svelte';
</script>

<style>

    p {
        text-align: center;
    }

    a {
        text-decoration: none;
        color: var(--white-1);
    }
    
    .main {
        width: 100px;
    } 
</style>

<Wrapper>
    <p class='bold'>neozxw</p>

    <img class='main' src='/neozxw.svg' alt='neozxw Logo'>

    <p>Expanding the Internet</p>

    <div class='hwrap'>
        <Button>
            🖥️ Linux
        </Button>
        <Button>
            📝 Web Developer
        </Button>
    </div>

    <div class='hwrap'>
        <Button clickable='true'>
            <a href='https://github.com/neozxw'>🌐 GitHub</a>
        </Button>
    </div>
</Wrapper>

<h2>Contributions</h2>
<div class='hwrap'>
    <Project name='neozxw.net' url='#' img='/neozxw.svg' >
        Personal information and contacts.
    </Project>
    <Project name='Web log' url='/posts' img='/neozxw.svg' >
        A periodic stream of web posts.
    </Project>
</div>