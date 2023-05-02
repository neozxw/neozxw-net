<script>
    import Project from '$lib/comp/Project.svelte';

    let projects = [
        {'name': 'Introduction', 'date': '2023-05-02'}
    ];

    projects = projects.map((x,id) => {
        if (x.id) return x;
        x.id = id;
        return x;
    });
</script>

<style>
    .hwrap {
        display: flex;
    }
</style>


<h2>Web log</h2>
<div class='hwrap'>
    {#each projects as proj}
        <Project name={proj.name} url='/posts/{proj.id}' img='/neozxw.svg' >
            Posted on {proj.date}
        </Project>
    {/each}
    
</div>