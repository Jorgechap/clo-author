# FARO Journal Profiles Seed Corpus

Este documento amplía el archivo base `journal-profiles.md` y lo convierte en un corpus semiestructurado de revistas, plataformas editoriales y recursos de evaluación detectados en los marcadores del usuario. Su propósito es servir como insumo de ejemplo para Claude en la construcción del framework FARO, de modo que el sistema aprenda a reconocer señales editoriales, familias de revistas, portales de envío y patrones de publicación en agricultura de precisión, IA aplicada, visión por computador, IoT, sensores, agua, sostenibilidad y áreas afines.[file:16][file:17]

El archivo original usa perfiles narrativos por revista con foco en cultura editorial y expectativas de revisión. Aquí se conserva esa intención, pero se expande a un inventario más amplio y operativo, organizado por clúster temático y acompañado por plantillas listas para que FARO derive perfiles formales, reglas heurísticas, taxonomías de indexación, criterios de ajuste revista-manuscrito y rutas de envío editorial.[file:17][file:16]

## Cómo usar este corpus

- Usar cada entrada como semilla de perfil editorial, no como perfil final validado.[file:17][file:16]
- Priorizar las revistas repetidas por familia editorial porque indican interés real y recurrencia temática del usuario.[file:16]
- Separar en FARO tres capas: `journal_profile`, `publisher_platform_profile` y `ranking_source_profile`.[file:17][file:16]
- Derivar reglas de compatibilidad manuscrito-revista con base en alcance temático, tipo de datos, rigor metodológico y orientación aplicada o teórica.[file:17]

