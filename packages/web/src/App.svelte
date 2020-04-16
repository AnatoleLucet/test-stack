<script type="text/typescript">
  import Title from "./Title.svelte";

  import { User } from "@packages/api/src/@types/User";

  const user: User = {
    email: 2
  };

  export let name: string;
</script>

<style type="text/scss">
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <Title {name} />
  <p>
    Visit the
    <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
    to learn how to build Svelte apps.
  </p>
</main>
