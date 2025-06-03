## 🧪 Estrategia de Pruebas

### 🎯 Objetivo General

Definir una estrategia de pruebas manual que garantice la calidad funcional, la experiencia de usuario y la estabilidad del sitio web **GoCuotas**, a través de la ejecución planificada de casos de prueba orientados a validar los principales flujos del sistema.

---

## 🧪 Resumen de Casos de Prueba

| Nº  | ID           | Funcionalidad                         | Descripción breve                            | Prioridad | Estado       |
|-----|--------------|----------------------------------------|----------------------------------------------|-----------|--------------|
| 1   | TC-GC-001    | Registro de usuario                    | Validación de formulario de registro         | Alta      | Ejecutado    |
| 2   | TC-GC-002    | Inicio de sesión                       | Login con credenciales válidas/erróneas      | Alta      | Ejecutado    |
| 3   | TC-GC-003    | Navegación general                     | Prueba de flujo entre secciones del sitio    | Alta      | Ejecutado    |
| 4   | TC-GC-004    | Página de inicio y contenido informativo | Verificación de textos, secciones y banners | Media     | Ejecutado    |
| 5   | TC-GC-005    | Compatibilidad navegadores/dispositivos | Validar diseño y funcionamiento responsive  | Alta      | Ejecutado    |
| 6   | TC-GC-006    | Enlaces, formularios y CTAs            | Validación de formularios y botones activos  | Alta      | Ejecutado    |
| 7   | TC-GC-007    | Tiempo de carga de páginas clave       | Medición de performance en páginas clave     | Alta      | Ejecutado    |

---
### 🧱 Alcance de la Estrategia

Se evaluarán los siguientes aspectos:

- Flujo de alta para usuarios (clientes y comercios).
- Flujo de navegación general.
- Página de inicio y contenido informativo.
- Compatibilidad entre navegadores y dispositivos.
- Validación de enlaces, formularios y llamadas a la acción.
- Tiempo de carga de páginas clave.


---

### 🧭 Tipos de Pruebas Aplicadas

| Tipo de Prueba           | Descripción                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Funcional**            | Validación de los flujos principales del sitio: navegación, formularios.    |
| **Exploratoria**         | Exploración libre para detectar fallos no previstos.                        |
| **Cross-browser**        | Pruebas en diferentes navegadores (Chrome, Firefox, Edge, Brave).           |
| **Responsiva**           | Verificación en tamaños de pantalla comunes (desktop, tablet, mobile).      |
| **Accesibilidad básica** | Validación visual, contraste y navegación por teclado.                      |
| **Usabilidad**           | Observación de la claridad, legibilidad y accesibilidad de los elementos.   |

---

### 🛠 Herramientas Utilizadas

- **Inspección de UI**: Chrome DevTools, Brave DevTools.
- **Pruebas responsivas**: Modo Responsive de cada navegador.
- **Auditoría de performance/accesibilidad**: Lighthouse.
- **Captura y gestión de evidencias**: Loom + GitHub.
- **Gestión de casos de prueba**: GitHub + Jira.
- **Casos automatizados**: Cypress
  
---

### ✅ Criterios de Aceptación

- Todos los flujos críticos deben ejecutarse sin errores visibles.
- No deben existir enlaces rotos o formularios que no respondan.
- El sitio debe cargar en menos de **3 segundos** en condiciones normales.
- El sitio debe comportarse adecuadamente en los navegadores definidos.
- Los formularios deben validar correctamente campos obligatorios y formatos.

---

### 🚫 Criterios de Salida

- Finalización de los casos de prueba definidos.
- Cierre o documentación de todos los bugs encontrados.
- Validación de los resultados por checklist.
- Generación de reporte final del análisis QA manual.
