# Toteat · Descargas

Versiones listas para usar de las herramientas Toteat. Este repositorio es público y **solo** tiene los programas
ya construidos: no tiene código, tokens ni datos de clientes. Se actualiza solo cada vez que se publica una versión.

## Descargas

| Herramienta | Versión | Fecha | Descargar |
|---|---|---|---|
| **Exportador de Ventas Toteat** | 2.4.2 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/exportador-v2.4.2/Exportador_Ventas_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/exportador-v2.4.2/Exportador_Ventas_Toteat_Mac.zip) |
| **Informe de Ventas por Plataforma** | 2.1.2 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/plataformas-v2.1.2/Informe_Plataformas_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/plataformas-v2.1.2/Informe_Plataformas_Toteat_Mac.zip) |
| **Informe de Inventario Toteat** | 1.1.1 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/inventario-v1.1.1/Informe_Inventario_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/inventario-v1.1.1/Informe_Inventario_Toteat_Mac.zip) |
| **Cargador de Compras Toteat** | 1.0.1 | 2026-11-03 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/compras-v1.0.1/Cargador_Compras_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/compras-v1.0.1/Cargador_Compras_Toteat_Mac.zip) |
| **Extractor Cadena Toteat** | 1.0.2 | 2026-11-05 | [Windows](https://github.com/darondonrin2407/toteat-descargas/releases/download/cadena-v1.0.2/Extractor_Cadena_Toteat_Windows.zip) · [Mac](https://github.com/darondonrin2407/toteat-descargas/releases/download/cadena-v1.0.2/Extractor_Cadena_Toteat_Mac.zip) |

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
| Exportador_Ventas_Toteat_Windows.zip | `1364751ad1c2bc6f7f77ec2d1cbad3f7fde33994326bd92c6abbd2463abfe69e` |
| Exportador_Ventas_Toteat_Mac.zip | `7d6c84db0d386900abb6eab02c69ba442e2e788145855bcd3b7868e7fa02924a` |
| Informe_Plataformas_Toteat_Windows.zip | `115faf30b10f0625f4893386dbfaa176ffcc6a93abf37c267839eba07f7e174a` |
| Informe_Plataformas_Toteat_Mac.zip | `b2cb2110f9352b8c79672343838b3f9b3881e36eb28375d557828dc14c877e8a` |
| Informe_Inventario_Toteat_Windows.zip | `d98fb3248357cfdfddefc0296d174fa24fca943f8b406e883959e62f26377d77` |
| Informe_Inventario_Toteat_Mac.zip | `e5b72e30db4b061e6a725f89793709692c177dba7f9ce167987c8b4f74ad51a6` |
| Cargador_Compras_Toteat_Windows.zip | `8804345917a17b2be52d2fe504666a2aec26d756a0160386d7af580bfff0adab` |
| Cargador_Compras_Toteat_Mac.zip | `6f34ffdbc38a0d8425dda89d3c6ccfb7c478b9aa404fedc19e36384e2117aee8` |
| Extractor_Cadena_Toteat_Windows.zip | `d86fe8562ab663ca266c6620337ff17705014c8ef2d443679b7b545647764c7f` |
| Extractor_Cadena_Toteat_Mac.zip | `f007993a167df5a15feaa38bddcaa9bcb4e9e334e2c6a0ca6fda1a52744e8949` |

Actualizado: 2026-11-05 · [versiones.json](versiones.json)
