
<style>
    :global(:root) {
        --white-1: rgb(255,255,255);
        --white-2: rgb(200,200,205);

        --black-1: rgb(0,0,0);
        --black-2: rgb(45, 48, 55);
        --black-3: rgb(130,135,140);

        --link-1: rgb(70, 173, 67);

        --shadow-1: 0 0px 5px 3px rgba(0,0,0,0.2);

        font-family: "Open Sans", sans-serif;
        font-size: 1.0rem;
    }

    :global(.bold) {
        font-weight: bold;
        color: var(--white-1);
        font-size: max(2vw,1.5rem);
        margin: 5px;
    }

    :global(.hwrap) {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }

    body {
        padding: 0;
        margin: 0;

        display: flex;

        flex-direction: column;
        align-items: center;

        color: var(--black-1);
        
        background: var(--white-1);
        background-position: center;
    }
    
</style>

<body>
    <slot />
</body>
