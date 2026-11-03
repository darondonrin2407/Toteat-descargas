# Toteat · Descargas

Versiones listas para usar de las herramientas Toteat. Este repositorio es público y **solo** tiene los programas
ya construidos: no tiene código, tokens ni datos de clientes. Se actualiza solo cada vez que se publica una versión.

## Descargas

| Herramienta | Versión | Fecha | Descargar |
|---|---|---|---|
| **Exportador de Ventas Toteat** | 2.4.1 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/exportador-v2.4.1/Exportador_Ventas_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/exportador-v2.4.1/Exportador_Ventas_Toteat_Mac.zip) |
| **Informe de Ventas por Plataforma** | 2.1.1 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/plataformas-v2.1.1/Informe_Plataformas_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/plataformas-v2.1.1/Informe_Plataformas_Toteat_Mac.zip) |
| **Informe de Inventario Toteat** | 1.1.1 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/inventario-v1.1.1/Informe_Inventario_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/inventario-v1.1.1/Informe_Inventario_Toteat_Mac.zip) |
| **Cargador de Compras Toteat** | 1.0.1 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/compras-v1.0.1/Cargador_Compras_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/compras-v1.0.1/Cargador_Compras_Toteat_Mac.zip) |
| **Extractor Cadena Toteat** | 1.0.1 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/cadena-v1.0.1/Extractor_Cadena_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/cadena-v1.0.1/Extractor_Cadena_Toteat_Mac.zip) |
| **Diagnóstico de Ventas (respuesta cruda)** | 2026.10.22 | 2026-11-03 | [ZIP](https://github.com/darondonrin2407/toteat-descargas/releases/download/diagnostico-ventas-v2026.10.22/Diagnostico_Ventas_Toteat.zip) |
| **Diagnóstico de Inventario (respuesta cruda)** | 2026.10.19 | 2026-11-03 | [ZIP](https://github.com/darondonrin2407/toteat-descargas/releases/download/diagnostico-inventario-v2026.10.19/Diagnostico_Inventario_Toteat.zip) |
| **Extraer Menú** | 2026.10.21 | 2026-11-03 | [ZIP](https://github.com/darondonrin2407/toteat-descargas/releases/download/extraer-menu-v2026.10.21/Extraer_Menu_Toteat.zip) |
| **Prueba de Compras (piloto, ambiente de pruebas)** | 2026.10.20 | 2026-11-03 | [ZIP](https://github.com/darondonrin2407/toteat-descargas/releases/download/prueba-compras-v2026.10.20/Prueba_Compras_Toteat.zip) |

**Cómo instalar o actualizar:** descarga el ZIP de tu sistema, descomprímelo y reemplaza la versión anterior.
Tus clientes y su configuración no se pierden: se guardan aparte en el computador
(`%APPDATA%\ExportadorToteat` en Windows, `~/Library/Application Support/ExportadorToteat` en Mac).
Los programas avisan solos al abrirlos cuando hay una versión nueva.

## Verificar que el archivo es el original (opcional)

Compara la huella del ZIP descargado con la de esta tabla. Deben ser idénticas.
- Windows (PowerShell): `Get-FileHash .\NOMBRE.zip -Algorithm SHA256`
- Mac (Terminal): `shasum -a 256 NOMBRE.zip`

| Archivo | SHA-256 |
|---|---|
| Exportador_Ventas_Toteat_Windows.zip | `e827a7441efae40ba6e15a8012a2dcbd515f8628046cafffd9cb1b047849c302` |
| Exportador_Ventas_Toteat_Mac.zip | `9ce4043b39eccc8d2e809d3899042edb4e373a8fdf354cf6220c80162513f0e6` |
| Informe_Plataformas_Toteat_Windows.zip | `70404c4269591224b9092651a7eefc882cc616e786f8f9be908f495781870edd` |
| Informe_Plataformas_Toteat_Mac.zip | `4736362feb666a80d673c288c9c41b787d4cbaddbcc1752113832bb0e5f12f9e` |
| Informe_Inventario_Toteat_Windows.zip | `d98fb3248357cfdfddefc0296d174fa24fca943f8b406e883959e62f26377d77` |
| Informe_Inventario_Toteat_Mac.zip | `e5b72e30db4b061e6a725f89793709692c177dba7f9ce167987c8b4f74ad51a6` |
| Cargador_Compras_Toteat_Windows.zip | `8804345917a17b2be52d2fe504666a2aec26d756a0160386d7af580bfff0adab` |
| Cargador_Compras_Toteat_Mac.zip | `6f34ffdbc38a0d8425dda89d3c6ccfb7c478b9aa404fedc19e36384e2117aee8` |
| Extractor_Cadena_Toteat_Windows.zip | `4811a3c1ac0ece630d6a61e475a02b8bdcad1f2ca566b799ef774d53495ad16e` |
| Extractor_Cadena_Toteat_Mac.zip | `5129c5f8c4b5da2811a16ea487bc944cf4da1ab782fd2edd45c6ace730059190` |
| Diagnostico_Ventas_Toteat.zip | `03e746c09812356c69665364ffaca3dcf98af38bf0b98e052ee47ad1bc2aa91c` |
| Diagnostico_Inventario_Toteat.zip | `aeb52a73980442de0ccd7c44dd84c14e29bbab1e03f6307cfb1c0da838325367` |
| Extraer_Menu_Toteat.zip | `c53b9bd7ed26b85bd1c91e4ccca854a90dcec9c3c16a0d11d6dfdb3cfd3126c8` |
| Prueba_Compras_Toteat.zip | `b60cec1cac6811dab3db4190c7394937a51779e221238abb506debe5f6aef9a9` |

Actualizado: 2026-11-03 · [versiones.json](versiones.json)
