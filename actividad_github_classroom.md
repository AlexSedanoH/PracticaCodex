# Plantilla de Propuesta de Tarea: Práctica Temática Pequeña en Entorno de Sistemas

## 1) Título de la práctica

**Diseño de Práctica Temática Pequeña para GitHub Classroom**

> Puedes personalizar el título final de tu propuesta con uno de estos estilos:
> - **Mini Toolkit en ARM64**
> - **Asistente de Estudio en Terminal**
> - **Reporteador de Información del Sistema**
> - **Organizador de Archivos**
> - **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general

En esta actividad, vas a **diseñar y documentar** la propuesta de un proyecto pequeño con temática libre, pensado para ejecutarse en terminal y administrarse con GitHub Classroom.

Tu objetivo principal es **planear bien el proyecto antes de programar**: justificar el caso de uso, delimitar alcance, proponer estructura de repositorio y definir pruebas mínimas.

### Lenguaje principal (elige uno)
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** úsalo solo si tu idea es **muy pequeña y acotada** (por ejemplo: operaciones aritméticas simples, manejo básico de entrada/salida o ejercicios cortos de lógica).

### Enfoque de la actividad
- Prioridad alta: **documentación, planeación y claridad técnica**.
- Prioridad media: prototipo mínimo opcional.
- Prioridad baja: implementación extensa.

### Restricciones del proyecto
Para mantener la práctica viable con herramientas gratuitas y límites de uso de IA:
- Evita proyectos grandes.
- No uses frameworks pesados.
- No uses APIs pagadas.
- No uses bases de datos.
- No uses servicios de nube.
- No uses contenedores.
- No agregues dependencias complejas.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir, como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcional (si decides incluir prototipo mínimo):
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio

Usa esta estructura base como referencia:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `main.<ext>` depende de tu lenguaje: `s`, `c`, `py` o `sh`.

---

## 5) Contenido mínimo esperado por archivo

### `README.md`
Debe incluir:
1. Nombre tentativo del proyecto.
2. Lenguaje principal elegido y por qué.
3. Descripción corta del problema que resolverá.
4. Alcance pequeño del proyecto (qué sí y qué no hará).
5. Lista de archivos clave del repositorio.

### `docs/propuesta.md`
Debe incluir:
1. **Tema** de la práctica.
2. **Objetivo general** (1 párrafo).
3. **Objetivos específicos** (3 a 5 bullets).
4. **Usuarios o contexto de uso**.
5. **Entradas, proceso y salidas** esperadas.
6. **Alcance y límites** (muy importante).
7. **Justificación técnica** del lenguaje elegido.

### `docs/caso_de_uso.md`
Debe incluir:
1. Nombre del caso de uso principal.
2. Actor principal.
3. Precondiciones.
4. Flujo principal (paso a paso).
5. Flujos alternos o errores esperados.
6. Resultado esperado.

### `docs/estructura_repositorio.md`
Debe incluir:
1. Árbol de carpetas propuesto.
2. Función de cada carpeta/archivo.
3. Convenciones de nombres (archivos, scripts, pruebas).
4. Estrategia breve de versionamiento (commits claros y pequeños).

### `docs/plan_de_pruebas.md`
Debe incluir:
1. Criterios de aceptación mínimos.
2. Al menos 5 casos de prueba (tabla recomendada).
3. Comandos de ejecución esperados.
4. Resultados esperados por caso.
5. Riesgos técnicos y cómo mitigarlos.

---

## 6) Alcance sugerido (para mantenerlo pequeño)

Tu propuesta debe poder completarse en una práctica corta. Como guía:
- 1 funcionalidad principal.
- 1 a 2 funcionalidades secundarias.
- Entrada/salida por terminal.
- Máximo 1 script de ejecución.
- Máximo 1 módulo principal (o archivo principal) para la primera versión.

---

## 7) Criterios de evaluación sugeridos

| Criterio | Ponderación |
|---|---:|
| Claridad y calidad de documentación | 35% |
| Coherencia del caso de uso y alcance | 25% |
| Estructura del repositorio y orden técnico | 20% |
| Plan de pruebas (calidad y factibilidad) | 15% |
| Prototipo mínimo opcional (si existe) | 5% |

---

## 8) Checklist de entrega (para el estudiante)

Marca cada punto antes de enviar:

- [ ] Elegí un lenguaje principal (`ARM64`, `C`, `Python` o `Bash`).
- [ ] Mi proyecto es pequeño y realista para una práctica corta.
- [ ] Documenté el alcance y también lo que **no** haré.
- [ ] Incluí todos los archivos obligatorios en `docs/`.
- [ ] Definí un caso de uso principal completo.
- [ ] Incluí al menos 5 casos de prueba con resultados esperados.
- [ ] El repositorio tiene estructura limpia y consistente.

---

## 9) Instrucciones de publicación en GitHub Classroom (docente)

1. Crear la actividad en GitHub Classroom usando este documento como guía principal.
2. Indicar al alumnado que esta entrega es de **diseño y documentación**.
3. Solicitar commits parciales por secciones (README, propuesta, caso de uso, pruebas).
4. Evaluar primero documentación; código solo como complemento opcional.

---

## 10) Formato de entrega

- Entrega por repositorio en GitHub Classroom.
- Todo en Markdown.
- Redacción técnica clara, concreta y sin ambigüedades.
- Si agregas código, debe ser mínimo y alineado con la propuesta.
