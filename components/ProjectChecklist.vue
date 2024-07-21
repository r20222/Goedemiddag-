<template>
  <section>
    <h2>Checklist Goedemiddag!</h2>

    <details>
      <summary>Toegankelijkheid</summary>
      <ul>
        <li>
          <input type="checkbox" id="color-contrast" />
          <label for="color-contrast">Kleuren contrast</label>
        </li>
        <li>
          <input type="checkbox" id="alt-text" />
          <label for="alt-text">Alt tekst</label>
        </li>
        <li>
          <input type="checkbox" id="tab" />
          <label for="tab">Pagina doortabbaar</label>
        </li>
        <li>
          <input type="checkbox" id="screenreader" />
          <label for="screenreader">Screenreader</label>
        </li>
        <li>
          <input type="checkbox" id="responsive" />
          <label for="responsive">Responsive</label>
        </li>
        <li>
          <input type="checkbox" id="semantic-html" />
          <label for="semantic-html">Semantische HTML</label>
        </li>
      </ul>
    </details>

    <details>
      <summary>Performance</summary>
      <ul>
        <li>
          <input type="checkbox" id="fcp" />
          <label for="fcp">First Contentful Paint</label>
        </li>
        <li>
          <input type="checkbox" id="lcp" />
          <label for="lcp">Largest Contentful Paint</label>
        </li>
        <li>
          <input type="checkbox" id="tbt" />
          <label for="tbt">Total Blocking Time</label>
        </li>
        <li>
          <input type="checkbox" id="cls" />
          <label for="cls">Cumulative Layout Shift</label>
        </li>
        <li>
          <input type="checkbox" id="si" />
          <label for="si">Speed Index</label>
        </li>
      </ul>
    </details>

    <details>
      <summary>Huisstijl</summary>
      <ul>
        <li>
          <input type="checkbox" id="favicon" />
          <label for="favicon">Favicon</label>
        </li>
        <li>
          <input type="checkbox" id="logo" />
          <label for="logo">Logo</label>
        </li>
        <li>
          <input type="checkbox" id="colors" />
          <label for="colors">Kleurenschema</label>
        </li>
        <li>
          <input type="checkbox" id="typografie" />
          <label for="typografie">Typografie</label>
        </li>
      </ul>
    </details>
  </section>
</template>

<style scoped>
ul {
  list-style: none;
  padding-left: 0;
}
section {
  background-color: var(--color1);
  padding: 1rem 1rem 3rem;
}
</style>
