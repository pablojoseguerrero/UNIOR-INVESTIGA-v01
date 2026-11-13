# UNIOR INVESTIGA-v01

Laboratorio de creación de herramientas para investigación científica, presentado en el 1.er Congreso Internacional de Integración Científica de UNIOR.

**Autor:** Prof. Dr. Pablo José Guerrero PhD. · RED CTII.AI · 2026 · https://guerrero-consultores.com/

## Experiencia

1. **Inicio:** recorrido de la necesidad a una herramienta comprobable.
2. **Mapa:** ocho ámbitos (problematización, literatura, teoría, metodología, instrumentos, análisis, escritura e integridad).
3. **Constructor:** propósito, destinatarios, entradas, pasos, criterios, límites, recursos y producto. Cinco salidas: prompt, skill, flujo de revisión, especificación de laboratorio y plan multiagente.
4. **Banco de pruebas:** casos completos, con información faltante y contradictorios; salida obtenida, evidencia, evaluación humana y bitácora descargable.
5. **Mis herramientas:** varios proyectos, duplicación, importación/exportación JSON y versiones con comparación de líneas.
6. **Referencias:** accesos a Episteme Lab, LABIMET (portal) y LAB-VALIDEZ IA, además de documentación de plataformas.

## Uso

Seleccionar una plantilla o comenzar desde cero. Completar cada etapa, añadir recursos TXT/MD/CSV/JSON y explicar cuándo consultarlos. Descargar las instrucciones o un ZIP con carpeta y recursos. Preparar casos de prueba, ejecutar en la plataforma elegida y registrar resultados auténticos. Guardar una versión después de los ajustes.

Los recursos se normalizan a nombres seguros; esos nombres son los que aparecen en las instrucciones y en el ZIP. Las guías APA no vienen incorporadas: cada participante debe aportar material verificado y con derechos de uso. El documento de prueba se proporciona al modelo durante la ejecución; no se publica en este repositorio.

El control estructural cuenta componentes definidos; **no certifica validez científica, seguridad ni correcto funcionamiento de un modelo**. El banco de pruebas no ejecuta IA: registra ejecuciones realizadas por el participante. Los planes multiagente y especificaciones de laboratorio necesitan un entorno adicional para implementarse.

## Datos

Sin cuentas ni servidor de análisis. El estado se guarda en localStorage del navegador. Un navegador privado, la limpieza de datos o falta de espacio pueden eliminar el progreso: conservar una copia JSON. Los archivos no se envían a un modelo o al repositorio. No incorporar datos personales identificables. Al abrir enlaces externos se aplican las condiciones del servicio correspondiente.

## Publicación

En GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**. Ejecutar el flujo **Comprobar y publicar laboratorio** desde Actions si no se inició automáticamente. El flujo ejecuta comprobaciones y publica únicamente los cuatro archivos de aplicación. Requiere Pages habilitado y permisos de Actions del repositorio.

## Comprobaciones

```sh
node --check core.js
node --check app.js
node --test tests/core.test.cjs
```

Aplicación sin dependencias externas de ejecución, fuentes remotas, claves ni analítica. ZIP sin compresión implementado con CRC-32 y nombres UTF-8.

La verificación inicial automatizada cubre generación de las ocho plantillas y cinco productos, validación de importaciones y límites, referencias de recursos y formato ZIP. No sustituye pruebas manuales de interfaz con teclado, dispositivos y descargas.

## Referencias de plataformas

- https://help.openai.com/en/articles/20001066-skills-in-chatgpt
- https://support.claude.com/en/articles/12512180-use-skills-in-claude

La interfaz y disponibilidad de los proveedores pueden cambiar. Un nombre de producto no implica patrocinio o certificación institucional del software.

© Prof. Dr. Pablo José Guerrero. 2026. Todos los derechos reservados. No se concede una licencia de redistribución de materiales de terceros.
