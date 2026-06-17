# CapacitaciónTS

## Descripción general

TypeScript es una extensión de JavaScript que permite trabajar con tipos de datos, detectar errores durante el desarrollo y escribir código más seguro y mantenible. 
## Unidades revisadas

### Unidad 2: Configuración inicial, `any` y `tsconfig.json`

Se revisa la creación de proyectos con Vite, seleccionando la opción Vanilla y TypeScript, además del papel del archivo `tsconfig.json` como configuración principal del compilador.

También se estudia el tipo especial `any`, el cual permite que una variable tenga cualquier tipo de dato. Aunque puede parecer práctico, se recomienda evitarlo porque desactiva la verificación de tipos de TypeScript y puede permitir errores difíciles de detectar. Además, se destaca la importancia de habilitar la opción `strict` para aprovechar mejor las ventajas del tipado.

### Unidad 3: TypeScript ESLint y calidad de código

Esta unidad presenta TypeScript ESLint como una herramienta de análisis estático que ayuda a encontrar y corregir problemas de calidad en el código TypeScript.

Se revisa cómo el compilador de TypeScript, junto con reglas de ESLint, permite evitar el uso de `any` de forma implícita o explícita. También se explican comentarios especiales como `@ts-ignore`, `@ts-nocheck` y `@ts-expect-error`, los cuales permiten desactivar temporalmente la verificación de tipos, aunque se recomienda usarlos con cuidado. Finalmente, se estudian reglas como `ban-ts-comment` y `ban-types`, que ayudan a mantener un código más limpio y consistente.

### Unidad 4: Tipos primitivos, anotaciones e inferencia

Esta unidad aborda los tipos primitivos que TypeScript ofrece para trabajar con valores básicos de JavaScript, como `string`, `number`, `boolean`, `undefined`, `null`, `bigint` y `symbol`.

Se estudia cómo anotar variables y parámetros indicando explícitamente su tipo, por ejemplo `const username: string = "Alex"`. También se revisa la inferencia de tipos, que permite a TypeScript deducir automáticamente el tipo de una variable a partir del valor asignado. Esta unidad muestra cómo TypeScript mejora la experiencia de desarrollo mediante autocompletado y prevención de errores al usar argumentos con tipos incorrectos.

### Unidad 5: Union types y narrowing

Esta unidad introduce los tipos unión, que permiten que una variable acepte más de un tipo de dato. Por ejemplo, `string | number` indica que un valor puede ser texto o número.

También se estudia el concepto de narrowing, que ocurre cuando TypeScript puede deducir un tipo más específico a partir de una condición del código. Se explica que los tipos de TypeScript existen durante el desarrollo y desaparecen al compilarse a JavaScript, mientras que operadores como `typeof` sí se ejecutan en tiempo real. Esta unidad es importante para manejar datos que pueden venir en distintos formatos.

### Unidad 6: Type aliases

Esta unidad presenta los type aliases, que permiten crear nombres personalizados para tipos de datos. Por ejemplo, `type StringOrNumber = string | number` permite reutilizar una definición de tipo de forma más clara y ordenada.

Los alias de tipo ayudan a mejorar la legibilidad del código y facilitan la organización de estructuras de datos más complejas. Además, se menciona que los type aliases no pueden cambiarse después de ser definidos.

## Relación con el proyecto

Los contenidos de esta capacitación aportan una base importante para desarrollar un dashboard interactivo más seguro y organizado.

El uso de TypeScript permite definir correctamente los tipos de datos del dataset, como variables numéricas para horas de uso de redes sociales, sueño, estrés o ansiedad, y variables categóricas como género, plataforma utilizada o nivel de interacción social. Esto ayuda a evitar errores al procesar datos, calcular indicadores, aplicar filtros y construir visualizaciones.

Además, herramientas como `tsconfig.json`, el modo `strict`, TypeScript ESLint, los tipos primitivos, los union types y los type aliases permiten estructurar mejor el código del dashboard, mejorar la mantenibilidad del proyecto y reducir errores durante el desarrollo de la aplicación web.
