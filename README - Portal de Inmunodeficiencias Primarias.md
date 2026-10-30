# 🛡️ Portal Integral de Inmunodeficiencias Primarias (IDP)

Un sitio web interactivo e integral diseñado para la divulgación, educación e información clínica sobre las **Inmunodeficiencias Primarias (IDP)** o **Errores Congénitos de la Inmunidad (ECI)**. 

El contenido está estructurado a partir de las recomendaciones e información oficial de las tres organizaciones principales en la materia:
* **IDF** ([Primary Immune Deficiency Foundation](https://primaryimmune.org/))
* **Info4PI** ([Jeffrey Modell Foundation](https://www.info4pi.org/))
* **FUMENI** ([Fundación Mexicana para Niños y Niñas con Inmunodeficiencias](https://fumeni.org.mx/))

---

## 🎯 Secciones y Perfiles de Usuario

La plataforma está dividida en tres perfiles interactivos accesibles mediante pestañas dinámicas en la barra superior:

### 1. 🎓 Estudiantes (Académico y Ciencia)
* **Concepto y Epidemiología:** Definiciones sobre Errores Congénitos de la Inmunidad y prevalencia global.
* **Clasificación Oficial de la IUIS:** Desglose en las categorías principales (Deficiencias combinadas, humorales, desregulación inmune, fagocíticas, inmunidad innata y complemento).
* **Fisiopatología Genética:** Tabla comparativa con genes afectados (ej. *BTK*, *IL2RG*, *CYBB*), mecanismos moleculares y hallazgos clave de laboratorio.

### 2. 🩺 Médicos (Práctica Clínica y Diagnóstico)
* **Algoritmo Diagnóstico:** Flujo secuencial de 4 niveles (Biometría Hemática, Inmunoglobulinas séricas, respuesta de anticuerpos y citometría/genética).
* **Calculadora de Dosis de Inmunoglobulina:** Herramienta interactiva en JavaScript para estimar la dosis mensual en gramos y volumen en mL de IGIV/IGSC según el peso del paciente.
* **Diagnóstico Diferencial:** Guía rápida para descartar pérdidas proteicas secundarias (Síndrome Nefrótico, Enteropatía) y advertencias críticas de vacunas contraindicadas (virus vivos atenuados).
* **Modalidades Terapéuticas:** Reemplazo inmunológico, profilaxis antimicrobiana y tratamiento curativo (TCPH/Terapia génica).

### 3. 👨‍👩‍👧 Familiares (Lenguaje Accesible)
* **Explicación Sencilla:** Conceptos explicados con metáforas comprensibles, desmitificando falsas creencias (no contagioso, no causado por el frío).
* **Lista Interactiva de las 10 Señales de Alarma:** Checkbox interactivo (basado en Info4PI y JMF) con contador y recomendaciones inmediatas.
* **Preguntas Frecuentes (FAQs):** Respuestas a dudas cotidianas sobre escuela, vacunas y curabilidad.
* **Directorio de Apoyo:** Enlaces y accesos a FUMENI, IDF e Info4PI.

---

## 🚀 Tecnologías Utilizadas

* **HTML5 Semantic Markup:** Estructura limpia y accesible.
* **Tailwind CSS (via CDN):** Diseño moderno, responsivo y adaptado para dispositivos móviles.
* **Lucide Icons:** Iconografía médica e interactiva.
* **JavaScript (Vanilla):** Lógica interactiva para la calculadora de dosis, conmutación de pestañas y lista de verificación de señales de alarma.
* **Google Fonts:** Tipografías *Inter* y *Outfit*.

---

## 💻 Instrucciones de Uso e Instalación

1. Descarga el archivo `index.html` generado.
2. Abre el archivo directamente en cualquier navegador web moderno (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge). No requiere un servidor backend ni instalación de paquetes adicionales (funciona con librerías vía CDN).
3. Asegúrate de contar con una conexión activa a Internet la primera vez para cargar los estilos de Tailwind CSS, los íconos e imágenes tipográficas.

---

## ⚠️ Descargo de Responsabilidad (Disclaimer)

Este proyecto tiene fines exclusivamente **educativos, informativos y de concientización**. La información y herramientas provistas (como la calculadora de dosis) no sustituyen la valoración, diagnóstico ni prescripción médica especializada realizada por un médico inmunólogo o pediatra certificado.