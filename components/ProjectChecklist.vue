<template>
  <section>
    <h2>Checklist Goedemiddag!</h2>
    <details>
      <AtomsSummaryItem summaryTitle="♿ Toegankelijkheid" />
      <ul>
        <MoleculesDetailsListItem
          id="color-contrast"
          title="Kleuren contrast"
        />
        <MoleculesDetailsListItem id="alt-text" title="Alt tekst" />
        <MoleculesDetailsListItem id="tab" title="Pagina doortabbaar" />
        <MoleculesDetailsListItem id="screenreader" title="Screenreader" />
        <MoleculesDetailsListItem id="responsive" title="Responsive" />
        <MoleculesDetailsListItem id="semantic-html" title="Semantische HTML" />
      </ul>
    </details>

    <details>
      <AtomsSummaryItem summaryTitle="⏱️ Performance" />
      <ul>
        <MoleculesDetailsListItem id="fcp" title="First Contentful Paint" />
        <MoleculesDetailsListItem id="lcp" title="Largest Contentful Paint" />
        <MoleculesDetailsListItem id="tbt" title="Total Blocking Time" />
        <MoleculesDetailsListItem id="cls" title="Cumulative Layout Shift" />
        <MoleculesDetailsListItem id="si" title="Speed Index" />
      </ul>
    </details>

    <details>
      <AtomsSummaryItem summaryTitle="💅 Huisstijl" />
      <ul>
        <MoleculesDetailsListItem id="favicon" title="Favicon" />
        <MoleculesDetailsListItem id="logo" title="Logo" />
        <MoleculesDetailsListItem id="colors" title="Kleurenschema" />
        <MoleculesDetailsListItem id="typografie" title="Typografie" />
        <MoleculesDetailsListItem id="icons" title="Icons" />
      </ul>
    </details>
    <details>
      <AtomsSummaryItem summaryTitle="📄 Pagina's" />
      <ul>
        <MoleculesDetailsListItem id="homepage" title="Homepagina" />
        <MoleculesDetailsListItem id="error" title="Error pagina" />
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
  background-color: var(--color5);
  padding: 1rem 1rem 3rem;
  border-radius: 1rem;
}
summary:hover {
  cursor: pointer;
}
</style>
