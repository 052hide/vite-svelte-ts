<svelte:options tag="my-app" />

<script lang="ts">
  import "~/lib/Button/index.svelte";
  import "~/assets/style.css";
</script>

<main class="flex flex-col justify-center items-center h-screen">
  <h1 class="text-3xl font-bold">Vite Svelte TS</h1>

  <atom-button theme="secondary" size="base">Button</atom-button>
</main>
