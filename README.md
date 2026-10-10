# Manager Library — Sitio Web Público (Page)

> **Prueba técnica · Ficha ADSO 3413974**  
> Portal web público estático de presentación para la comunidad y usuarios de *Manager Library*.

---

## 1. Características

* **Independencia Total (Tarea T-23):** Funciona como un sitio estático desacoplado. No requiere conexión directa con la base de datos ni con la API para su renderizado, garantizando alta disponibilidad y carga instantánea.
* **Diseño Responsivo:** Diseñado y optimizado para visualización en dispositivos móviles y de escritorio.
* **Integración:** Proporciona accesos directos hacia el catálogo de la biblioteca y hacia la aplicación interna de gestión (`http://localhost:5173`).

---

## 2. Ejecución y Despliegue

### En Docker Compose:
El contenedor `library_page` sirve el portal en el puerto `8080`:
```bash
docker compose -f test-manager-library-3413974-infra/docker-compose.yml up -d page
```
* **Acceso web:** [http://localhost:8080](http://localhost:8080)

### En Servidor Local:
Puede servirse con cualquier servidor estático o abriendo directamente `index.html` en un navegador web.
