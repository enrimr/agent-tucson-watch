# Changelog — Tucson PHEV Watch

## 2026-08-06

Primera ejecución del agente de vigilancia. Se ha creado la línea base con los 10 anuncios conocidos (A–J) y se ha realizado además la primera comprobación real en las cuatro webs.

**9 anuncios nuevos encontrados:**

- **K** — ocasionplus.com: 1.6 TGDI PHEV Maxx 4X4 Auto, 21.950 €, 108.420 km, 2022, Valencia-Paterna.
- **L** — autohero.com: 1.6 T-GDI Plug-in Hybrid Maxx 4WD, 23.199 €, 76.540 km, 2022.
- **M** — autohero.com: 1.6 T-GDI Plug-in Hybrid Tecno Sky 4WD, 22.099 €, 131.410 km, 2021.
- **N** — coches.net: 1.6T PHEV AT Tecno Sky, 39.490 €, 1 km (prácticamente nuevo), 2026, Madrid. 288 CV, garantía oficial 5 años.
- **O** — coches.net: 1.6 TGDI PHEV Style Auto 4x4, 27.900 €, 95.500 km, 2021, Madrid. 1 propietario, garantía 1 año.
- **P** — coches.net: 1.6T PHEV AT Tecno Sky, 37.790 €, 10.580 km, 2025, Murcia.
- **Q** — coches.net: 1.6 TGDI PHEV Maxx Auto 4x4, 22.890 €, 100.094 km, 2022, Madrid.
- **R** — coches.net: 1.6 TGDI PHEV Maxx Auto 4x4, 23.990 €, 51.500 km, 2022, Las Palmas.
- **S** — coches.net: 1.6 TGDI PHEV Tecno Sky Auto 4x4, 24.990 €, 44.000 km, 2021, Las Palmas.

**1 cambio de precio:**

- **A** (ocasionplus.com, 1.6 TGDI PHEV Maxx 4x4 Auto, 53.641 km, 2023): 26.450 € → 25.990 € (↓ 460 €).

**Sin cambios:** B, C, D, E, F, G, H, I, J confirmados activos hoy, mismo precio que la línea base.

**Incidencias:**
- coches.net bloqueó por detección de bot 4 de las fetch individuales a fichas de detalle (P, Q, R, S); sus datos se han tomado de la página de listado/categoría (que sí respondió correctamente), por lo que potencia, nº de propietarios y garantía constan como "no especificado" para esos cuatro anuncios.
- carplus.es renderiza el listado de categoría vía JavaScript y no devolvió resultados al hacer fetch estático; solo se han podido verificar los anuncios ya conocidos (E, J) accediendo directamente a sus URLs. No se puede descartar que existan más anuncios PHEV en carplus.es no detectados hoy.
- Varias URLs de ocasionplus.com encontradas en la búsqueda inicial (variantes Style/Tecno Sky en Madrid, Girona, Huelva, Valencia) devolvieron error 404/410 (anuncio ya retirado o URL caducada) y no se han incluido.

Total anuncios activos monitorizados: 19.
