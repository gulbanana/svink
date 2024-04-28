<script lang="ts">
    function onClick() {
        console.log("click");
    }
</script>

<svg width="120" height="120" viewBox="0 0 120 120">
    <g class="interact" on:click={onClick}>
        <circle class="outer" cx="60" cy="60" r="50" />
        <circle class="bezel" cx="60" cy="60" r="49" />
        <circle class="outer" cx="60" cy="60" r="46" />
        <circle class="inner" cx="60" cy="60" r="45" />
    </g>
</svg>

<style>
    .outer {
        fill: #a0a;
    }

    .bezel {
        fill: #606;
    }

    .inner {
        fill: #0a0;
    }

    .interact:hover {
        & > .bezel {
            fill: #303;
        }

        & > .inner {
            fill: #090;
        }
    }
</style>