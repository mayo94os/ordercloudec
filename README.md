# 👜 Carteras E-commerce con OrderCloud + Webflow + Make

Este proyecto tiene dos propósitos:
1. Construir un MVP funcional de tienda online de carteras usando herramientas gratuitas.
2. Documentar el proceso en forma de tutoriales para emprendedores o desarrolladores que quieran aprender.

---

## 🔧 Stack utilizado

- **OrderCloud (sandbox)** – Headless e-commerce backend (productos, órdenes, usuarios).
- **Webflow** – Frontend visual para mostrar el catálogo y manejar el checkout.
- **Make** – Automatización entre OrderCloud, Webflow, Stripe y CRM.
- **Stripe** – Procesador de pagos.
- **HubSpot** (tentativo) – CRM gratuito para retención de clientes y campañas.

---

## 📁 Estructura del repositorio

- `/make-scenarios`: Escenarios exportados de Make.
- `/ordercloud-config`: Configuración inicial del marketplace, catálogos, buyers, etc.
- `/webflow-frontend`: Códigos y snippets usados en Webflow.
- `/docs/blog-posts`: Borradores de tutoriales paso a paso.
- `/assets`: Capturas e imágenes de ayuda.

---

## 🚀 Plan de trabajo (roadmap MVP)

### Etapa 1: Configuración inicial
- [x] Crear proyecto en OrderCloud (sandbox)
- [x] Crear catálogos y productos básicos
- [ ] Conectar OrderCloud a Webflow vía Make (catálogo → frontend)

### Etapa 2: Flujo de compra
- [ ] Crear buyer users y manejo de carrito
- [ ] Conectar checkout en Webflow con OrderCloud y Stripe
- [ ] Registrar órdenes correctamente en el backend

### Etapa 3: CRM y automatización
- [ ] Elegir e integrar CRM (HubSpot o Salesforce)
- [ ] Capturar correos y datos de clientes
- [ ] Activar flujos automáticos de retención en Make

### Etapa 4: Blog y documentación
- [ ] Escribir tutoriales técnicos paso a paso
- [ ] Publicar primeros posts en blog personal o Medium

---

## 📄 Licencia
MIT – uso libre educativo y personal.
