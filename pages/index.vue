<template>
  <section>
    <ProjectNavigation />
    <ProjectHeader />
    <ProjectChecklist />
    <ProjectFooter />
  </section>
</template>

<style>
:root {
  --color1: #ff6b73;
  --color2: #2b61a3;
  --color3: #a6edb5;
  --color4: #595754;
  --color5: #d1a19c;
}
html {
  background-color: var(--color3);
  scrollbar-gutter: stable;
}
body {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
section {
  max-width: 40rem;
  margin: auto;
}
</style>
