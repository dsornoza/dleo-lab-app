# NOTICE — Dependencias de terceros y atribuciones

DLEO Lab — Laboratorio matemático de decisiones para emprendedores. Versión 1.1.0.
Titular: Diego Sornoza Parrales. Autores: María Leonor Parrales Poveda (autora principal); Diego Sornoza Parrales. TODO(coautores)

Licencias leídas del `package.json` de cada paquete instalado el 2026-10-27 (no de memoria).
Este archivo lo genera `node scripts/notice.mjs`; no se edita a mano. No se agrega un archivo `LICENSE` propio: el titular no ha decidido la licencia del código.

## Qué se distribuye

La aplicación publicada (carpeta `dist/`) contiene el código propio y **solo** React y React DOM. Todo lo demás es herramienta de desarrollo y no se distribuye. Como el empaquetado no conserva los avisos de derechos de autor, sus textos de licencia MIT se reproducen al final de este archivo, que se sirve junto con la aplicación.

## Dependencias de ejecución (se distribuyen en el build)

| Paquete | Versión | Licencia | Repositorio |
|---|---|---|---|
| react | 19.3.1 | MIT | https://github.com/react/react |
| react-dom | 19.3.1 | MIT | https://github.com/react/react |

Justificación: React y React DOM se usan para la interfaz. Los gráficos y todo el cálculo (simplex, simulación, estadística, grafos) son código propio, sin librerías.

## Dependencias de desarrollo (no se distribuyen)

| Paquete | Versión | Licencia | Repositorio |
|---|---|---|---|
| @eslint/js | 10.0.1 | MIT | https://github.com/eslint/eslint |
| @testing-library/dom | 10.4.2 | MIT | https://github.com/testing-library/dom-testing-library |
| @testing-library/react | 16.3.3 | MIT | https://github.com/testing-library/react-testing-library |
| @types/node | 26.6.5 | MIT | https://github.com/DefinitelyTyped/DefinitelyTyped |
| @types/react | 19.3.0 | MIT | https://github.com/DefinitelyTyped/DefinitelyTyped |
| @types/react-dom | 19.3.0 | MIT | https://github.com/DefinitelyTyped/DefinitelyTyped |
| @vitejs/plugin-react | 6.1.2 | MIT | https://github.com/vitejs/vite-plugin-react |
| @vitest/coverage-v8 | 5.0.5 | MIT | https://github.com/vitest-dev/vitest |
| eslint | 10.13.0 | MIT | https://github.com/eslint/eslint |
| eslint-plugin-react-hooks | 7.1.1 | MIT | https://github.com/facebook/react |
| globals | 17.13.0 | MIT | https://github.com/sindresorhus/globals |
| jsdom | 30.1.3 | MIT | https://github.com/jsdom/jsdom |
| prettier | 3.9.10 | MIT | https://github.com/prettier/prettier |
| typescript | 6.0.3 | Apache-2.0 | https://github.com/microsoft/TypeScript |
| typescript-eslint | 8.72.1 | MIT | https://github.com/typescript-eslint/typescript-eslint |
| vite | 8.3.5 | MIT | https://github.com/vitejs/vite |
| vitest | 5.0.5 | MIT | https://github.com/vitest-dev/vitest |

## Todas las licencias instaladas

225 paquetes instalados (directos y transitivos): MIT 180, Apache-2.0 17, ISC 10, BSD-2-Clause 8, BSD-3-Clause 3, MIT-0 2, MPL-2.0 2, CC-BY-4.0 1, CC0-1.0 1, BlueOak-1.0.0 1.

Licencias distintas de MIT, ISC y BSD, todas en herramientas de desarrollo que no forman parte del código distribuido:

- **Apache-2.0** (17): @eslint/config-array@0.23.5, @eslint/config-helpers@0.7.0, @eslint/core@1.2.1, @eslint/object-schema@3.0.5, @eslint/plugin-kit@0.7.3, @humanfs/core@0.19.2, …
- **CC-BY-4.0** (1): caniuse-lite@1.0.30001819
- **MPL-2.0** (2): lightningcss@1.33.0, lightningcss-darwin-arm64@1.33.0
- **BlueOak-1.0.0** (1): minimatch@10.2.6

Atribución requerida por CC-BY-4.0: caniuse-lite (autor del paquete: Ben Briggs), https://github.com/browserslist/caniuse-lite. Es una herramienta de desarrollo y no forma parte del código distribuido; el texto completo de su licencia está en node_modules/caniuse-lite/LICENSE.

Nota: algunos paquetes son específicos de la plataforma donde se instalaron (por ejemplo, binarios de lightningcss para macOS); en otro sistema se instalan los equivalentes con la misma licencia.

## Textos de licencia de lo que se distribuye

### react 19.3.1

```
MIT License

Copyright (c) Meta Platforms, Inc. and affiliates.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### react-dom 19.3.1

```
MIT License

Copyright (c) Meta Platforms, Inc. and affiliates.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
