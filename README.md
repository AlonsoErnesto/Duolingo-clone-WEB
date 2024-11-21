# Lingo - Duolingo Clone  
Lingo es una aplicación web inspirada en Duolingo, diseñada para practicar y aprender nuevos idiomas a través de lecciones interactivas. Este proyecto aprovecha tecnologías modernas para crear una experiencia fluida, accesible y altamente personalizable.

## **Características principales**  
- Gestión de usuarios y autenticación segura.
- Lecciones interactivas con retroalimentación visual y sonora.
- Puntuaciones y progreso del usuario.
- Diseño moderno y responsivo.
- Panel de administración para gestionar cursos y lecciones.

---

## **Tecnologías utilizadas**  

### **Framework y Entorno**
- **Next.js 14**  
  Framework para aplicaciones web con renderizado del lado del servidor y generación de páginas estáticas.  
  - Ofrece soporte para rutas, manejo de datos y renderizado optimizado.
  - Mejora el rendimiento y la experiencia de usuario.  

- **React 18**  
  Librería para construir interfaces de usuario dinámicas.  
  - Implementación de componentes reutilizables y declarativos.  

---

### **Autenticación**
- **@clerk/nextjs**  
  Maneja autenticación de usuarios, registro y gestión de sesiones.  
  - Soporte para múltiples proveedores de autenticación.  
  - Fácil integración con Next.js.  

---

### **Base de Datos**
- **Drizzle ORM**  
  ORM de última generación para gestionar datos de manera sencilla y tipada.  
  - Soporte para migraciones y consultas personalizadas.  
  - Integración con bases de datos PostgreSQL usando `@neondatabase/serverless`.  

- **Neon**  
  Base de datos PostgreSQL como servicio serverless.  
  - Optimizado para aplicaciones modernas con alta escalabilidad.  

---

### **UI y Componentes**
- **Radix UI**  
  Componentes accesibles y personalizables como `Dialog`, `Progress`, `Avatar`, `Separator`, y `Slot`.  
  - Mejora la accesibilidad y consistencia del diseño.  

- **Lucide React**  
  Librería de iconos SVG reactivos.  
  - Ligera y optimizada para aplicaciones modernas.  

- **React Circular Progressbar**  
  Visualización de progreso circular para gamificar el aprendizaje.  

- **React Confetti**  
  Efecto visual al completar logros o lecciones.  

- **Sonner**  
  Sistema de notificaciones sencillo y elegante.  

- **TailwindCSS**  
  Framework CSS para diseño de interfaces modernas y responsivas.  
  - Complementos utilizados:  
    - **tailwind-merge**: Combina y sobrescribe clases CSS.  
    - **tailwindcss-animate**: Añade animaciones predefinidas para mejorar la experiencia visual.  

---

### **Gestión de Estado**
- **Zustand**  
  Librería para gestionar el estado global de la aplicación.  
  - Simple, escalable y eficiente.  

- **React Use**  
  Colección de hooks para funcionalidades comunes.  
  - Simplifica el manejo del ciclo de vida y eventos en React.  

---

### **Panel de Administración**
- **React Admin**  
  Framework para construir interfaces administrativas basadas en datos.  
  - Soporte para CRUD, manejo de recursos y autenticación.  

- **RA Data Simple Rest**  
  Proveedor de datos para integrar React Admin con una API REST sencilla.  

---

### **Integraciones**
- **Stripe**  
  Herramienta para gestionar pagos y suscripciones de manera segura.  
  - Implementación para modelos de negocio basados en suscripción.  

---

### **Scripts Personalizados**
- **Drizzle Kit**  
  Scripts preconfigurados para gestionar la base de datos:  
  - `db:studio`: Interfaz gráfica para explorar datos.  
  - `db:push`: Migraciones automáticas.  
  - `db:seed`: Generación de datos iniciales.  
  - `db:reset`: Reinicio completo de la base de datos.  

---
