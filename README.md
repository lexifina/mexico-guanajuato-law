# Guanajuato: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Guanajuato, Mexico, which global-law reads at `mexico/guanajuato/acts/`.

The law of the State of Guanajuato (Estado Libre y Soberano de Guanajuato, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-gua/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

116 ordenamientos with 1143 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE GUANAJUATO | 142 | as first published, then each reform: 21 October 1917 to 1 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE GUANAJUATO | 87 | as first published, then each reform: 17 May 1967 to 19 December 2025 |
| `codigo-de-procedimiento-y-justicia-administrativa/` | CODIGO DE PROCEDIMIENTO Y JUSTICIA ADMINISTRATIVA PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 14 | as first published, then each reform: 20 August 2007 to 5 November 2025 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES DEL ESTADO DE GUANAJUATO | 52 | as first published, then each reform: 1 April 1934 to 4 July 2026 |
| `codigo-fiscal/` | CODIGO FISCAL PARA EL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 1 September 2020 to 1 January 2026 |
| `codigo-penal/` | CODIGO PENAL DEL ESTADO DE GUANAJUATO -ANTES CODIGO PENAL PARA EL ESTADO DE GUANAJUATO- | 76 | as first published, then each reform: 1 January 2002 to 15 May 2026 |
| `codigo-reglamentario-de-desarrollo-urbano-para-el-municipio/` | CODIGO REGLAMENTARIO DE DESARROLLO URBANO PARA EL MUNICIPIO DE LEON, GUANAJUATO | 24 | as first published, then each reform: 7 August 2010 to 13 July 2023 |
| `codigo-territorial/` | CODIGO TERRITORIAL PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 19 | as first published, then each reform: 1 January 2013 to 28 May 2026 |
| `ley-arancelaria-para-el-cobro-de-honorarios-profesionales-de/` | LEY ARANCELARIA PARA EL COBRO DE HONORARIOS PROFESIONALES DE ABOGADOS Y NOTARIOS Y DE COSTAS PROCESALES PARA EL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 1 April 2006 to 2 July 2016 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE GUANAJUATO | 34 | as first published, then each reform: 27 November 2010 to 9 July 2026 |
| `ley-de-aparceria-agricola-y-ganadera/` | LEY DE APARCERIA AGRICOLA Y GANADERA PARA EL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 20 March 1972 to 8 June 2013 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 14 July 2020 to 23 December 2022 |
| `ley-de-asistencia-social-y-fortalecimiento-familiar/` | LEY DE ASISTENCIA SOCIAL Y FORTALECIMIENTO FAMILIAR PARA EL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 5 January 2024 to 26 June 2025 |
| `ley-de-bebidas-alcoholicas/` | LEY DE BEBIDAS ALCOHOLICAS PARA EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 1 September 2020 to 1 January 2026 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 10 | as first published, then each reform: 1 January 2014 to 9 July 2026 |
| `ley-de-concesiones-de-servicios-e-infraestructura-publica/` | LEY DE CONCESIONES DE SERVICIOS E INFRAESTRUCTURA PUBLICA PARA EL ESTADO DE GUANAJUATO | 3 | oldest version available, then each reform: 25 December 2002 to 26 September 2018 |
| `ley-de-contrataciones-publicas/` | LEY DE CONTRATACIONES PUBLICAS PARA EL ESTADO DE GUANAJUATO | 4 | as first published, then each reform: 1 February 2015 to 22 July 2022 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE GUANAJUATO | 1 | as first published: 3 January 2026 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE GUANAJUATO | 8 | as first published, then each reform: 1 January 2018 to 31 October 2025 |
| `ley-de-declaracion-especial-de-ausencia/` | LEY DE DECLARACION ESPECIAL DE AUSENCIA PARA EL ESTADO DE GUANAJUATO | 1 | as first published: 23 December 2020 |
| `ley-de-derechos-culturales/` | LEY DE DERECHOS CULTURALES PARA EL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 21 April 2018 to 26 September 2024 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 3 | as first published, then each reform: 1 January 2020 to 22 April 2026 |
| `ley-de-desarrollo-social-y-humano/` | LEY DE DESARROLLO SOCIAL Y HUMANO PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 7 | as first published, then each reform: 3 June 2006 to 14 November 2025 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 1 | as first published: 29 October 2016 |
| `ley-de-economia-circular/` | LEY DE ECONOMIA CIRCULAR PARA EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 1 | as first published: 18 September 2024 |
| `ley-de-educacion/` | LEY DE EDUCACION PARA EL ESTADO DE GUANAJUATO | 12 | as first published, then each reform: 23 July 2020 to 15 May 2026 |
| `ley-de-educacion-superior/` | LEY DE EDUCACION SUPERIOR PARA EL ESTADO DE GUANAJUATO | 1 | as first published: 20 July 2024 |
| `ley-de-ejecucion-de-medidas-judiciales-y-sanciones-penales/` | LEY DE EJECUCION DE MEDIDAS JUDICIALES Y SANCIONES PENALES DEL ESTADO DE GUANAJUATO | 10 | as first published, then each reform: 18 April 2011 to 2 July 2016 |
| `ley-de-expropiacion-de-ocupacion-temporal-y-de-limitacion-de/` | LEY DE EXPROPIACION, DE OCUPACION TEMPORAL Y DE LIMITACION DE DOMINIO PARA EL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 2 August 1992 to 15 June 2002 |
| `ley-de-fiscalizacion-superior/` | LEY DE FISCALIZACION SUPERIOR DEL ESTADO DE GUANAJUATO | 8 | as first published, then each reform: 24 December 2015 to 9 January 2024 |
| `ley-de-fomento-a-la-actividad-vitivinicola/` | LEY DE FOMENTO A LA ACTIVIDAD VITIVINICOLA DEL ESTADO DE GUANAJUATO | 1 | as first published: 23 December 2020 |
| `ley-de-fomento-a-la-agricultura-familiar/` | LEY DE FOMENTO A LA AGRICULTURA FAMILIAR DEL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 25 September 2021 to 16 October 2026 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE GUANAJUATO | 4 | as first published, then each reform: 26 September 2015 to 14 November 2025 |
| `ley-de-fomento-y-desarrollo-agricola/` | LEY DE FOMENTO Y DESARROLLO AGRICOLA PARA EL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 25 September 2021 to 31 October 2025 |
| `ley-de-hacienda/` | LEY DE HACIENDA PARA EL ESTADO DE GUANAJUATO | 11 | as first published, then each reform: 2 January 2020 to 1 January 2026 |
| `ley-de-hacienda-para-los-municipios/` | LEY DE HACIENDA PARA LOS MUNICIPIOS DEL ESTADO DE GUANAJUATO | 28 | as first published, then each reform: 29 December 1989 to 9 July 2026 |
| `ley-de-hospedaje-a-traves-de-plataformas-digitales/` | LEY DE HOSPEDAJE A TRAVES DE PLATAFORMAS DIGITALES DEL ESTADO DE GUANAJUATO | 1 | as first published: 10 December 2020 |
| `ley-de-inclusion-para-las-personas-con-discapacidad-en-el-es/` | LEY DE INCLUSION PARA LAS PERSONAS CON DISCAPACIDAD EN EL ESTADO DE GUANAJUATO | 11 | as first published, then each reform: 15 September 2012 to 31 October 2025 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE GUANAJUATO PARA EL EJERCICIO FISCAL DE 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES PARA EL ESTADO DE GUANAJUATO | 15 | as first published, then each reform: 28 June 2014 to 30 May 2026 |
| `ley-de-justicia-alternativa/` | LEY DE JUSTICIA ALTERNATIVA DEL ESTADO DE GUANAJUATO | 4 | as first published, then each reform: 27 November 2003 to 28 February 2021 |
| `ley-de-justicia-civica/` | LEY DE JUSTICIA CIVICA DEL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 24 April 2021 to 25 October 2023 |
| `ley-de-la-defensoria-publica-penal/` | LEY DE LA DEFENSORIA PUBLICA PENAL DEL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 4 June 2011 to 29 November 2014 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES PARA EL ESTADO DE GUANAJUATO | 7 | as first published, then each reform: 1 January 2014 to 29 July 2025 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE GUANAJUATO | 18 | as first published, then each reform: 1 January 2016 to 15 May 2026 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 1 January 2019 to 5 July 2023 |
| `ley-de-movilidad/` | LEY DE MOVILIDAD DEL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 22 | as first published, then each reform: 19 March 2016 to 29 May 2026 |
| `ley-de-obra-publica-y-servicios-relacionados-con-la-misma/` | LEY DE OBRA PUBLICA Y SERVICIOS RELACIONADOS CON LA MISMA PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 5 | as first published, then each reform: 19 June 2018 to 29 October 2022 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 23 October 2002 to 6 July 2018 |
| `ley-de-planeacion/` | LEY DE PLANEACION PARA EL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 28 December 2011 to 29 October 2022 |
| `ley-de-premios-y-estimulos-al-merito-ciudadano/` | LEY DE PREMIOS Y ESTIMULOS AL MERITO CIUDADANO PARA EL ESTADO DE GUANAJUATO | 4 | as first published, then each reform: 28 December 2004 to 15 May 2026 |
| `ley-de-profesiones/` | LEY DE PROFESIONES PARA EL ESTADO DE GUANAJUATO | 9 | as first published, then each reform: 18 February 2006 to 23 July 2020 |
| `ley-de-propiedad-en-condominio-de-inmuebles/` | LEY DE PROPIEDAD EN CONDOMINIO DE INMUEBLES PARA EL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 10 December 2012 to 1 December 2022 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE GUANAJUATO | 7 | as first published, then each reform: 25 October 1997 to 10 October 2018 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS PARA EL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 15 July 2017 to 6 December 2017 |
| `ley-de-proyectos-de-prestacion-de-servicios/` | LEY DE PROYECTOS DE PRESTACION DE SERVICIOS PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 4 | as first published, then each reform: 12 June 2010 to 29 October 2016 |
| `ley-de-representacion-gratuita-en-materia-civil-guanajuato/` | LEY DE REPRESENTACION GRATUITA EN MATERIA CIVIL, GUANAJUATO | 2 | as first published, then each reform: 24 June 1995 to 2 August 2019 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 8 | as first published, then each reform: 10 January 2005 to 21 November 2023 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS PARA EL ESTADO DE GUANAJUATO | 7 | as first published, then each reform: 19 July 2017 to 30 June 2026 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE GUANAJUATO | 36 | as first published, then each reform: 9 August 1986 to 16 October 2026 |
| `ley-de-seguridad-privada/` | LEY DE SEGURIDAD PRIVADA DEL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 22 July 2021 to 22 December 2023 |
| `ley-de-seguridad-social/` | LEY DE SEGURIDAD SOCIAL DEL ESTADO DE GUANAJUATO | 1 | as first published: 19 April 2018 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA PARA EL ESTADO DE GUANAJUATO | 9 | as first published, then each reform: 14 May 2016 to 9 April 2026 |
| `ley-de-turismo/` | LEY DE TURISMO PARA EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 1 | as first published: 31 December 2022 |
| `ley-de-victimas/` | LEY DE VICTIMAS DEL ESTADO DE GUANAJUATO | 6 | as first published, then each reform: 28 May 2020 to 22 April 2026 |
| `ley-de-voluntad-anticipada/` | LEY DE VOLUNTAD ANTICIPADA PARA EL ESTADO DE GUANAJUATO | 1 | as first published: 6 June 2011 |
| `ley-del-escudo-la-bandera-y-el-himno/` | LEY DEL ESCUDO, LA BANDERA Y EL HIMNO DEL ESTADO DE GUANAJUATO | 1 | as first published: 25 November 2023 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE GUANAJUATO | 6 | as first published, then each reform: 1 January 2007 to 14 December 2023 |
| `ley-del-patrimonio-cultural/` | LEY DEL PATRIMONIO CULTURAL DEL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 2 August 2006 to 20 July 2021 |
| `ley-del-patrimonio-inmobiliario/` | LEY DEL PATRIMONIO INMOBILIARIO DEL ESTADO DE GUANAJUATO | 1 | as first published: 9 December 2022 |
| `ley-del-proceso-penal/` | LEY DEL PROCESO PENAL PARA EL ESTADO DE GUANAJUATO | 11 | as first published, then each reform: 6 September 2010 to 2 July 2016 |
| `ley-del-secreto-profesional-del-periodista/` | LEY DEL SECRETO PROFESIONAL DEL PERIODISTA DEL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 22 November 2014 to 27 October 2017 |
| `ley-del-servicio-de-administracion-tributaria/` | LEY DEL SERVICIO DE ADMINISTRACION TRIBUTARIA DEL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 1 September 2020 to 31 December 2023 |
| `ley-del-servicio-profesional-de-carrera-policial/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA POLICIAL DEL ESTADO Y MUNICIPIOS DE GUANAJUATO | 3 | as first published, then each reform: 17 October 2021 to 16 November 2023 |
| `ley-del-sistema-de-seguridad-publica/` | LEY DEL SISTEMA DE SEGURIDAD PUBLICA DEL ESTADO DE GUANAJUATO | 25 | as first published, then each reform: 1 January 2015 to 9 July 2026 |
| `ley-del-sistema-estatal-anticorrupcion-de-guanajuato/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DE GUANAJUATO | 2 | as first published, then each reform: 17 May 2017 to 2 November 2019 |
| `ley-del-trabajo-de-los-servidores-publicos-al-servicio/` | LEY DEL TRABAJO DE LOS SERVIDORES PUBLICOS AL SERVICIO DEL ESTADO Y DE LOS MUNICIPIOS, GUANAJUATO | 21 | as first published, then each reform: 5 December 1992 to 30 June 2026 |
| `ley-ganadera/` | LEY GANADERA PARA EL ESTADO DE GUANAJUATO | 6 | as first published, then each reform: 23 December 1998 to 26 November 2019 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 18 February 2019 to 22 April 2026 |
| `ley-organica-de-la-universidad-de-guanajuato/` | LEY ORGANICA DE LA UNIVERSIDAD DE GUANAJUATO | 3 | as first published, then each reform: 15 October 2007 to 21 July 2018 |
| `ley-organica-de-las-fuerzas-de-seguridad-publica/` | LEY ORGANICA DE LAS FUERZAS DE SEGURIDAD PUBLICA DEL ESTADO, GUANAJUATO | 2 | as first published, then each reform: 31 December 1972 to 16 August 1995 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 23 December 2020 to 25 October 2023 |
| `ley-organica-del-poder-ejecutivo/` | LEY ORGANICA DEL PODER EJECUTIVO PARA EL ESTADO DE GUANAJUATO | 33 | as first published, then each reform: 1 January 2001 to 9 April 2026 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE GUANAJUATO | 17 | as first published, then each reform: 23 May 2012 to 29 April 2025 |
| `ley-organica-del-poder-legislativo/` | LEY ORGANICA DEL PODER LEGISLATIVO DEL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 21 June 2025 to 30 May 2026 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE GUANAJUATO | 8 | as first published, then each reform: 21 June 2017 to 14 December 2023 |
| `ley-para-el-desarrollo-y-competitividad-economica/` | LEY PARA EL DESARROLLO Y COMPETITIVIDAD ECONOMICA DEL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 11 | as first published, then each reform: 18 November 2013 to 12 December 2025 |
| `ley-para-el-ejercicio-y-control-de-los-recursos-publicos/` | LEY PARA EL EJERCICIO Y CONTROL DE LOS RECURSOS PUBLICOS PARA EL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 17 | as first published, then each reform: 13 August 2003 to 28 May 2026 |
| `ley-para-el-fomento-de-la-industria-cinematografica-y-audiov/` | LEY PARA EL FOMENTO DE LA INDUSTRIA CINEMATOGRAFICA Y AUDIOVISUAL DEL ESTADO DE GUANAJUATO | 1 | as first published: 28 June 2014 |
| `ley-para-el-gobierno-y-administracion-de-los-municipios/` | LEY PARA EL GOBIERNO Y ADMINISTRACION DE LOS MUNICIPIOS DEL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 18 September 2024 to 30 May 2026 |
| `ley-para-fomentar-el-acceso-al-financiamiento-a-las-micros-p/` | LEY PARA FOMENTAR EL ACCESO AL FINANCIAMIENTO A LAS MICROS, PEQUEÑAS Y MEDIANAS EMPRESAS EN EL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 29 November 2022 to 26 September 2024 |
| `ley-para-la-administracion-y-disposicion-de-bienes-relaciona/` | LEY PARA LA ADMINISTRACION Y DISPOSICION DE BIENES RELACIONADOS CON HECHOS DELICTUOSOS PARA EL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 15 August 2011 to 1 June 2016 |
| `ley-para-la-busqueda-de-personas-desaparecidas-en-el-estado/` | LEY PARA LA BUSQUEDA DE PERSONAS DESAPARECIDAS EN EL ESTADO DE GUANAJUATO | 7 | as first published, then each reform: 4 June 2020 to 22 April 2026 |
| `ley-para-la-gestion-integral-de-residuos/` | LEY PARA LA GESTION INTEGRAL DE RESIDUOS DEL ESTADO Y LOS MUNICIPIOS DE GUANAJUATO | 7 | as first published, then each reform: 8 August 2005 to 27 June 2025 |
| `ley-para-la-igualdad-entre-mujeres-y-hombres/` | LEY PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE GUANAJUATO | 7 | as first published, then each reform: 11 May 2013 to 26 June 2025 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA DEL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 13 March 2019 to 26 June 2025 |
| `ley-para-la-proteccion-a-las-abejas-y-el-desarrollo-apicola/` | LEY PARA LA PROTECCION A LAS ABEJAS Y EL DESARROLLO APICOLA PARA EL ESTADO DE GUANAJUATO | 1 | as first published: 26 November 2019 |
| `ley-para-la-proteccion-animal/` | LEY PARA LA PROTECCION ANIMAL DEL ESTADO DE GUANAJUATO | 7 | as first published, then each reform: 30 March 2016 to 3 August 2024 |
| `ley-para-la-proteccion-de-los-derechos-humanos-en-el-estado/` | LEY PARA LA PROTECCION DE LOS DERECHOS HUMANOS EN EL ESTADO DE GUANAJUATO | 16 | as first published, then each reform: 29 September 2000 to 8 June 2024 |
| `ley-para-la-proteccion-de-los-pueblos-y-comunidades-indigena/` | LEY PARA LA PROTECCION DE LOS PUEBLOS Y COMUNIDADES INDIGENAS Y AFROMEXICANAS EN EL ESTADO DE GUANAJUATO -- ANTES LEY PARA LA PROTECCION DE LOS PUEBLOS Y COMUNIDADES INDIGENAS EN EL ESTADO DE GUANAJUATO -- | 6 | as first published, then each reform: 9 April 2011 to 31 October 2025 |
| `ley-para-la-proteccion-de-personas-defensoras-de-derechos-hu/` | LEY PARA LA PROTECCION DE PERSONAS DEFENSORAS DE DERECHOS HUMANOS Y PERIODISTAS DEL ESTADO DE GUANAJUATO | 3 | as first published, then each reform: 27 October 2017 to 15 October 2025 |
| `ley-para-la-proteccion-y-atencion-de-las-personas-migrantes/` | LEY PARA LA PROTECCION Y ATENCION DE LAS PERSONAS MIGRANTES Y SUS FAMILIAS DEL ESTADO DE GUANAJUATO --ANTES LEY PARA LA PROTECCION Y ATENCION DEL MIGRANTE Y SUS FAMILIAS DEL ESTADO DE GUANAJUATO-- | 8 | as first published, then each reform: 17 June 2017 to 29 July 2025 |
| `ley-para-la-proteccion-y-preservacion-del-ambiente/` | LEY PARA LA PROTECCION Y PRESERVACION DEL AMBIENTE DEL ESTADO DE GUANAJUATO | 14 | as first published, then each reform: 9 February 2000 to 18 September 2024 |
| `ley-para-la-regularizacion-de-predios-rusticos-en-el-estado/` | LEY PARA LA REGULARIZACION DE PREDIOS RUSTICOS EN EL ESTADO DE GUANAJUATO | 5 | as first published, then each reform: 27 November 1995 to 8 June 2013 |
| `ley-para-las-juventudes/` | LEY PARA LAS JUVENTUDES DEL ESTADO DE GUANAJUATO | 4 | as first published, then each reform: 22 October 2020 to 29 July 2025 |
| `ley-para-las-personas-de-la-diversidad-sexual-y-de-genero/` | LEY PARA LAS PERSONAS DE LA DIVERSIDAD SEXUAL Y DE GENERO DEL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 2 | as first published, then each reform: 8 June 2024 to 26 June 2025 |
| `ley-para-prevenir-atender-y-erradicar-la-discriminacion-en-e/` | LEY PARA PREVENIR, ATENDER Y ERRADICAR LA DISCRIMINACION EN EL ESTADO DE GUANAJUATO | 7 | as first published, then each reform: 28 June 2014 to 4 December 2025 |
| `ley-para-prevenir-atender-y-erradicar-la-trata-de-personas-e/` | LEY PARA PREVENIR, ATENDER Y ERRADICAR LA TRATA DE PERSONAS EN EL ESTADO DE GUANAJUATO | 1 | as first published: 1 March 2014 |
| `ley-para-prevenir-atender-y-erradicar-la-violencia-en-el-est/` | LEY PARA PREVENIR, ATENDER Y ERRADICAR LA VIOLENCIA EN EL ESTADO DE GUANAJUATO | 17 | as first published, then each reform: 28 March 2009 to 26 June 2025 |
| `ley-para-regular-la-prestacion-de-servicios-de-atencion-cuid/` | LEY PARA REGULAR LA PRESTACION DE SERVICIOS DE ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL EN EL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 1 January 2017 to 2 August 2019 |
| `ley-para-una-convivencia-libre-de-violencia-en-el-entorno-es/` | LEY PARA UNA CONVIVENCIA LIBRE DE VIOLENCIA EN EL ENTORNO ESCOLAR PARA EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 6 | as first published, then each reform: 3 July 2013 to 27 October 2023 |
| `ley-que-regula-a-los-agentes-inmobiliarios-en-el-estado-de-g/` | LEY QUE REGULA A LOS AGENTES INMOBILIARIOS EN EL ESTADO DE GUANAJUATO | 2 | as first published, then each reform: 24 November 2014 to 2 July 2016 |
| `ley-que-regula-las-bases-del-permiso-para-el-establecimiento/` | LEY QUE REGULA LAS BASES DEL PERMISO PARA EL ESTABLECIMIENTO DE LAS CASAS DE EMPEÑO EN EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 20 October 2014 to 1 September 2020 |
| `ley-que-regula-los-establecimientos-dedicados-a-la-compraven/` | LEY QUE REGULA LOS ESTABLECIMIENTOS DEDICADOS A LA COMPRAVENTA O ADQUISICION DE VEHICULOS AUTOMOTORES EN DESUSO Y SUS AUTOPARTES, ASI COMO EN LOS QUE SE COMERCIALIZAN, MANEJAN O DISPONEN DE METALES PARA RECICLAJE, PARA EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 7 | as first published, then each reform: 1 January 2015 to 1 September 2020 |
| `ley-reglamentaria-de-la-fraccion-xv-del-articulo-88-de-la-co/` | LEY REGLAMENTARIA DE LA FRACCION XV DEL ARTICULO 88 DE LA CONSTITUCION POLITICA PARA EL ESTADO DE GUANAJUATO -- ANTES LEY REGLAMENTARIA DE LA FRACCION XV DEL ARTICULO 89 DE LA CONSTITUCION POLITICA PARA EL ESTADO DE GUANAJUATO -- | 2 | as first published, then each reform: 6 August 2001 to 15 May 2018 |
| `ley-sobre-el-uso-de-medios-electronicos-y-firma-electronica/` | LEY SOBRE EL USO DE MEDIOS ELECTRONICOS Y FIRMA ELECTRONICA PARA EL ESTADO DE GUANAJUATO Y SUS MUNICIPIOS | 5 | as first published, then each reform: 1 November 2004 to 31 December 2020 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
