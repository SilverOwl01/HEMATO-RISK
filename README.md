# 🩸 HEMATO-RISK: Evaluador Integrado de Riesgo Hematológico (v3 - Neumorfismo)

**HEMATO-RISK** es una aplicación web interactiva y dinámica diseñada para profesionales de la salud. Permite la estratificación de riesgo rápida y precisa de pacientes hospitalizados o ambulatorios, integrando múltiples escalas de riesgo trombótico y hemorrágico en una única interfaz.

## ✨ Características Principales

* **Evaluación Multi-Escala:** Calcula simultáneamente las puntuaciones de las principales herramientas de riesgo.
* **Diseño Neumórfico:** Interfaz de usuario moderna y limpia, optimizada para la claridad clínica.
* **Cálculos Automáticos:** Genera indicadores clave como el Índice de Masa Corporal (IMC) y el Aclaramiento de Creatinina (ClCr) por Cockcroft-Gault.
* **Trazabilidad:** Proporciona un desglose detallado (trace) de los puntos asignados para cada escala de riesgo, garantizando transparencia en la decisión clínica.
* **Persistencia de Datos:** Permite guardar las evaluaciones localmente en el navegador (`localStorage`).
* **Exportación de Datos:** Funcionalidad para exportar el historial de evaluaciones a formato CSV (Excel) para análisis posteriores o integración con registros.

## 📊 Escalas de Riesgo Incluidas

La herramienta proporciona una evaluación integrada cubriendo cinco áreas clave:

| Escala | Tipo de Riesgo | Objetivo Clínico | Clasificaciones |
| :--- | :--- | :--- | :--- |
| **Caprini** | Trombótico (TEV) | Riesgo de TEV perioperatorio. | Muy Bajo, Bajo, Moderado, Alto. |
| **PADUA** | Trombótico (TEV) | Riesgo de TEV en pacientes médicos hospitalizados. | Bajo, Alto. |
| **IMPROVE VTE** | Trombótico (TEV) | Riesgo de TEV general en pacientes hospitalizados. | Bajo, Moderado, Alto. |
| **IMPROVE Bleeding** | Hemorrágico | Riesgo de sangrado mayor. | Bajo, Alto. |
| **Vienna** | Recurrencia de TEV | Riesgo de TEV recurrente (para seguimiento). | Bajo, Alto. |

## 🚀 Uso e Instalación

Dado que **HEMATO-RISK** es un archivo HTML plano con CSS y JavaScript integrado, su uso es sumamente sencillo:

### 1. Despliegue (Hosting)

Simplemente sube el archivo `HEMATO-RISK-v3.html` a un servidor web.

**Opción Rápida (Recomendada para Desarrollo/Prueba):**

1.  Abre tu navegador web.
2.  Arrastra el archivo `HEMATO-RISK-v3.html` directamente a la ventana del navegador.

### 2. Contribución a GitHub (Subir el Archivo)

Para alojar esta herramienta en tu cuenta de GitHub, puedes seguir estos pasos:

1.  Crea un nuevo repositorio en GitHub (ej. `hemato-risk`).
2.  Sube el archivo `HEMATO-RISK-v3.html` directamente a la raíz del repositorio usando la opción **"Add file" > "Upload files"**.
3.  Activa **GitHub Pages** en la configuración del repositorio, seleccionando la rama `main` (o `master`) como fuente. Tu aplicación estará disponible en una URL pública (ej. `https://usuario.github.io/hemato-risk`).

## ⚙️ Tecnologías

* **HTML5**
* **CSS3** (Estilo Neumorfismo)
* **JavaScript (Vanilla JS)** (Para todos los cálculos y la persistencia de datos)

## ✍️ Autores y Referencias

### Desarrolladores y Contribuyentes
* MPSS Enrique Aguilar Camacho - Instituto Nacional de Cardiología Ignacio Chávez, Ciudad de México, México.
* Dr. Flavio A. Grimaldo Gómez - Instituto Nacional de Cardiología Ignacio Chávez, Ciudad de México, México.

### Referencias Clínicas
El desarrollo de esta herramienta se basa en los siguientes artículos y validaciones:
1.  Cronin, M., et al. (2019). Completion of the updated Caprini risk assessment model (2013 version).
2.  Decousus, H., et al. (2011). IMPROVE Bleeding Risk. Chest.
3.  Spyropoulos, A. C., et al. (2011). IMPROVE VTE Risk. Chest.
4.  Barbar, S., et al. (2010). Padua Prediction Score. J Thromb Haemost.

---

**NOTA:** Esta herramienta es un apoyo informativo y no sustituye el juicio ni la evaluación clínica de un médico.
