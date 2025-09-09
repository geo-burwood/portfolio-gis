# 01 - Mapa Temático: Pelotas, RS

**Resumo:** mapa de cobertura do solo para o município de Pelotas (RS) usando MapBiomas — demonstrar processamento raster, simbologia e layout cartográfico.

**Skills demonstradas:** QGIS, processamento raster, recorte espacial, export de mapa.

**Dados (origem):**
- Uso e cobertura da Terra: Projeto MapBiomas – Coleção 10 da Série Anual de Mapas de Cobertura e Uso da Terra do Brasil, acessado em 09/09/2025 através do link: https://brasil.mapbiomas.org/colecoes-mapbiomas/. Acesse a publicação científica de referência: Souza at. al. (2020) - Reconstructing Three Decades of Land Use and Land Cover Changes in Brazilian Biomes with Landsat Archive and Earth Engine - Remote Sensing, Volume 12, Issue 17, 10.3390/rs12172735.
- Malha municipal — IBGE. Link: https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html

**Atribuição / como citar (exemplo):**
MapBiomas — Coleção <COLEÇÃO/VERSÃO>. Série Anual de Mapas de Cobertura e Uso da Terra. Acessado em <DD/MM/2025>. URL: <LINK>

**Passos reprodutíveis (resumo):**
1. Baixar o raster MapBiomas para o Brasil / RS.
2. Carregar raster no QGIS e recortar pelo limite municipal de Pelotas (IBGE).
3. Ajustar simbologia e exportar mapa em PNG/PDF.
4. Incluir scripts/notebook em `scripts/` e outputs em `outputs/maps/`.

**Obs:** Não subir rasters inteiros para o GitHub; inclua apenas amostras ou instruções para download.
