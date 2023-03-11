# CompanionJM
Este repositorio contiene los ficheros en texto plano (Unix LF, UTF-8) de las obras completas de don Juan Manuel para ejecutar los análisis del «Did don Juan Manuel Write _Conde Lucanor_'s _exemplum_ 51? An Approach from Stylometry» publicado en el libro _Companion to Don Juan Manuel_ (Leinden: Brill, en prensa) coordinado por Mario Cossio Olavide, Anita Savo & Daniela Santonocito.

Los textos proceden del corpus del [Hispanic Seminary of Medieval Studies](http://hispanicseminary.org/index.htm) y del [Old Spanish Textual Archive](http://osta.oldspanishtextualarchive.org/). Se les han retirado todas las indicaciones no textuales (indicación de folio, de columna, rúbrica, enmiendas, etc.).

El directorio `corpus` contiene los textos para realizar los análisis de grupo (_cluster analysis_), los de componentes principales (_PCA_) e `impostors`
según la librería `stylo`.

Los directorios `primary_set`, `secondary_set`, `reference_set` y `test_set` tienen los mismos textos que el direcotrio `corpus`, pero ya organizados y nombrados de acuerdo con las exigencias de la librería `stylo` para llevar a cabo los análisis ìmpostors(), `rolling.delta()` y `rolling.classify()`.

Este trabajo forma parte de los desarrollos y resultados del proyecto [7PartidasDigital](https://7partidas.hypotheses.org/) que se desarrolla en la [Universidad de Valladolid](https://www.uva.es/export/sites/uva/) financiado por la Agencia Estatal de Investigación de España (ref. PID2020-112621GB-I00).

En el momento de su primera carga (2023.03.11) es un trabajo en marcha (_work in progress_) por lo que puede haber modificaciones hasta el momento en el que se publique el volumen definitivo.

