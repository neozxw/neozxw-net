<style>
    .main {
        min-height: 40vh;
        width: 100vw;

        padding: 5vh;

        background: var(--black-2);

        display: flex;

        flex-direction: column;
        align-items: center;
        justify-content: center;

        color: var(--white-2);
    }
</style>

<div class='main'>
    <slot />
</div>