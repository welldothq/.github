# Welldot

**An open file format and toolkit for water well data.**

Most software for documenting water wells is proprietary, expensive and not interoperable. Welldot is an open alternative, built around **`.well`**: a JSON-based format that records a well's construction, lithology, hydraulic tests and water quality in one portable file.

- **Try it:** [welldot.org](https://welldot.org). Draw, edit and export well profiles in the browser.
- **Read the spec:** [`.well` specification](https://github.com/welldothq/welldot/tree/main/spec) and [JSON Schema](https://welldot.org/schema/v2/well.schema.json).
- **Use the libraries:** [`@welldot/*` on npm](https://www.npmjs.com/org/welldot).

| Package | What it does |
| --- | --- |
| [`@welldot/core`](https://www.npmjs.com/package/@welldot/core) | Types, Zod validators and serialization for `.well` files |
| [`@welldot/utils`](https://www.npmjs.com/package/@welldot/utils) | Depth, volume, gravel pack and aquifer calculations |
| [`@welldot/render`](https://www.npmjs.com/package/@welldot/render) | D3-based SVG renderer for well profiles |
| [`@welldot/pdf`](https://www.npmjs.com/package/@welldot/pdf) | Customizable PDF reports |
| [`@welldot/vue`](https://www.npmjs.com/package/@welldot/vue) | Vue 3 components for building `.well` editors |

Everything is free and open source under the Apache 2.0 license. Contributions are welcome: see the [contributing guide](https://github.com/welldothq/welldot/blob/main/CONTRIBUTING.md).

---

Created and maintained by [Rafael Neto](https://www.linkedin.com/in/rafaeelneto/).
