# Práctica 3: Automatización de Página Web con GitHub Pages

**Materia:** Electiva 2  
**Estudiante:** Adrian Francisco Brito Nelkitts  
**Usuario de GitHub:** [@Adrixn23](https://github.com/Adrixn23)  

---

## 🌐 Enlaces del Proyecto

* 🔗 **Repositorio en GitHub:** [https://github.com/Adrixn23/Practica3-Automatizacion-Web](https://github.com/Adrixn23/Practica3-Automatizacion-Web)
* 🚀 **Página Web en Vivo (GitHub Pages):** [https://adrixn23.github.io/Practica3-Automatizacion-Web/](https://adrixn23.github.io/Practica3-Automatizacion-Web/)

---

## 📋 Descripción de la Práctica

Esta práctica consiste en la creación de una página web estática *"Hola Mundo"* con integración y despliegue continuo (CI/CD) completamente automatizado desde GitHub hacia un servicio de hosting en la nube (GitHub Pages).

Cada cambio introducido en la rama principal (`main`) dispara de forma automática un flujo de trabajo (workflow) en **GitHub Actions**, el cual empaqueta y publica la versión más reciente del sitio web sin intervención manual.

---

## ⚙️ Flujo de Automatización (CI/CD)

1. **Commit & Push:** Se envían los cambios a la rama `main`.
2. **GitHub Actions Workflow (`deploy.yml`):**
   - Configura el entorno de ejecución para GitHub Pages.
   - Sube los artefactos estáticos (`index.html`, hojas de estilo y scripts).
   - Ejecuta el despliegue al entorno en la nube.
3. **Distribución en la Nube:** El sitio se encuentra disponible globalmente a través del CDN de GitHub Pages con certificado SSL/HTTPS activo.
