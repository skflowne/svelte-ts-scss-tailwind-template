<script lang="ts">
    import Tailwind from "./Tailwind.svelte"
</script>

<style lang="scss">
    main {
        h1 {
            font-size: 22rem;
        }
    }
</style>

<Tailwind />
<main>
    <h1 class="text-blue-900">Hello!</h1>
    <p>
        Visit the
        <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
        to learn how to build Svelte apps.
    </p>
</main>
