<script lang="ts">
    import Clickable from "$lib/Clickable.svelte";
</script>

<main>
    <p>
        The courtyard is suddenly surrounded as your entourage floods in,
        spreading out along the walls, leery of the cracked earth at its center.
        Leaning on the far side are two gardener's tools: a shovel and mattock.
        No hope of a misunderstanding at this point. Carvallo gestures, and the
        two strongest take them up.
    </p>
    <p>
        There's a growing silence as your men apply their muscles. None of the
        onlookers want to give voice to what they'll dig up, and neither do you,
        but it's your job:
    </p>
    <p>
        "When you find the body..."<br />
        "Search there, where the fennel is disturbed..."<br />
        "Where's the coroner gone?"
    </p>

    <Clickable />
</main>

<style>
    main {
        font-family: "Cormorant Garamond", serif;
        font-size: 24px;
        font-weight: 500;
    }

    main > p {
        margin-left: 1em;
        margin-right: 1em;
    }

    main > p:last-of-type {
        color: #0000ff;
    }
</style>