## Agricultura de precisión e IA
Se identificaron 12 recursos en este clúster temático a partir del archivo de marcadores exportado. La densidad de enlaces sugiere que este conjunto debe tratarse en FARO como una colección prioritaria para construir perfiles, reglas de enrutamiento editorial y sugerencias de revistas objetivo.[file:16]
### Smart Agricultural Technology | Journal | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/smart-agricultural-technology](https://www.sciencedirect.com/journal/smart-agricultural-technology)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `smart-agricultural-technology-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: smart-agricultural-technology-journal-sciencedirect-com-by-elsevier
name: "Smart Agricultural Technology | Journal | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/smart-agricultural-technology"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Crop Design | Journal | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/crop-design](https://www.sciencedirect.com/journal/crop-design)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `crop-design-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: crop-design-journal-sciencedirect-com-by-elsevier
name: "Crop Design | Journal | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/crop-design"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### AI | Special Issue : Harvesting the Future: AI applications in Precision Agriculture
- URL: [https://www.mdpi.com/journal/ai/special_issues/X6J7QW6Z91](https://www.mdpi.com/journal/ai/special_issues/X6J7QW6Z91)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `ai-special-issue-harvesting-the-future-ai-applications-in-precision-agriculture`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: ai-special-issue-harvesting-the-future-ai-applications-in-precision-agriculture
name: "AI | Special Issue : Harvesting the Future: AI applications in Precision Agriculture"
url: "https://www.mdpi.com/journal/ai/special_issues/X6J7QW6Z91"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Computers and Electronics in Agriculture | Journal | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/computers-and-electronics-in-agriculture](https://www.sciencedirect.com/journal/computers-and-electronics-in-agriculture)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `computers-and-electronics-in-agriculture-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: computers-and-electronics-in-agriculture-journal-sciencedirect-com-by-elsevier
name: "Computers and Electronics in Agriculture | Journal | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/computers-and-electronics-in-agriculture"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Insights - Information Processing in Agriculture | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/information-processing-in-agriculture/about/insights](https://www.sciencedirect.com/journal/information-processing-in-agriculture/about/insights)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `insights-information-processing-in-agriculture-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: insights-information-processing-in-agriculture-sciencedirect-com-by-elsevier
name: "Insights - Information Processing in Agriculture | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/information-processing-in-agriculture/about/insights"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Artificial Intelligence in Agriculture | Vol 9, Pages 1-126 (September 2023) | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/artificial-intelligence-in-agriculture/vol/9/suppl/C](https://www.sciencedirect.com/journal/artificial-intelligence-in-agriculture/vol/9/suppl/C)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `artificial-intelligence-in-agriculture-vol-9-pages-1-126-september-2023-scienced`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: artificial-intelligence-in-agriculture-vol-9-pages-1-126-september-2023-scienced
name: "Artificial Intelligence in Agriculture | Vol 9, Pages 1-126 (September 2023) | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/artificial-intelligence-in-agriculture/vol/9/suppl/C"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Home | Precision Agriculture
- URL: [https://link.springer.com/journal/11119](https://link.springer.com/journal/11119)
- Dominio: `link.springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `home-precision-agriculture`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: home-precision-agriculture
name: "Home | Precision Agriculture"
url: "https://link.springer.com/journal/11119"
domain: "link.springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Insights - The Crop Journal | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/the-crop-journal/about/insights](https://www.sciencedirect.com/journal/the-crop-journal/about/insights)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `insights-the-crop-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: insights-the-crop-journal-sciencedirect-com-by-elsevier
name: "Insights - The Crop Journal | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/the-crop-journal/about/insights"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Artificial Intelligence in Agriculture
- URL: [https://www.scimagojr.com/journalsearch.php?q=21101042196&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21101042196&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `artificial-intelligence-in-agriculture`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: artificial-intelligence-in-agriculture
name: "Artificial Intelligence in Agriculture"
url: "https://www.scimagojr.com/journalsearch.php?q=21101042196&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Artificial Intelligence in Agriculture | Journal | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/artificial-intelligence-in-agriculture](https://www.sciencedirect.com/journal/artificial-intelligence-in-agriculture)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `artificial-intelligence-in-agriculture-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: artificial-intelligence-in-agriculture-journal-sciencedirect-com-by-elsevier
name: "Artificial Intelligence in Agriculture | Journal | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/artificial-intelligence-in-agriculture"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Intelligent Computing and Sensing Systems for Sustainable Precision Agriculture | Computers | MDPI
- URL: [https://www.mdpi.com/journal/computers/special_issues/5RD2OE34S0](https://www.mdpi.com/journal/computers/special_issues/5RD2OE34S0)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `intelligent-computing-and-sensing-systems-for-sustainable-precision-agriculture-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: intelligent-computing-and-sensing-systems-for-sustainable-precision-agriculture-
name: "Intelligent Computing and Sensing Systems for Sustainable Precision Agriculture | Computers | MDPI"
url: "https://www.mdpi.com/journal/computers/special_issues/5RD2OE34S0"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Guide for authors - Computers and Electronics in Agriculture - ISSN 0168-1699 | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/computers-and-electronics-in-agriculture/publish/guide-for-authors](https://www.sciencedirect.com/journal/computers-and-electronics-in-agriculture/publish/guide-for-authors)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `guide-for-authors-computers-and-electronics-in-agriculture-issn-0168-1699-scienc`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: guide-for-authors-computers-and-electronics-in-agriculture-issn-0168-1699-scienc
name: "Guide for authors - Computers and Electronics in Agriculture - ISSN 0168-1699 | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/computers-and-electronics-in-agriculture/publish/guide-for-authors"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```

## Visión por computador, sensores e IoT
Se identificaron 16 recursos en este clúster temático a partir del archivo de marcadores exportado. La densidad de enlaces sugiere que este conjunto debe tratarse en FARO como una colección prioritaria para construir perfiles, reglas de enrutamiento editorial y sugerencias de revistas objetivo.[file:16]
### From GIS to Remote Sensing: Semi-Automatic Classification Plugin for QGIS
- URL: [https://fromgistors.blogspot.com/p/semi-automatic-classification-plugin.html](https://fromgistors.blogspot.com/p/semi-automatic-classification-plugin.html)
- Dominio: `fromgistors.blogspot.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `from-gis-to-remote-sensing-semi-automatic-classification-plugin-for-qgis`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: from-gis-to-remote-sensing-semi-automatic-classification-plugin-for-qgis
name: "From GIS to Remote Sensing: Semi-Automatic Classification Plugin for QGIS"
url: "https://fromgistors.blogspot.com/p/semi-automatic-classification-plugin.html"
domain: "fromgistors.blogspot.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Introduction to Multispectral Remote Sensing Data in Python | Earth Data Science - Earth Lab
- URL: [https://www.earthdatascience.org/courses/use-data-open-source-python/multispectral-remote-sensing/intro-multispectral-data/](https://www.earthdatascience.org/courses/use-data-open-source-python/multispectral-remote-sensing/intro-multispectral-data/)
- Dominio: `earthdatascience.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `introduction-to-multispectral-remote-sensing-data-in-python-earth-data-science-e`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: introduction-to-multispectral-remote-sensing-data-in-python-earth-data-science-e
name: "Introduction to Multispectral Remote Sensing Data in Python | Earth Data Science - Earth Lab"
url: "https://www.earthdatascience.org/courses/use-data-open-source-python/multispectral-remote-sensing/intro-multispectral-data/"
domain: "earthdatascience.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### UAV Remote Sensing applications and current trends in crop monitoring and diagnostics: A Systematic Literature Review | IEEE Conference Publication | IEEE Xplore
- URL: [https://ieeexplore-ieee-org.udea.lookproxy.com/document/10179038](https://ieeexplore-ieee-org.udea.lookproxy.com/document/10179038)
- Dominio: `ieeexplore-ieee-org.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `uav-remote-sensing-applications-and-current-trends-in-crop-monitoring-and-diagno`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: uav-remote-sensing-applications-and-current-trends-in-crop-monitoring-and-diagno
name: "UAV Remote Sensing applications and current trends in crop monitoring and diagnostics: A Systematic Literature Review | IEEE Conference Publication | IEEE Xplore"
url: "https://ieeexplore-ieee-org.udea.lookproxy.com/document/10179038"
domain: "ieeexplore-ieee-org.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Machine Vision and Applications | Home
- URL: [https://link.springer.com/journal/138](https://link.springer.com/journal/138)
- Dominio: `link.springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `machine-vision-and-applications-home`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: machine-vision-and-applications-home
name: "Machine Vision and Applications | Home"
url: "https://link.springer.com/journal/138"
domain: "link.springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### International Journal of Applied Earth Observation and Geoinformation | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/international-journal-of-applied-earth-observation-and-geoinformation](https://www.sciencedirect.com/journal/international-journal-of-applied-earth-observation-and-geoinformation)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `international-journal-of-applied-earth-observation-and-geoinformation-sciencedir`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: international-journal-of-applied-earth-observation-and-geoinformation-sciencedir
name: "International Journal of Applied Earth Observation and Geoinformation | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/international-journal-of-applied-earth-observation-and-geoinformation"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Remote Sensing | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/remotesensing](https://www.mdpi.com/journal/remotesensing)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `remote-sensing-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: remote-sensing-an-open-access-journal-from-mdpi
name: "Remote Sensing | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/remotesensing"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Remote sensing tools for monitoring water requirements and water stress in vineyards and fruit trees | IEEE Conference Publication | IEEE Xplore
- URL: [https://ieeexplore.ieee.org/document/10006120](https://ieeexplore.ieee.org/document/10006120)
- Dominio: `ieeexplore.ieee.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `remote-sensing-tools-for-monitoring-water-requirements-and-water-stress-in-viney`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: remote-sensing-tools-for-monitoring-water-requirements-and-water-stress-in-viney
name: "Remote sensing tools for monitoring water requirements and water stress in vineyards and fruit trees | IEEE Conference Publication | IEEE Xplore"
url: "https://ieeexplore.ieee.org/document/10006120"
domain: "ieeexplore.ieee.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Sensors | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/sensors](https://www.mdpi.com/journal/sensors)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `sensors-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: sensors-an-open-access-journal-from-mdpi
name: "Sensors | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/sensors"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Results | Journal Finder
- URL: [https://journalfinder.elsevier.com/results?goldOpenAccess=true&subscription=true&elsevierOnly=true&sortBy=default&sortOrder=desc&query=Nitrogen+is+the+most+crucial+nutritional+element+during+the+vegetative+growth+stage+of+pineapple+cultivation.+In+this+study%2C+nine+machine+learning+techniques+were+validated+to+estimate+the+total+nitrogen+content+in+MD2+pineapple+crops%2C+using+multispectral+images%2C+crop-installed+sensors%2C+and+SPAD+values+representing+leaf+chlorophyll+content.+To+introduce+nitrogen+variability%2C+a+complete+randomized+block+experimental+design+was+implemented%2C+applying+five+different+treatments+in+five+blocks%2C+each+with+12+replications%2C+over+a+period+of+6+months+in+a+pineapple+crop+located+in+Tauramena%2C+Colombia.+Image+capture+was+carried+out+using+a+multispectral+camera+mounted+on+an+unmanned+aerial+vehicle+%28UAV%29%2C+while+sensors+integrated+into+an+IoT+platform+collected+data+on+ecological+factors+such+as+pH%2C+temperature%2C+solar+radiation%2C+relative+humidity%2C+soil+moisture%2C+wind+speed%2C+and+wind+direction.+Total+nitrogen+values+were+determined+by+collecting+leaf+tissue+samples%2C+which+were+then+sent+to+a+laboratory+for+the+corresponding+analyses.+Chlorophyll+content+was+measured+using+the+SPAD-502+plus+device.+For+the+implementation+of+machine+learning+models%2C+the+total+nitrogen+content+served+as+an+independent+variable.+The+predictor+variables+included+sensor+data%2C+SPAD+values%2C+and+statistical+information+generated+from+16+vegetation+indices+computed+from+multispectral+images.+To+reduce+the+dimensionality+of+the+predictor+variable+data+set%2C+the+Principal+Component+Analysis+%28PCA%29+was+applied.+After+dimensionality+reduction%2C+nine+regression+algorithms+were+used+to+estimate+the+leaf+nitrogen+content+in+each+of+the+four+study+periods.+The+results+indicated+that+the+MLP+and+XGB+regressor+algorithms+showed+the+best+performance+metrics.&mode=recommend-stem](https://journalfinder.elsevier.com/results?goldOpenAccess=true&subscription=true&elsevierOnly=true&sortBy=default&sortOrder=desc&query=Nitrogen+is+the+most+crucial+nutritional+element+during+the+vegetative+growth+stage+of+pineapple+cultivation.+In+this+study%2C+nine+machine+learning+techniques+were+validated+to+estimate+the+total+nitrogen+content+in+MD2+pineapple+crops%2C+using+multispectral+images%2C+crop-installed+sensors%2C+and+SPAD+values+representing+leaf+chlorophyll+content.+To+introduce+nitrogen+variability%2C+a+complete+randomized+block+experimental+design+was+implemented%2C+applying+five+different+treatments+in+five+blocks%2C+each+with+12+replications%2C+over+a+period+of+6+months+in+a+pineapple+crop+located+in+Tauramena%2C+Colombia.+Image+capture+was+carried+out+using+a+multispectral+camera+mounted+on+an+unmanned+aerial+vehicle+%28UAV%29%2C+while+sensors+integrated+into+an+IoT+platform+collected+data+on+ecological+factors+such+as+pH%2C+temperature%2C+solar+radiation%2C+relative+humidity%2C+soil+moisture%2C+wind+speed%2C+and+wind+direction.+Total+nitrogen+values+were+determined+by+collecting+leaf+tissue+samples%2C+which+were+then+sent+to+a+laboratory+for+the+corresponding+analyses.+Chlorophyll+content+was+measured+using+the+SPAD-502+plus+device.+For+the+implementation+of+machine+learning+models%2C+the+total+nitrogen+content+served+as+an+independent+variable.+The+predictor+variables+included+sensor+data%2C+SPAD+values%2C+and+statistical+information+generated+from+16+vegetation+indices+computed+from+multispectral+images.+To+reduce+the+dimensionality+of+the+predictor+variable+data+set%2C+the+Principal+Component+Analysis+%28PCA%29+was+applied.+After+dimensionality+reduction%2C+nine+regression+algorithms+were+used+to+estimate+the+leaf+nitrogen+content+in+each+of+the+four+study+periods.+The+results+indicated+that+the+MLP+and+XGB+regressor+algorithms+showed+the+best+performance+metrics.&mode=recommend-stem)
- Dominio: `journalfinder.elsevier.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `results-journal-finder`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: results-journal-finder
name: "Results | Journal Finder"
url: "https://journalfinder.elsevier.com/results?goldOpenAccess=true&subscription=true&elsevierOnly=true&sortBy=default&sortOrder=desc&query=Nitrogen+is+the+most+crucial+nutritional+element+during+the+vegetative+growth+stage+of+pineapple+cultivation.+In+this+study%2C+nine+machine+learning+techniques+were+validated+to+estimate+the+total+nitrogen+content+in+MD2+pineapple+crops%2C+using+multispectral+images%2C+crop-installed+sensors%2C+and+SPAD+values+representing+leaf+chlorophyll+content.+To+introduce+nitrogen+variability%2C+a+complete+randomized+block+experimental+design+was+implemented%2C+applying+five+different+treatments+in+five+blocks%2C+each+with+12+replications%2C+over+a+period+of+6+months+in+a+pineapple+crop+located+in+Tauramena%2C+Colombia.+Image+capture+was+carried+out+using+a+multispectral+camera+mounted+on+an+unmanned+aerial+vehicle+%28UAV%29%2C+while+sensors+integrated+into+an+IoT+platform+collected+data+on+ecological+factors+such+as+pH%2C+temperature%2C+solar+radiation%2C+relative+humidity%2C+soil+moisture%2C+wind+speed%2C+and+wind+direction.+Total+nitrogen+values+were+determined+by+collecting+leaf+tissue+samples%2C+which+were+then+sent+to+a+laboratory+for+the+corresponding+analyses.+Chlorophyll+content+was+measured+using+the+SPAD-502+plus+device.+For+the+implementation+of+machine+learning+models%2C+the+total+nitrogen+content+served+as+an+independent+variable.+The+predictor+variables+included+sensor+data%2C+SPAD+values%2C+and+statistical+information+generated+from+16+vegetation+indices+computed+from+multispectral+images.+To+reduce+the+dimensionality+of+the+predictor+variable+data+set%2C+the+Principal+Component+Analysis+%28PCA%29+was+applied.+After+dimensionality+reduction%2C+nine+regression+algorithms+were+used+to+estimate+the+leaf+nitrogen+content+in+each+of+the+four+study+periods.+The+results+indicated+that+the+MLP+and+XGB+regressor+algorithms+showed+the+best+performance+metrics.&mode=recommend-stem"
domain: "journalfinder.elsevier.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Machine Vision and Applications
- URL: [https://www.scimagojr.com/journalsearch.php?q=12984&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=12984&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `machine-vision-and-applications`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: machine-vision-and-applications
name: "Machine Vision and Applications"
url: "https://www.scimagojr.com/journalsearch.php?q=12984&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Neural Computing and Applications
- URL: [https://www.scimagojr.com/journalsearch.php?q=24800&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=24800&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `neural-computing-and-applications`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: neural-computing-and-applications
name: "Neural Computing and Applications"
url: "https://www.scimagojr.com/journalsearch.php?q=24800&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### IEEE Internet of Things Journal
- URL: [https://www.scimagojr.com/journalsearch.php?q=21100338350&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21100338350&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `ieee-internet-of-things-journal`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: ieee-internet-of-things-journal
name: "IEEE Internet of Things Journal"
url: "https://www.scimagojr.com/journalsearch.php?q=21100338350&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Circuits, Systems and Computers
- URL: [https://www.scimagojr.com/journalsearch.php?q=26046&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=26046&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `journal-of-circuits-systems-and-computers`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-circuits-systems-and-computers
name: "Journal of Circuits, Systems and Computers"
url: "https://www.scimagojr.com/journalsearch.php?q=26046&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Internet of Things | Journal | ScienceDirect.com by Elsevier
- URL: [https://www-sciencedirect-com.udea.lookproxy.com/journal/internet-of-things](https://www-sciencedirect-com.udea.lookproxy.com/journal/internet-of-things)
- Dominio: `www-sciencedirect-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `internet-of-things-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: internet-of-things-journal-sciencedirect-com-by-elsevier
name: "Internet of Things | Journal | ScienceDirect.com by Elsevier"
url: "https://www-sciencedirect-com.udea.lookproxy.com/journal/internet-of-things"
domain: "www-sciencedirect-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Microprocessors and Microsystems | Journal | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/microprocessors-and-microsystems](https://www.sciencedirect.com/journal/microprocessors-and-microsystems)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `microprocessors-and-microsystems-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: microprocessors-and-microsystems-journal-sciencedirect-com-by-elsevier
name: "Microprocessors and Microsystems | Journal | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/microprocessors-and-microsystems"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### GIScience & Remote Sensing | Taylor & Francis Online
- URL: [https://www.tandfonline.com/journals/tgrs20](https://www.tandfonline.com/journals/tgrs20)
- Dominio: `tandfonline.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `giscience-remote-sensing-taylor-francis-online`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: giscience-remote-sensing-taylor-francis-online
name: "GIScience & Remote Sensing | Taylor & Francis Online"
url: "https://www.tandfonline.com/journals/tgrs20"
domain: "tandfonline.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```

## Agronomía, plantas y cultivos
Se identificaron 11 recursos en este clúster temático a partir del archivo de marcadores exportado. La densidad de enlaces sugiere que este conjunto debe tratarse en FARO como una colección prioritaria para construir perfiles, reglas de enrutamiento editorial y sugerencias de revistas objetivo.[file:16]
### Online First - Journal of Agronomy
- URL: [https://scialert.net/onlinefirst.php?issn=1812-5379](https://scialert.net/onlinefirst.php?issn=1812-5379)
- Dominio: `scialert.net`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `online-first-journal-of-agronomy`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: online-first-journal-of-agronomy
name: "Online First - Journal of Agronomy"
url: "https://scialert.net/onlinefirst.php?issn=1812-5379"
domain: "scialert.net"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Plants
- URL: [https://www.mdpi.com/journal/plants/special_issues/3545QH7OLU/abstract](https://www.mdpi.com/journal/plants/special_issues/3545QH7OLU/abstract)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `plants`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: plants
name: "Plants"
url: "https://www.mdpi.com/journal/plants/special_issues/3545QH7OLU/abstract"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### MDPI | Manuscript Submission
- URL: [https://susy.mdpi.com/user/submit_manuscript/e663aa38f6543061570f7427aa351933/1?form%5Bspecial_issue_id%5D=248717&journal=plants](https://susy.mdpi.com/user/submit_manuscript/e663aa38f6543061570f7427aa351933/1?form%5Bspecial_issue_id%5D=248717&journal=plants)
- Dominio: `susy.mdpi.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `mdpi-manuscript-submission`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: mdpi-manuscript-submission
name: "MDPI | Manuscript Submission"
url: "https://susy.mdpi.com/user/submit_manuscript/e663aa38f6543061570f7427aa351933/1?form%5Bspecial_issue_id%5D=248717&journal=plants"
domain: "susy.mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Frontiers in Food Science and Technology
- URL: [https://www.frontiersin.org/journals/food-science-and-technology](https://www.frontiersin.org/journals/food-science-and-technology)
- Dominio: `frontiersin.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `frontiers-in-food-science-and-technology`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: frontiers-in-food-science-and-technology
name: "Frontiers in Food Science and Technology"
url: "https://www.frontiersin.org/journals/food-science-and-technology"
domain: "frontiersin.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Agronomy | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/agronomy](https://www.mdpi.com/journal/agronomy)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `agronomy-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: agronomy-an-open-access-journal-from-mdpi
name: "Agronomy | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/agronomy"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Horticulturae | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/horticulturae](https://www.mdpi.com/journal/horticulturae)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `horticulturae-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: horticulturae-an-open-access-journal-from-mdpi
name: "Horticulturae | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/horticulturae"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Agriculture and Food Research
- URL: [https://www.scimagojr.com/journalsearch.php?q=21101044948&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21101044948&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `journal-of-agriculture-and-food-research`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-agriculture-and-food-research
name: "Journal of Agriculture and Food Research"
url: "https://www.scimagojr.com/journalsearch.php?q=21101044948&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Plants | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/plants](https://www.mdpi.com/journal/plants)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `plants-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: plants-an-open-access-journal-from-mdpi
name: "Plants | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/plants"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Agronomy
- URL: [https://www.scimagojr.com/journalsearch.php?q=21100447811&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21100447811&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `agronomy`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: agronomy
name: "Agronomy"
url: "https://www.scimagojr.com/journalsearch.php?q=21100447811&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Molecules | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/molecules](https://www.mdpi.com/journal/molecules)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `molecules-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: molecules-an-open-access-journal-from-mdpi
name: "Molecules | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/molecules"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Frontiers in Plant Science
- URL: [https://www.frontiersin.org/journals/plant-science](https://www.frontiersin.org/journals/plant-science)
- Dominio: `frontiersin.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `frontiers-in-plant-science`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: frontiers-in-plant-science
name: "Frontiers in Plant Science"
url: "https://www.frontiersin.org/journals/plant-science"
domain: "frontiersin.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```

## Agua, riego y ambiente
Se identificaron 12 recursos en este clúster temático a partir del archivo de marcadores exportado. La densidad de enlaces sugiere que este conjunto debe tratarse en FARO como una colección prioritaria para construir perfiles, reglas de enrutamiento editorial y sugerencias de revistas objetivo.[file:16]
### CIAT | The International Center for Tropical Agriculture is a not-for-profit research and development organization dedicated to increase prosperity and improve human nutrition in the tropics through research-based solutions in agriculture and the environment
- URL: [https://ciat.cgiar.org/](https://ciat.cgiar.org/)
- Dominio: `ciat.cgiar.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `ciat-the-international-center-for-tropical-agriculture-is-a-not-for-profit-resea`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: ciat-the-international-center-for-tropical-agriculture-is-a-not-for-profit-resea
name: "CIAT | The International Center for Tropical Agriculture is a not-for-profit research and development organization dedicated to increase prosperity and improve human nutrition in the tropics through research-based solutions in agriculture and the environment"
url: "https://ciat.cgiar.org/"
domain: "ciat.cgiar.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### CropWat | Tierras y Aguas | Organización de las Naciones Unidas para la Alimentación y la Agricultura | Land & Water | Food and Agriculture Organization of the United Nations
- URL: [https://www.fao.org/land-water/databases-and-software/cropwat/es/](https://www.fao.org/land-water/databases-and-software/cropwat/es/)
- Dominio: `fao.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `cropwat-tierras-y-aguas-organizaci-n-de-las-naciones-unidas-para-la-alimentaci-n`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: cropwat-tierras-y-aguas-organizaci-n-de-las-naciones-unidas-para-la-alimentaci-n
name: "CropWat | Tierras y Aguas | Organización de las Naciones Unidas para la Alimentación y la Agricultura | Land & Water | Food and Agriculture Organization of the United Nations"
url: "https://www.fao.org/land-water/databases-and-software/cropwat/es/"
domain: "fao.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### UAV-based multispectral vegetation indices for assessing the interactive effects of water and nitrogen in irrigated horticultural crops production under tropical sub-humid conditions: A case of African eggplant - ScienceDirect
- URL: [https://www.sciencedirect.com/science/article/pii/S0378377422000634](https://www.sciencedirect.com/science/article/pii/S0378377422000634)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `uav-based-multispectral-vegetation-indices-for-assessing-the-interactive-effects`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: uav-based-multispectral-vegetation-indices-for-assessing-the-interactive-effects
name: "UAV-based multispectral vegetation indices for assessing the interactive effects of water and nitrogen in irrigated horticultural crops production under tropical sub-humid conditions: A case of African eggplant - ScienceDirect"
url: "https://www.sciencedirect.com/science/article/pii/S0378377422000634"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Multispectral Indices for Crop Water Stress Assessment and Precision Irrigation in Arid Agriculture: A Case Study from Béchar, Algeria | Inciteful.xyz
- URL: [https://inciteful.xyz/p/W4412930659](https://inciteful.xyz/p/W4412930659)
- Dominio: `inciteful.xyz`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `multispectral-indices-for-crop-water-stress-assessment-and-precision-irrigation-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: multispectral-indices-for-crop-water-stress-assessment-and-precision-irrigation-
name: "Multispectral Indices for Crop Water Stress Assessment and Precision Irrigation in Arid Agriculture: A Case Study from Béchar, Algeria | Inciteful.xyz"
url: "https://inciteful.xyz/p/W4412930659"
domain: "inciteful.xyz"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Water | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/water](https://www.mdpi.com/journal/water)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `water-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: water-an-open-access-journal-from-mdpi
name: "Water | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/water"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### MDPI | Manuscript Submission
- URL: [https://susy.mdpi.com/user/submit_manuscript/e663aa38f6543061570f7427aa351933/1?journal=water](https://susy.mdpi.com/user/submit_manuscript/e663aa38f6543061570f7427aa351933/1?journal=water)
- Dominio: `susy.mdpi.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `mdpi-manuscript-submission`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: mdpi-manuscript-submission
name: "MDPI | Manuscript Submission"
url: "https://susy.mdpi.com/user/submit_manuscript/e663aa38f6543061570f7427aa351933/1?journal=water"
domain: "susy.mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Environmental Sciences Proceedings | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/environsciproc](https://www.mdpi.com/journal/environsciproc)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `environmental-sciences-proceedings-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: environmental-sciences-proceedings-an-open-access-journal-from-mdpi
name: "Environmental Sciences Proceedings | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/environsciproc"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Files : Submission : Irrigation Science : springer.com
- URL: [https://submission.springernature.com/submission/1ef7b4b6-6354-467d-90ee-e4e2d23c25d0/upload-files](https://submission.springernature.com/submission/1ef7b4b6-6354-467d-90ee-e4e2d23c25d0/upload-files)
- Dominio: `submission.springernature.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `files-submission-irrigation-science-springer-com`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: files-submission-irrigation-science-springer-com
name: "Files : Submission : Irrigation Science : springer.com"
url: "https://submission.springernature.com/submission/1ef7b4b6-6354-467d-90ee-e4e2d23c25d0/upload-files"
domain: "submission.springernature.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Sustainability | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/sustainability](https://www.mdpi.com/journal/sustainability)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `sustainability-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: sustainability-an-open-access-journal-from-mdpi
name: "Sustainability | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/sustainability"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Atmosphere | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/atmosphere](https://www.mdpi.com/journal/atmosphere)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `atmosphere-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: atmosphere-an-open-access-journal-from-mdpi
name: "Atmosphere | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/atmosphere"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Ecological Modelling
- URL: [https://www.scimagojr.com/journalsearch.php?q=23274&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=23274&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `ecological-modelling`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: ecological-modelling
name: "Ecological Modelling"
url: "https://www.scimagojr.com/journalsearch.php?q=23274&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Multispectral Indices for Crop Water Stress Assessment and Precision Irrigation in Arid Agriculture: A Case Study from Béchar, Algeria | International Journal of Computational and Experimental Science and Engineering
- URL: [https://www.ijcesen.com/index.php/ijcesen/article/view/3414](https://www.ijcesen.com/index.php/ijcesen/article/view/3414)
- Dominio: `ijcesen.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `multispectral-indices-for-crop-water-stress-assessment-and-precision-irrigation-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: multispectral-indices-for-crop-water-stress-assessment-and-precision-irrigation-
name: "Multispectral Indices for Crop Water Stress Assessment and Precision Irrigation in Arid Agriculture: A Case Study from Béchar, Algeria | International Journal of Computational and Experimental Science and Engineering"
url: "https://www.ijcesen.com/index.php/ijcesen/article/view/3414"
domain: "ijcesen.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```

## Plataformas editoriales y apoyo a publicación
Se identificaron 17 recursos en este clúster temático a partir del archivo de marcadores exportado. La densidad de enlaces sugiere que este conjunto debe tratarse en FARO como una colección prioritaria para construir perfiles, reglas de enrutamiento editorial y sugerencias de revistas objetivo.[file:16]
### Editorial Manager®
- URL: [https://www.editorialmanager.com/jag/default2.aspx](https://www.editorialmanager.com/jag/default2.aspx)
- Dominio: `editorialmanager.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `editorial-manager`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: editorial-manager
name: "Editorial Manager®"
url: "https://www.editorialmanager.com/jag/default2.aspx"
domain: "editorialmanager.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Feedback: EquinOCS Springer Nature Submission System
- URL: [https://docs.google.com/forms/d/e/1FAIpQLSccjD4qnSCWtFVtahV5HC1g9QAUKUDutF82nf287HRirzCzXQ/viewform](https://docs.google.com/forms/d/e/1FAIpQLSccjD4qnSCWtFVtahV5HC1g9QAUKUDutF82nf287HRirzCzXQ/viewform)
- Dominio: `docs.google.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `feedback-equinocs-springer-nature-submission-system`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: feedback-equinocs-springer-nature-submission-system
name: "Feedback: EquinOCS Springer Nature Submission System"
url: "https://docs.google.com/forms/d/e/1FAIpQLSccjD4qnSCWtFVtahV5HC1g9QAUKUDutF82nf287HRirzCzXQ/viewform"
domain: "docs.google.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Instructions & Submissions – CVCRD
- URL: [https://www.cvc.uab.es/cvcrd/?page_id=7](https://www.cvc.uab.es/cvcrd/?page_id=7)
- Dominio: `cvc.uab.es`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `instructions-submissions-cvcrd`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: instructions-submissions-cvcrd
name: "Instructions & Submissions – CVCRD"
url: "https://www.cvc.uab.es/cvcrd/?page_id=7"
domain: "cvc.uab.es"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Editorial Manager®
- URL: [https://www2.cloud.editorialmanager.com/jafr/default2.aspx?pg=login.asp%3floginError%3d1%26username%3djorgechap123](https://www2.cloud.editorialmanager.com/jafr/default2.aspx?pg=login.asp%3floginError%3d1%26username%3djorgechap123)
- Dominio: `www2.cloud.editorialmanager.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `editorial-manager`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: editorial-manager
name: "Editorial Manager®"
url: "https://www2.cloud.editorialmanager.com/jafr/default2.aspx?pg=login.asp%3floginError%3d1%26username%3djorgechap123"
domain: "www2.cloud.editorialmanager.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Editorial Manager®
- URL: [https://www2.cloud.editorialmanager.com/jag/default2.aspx](https://www2.cloud.editorialmanager.com/jag/default2.aspx)
- Dominio: `www2.cloud.editorialmanager.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `editorial-manager`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: editorial-manager
name: "Editorial Manager®"
url: "https://www2.cloud.editorialmanager.com/jag/default2.aspx"
domain: "www2.cloud.editorialmanager.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Información para autores de artículos de revistas | Springer - Editorial internacional
- URL: [https://www-springer-com.udea.lookproxy.com/gp/authors-editors/journal-author](https://www-springer-com.udea.lookproxy.com/gp/authors-editors/journal-author)
- Dominio: `www-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `informaci-n-para-autores-de-art-culos-de-revistas-springer-editorial-internacion`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: informaci-n-para-autores-de-art-culos-de-revistas-springer-editorial-internacion
name: "Información para autores de artículos de revistas | Springer - Editorial internacional"
url: "https://www-springer-com.udea.lookproxy.com/gp/authors-editors/journal-author"
domain: "www-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Find a journal | Journal Finder
- URL: [https://journalfinder.elsevier.com/?dgcid=eman:jf-editor-insuff-imp_email](https://journalfinder.elsevier.com/?dgcid=eman:jf-editor-insuff-imp_email)
- Dominio: `journalfinder.elsevier.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `find-a-journal-journal-finder`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: find-a-journal-journal-finder
name: "Find a journal | Journal Finder"
url: "https://journalfinder.elsevier.com/?dgcid=eman:jf-editor-insuff-imp_email"
domain: "journalfinder.elsevier.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### js - For authors | Hindawi
- URL: [https://www.hindawi.com/journals/js/guidelines/](https://www.hindawi.com/journals/js/guidelines/)
- Dominio: `hindawi.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `js-for-authors-hindawi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: js-for-authors-hindawi
name: "js - For authors | Hindawi"
url: "https://www.hindawi.com/journals/js/guidelines/"
domain: "hindawi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### MDPI | Preparación de manuscritos en LaTeX
- URL: [https://www.mdpi.com/authors/latex](https://www.mdpi.com/authors/latex)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `mdpi-preparaci-n-de-manuscritos-en-latex`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: mdpi-preparaci-n-de-manuscritos-en-latex
name: "MDPI | Preparación de manuscritos en LaTeX"
url: "https://www.mdpi.com/authors/latex"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Editorial Manager®
- URL: [https://www.editorialmanager.com/wspc-jcsc/Default.aspx?pg=login.asp&username=](https://www.editorialmanager.com/wspc-jcsc/Default.aspx?pg=login.asp&username=)
- Dominio: `editorialmanager.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `editorial-manager`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: editorial-manager
name: "Editorial Manager®"
url: "https://www.editorialmanager.com/wspc-jcsc/Default.aspx?pg=login.asp&username="
domain: "editorialmanager.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### jfq - For authors | Hindawi
- URL: [https://www.hindawi.com/journals/jfq/guidelines/](https://www.hindawi.com/journals/jfq/guidelines/)
- Dominio: `hindawi.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `jfq-for-authors-hindawi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: jfq-for-authors-hindawi
name: "jfq - For authors | Hindawi"
url: "https://www.hindawi.com/journals/jfq/guidelines/"
domain: "hindawi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Article Type | Wiley Authors
- URL: [https://wiley.atyponrex.com/submission/qualifications/dae863c5-8f5a-49ce-893a-a2e2d7de50d2](https://wiley.atyponrex.com/submission/qualifications/dae863c5-8f5a-49ce-893a-a2e2d7de50d2)
- Dominio: `wiley.atyponrex.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `article-type-wiley-authors`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: article-type-wiley-authors
name: "Article Type | Wiley Authors"
url: "https://wiley.atyponrex.com/submission/qualifications/dae863c5-8f5a-49ce-893a-a2e2d7de50d2"
domain: "wiley.atyponrex.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Editorial Manager®
- URL: [https://www.editorialmanager.com/atech/default2.aspx](https://www.editorialmanager.com/atech/default2.aspx)
- Dominio: `editorialmanager.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `editorial-manager`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: editorial-manager
name: "Editorial Manager®"
url: "https://www.editorialmanager.com/atech/default2.aspx"
domain: "editorialmanager.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Editorial Manager®
- URL: [https://www.editorialmanager.com/aia/default2.aspx](https://www.editorialmanager.com/aia/default2.aspx)
- Dominio: `editorialmanager.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `editorial-manager`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: editorial-manager
name: "Editorial Manager®"
url: "https://www.editorialmanager.com/aia/default2.aspx"
domain: "editorialmanager.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Author Panel | IntechOpen
- URL: [https://publish.intechopen.com/s/author-panel?c__uiState=submitProposal&c__chapterId=a09Tc000001ZTEfIAO](https://publish.intechopen.com/s/author-panel?c__uiState=submitProposal&c__chapterId=a09Tc000001ZTEfIAO)
- Dominio: `publish.intechopen.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `author-panel-intechopen`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: author-panel-intechopen
name: "Author Panel | IntechOpen"
url: "https://publish.intechopen.com/s/author-panel?c__uiState=submitProposal&c__chapterId=a09Tc000001ZTEfIAO"
domain: "publish.intechopen.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Author Profile
- URL: [https://www.oajaiml.com/author/home](https://www.oajaiml.com/author/home)
- Dominio: `oajaiml.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `author-profile`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: author-profile
name: "Author Profile"
url: "https://www.oajaiml.com/author/home"
domain: "oajaiml.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Descripción general de la revisión de PeerJ
- URL: [https://peerj.com/submissions/117364/reviews/2065227/overview/](https://peerj.com/submissions/117364/reviews/2065227/overview/)
- Dominio: `peerj.com`.[file:16]
- Tipo estimado: plataforma editorial.[file:16]
- Identificador FARO sugerido: `descripci-n-general-de-la-revisi-n-de-peerj`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: descripci-n-general-de-la-revisi-n-de-peerj
name: "Descripción general de la revisión de PeerJ"
url: "https://peerj.com/submissions/117364/reviews/2065227/overview/"
domain: "peerj.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```

## Rankings y evaluación de revistas
Se identificaron 18 recursos en este clúster temático a partir del archivo de marcadores exportado. La densidad de enlaces sugiere que este conjunto debe tratarse en FARO como una colección prioritaria para construir perfiles, reglas de enrutamiento editorial y sugerencias de revistas objetivo.[file:16]
### ICIC Express Letters
- URL: [https://www.scimagojr.com/journalsearch.php?q=17300154986&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=17300154986&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `icic-express-letters`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: icic-express-letters
name: "ICIC Express Letters"
url: "https://www.scimagojr.com/journalsearch.php?q=17300154986&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Informacion Tecnologica
- URL: [https://www.scimagojr.com/journalsearch.php?q=22476&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=22476&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `informacion-tecnologica`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: informacion-tecnologica
name: "Informacion Tecnologica"
url: "https://www.scimagojr.com/journalsearch.php?q=22476&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of the Saudi Society of Agricultural Sciences
- URL: [https://www.scimagojr.com/journalsearch.php?q=21100817638&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21100817638&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `journal-of-the-saudi-society-of-agricultural-sciences`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-the-saudi-society-of-agricultural-sciences
name: "Journal of the Saudi Society of Agricultural Sciences"
url: "https://www.scimagojr.com/journalsearch.php?q=21100817638&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Global Food Security
- URL: [https://www.scimagojr.com/journalsearch.php?q=21100218328&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21100218328&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `global-food-security`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: global-food-security
name: "Global Food Security"
url: "https://www.scimagojr.com/journalsearch.php?q=21100218328&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Agriculture (Switzerland)
- URL: [https://www.scimagojr.com/journalsearch.php?q=21100781511&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21100781511&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `agriculture-switzerland`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: agriculture-switzerland
name: "Agriculture (Switzerland)"
url: "https://www.scimagojr.com/journalsearch.php?q=21100781511&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Sostenibilidad
- URL: [https://www.scimagojr.com/journalsearch.php?q=21100240100&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21100240100&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `sostenibilidad`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: sostenibilidad
name: "Sostenibilidad"
url: "https://www.scimagojr.com/journalsearch.php?q=21100240100&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Clasificaciones de revistas sobre ingeniería
- URL: [https://www.scimagojr.com/journalrank.php?area=2200](https://www.scimagojr.com/journalrank.php?area=2200)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `clasificaciones-de-revistas-sobre-ingenier-a`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: clasificaciones-de-revistas-sobre-ingenier-a
name: "Clasificaciones de revistas sobre ingeniería"
url: "https://www.scimagojr.com/journalrank.php?area=2200"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal Rankings on Computer Vision and Pattern Recognition
- URL: [https://www.scimagojr.com/journalrank.php?category=1707&area=1700&type=j](https://www.scimagojr.com/journalrank.php?category=1707&area=1700&type=j)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `journal-rankings-on-computer-vision-and-pattern-recognition`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-rankings-on-computer-vision-and-pattern-recognition
name: "Journal Rankings on Computer Vision and Pattern Recognition"
url: "https://www.scimagojr.com/journalrank.php?category=1707&area=1700&type=j"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Drones
- URL: [https://www.scimagojr.com/journalsearch.php?q=21101017244&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21101017244&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `drones`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: drones
name: "Drones"
url: "https://www.scimagojr.com/journalsearch.php?q=21101017244&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### SJR : Scientific Journal Rankings
- URL: [https://www.scimagojr.com/journalrank.php?country=ES](https://www.scimagojr.com/journalrank.php?country=ES)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `sjr-scientific-journal-rankings`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: sjr-scientific-journal-rankings
name: "SJR : Scientific Journal Rankings"
url: "https://www.scimagojr.com/journalrank.php?country=ES"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Expert Systems with Applications
- URL: [https://www.scimagojr.com/journalsearch.php?q=24201&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=24201&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `expert-systems-with-applications`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: expert-systems-with-applications
name: "Expert Systems with Applications"
url: "https://www.scimagojr.com/journalsearch.php?q=24201&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Theoretical and Applied Information Technology
- URL: [https://www.scimagojr.com/journalsearch.php?q=19700182903&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=19700182903&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `journal-of-theoretical-and-applied-information-technology`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-theoretical-and-applied-information-technology
name: "Journal of Theoretical and Applied Information Technology"
url: "https://www.scimagojr.com/journalsearch.php?q=19700182903&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Food Composition and Analysis
- URL: [https://www.scimagojr.com/journalsearch.php?q=20582&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=20582&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `journal-of-food-composition-and-analysis`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-food-composition-and-analysis
name: "Journal of Food Composition and Analysis"
url: "https://www.scimagojr.com/journalsearch.php?q=20582&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Infrastructure, Policy and Development
- URL: [https://www.scimagojr.com/journalsearch.php?q=21101052847&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21101052847&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `journal-of-infrastructure-policy-and-development`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-infrastructure-policy-and-development
name: "Journal of Infrastructure, Policy and Development"
url: "https://www.scimagojr.com/journalsearch.php?q=21101052847&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Avances en inteligencia artificial y aprendizaje automático
- URL: [https://www.scimagojr.com/journalsearch.php?q=21101164612&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21101164612&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `avances-en-inteligencia-artificial-y-aprendizaje-autom-tico`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: avances-en-inteligencia-artificial-y-aprendizaje-autom-tico
name: "Avances en inteligencia artificial y aprendizaje automático"
url: "https://www.scimagojr.com/journalsearch.php?q=21101164612&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Computers
- URL: [https://www.scimagojr.com/journalsearch.php?q=21100886391&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21100886391&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `computers`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: computers
name: "Computers"
url: "https://www.scimagojr.com/journalsearch.php?q=21100886391&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Management Analytics - Impact Factor, Indexing, Rank, and APC 2026 - AskBisht
- URL: [https://askbisht.com/journals/journal-of-management-analytics](https://askbisht.com/journals/journal-of-management-analytics)
- Dominio: `askbisht.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `journal-of-management-analytics-impact-factor-indexing-rank-and-apc-2026-askbish`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-management-analytics-impact-factor-indexing-rank-and-apc-2026-askbish
name: "Journal of Management Analytics - Impact Factor, Indexing, Rank, and APC 2026 - AskBisht"
url: "https://askbisht.com/journals/journal-of-management-analytics"
domain: "askbisht.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Intelligent Systems with Applications
- URL: [https://www.scimagojr.com/journalsearch.php?q=21101051831&tip=sid&clean=0](https://www.scimagojr.com/journalsearch.php?q=21101051831&tip=sid&clean=0)
- Dominio: `scimagojr.com`.[file:16]
- Tipo estimado: fuente de ranking.[file:16]
- Identificador FARO sugerido: `intelligent-systems-with-applications`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: intelligent-systems-with-applications
name: "Intelligent Systems with Applications"
url: "https://www.scimagojr.com/journalsearch.php?q=21101051831&tip=sid&clean=0"
domain: "scimagojr.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```

## Otras revistas científicas relevantes
Se identificaron 77 recursos en este clúster temático a partir del archivo de marcadores exportado. La densidad de enlaces sugiere que este conjunto debe tratarse en FARO como una colección prioritaria para construir perfiles, reglas de enrutamiento editorial y sugerencias de revistas objetivo.[file:16]
### Home - Springer
- URL: [https://link.springer.com/](https://link.springer.com/)
- Dominio: `link.springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `home-springer`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: home-springer
name: "Home - Springer"
url: "https://link.springer.com/"
domain: "link.springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Sign In / Sign Up
- URL: [https://www.mdpi.com/user/login](https://www.mdpi.com/user/login)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `sign-in-sign-up`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: sign-in-sign-up
name: "Sign In / Sign Up"
url: "https://www.mdpi.com/user/login"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### ERIC - Search Results
- URL: [https://eric.ed.gov/?q=Methods+to+measure+the+amount+of+nitrogen+in+fruit+crops](https://eric.ed.gov/?q=Methods+to+measure+the+amount+of+nitrogen+in+fruit+crops)
- Dominio: `eric.ed.gov`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `eric-search-results`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: eric-search-results
name: "ERIC - Search Results"
url: "https://eric.ed.gov/?q=Methods+to+measure+the+amount+of+nitrogen+in+fruit+crops"
domain: "eric.ed.gov"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### THE ELECTRONIC JOURNAL OF INFORMATION SYSTEMS IN DEVELOPING COUNTRIES - Wiley Online Library
- URL: [https://onlinelibrary.wiley.com/journal/16814835](https://onlinelibrary.wiley.com/journal/16814835)
- Dominio: `onlinelibrary.wiley.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `the-electronic-journal-of-information-systems-in-developing-countries-wiley-onli`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: the-electronic-journal-of-information-systems-in-developing-countries-wiley-onli
name: "THE ELECTRONIC JOURNAL OF INFORMATION SYSTEMS IN DEVELOPING COUNTRIES - Wiley Online Library"
url: "https://onlinelibrary.wiley.com/journal/16814835"
domain: "onlinelibrary.wiley.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Predicción del rendimiento de cultivos y uso eficiente de fertilizantes | Académico semántico
- URL: [https://www.semanticscholar.org/paper/Crop-Yield-Prediction-and-Efficient-use-of-Bhanumathi-Vineeth/886b0a079dfece29bf4c27afe05741357c543e13](https://www.semanticscholar.org/paper/Crop-Yield-Prediction-and-Efficient-use-of-Bhanumathi-Vineeth/886b0a079dfece29bf4c27afe05741357c543e13)
- Dominio: `semanticscholar.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `predicci-n-del-rendimiento-de-cultivos-y-uso-eficiente-de-fertilizantes-acad-mic`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: predicci-n-del-rendimiento-de-cultivos-y-uso-eficiente-de-fertilizantes-acad-mic
name: "Predicción del rendimiento de cultivos y uso eficiente de fertilizantes | Académico semántico"
url: "https://www.semanticscholar.org/paper/Crop-Yield-Prediction-and-Efficient-use-of-Bhanumathi-Vineeth/886b0a079dfece29bf4c27afe05741357c543e13"
domain: "semanticscholar.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Hyperspectral Imaging for Agriculture - EE Times Europe
- URL: [https://www.eetimes.eu/hyperspectral-imaging-for-agriculture/](https://www.eetimes.eu/hyperspectral-imaging-for-agriculture/)
- Dominio: `eetimes.eu`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `hyperspectral-imaging-for-agriculture-ee-times-europe`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: hyperspectral-imaging-for-agriculture-ee-times-europe
name: "Hyperspectral Imaging for Agriculture - EE Times Europe"
url: "https://www.eetimes.eu/hyperspectral-imaging-for-agriculture/"
domain: "eetimes.eu"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Segmentación tisular automática de imágenes hiperespectrales en cirugías de hígado y cabeza y cuello mediante aprendizaje automático
- URL: [https://aisjournal.net/article/view/4291](https://aisjournal.net/article/view/4291)
- Dominio: `aisjournal.net`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `segmentaci-n-tisular-autom-tica-de-im-genes-hiperespectrales-en-cirug-as-de-h-ga`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: segmentaci-n-tisular-autom-tica-de-im-genes-hiperespectrales-en-cirug-as-de-h-ga
name: "Segmentación tisular automática de imágenes hiperespectrales en cirugías de hígado y cabeza y cuello mediante aprendizaje automático"
url: "https://aisjournal.net/article/view/4291"
domain: "aisjournal.net"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Procesamiento paralelo de Python para simulación de imágenes hiperespectrales: basado en funciones de distancia | SpringerLink
- URL: [https://aplicacionesbiblioteca.udea.edu.co:2430/article/10.1007/s12145-021-00690-7](https://aplicacionesbiblioteca.udea.edu.co:2430/article/10.1007/s12145-021-00690-7)
- Dominio: `aplicacionesbiblioteca.udea.edu.co:2430`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `procesamiento-paralelo-de-python-para-simulaci-n-de-im-genes-hiperespectrales-ba`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: procesamiento-paralelo-de-python-para-simulaci-n-de-im-genes-hiperespectrales-ba
name: "Procesamiento paralelo de Python para simulación de imágenes hiperespectrales: basado en funciones de distancia | SpringerLink"
url: "https://aplicacionesbiblioteca.udea.edu.co:2430/article/10.1007/s12145-021-00690-7"
domain: "aplicacionesbiblioteca.udea.edu.co:2430"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Convolutional Neural Networks | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-5364-9_6](https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-5364-9_6)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `convolutional-neural-networks-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: convolutional-neural-networks-springerlink
name: "Convolutional Neural Networks | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-5364-9_6"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Image Analysis and Processing – ICIAP 2022 | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-06430-2](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-06430-2)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `image-analysis-and-processing-iciap-2022-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: image-analysis-and-processing-iciap-2022-springerlink
name: "Image Analysis and Processing – ICIAP 2022 | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-06430-2"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Computer Vision and Image Processing | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-11349-9](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-11349-9)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `computer-vision-and-image-processing-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: computer-vision-and-image-processing-springerlink
name: "Computer Vision and Image Processing | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-11349-9"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Search Results - Springer
- URL: [https://link-springer-com.udea.lookproxy.com/search/page/3?query=%22computer+vision%22+in+python&facet-content-type=%22Book%22](https://link-springer-com.udea.lookproxy.com/search/page/3?query=%22computer+vision%22+in+python&facet-content-type=%22Book%22)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `search-results-springer`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: search-results-springer
name: "Search Results - Springer"
url: "https://link-springer-com.udea.lookproxy.com/search/page/3?query=%22computer+vision%22+in+python&facet-content-type=%22Book%22"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Programming with TensorFlow | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-030-57077-4](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-030-57077-4)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `programming-with-tensorflow-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: programming-with-tensorflow-springerlink
name: "Programming with TensorFlow | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-030-57077-4"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Medical Image Understanding and Analysis | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-12053-4](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-12053-4)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `medical-image-understanding-and-analysis-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: medical-image-understanding-and-analysis-springerlink
name: "Medical Image Understanding and Analysis | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-12053-4"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Image Classification | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-8273-1_2](https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-8273-1_2)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `image-classification-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: image-classification-springerlink
name: "Image Classification | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-8273-1_2"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### https://link-springer-com.udea.lookproxy.com/content/pdf/10.1007/978-1-4842-3913-1.pdf
- URL: [https://link-springer-com.udea.lookproxy.com/content/pdf/10.1007/978-1-4842-3913-1.pdf](https://link-springer-com.udea.lookproxy.com/content/pdf/10.1007/978-1-4842-3913-1.pdf)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `https-link-springer-com-udea-lookproxy-com-content-pdf-10-1007-978-1-4842-3913-1`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: https-link-springer-com-udea-lookproxy-com-content-pdf-10-1007-978-1-4842-3913-1
name: "https://link-springer-com.udea.lookproxy.com/content/pdf/10.1007/978-1-4842-3913-1.pdf"
url: "https://link-springer-com.udea.lookproxy.com/content/pdf/10.1007/978-1-4842-3913-1.pdf"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Computer Vision Using Deep Learning | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-6616-8](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-6616-8)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `computer-vision-using-deep-learning-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: computer-vision-using-deep-learning-springerlink
name: "Computer Vision Using Deep Learning | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-6616-8"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Hindawi Revista Para Publicar
- URL: [https://review.hindawi.com/submit/3c776e52-9aab-4720-bc23-851e00cb4bf9/43d23346-81e4-44b3-b9f3-60f699f63ad3](https://review.hindawi.com/submit/3c776e52-9aab-4720-bc23-851e00cb4bf9/43d23346-81e4-44b3-b9f3-60f699f63ad3)
- Dominio: `review.hindawi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `hindawi-revista-para-publicar`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: hindawi-revista-para-publicar
name: "Hindawi Revista Para Publicar"
url: "https://review.hindawi.com/submit/3c776e52-9aab-4720-bc23-851e00cb4bf9/43d23346-81e4-44b3-b9f3-60f699f63ad3"
domain: "review.hindawi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Applied Sciences | Free Full-Text | Fusion Network for Change Detection of High-Resolution Panchromatic Imagery
- URL: [https://www.mdpi.com/2076-3417/9/7/1441](https://www.mdpi.com/2076-3417/9/7/1441)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `applied-sciences-free-full-text-fusion-network-for-change-detection-of-high-reso`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: applied-sciences-free-full-text-fusion-network-for-change-detection-of-high-reso
name: "Applied Sciences | Free Full-Text | Fusion Network for Change Detection of High-Resolution Panchromatic Imagery"
url: "https://www.mdpi.com/2076-3417/9/7/1441"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Sistema de procesamiento de imágenes aéreas multiespectrales para agricultura de precisión
- URL: [https://www.redalyc.org/journal/4115/411557165003/html/](https://www.redalyc.org/journal/4115/411557165003/html/)
- Dominio: `redalyc.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `sistema-de-procesamiento-de-im-genes-a-reas-multiespectrales-para-agricultura-de`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: sistema-de-procesamiento-de-im-genes-a-reas-multiespectrales-para-agricultura-de
name: "Sistema de procesamiento de imágenes aéreas multiespectrales para agricultura de precisión"
url: "https://www.redalyc.org/journal/4115/411557165003/html/"
domain: "redalyc.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Performance Analysis of Smart Farming System Based on IoT | Journal of Telecommunication, Electronic and Computer Engineering (JTEC)
- URL: [https://jtec.utem.edu.my/jtec/article/view/6127](https://jtec.utem.edu.my/jtec/article/view/6127)
- Dominio: `jtec.utem.edu.my`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `performance-analysis-of-smart-farming-system-based-on-iot-journal-of-telecommuni`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: performance-analysis-of-smart-farming-system-based-on-iot-journal-of-telecommuni
name: "Performance Analysis of Smart Farming System Based on IoT | Journal of Telecommunication, Electronic and Computer Engineering (JTEC)"
url: "https://jtec.utem.edu.my/jtec/article/view/6127"
domain: "jtec.utem.edu.my"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Theories and Methods for Spectroscopy-Based Crop Nutrient Sensing | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-3-030-70432-2_5](https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-3-030-70432-2_5)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `theories-and-methods-for-spectroscopy-based-crop-nutrient-sensing-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: theories-and-methods-for-spectroscopy-based-crop-nutrient-sensing-springerlink
name: "Theories and Methods for Spectroscopy-Based Crop Nutrient Sensing | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-3-030-70432-2_5"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Detección de suelos y cultivos para la producción de cultivos de precisión | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-030-70432-2](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-030-70432-2)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `detecci-n-de-suelos-y-cultivos-para-la-producci-n-de-cultivos-de-precisi-n-sprin`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: detecci-n-de-suelos-y-cultivos-para-la-producci-n-de-cultivos-de-precisi-n-sprin
name: "Detección de suelos y cultivos para la producción de cultivos de precisión | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-030-70432-2"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Técnicas de aprendizaje profundo para clasificar cultivos agrícolas mediante imágenes de vehículos aéreos no tripulados: una revisión | Computación neuronal y aplicaciones
- URL: [https://link.springer.com/article/10.1007/s00521-022-07104-9#Tab3](https://link.springer.com/article/10.1007/s00521-022-07104-9#Tab3)
- Dominio: `link.springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `t-cnicas-de-aprendizaje-profundo-para-clasificar-cultivos-agr-colas-mediante-im-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: t-cnicas-de-aprendizaje-profundo-para-clasificar-cultivos-agr-colas-mediante-im-
name: "Técnicas de aprendizaje profundo para clasificar cultivos agrícolas mediante imágenes de vehículos aéreos no tripulados: una revisión | Computación neuronal y aplicaciones"
url: "https://link.springer.com/article/10.1007/s00521-022-07104-9#Tab3"
domain: "link.springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Machine learning in nutrient management: A review - ScienceDirect
- URL: [https://www.sciencedirect.com/science/article/pii/S258972172300017X?via%3Dihub](https://www.sciencedirect.com/science/article/pii/S258972172300017X?via%3Dihub)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `machine-learning-in-nutrient-management-a-review-sciencedirect`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: machine-learning-in-nutrient-management-a-review-sciencedirect
name: "Machine learning in nutrient management: A review - ScienceDirect"
url: "https://www.sciencedirect.com/science/article/pii/S258972172300017X?via%3Dihub"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Combinando índices de vegetación, color y textura con parámetros hiperespectrales mediante métodos de aprendizaje automático para estimar la concentración de nitrógeno en tallos y hojas de arroz - ScienceDirect
- URL: [https://www-sciencedirect-com.udea.lookproxy.com/science/article/pii/S0378429023003684](https://www-sciencedirect-com.udea.lookproxy.com/science/article/pii/S0378429023003684)
- Dominio: `www-sciencedirect-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `combinando-ndices-de-vegetaci-n-color-y-textura-con-par-metros-hiperespectrales-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: combinando-ndices-de-vegetaci-n-color-y-textura-con-par-metros-hiperespectrales-
name: "Combinando índices de vegetación, color y textura con parámetros hiperespectrales mediante métodos de aprendizaje automático para estimar la concentración de nitrógeno en tallos y hojas de arroz - ScienceDirect"
url: "https://www-sciencedirect-com.udea.lookproxy.com/science/article/pii/S0378429023003684"
domain: "www-sciencedirect-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Agricultura | Texto completo gratuito | Una revisión de las técnicas de aprendizaje automático en estudios agroclimáticos
- URL: [https://www.mdpi.com/2077-0472/14/3/481](https://www.mdpi.com/2077-0472/14/3/481)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `agricultura-texto-completo-gratuito-una-revisi-n-de-las-t-cnicas-de-aprendizaje-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: agricultura-texto-completo-gratuito-una-revisi-n-de-las-t-cnicas-de-aprendizaje-
name: "Agricultura | Texto completo gratuito | Una revisión de las técnicas de aprendizaje automático en estudios agroclimáticos"
url: "https://www.mdpi.com/2077-0472/14/3/481"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Un aprendizaje de transferencia conjunto para la identificación de deficiencias de nutrientes y la predicción de pérdidas de rendimiento en cultivos | Herramientas y aplicaciones multimedia
- URL: [https://link-springer-com.udea.lookproxy.com/article/10.1007/s11042-024-18592-3](https://link-springer-com.udea.lookproxy.com/article/10.1007/s11042-024-18592-3)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `un-aprendizaje-de-transferencia-conjunto-para-la-identificaci-n-de-deficiencias-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: un-aprendizaje-de-transferencia-conjunto-para-la-identificaci-n-de-deficiencias-
name: "Un aprendizaje de transferencia conjunto para la identificación de deficiencias de nutrientes y la predicción de pérdidas de rendimiento en cultivos | Herramientas y aplicaciones multimedia"
url: "https://link-springer-com.udea.lookproxy.com/article/10.1007/s11042-024-18592-3"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Sci-Hub journal:latest sci-hub mirror links
- URL: [https://sci-hub.wf/](https://sci-hub.wf/)
- Dominio: `sci-hub.wf`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `sci-hub-journal-latest-sci-hub-mirror-links`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: sci-hub-journal-latest-sci-hub-mirror-links
name: "Sci-Hub journal:latest sci-hub mirror links"
url: "https://sci-hub.wf/"
domain: "sci-hub.wf"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### EquinOCS
- URL: [https://equinocs.springernature.com/home](https://equinocs.springernature.com/home)
- Dominio: `equinocs.springernature.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `equinocs`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: equinocs
name: "EquinOCS"
url: "https://equinocs.springernature.com/home"
domain: "equinocs.springernature.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### EquinOCS : Springer Nature Support
- URL: [https://support.springernature.com/en/support/solutions/folders/6000239310](https://support.springernature.com/en/support/solutions/folders/6000239310)
- Dominio: `support.springernature.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `equinocs-springer-nature-support`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: equinocs-springer-nature-support
name: "EquinOCS : Springer Nature Support"
url: "https://support.springernature.com/en/support/solutions/folders/6000239310"
domain: "support.springernature.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Deep learning implementation of image segmentation in agricultural applications: a comprehensive review | Artificial Intelligence Review
- URL: [https://link.springer.com/article/10.1007/s10462-024-10775-6](https://link.springer.com/article/10.1007/s10462-024-10775-6)
- Dominio: `link.springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `deep-learning-implementation-of-image-segmentation-in-agricultural-applications-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: deep-learning-implementation-of-image-segmentation-in-agricultural-applications-
name: "Deep learning implementation of image segmentation in agricultural applications: a comprehensive review | Artificial Intelligence Review"
url: "https://link.springer.com/article/10.1007/s10462-024-10775-6"
domain: "link.springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### GitHub - Cybonic/MISAgriculture
- URL: [https://github.com/Cybonic/MISAgriculture](https://github.com/Cybonic/MISAgriculture)
- Dominio: `github.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `github-cybonic-misagriculture`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: github-cybonic-misagriculture
name: "GitHub - Cybonic/MISAgriculture"
url: "https://github.com/Cybonic/MISAgriculture"
domain: "github.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Artificial Intelligence and Cognitive Science: 30th Irish Conference, AICS 2022, Munster, Ireland, December 8–9, 2022, Revised Selected Papers | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-26438-2](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-26438-2)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `artificial-intelligence-and-cognitive-science-30th-irish-conference-aics-2022-mu`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: artificial-intelligence-and-cognitive-science-30th-irish-conference-aics-2022-mu
name: "Artificial Intelligence and Cognitive Science: 30th Irish Conference, AICS 2022, Munster, Ireland, December 8–9, 2022, Revised Selected Papers | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-26438-2"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Hands-on Machine Learning with Python: Implement Neural Network Solutions with Scikit-learn and PyTorch | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-7921-2](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-7921-2)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `hands-on-machine-learning-with-python-implement-neural-network-solutions-with-sc`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: hands-on-machine-learning-with-python-implement-neural-network-solutions-with-sc
name: "Hands-on Machine Learning with Python: Implement Neural Network Solutions with Scikit-learn and PyTorch | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-7921-2"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Modelos básicos para el procesamiento del lenguaje natural: modelos de lenguaje previamente entrenados que integran medios | SpringerEnlace
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-23190-2](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-23190-2)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `modelos-b-sicos-para-el-procesamiento-del-lenguaje-natural-modelos-de-lenguaje-p`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: modelos-b-sicos-para-el-procesamiento-del-lenguaje-natural-modelos-de-lenguaje-p
name: "Modelos básicos para el procesamiento del lenguaje natural: modelos de lenguaje previamente entrenados que integran medios | SpringerEnlace"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-23190-2"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Aprendizaje profundo aplicado con TensorFlow 2: aprenda a implementar técnicas avanzadas de aprendizaje profundo con Python | SpringerEnlace
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-8020-1](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-8020-1)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `aprendizaje-profundo-aplicado-con-tensorflow-2-aprenda-a-implementar-t-cnicas-av`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: aprendizaje-profundo-aplicado-con-tensorflow-2-aprenda-a-implementar-t-cnicas-av
name: "Aprendizaje profundo aplicado con TensorFlow 2: aprenda a implementar técnicas avanzadas de aprendizaje profundo con Python | SpringerEnlace"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-8020-1"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Classification and Data Science in the Digital Age | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-09034-9](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-09034-9)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `classification-and-data-science-in-the-digital-age-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: classification-and-data-science-in-the-digital-age-springerlink
name: "Classification and Data Science in the Digital Age | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-3-031-09034-9"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Convolutional Neural Networks | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-7921-2_14](https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-7921-2_14)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `convolutional-neural-networks-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: convolutional-neural-networks-springerlink
name: "Convolutional Neural Networks | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-7921-2_14"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Redes neuronales convolucionales | SpringerEnlace
- URL: [https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-8020-1_7](https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-8020-1_7)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `redes-neuronales-convolucionales-springerenlace`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: redes-neuronales-convolucionales-springerenlace
name: "Redes neuronales convolucionales | SpringerEnlace"
url: "https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-1-4842-8020-1_7"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Artificial Intelligence Technology | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-19-2879-6](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-19-2879-6)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `artificial-intelligence-technology-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: artificial-intelligence-technology-springerlink
name: "Artificial Intelligence Technology | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-19-2879-6"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Human Centered Implementation Process of AI in SMEs – Conditions for Success | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-3-658-43705-3_7](https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-3-658-43705-3_7)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `human-centered-implementation-process-of-ai-in-smes-conditions-for-success-sprin`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: human-centered-implementation-process-of-ai-in-smes-conditions-for-success-sprin
name: "Human Centered Implementation Process of AI in SMEs – Conditions for Success | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/chapter/10.1007/978-3-658-43705-3_7"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Inteligencia artificial con Python | SpringerEnlace
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-16-8615-3](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-16-8615-3)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `inteligencia-artificial-con-python-springerenlace`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: inteligencia-artificial-con-python-springerenlace
name: "Inteligencia artificial con Python | SpringerEnlace"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-16-8615-3"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Deep Reinforcement Learning | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-19-0638-1](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-19-0638-1)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `deep-reinforcement-learning-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: deep-reinforcement-learning-springerlink
name: "Deep Reinforcement Learning | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-981-19-0638-1"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### IA práctica y explicable usando Python: explicaciones del modelo de inteligencia artificial usando bibliotecas, extensiones y marcos basados ​​en Python | SpringerEnlace
- URL: [https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-7158-2](https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-7158-2)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `ia-pr-ctica-y-explicable-usando-python-explicaciones-del-modelo-de-inteligencia-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: ia-pr-ctica-y-explicable-usando-python-explicaciones-del-modelo-de-inteligencia-
name: "IA práctica y explicable usando Python: explicaciones del modelo de inteligencia artificial usando bibliotecas, extensiones y marcos basados ​​en Python | SpringerEnlace"
url: "https://link-springer-com.udea.lookproxy.com/book/10.1007/978-1-4842-7158-2"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Search Results - Springer
- URL: [https://link-springer-com.udea.lookproxy.com/search/page/2?facet-content-type=%22Book%22&sortOrder=newestFirst&showAll=false&query=neural+network+in+python&facet-sub-discipline=%22Artificial+Intelligence%22&facet-discipline=%22Computer+Science%22](https://link-springer-com.udea.lookproxy.com/search/page/2?facet-content-type=%22Book%22&sortOrder=newestFirst&showAll=false&query=neural+network+in+python&facet-sub-discipline=%22Artificial+Intelligence%22&facet-discipline=%22Computer+Science%22)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `search-results-springer`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: search-results-springer
name: "Search Results - Springer"
url: "https://link-springer-com.udea.lookproxy.com/search/page/2?facet-content-type=%22Book%22&sortOrder=newestFirst&showAll=false&query=neural+network+in+python&facet-sub-discipline=%22Artificial+Intelligence%22&facet-discipline=%22Computer+Science%22"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Un conjunto de imágenes multiespectrales de vehículos aéreos no tripulados adquiridas sobre un campo para identificar los requisitos de nitrógeno - ScienceDirect
- URL: [https://www.sciencedirect.com/science/article/pii/S2352340924004487](https://www.sciencedirect.com/science/article/pii/S2352340924004487)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `un-conjunto-de-im-genes-multiespectrales-de-veh-culos-a-reos-no-tripulados-adqui`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: un-conjunto-de-im-genes-multiespectrales-de-veh-culos-a-reos-no-tripulados-adqui
name: "Un conjunto de imágenes multiespectrales de vehículos aéreos no tripulados adquiridas sobre un campo para identificar los requisitos de nitrógeno - ScienceDirect"
url: "https://www.sciencedirect.com/science/article/pii/S2352340924004487"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### agriculture 4.0 - Search | ScienceDirect.com
- URL: [https://www.sciencedirect.com/search?qs=agriculture%204.0&years=2024%2C2025&lastSelectedFacet=years](https://www.sciencedirect.com/search?qs=agriculture%204.0&years=2024%2C2025&lastSelectedFacet=years)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `agriculture-4-0-search-sciencedirect-com`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: agriculture-4-0-search-sciencedirect-com
name: "agriculture 4.0 - Search | ScienceDirect.com"
url: "https://www.sciencedirect.com/search?qs=agriculture%204.0&years=2024%2C2025&lastSelectedFacet=years"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### CESFRA - Investigador Postdoctoral en Sistemas de Cultivo utilizando Teledetección y Modelos de Cultivo - Puestos Académicos
- URL: [https://academicpositions.com/ad/mohammed-vi-polytechnic-university/2024/cesfra-postdoctoral-researcher-in-cropping-systems-using-remote-sensing-and-crop-models/221220](https://academicpositions.com/ad/mohammed-vi-polytechnic-university/2024/cesfra-postdoctoral-researcher-in-cropping-systems-using-remote-sensing-and-crop-models/221220)
- Dominio: `academicpositions.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `cesfra-investigador-postdoctoral-en-sistemas-de-cultivo-utilizando-teledetecci-n`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: cesfra-investigador-postdoctoral-en-sistemas-de-cultivo-utilizando-teledetecci-n
name: "CESFRA - Investigador Postdoctoral en Sistemas de Cultivo utilizando Teledetección y Modelos de Cultivo - Puestos Académicos"
url: "https://academicpositions.com/ad/mohammed-vi-polytechnic-university/2024/cesfra-postdoctoral-researcher-in-cropping-systems-using-remote-sensing-and-crop-models/221220"
domain: "academicpositions.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Cartas sobre agricultura y medio ambiente - Biblioteca en línea de Wiley
- URL: [https://acsess.onlinelibrary.wiley.com/journal/24719625](https://acsess.onlinelibrary.wiley.com/journal/24719625)
- Dominio: `acsess.onlinelibrary.wiley.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `cartas-sobre-agricultura-y-medio-ambiente-biblioteca-en-l-nea-de-wiley`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: cartas-sobre-agricultura-y-medio-ambiente-biblioteca-en-l-nea-de-wiley
name: "Cartas sobre agricultura y medio ambiente - Biblioteca en línea de Wiley"
url: "https://acsess.onlinelibrary.wiley.com/journal/24719625"
domain: "acsess.onlinelibrary.wiley.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Insights - Scientific African | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/scientific-african/about/insights](https://www.sciencedirect.com/journal/scientific-african/about/insights)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `insights-scientific-african-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: insights-scientific-african-sciencedirect-com-by-elsevier
name: "Insights - Scientific African | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/scientific-african/about/insights"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### js - About this journal | Hindawi
- URL: [https://www.hindawi.com/journals/js/about/](https://www.hindawi.com/journals/js/about/)
- Dominio: `hindawi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `js-about-this-journal-hindawi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: js-about-this-journal-hindawi
name: "js - About this journal | Hindawi"
url: "https://www.hindawi.com/journals/js/about/"
domain: "hindawi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Ciencia del riego | Cómo publicar con nosotros
- URL: [https://www.springer.com/journal/271/how-to-publish-with-us](https://www.springer.com/journal/271/how-to-publish-with-us)
- Dominio: `springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `ciencia-del-riego-c-mo-publicar-con-nosotros`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: ciencia-del-riego-c-mo-publicar-con-nosotros
name: "Ciencia del riego | Cómo publicar con nosotros"
url: "https://www.springer.com/journal/271/how-to-publish-with-us"
domain: "springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Ciencia del riego | Hogar
- URL: [https://www.springer.com/journal/271](https://www.springer.com/journal/271)
- Dominio: `springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `ciencia-del-riego-hogar`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: ciencia-del-riego-hogar
name: "Ciencia del riego | Hogar"
url: "https://www.springer.com/journal/271"
domain: "springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Multispectral images, IoT data to estimate foliar nitrogen in Pineapple crops - Mendeley Data
- URL: [https://data.mendeley.com/drafts/94pxtywr6x](https://data.mendeley.com/drafts/94pxtywr6x)
- Dominio: `data.mendeley.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `multispectral-images-iot-data-to-estimate-foliar-nitrogen-in-pineapple-crops-men`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: multispectral-images-iot-data-to-estimate-foliar-nitrogen-in-pineapple-crops-men
name: "Multispectral images, IoT data to estimate foliar nitrogen in Pineapple crops - Mendeley Data"
url: "https://data.mendeley.com/drafts/94pxtywr6x"
domain: "data.mendeley.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Procesamiento de información en agricultura | Diario | ScienceDirect.com por Elsevier
- URL: [https://www.sciencedirect.com/journal/information-processing-in-agriculture](https://www.sciencedirect.com/journal/information-processing-in-agriculture)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `procesamiento-de-informaci-n-en-agricultura-diario-sciencedirect-com-por-elsevie`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: procesamiento-de-informaci-n-en-agricultura-diario-sciencedirect-com-por-elsevie
name: "Procesamiento de información en agricultura | Diario | ScienceDirect.com por Elsevier"
url: "https://www.sciencedirect.com/journal/information-processing-in-agriculture"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Revista de Investigación Agrícola y Alimentaria | ScienceDirect.com por Elsevier
- URL: [https://www.sciencedirect.com/journal/journal-of-agriculture-and-food-research](https://www.sciencedirect.com/journal/journal-of-agriculture-and-food-research)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `revista-de-investigaci-n-agr-cola-y-alimentaria-sciencedirect-com-por-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: revista-de-investigaci-n-agr-cola-y-alimentaria-sciencedirect-com-por-elsevier
name: "Revista de Investigación Agrícola y Alimentaria | ScienceDirect.com por Elsevier"
url: "https://www.sciencedirect.com/journal/journal-of-agriculture-and-food-research"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### A GAN–SVR Prediction Method of the Metal Tube-Bending Rebound with Small Samples
- URL: [https://www.hindawi.com/journals/js/2023/6616607/](https://www.hindawi.com/journals/js/2023/6616607/)
- Dominio: `hindawi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `a-gan-svr-prediction-method-of-the-metal-tube-bending-rebound-with-small-samples`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: a-gan-svr-prediction-method-of-the-metal-tube-bending-rebound-with-small-samples
name: "A GAN–SVR Prediction Method of the Metal Tube-Bending Rebound with Small Samples"
url: "https://www.hindawi.com/journals/js/2023/6616607/"
domain: "hindawi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Agriculture | An Open Access Journal from MDPI
- URL: [https://www.mdpi.com/journal/agriculture](https://www.mdpi.com/journal/agriculture)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `agriculture-an-open-access-journal-from-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: agriculture-an-open-access-journal-from-mdpi
name: "Agriculture | An Open Access Journal from MDPI"
url: "https://www.mdpi.com/journal/agriculture"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### MDPI | Nueva presentación
- URL: [https://susy.mdpi.com/user/manuscripts/upload/e663aa38f6543061570f7427aa351933?&form%5Bjournal_id%5D=](https://susy.mdpi.com/user/manuscripts/upload/e663aa38f6543061570f7427aa351933?&form%5Bjournal_id%5D=)
- Dominio: `susy.mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `mdpi-nueva-presentaci-n`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: mdpi-nueva-presentaci-n
name: "MDPI | Nueva presentación"
url: "https://susy.mdpi.com/user/manuscripts/upload/e663aa38f6543061570f7427aa351933?&form%5Bjournal_id%5D="
domain: "susy.mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Home | SpringerLink
- URL: [https://link-springer-com.udea.lookproxy.com/](https://link-springer-com.udea.lookproxy.com/)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `home-springerlink`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: home-springerlink
name: "Home | SpringerLink"
url: "https://link-springer-com.udea.lookproxy.com/"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### wcmc - About this journal | Hindawi
- URL: [https://www.hindawi.com/journals/wcmc/about/](https://www.hindawi.com/journals/wcmc/about/)
- Dominio: `hindawi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `wcmc-about-this-journal-hindawi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: wcmc-about-this-journal-hindawi
name: "wcmc - About this journal | Hindawi"
url: "https://www.hindawi.com/journals/wcmc/about/"
domain: "hindawi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Theoretical and Applied Information Technology (JATIT)- Home page
- URL: [https://www.jatit.org/submit_paper.php](https://www.jatit.org/submit_paper.php)
- Dominio: `jatit.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `journal-of-theoretical-and-applied-information-technology-jatit-home-page`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-theoretical-and-applied-information-technology-jatit-home-page
name: "Journal of Theoretical and Applied Information Technology (JATIT)- Home page"
url: "https://www.jatit.org/submit_paper.php"
domain: "jatit.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Encuentra una revista | Buscador de revistas
- URL: [https://journalfinder.elsevier.com/](https://journalfinder.elsevier.com/)
- Dominio: `journalfinder.elsevier.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `encuentra-una-revista-buscador-de-revistas`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: encuentra-una-revista-buscador-de-revistas
name: "Encuentra una revista | Buscador de revistas"
url: "https://journalfinder.elsevier.com/"
domain: "journalfinder.elsevier.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Insights - Data in Brief | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/data-in-brief/about/insights](https://www.sciencedirect.com/journal/data-in-brief/about/insights)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `insights-data-in-brief-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: insights-data-in-brief-sciencedirect-com-by-elsevier
name: "Insights - Data in Brief | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/data-in-brief/about/insights"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Energies | Free Full-Text | Wind, Solar, and Photovoltaic Renewable Energy Systems with and without Energy Storage Optimization: A Survey of Advanced Machine Learning and Deep Learning Techniques
- URL: [https://www.mdpi.com/1996-1073/15/2/578](https://www.mdpi.com/1996-1073/15/2/578)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `energies-free-full-text-wind-solar-and-photovoltaic-renewable-energy-systems-wit`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: energies-free-full-text-wind-solar-and-photovoltaic-renewable-energy-systems-wit
name: "Energies | Free Full-Text | Wind, Solar, and Photovoltaic Renewable Energy Systems with and without Energy Storage Optimization: A Survey of Advanced Machine Learning and Deep Learning Techniques"
url: "https://www.mdpi.com/1996-1073/15/2/578"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Artificial Intelligence Journal, Machine Learning Journal
- URL: [https://www.oajaiml.com/](https://www.oajaiml.com/)
- Dominio: `oajaiml.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `artificial-intelligence-journal-machine-learning-journal`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: artificial-intelligence-journal-machine-learning-journal
name: "Artificial Intelligence Journal, Machine Learning Journal"
url: "https://www.oajaiml.com/"
domain: "oajaiml.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Fronteras
- URL: [https://review.frontiersin.org/review/1592329/14/3043080#/tab/Reviewer3](https://review.frontiersin.org/review/1592329/14/3043080#/tab/Reviewer3)
- Dominio: `review.frontiersin.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `fronteras`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: fronteras
name: "Fronteras"
url: "https://review.frontiersin.org/review/1592329/14/3043080#/tab/Reviewer3"
domain: "review.frontiersin.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Loop | Jorge Chaparro
- URL: [https://loop.frontiersin.org/people/3043080/bio](https://loop.frontiersin.org/people/3043080/bio)
- Dominio: `loop.frontiersin.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `loop-jorge-chaparro`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: loop-jorge-chaparro
name: "Loop | Jorge Chaparro"
url: "https://loop.frontiersin.org/people/3043080/bio"
domain: "loop.frontiersin.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Fake Journal warning | International Journal of Computational and Experimental Science and Engineering
- URL: [https://www.ijcesen.com/index.php/ijcesen/announcement/view/7](https://www.ijcesen.com/index.php/ijcesen/announcement/view/7)
- Dominio: `ijcesen.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `fake-journal-warning-international-journal-of-computational-and-experimental-sci`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: fake-journal-warning-international-journal-of-computational-and-experimental-sci
name: "Fake Journal warning | International Journal of Computational and Experimental Science and Engineering"
url: "https://www.ijcesen.com/index.php/ijcesen/announcement/view/7"
domain: "ijcesen.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### MDPI Susy
- URL: [https://susy.mdpi.com/user/myprofile](https://susy.mdpi.com/user/myprofile)
- Dominio: `susy.mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `mdpi-susy`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: mdpi-susy
name: "MDPI Susy"
url: "https://susy.mdpi.com/user/myprofile"
domain: "susy.mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Open Access Journals | MDPI
- URL: [https://www.mdpi.com/about/journals/](https://www.mdpi.com/about/journals/)
- Dominio: `mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `open-access-journals-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: open-access-journals-mdpi
name: "Open Access Journals | MDPI"
url: "https://www.mdpi.com/about/journals/"
domain: "mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Process Invitation | MDPI
- URL: [https://susy.mdpi.com/editor/paper-invitation/process/172292045/dqX8jM2s](https://susy.mdpi.com/editor/paper-invitation/process/172292045/dqX8jM2s)
- Dominio: `susy.mdpi.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `process-invitation-mdpi`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: process-invitation-mdpi
name: "Process Invitation | MDPI"
url: "https://susy.mdpi.com/editor/paper-invitation/process/172292045/dqX8jM2s"
domain: "susy.mdpi.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Resistance of rice against infection by Bipolaris oryzae is differentially induced by β-aminobutyric and γ-aminobutyric acids | Plant and Soil | Springer Nature Link
- URL: [https://link.springer.com/article/10.1007/s11104-025-07382-x](https://link.springer.com/article/10.1007/s11104-025-07382-x)
- Dominio: `link.springer.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `resistance-of-rice-against-infection-by-bipolaris-oryzae-is-differentially-induc`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: resistance-of-rice-against-infection-by-bipolaris-oryzae-is-differentially-induc
name: "Resistance of rice against infection by Bipolaris oryzae is differentially induced by β-aminobutyric and γ-aminobutyric acids | Plant and Soil | Springer Nature Link"
url: "https://link.springer.com/article/10.1007/s11104-025-07382-x"
domain: "link.springer.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Resource-based view and SME internationalization: a systematic literature review of resource optimization for global growth | Management Review Quarterly | Springer Nature Link
- URL: [https://link-springer-com.udea.lookproxy.com/article/10.1007/s11301-024-00478-1](https://link-springer-com.udea.lookproxy.com/article/10.1007/s11301-024-00478-1)
- Dominio: `link-springer-com.udea.lookproxy.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `resource-based-view-and-sme-internationalization-a-systematic-literature-review-`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: resource-based-view-and-sme-internationalization-a-systematic-literature-review-
name: "Resource-based view and SME internationalization: a systematic literature review of resource optimization for global growth | Management Review Quarterly | Springer Nature Link"
url: "https://link-springer-com.udea.lookproxy.com/article/10.1007/s11301-024-00478-1"
domain: "link-springer-com.udea.lookproxy.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Journal of Artificial Intelligence Research
- URL: [https://www.jair.org/index.php/jair](https://www.jair.org/index.php/jair)
- Dominio: `jair.org`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `journal-of-artificial-intelligence-research`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: journal-of-artificial-intelligence-research
name: "Journal of Artificial Intelligence Research"
url: "https://www.jair.org/index.php/jair"
domain: "jair.org"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```
### Intelligent Systems with Applications | Journal | ScienceDirect.com by Elsevier
- URL: [https://www.sciencedirect.com/journal/intelligent-systems-with-applications](https://www.sciencedirect.com/journal/intelligent-systems-with-applications)
- Dominio: `sciencedirect.com`.[file:16]
- Tipo estimado: revista o portal de revista.[file:16]
- Identificador FARO sugerido: `intelligent-systems-with-applications-journal-sciencedirect-com-by-elsevier`.
- Uso sugerido en FARO: construir un nodo de conocimiento con campos `name`, `url`, `publisher`, `scope_hint`, `workflow_hint`, `quality_signal`, `submission_signal` y `notes`.[file:17][file:16]
- Observación: esta entrada proviene de un marcador real del usuario y por tanto representa una señal práctica de interés, consulta o posible destino editorial.[file:16]
- Plantilla mínima:
```yaml
id: intelligent-systems-with-applications-journal-sciencedirect-com-by-elsevier
name: "Intelligent Systems with Applications | Journal | ScienceDirect.com by Elsevier"
url: "https://www.sciencedirect.com/journal/intelligent-systems-with-applications"
domain: "sciencedirect.com"
entity_type: journal|publisher_platform|ranking_source
scope_hint: "pending_manual_curation"
workflow_hint: "pending_manual_curation"
quality_signal: "bookmark_detected"
submission_signal: true|false
notes: "Imported from personal bookmarks for FARO seed corpus"
```

## Plantilla de perfil extendido

La siguiente plantilla está alineada con el espíritu del archivo base, pero orientada a un framework programable. Puede instanciarse para cada revista detectada y luego enriquecerse manualmente o mediante scraping controlado.[file:17][file:16]

```yaml
journal_name: ""
abbreviation: ""
publisher: ""
url_home: ""
url_guide_for_authors: ""
url_submission: ""
domain_family: "Elsevier|Springer|MDPI|Wiley|Frontiers|Hindawi|IEEE|Other"
broad_area: ""
topic_tags:
  - "precision agriculture"
  - "computer vision"
  - "iot"
  - "remote sensing"
methods_fit:
  - "machine learning"
  - "field experimentation"
  - "uav imaging"
article_types:
  - "research article"
  - "review"
editorial_style_notes: ""
review_culture_notes: ""
expected_evidence: ""
common_reject_reasons:
  - "scope mismatch"
  - "weak validation"
  - "insufficient novelty"
ranking_sources:
  - "SJR"
  - "Journal Finder"
faro_confidence: 0.0
needs_manual_validation: true
provenance: "Imported from bookmarks_17_5_26.html"
```

## Reglas FARO propuestas

- Si el dominio pertenece a `sciencedirect.com`, `link.springer.com`, `mdpi.com`, `frontiersin.org`, `hindawi.com`, `onlinelibrary.wiley.com` o `ieeexplore.ieee.org`, FARO debe clasificar primero la entrada como `publisher_or_journal_page` y luego resolver si es homepage, about, guide for authors o submission.[file:16]
- Si el enlace contiene `editorialmanager`, `submission`, `author`, `guide`, `how-to-publish`, `for-authors` o `upload-files`, FARO debe activar el submódulo de flujo editorial y no el de análisis temático puro.[file:16]
- Si el enlace pertenece a `scimagojr.com`, FARO debe tipificarlo como fuente de ranking y usarlo para métricas comparativas, no como fuente primaria de alcance editorial.[file:16]
- Si varias entradas del mismo journal aparecen en home, about, submission y ranking, FARO debe fusionarlas en una sola entidad compuesta con múltiples evidencias.[file:16][file:17]
