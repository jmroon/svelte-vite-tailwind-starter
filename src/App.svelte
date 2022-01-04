<script>
  import logo from './assets/svelte.png'
  import Counter from './lib/Counter.svelte'
</script>

<main class="flex flex-col gap-16 items-center p-4 mx-auto"> 
  <img class="w-64 h-64" src={logo} alt="Svelte Logo" />
  <h1 class="mt-4 text-6xl font-thin text-red-500">Hello world!</h1>   
  <Counter />
  <div class="flex flex-col gap-4 text-center">
  <p class="text-lg">
    Visit <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte
    apps.
  </p>
  <p class="text-lg">
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>
</div>
</main>
