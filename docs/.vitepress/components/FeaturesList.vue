<template>
  <ul
    class="features-list"
    dir="auto"
    flex="~ col gap2 md:gap-3"
  >
    <ListItem><a target="_blank" href="https://vitejs.dev" rel="noopener noreferrer">Vite</a>'s config, transformers, resolvers, and plugins.</ListItem>
    <ListItem>Use the same setup from your app to run the tests!</ListItem>
    <ListItem><a target="_blank" href="https://twitter.com/antfu7/status/1468233216939245579" rel="noopener noreferrer">Smart & instant watch mode, like HMR for tests!</a></ListItem>
    <ListItem>Component testing for Vue, React, Svelte, Lit and more</ListItem>
    <ListItem>Out-of-the-box TypeScript / JSX support</ListItem>
    <ListItem>ESM first, top level await</ListItem>
    <ListItem>Workers multi-threading via <a target="_blank" href="https://github.com/tinylibs/tinypool" rel="noopener noreferrer">Tinypool</a></ListItem>
    <ListItem>Benchmarking support with <a target="_blank" href="https://github.com/tinylibs/tinybench" rel="noopener noreferrer">Tinybench</a></ListItem>
    <ListItem>Filtering, timeouts, concurrent for suite and tests</ListItem>
    <ListItem><a href="/guide/workspace">Workspace</a> support</ListItem>
    <ListItem>
      <a href="/guide/snapshot">
        Jest-compatible Snapshot
      </a>
    </ListItem>
    <ListItem><a target="_blank" href="https://www.chaijs.com/" rel="noopener noreferrer">Chai</a> built-in for assertions + <a target="_blank" href="https://jestjs.io/docs/expect" rel="noopener noreferrer">Jest expect</a> compatible APIs</ListItem>
    <ListItem><a target="_blank" href="https://github.com/tinylibs/tinyspy" rel="noopener noreferrer">Tinyspy</a> built-in for mocking</ListItem>
    <ListItem><a target="_blank" href="https://github.com/capricorn86/happy-dom" rel="noopener noreferrer">happy-dom</a> or <a target="_blank" href="https://github.com/jsdom/jsdom" rel="noopener noreferrer">jsdom</a> for DOM mocking</ListItem>
    <ListItem>Code coverage via <a target="_blank" href="https://github.com/bcoe/c8" rel="noopener noreferrer">c8</a> or <a target="_blank" href="https://istanbul.js.org/" rel="noopener noreferrer">istanbul</a></ListItem>
    <ListItem>Rust-like <a href="/guide/in-source">in-source testing</a></ListItem>
    <ListItem>Type Testing via <a target="_blank" href="https://github.com/mmkal/expect-type" rel="noopener noreferrer">expect-type</a></ListItem>
  </ul>
</template>

<style scoped>
.features-list li {
  list-style: none;
  display: flex;
  gap: 0.4rem;
  margin: 0;
}

.features-list {
  padding: 0;
}
</style>
