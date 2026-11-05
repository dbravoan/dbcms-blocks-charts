# dbravoan/dbcms-blocks-charts 1.0.0

## Qué hace

`dbravoan/dbcms-blocks-charts` (Bloques de gráficas, KPI y calculadora ROI.) Identifier Composer/CMS: `charts`.

## Requisitos y dependencias

- `dbravoan/dbcms-core` `^1.0`

## Instalación y activación

Añade el paquete con Composer. Los bloques se descubren vía `extra.dbcms.blocks`. Deben estar instalados/habilitados en la composición del proyecto (`cms.block_packages` / instalación CMS) para aparecer en el catálogo de secciones. Desactivar el propietario del bloque impide su ejecución conservando instancias.

## Configuración

Ninguno (sin `config/*.php` ni claves `.env` propias del paquete).

## Rutas

No aplica.

## Comandos Artisan

Ninguno.

## Permisos

No aplica (usan los de la entidad/editor que inserta el bloque).

## Privacidad y datos

No aplica de forma propia. El contenido que el editor introduzca en cada instancia sigue las políticas del propietario de la página/entidad.

## Plantillas y tipos aportados

Tipos registrados (`getType()`):

- `charts`
- `kpi`
- `roi`

Clases listadas en `composer.json` → `extra.dbcms.blocks`.

## Enlaces

- [Extensiones](../../../docs/EXTENSIONS.md)
- [Núcleo y extensiones](../../../specs/CORE_AND_EXTENSIONS.md)
- [README del núcleo](../../../packages/core/README.md)
- [README del monorepo](../../../README.md)
