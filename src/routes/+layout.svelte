<script>
    import "../global.css";
</script>

<div class="backdrop">
    <div class="separator">
        <div class="column">
            <slot />
        </div>
    </div>
</div>

<style>
    .backdrop {
        width: 100vw;
        min-height: 100dvh;
        background: #247696;
        display: flex;
        justify-content: center;
    }

    .separator {
        display: flex;
        border: 1px solid rgb(235, 254, 203);
        border-width: 0 2px;
        padding: 0 4px;
        background: #9de0fb;
        display: grid;
        grid-template-columns: minmax(auto, 100vh);
    }

    .column {
        border: 1px solid rgb(235, 254, 203);
        border-width: 0 2px;
        background: #9de0fb;
    }
</style>
