# W Gestión Inmobiliaria - Checkpoint 1 (Versión Básica)

> 📌 **Estado de la Versión:** Entregable Oficial - Versión Básica ($50.000 CLP)  
> 🔒 **Estado de Desarrollo:** **Congelado / Línea Base**  
> *Esta versión constituye el alcance básico cerrado. Únicamente se aplican ajustes menores de textos o datos de contacto a solicitud del cliente.*

---

## 🌟 Descripción General
Landing page y catálogo digital de alto estándar para **W Gestión Inmobiliaria**, diseñada específicamente para el mercado de propiedades exclusivas en la Región de Valparaíso (Viña del Mar, Reñaca, Concón, Quilpué) y Santiago (Las Condes, Vitacura, Lo Barnechea).

---

## 💎 Componentes y Funcionalidades Incluidas (Checkpoint 1)

1. **Hero Monumental Limpio & Dinámico:**
   - Visualización panorámica a pantalla completa con fotografías HD de arquitectura residencial premium.
   - Rotación automática de 5 diapositivas con transiciones suaves cada 5 segundos.
   - Experiencia visual sin cajas pesadas ni elementos invasivos sobre la imagen.
   - Llamados a la acción directos (*Explorar Propiedades* y *Agendar Asesoría*).

2. **Selector de Servicios Automatizado:**
   - Pestañas centrales con alternancia automática cada 4.5 segundos:
     - 🏢 **Compra & Venta:** Gestión fiduciaria y comercialización de activos.
     - 🔑 **Arriendo Residencial:** Colocación fiduciaria y administración con perfilamiento riguroso.
     - 🛡️ **Administración de Copropiedades:** Gestión legal, operacional y financiera de edificios.
   - Pausa inteligente de lectura de 12 segundos al interactuar en cualquier punto de la página.
   - Estilo limpio y moderno sin líneas de progreso inferiores distractivas.

3. **Buscador & Filtros por Enclave:**
   - Filtrado rápido por Comuna (*Viña del Mar, Concón, Reñaca, Las Condes, Vitacura*).
   - Tipo de Operación y Tipo de Inmueble (*Departamento, Casa, Terreno, Oficina*).

4. **Catálogo de Propiedades & Ficha Detallada (Modal Autónomo):**
   - Tarjetas de presentación con imagen, valor en UF, metraje útil, dormitorios, baños y estacionamientos.
   - Modal pop-up de ficha técnica autónomo (`bg-[#0D121D]`), con galería de imágenes en miniatura, especificaciones y botón directo de contacto por WhatsApp.

5. **Flujo de Consignación en 6 Fases (`servicios.html`):**
   - Página independiente dedicada a explicar paso a paso el procedimiento fiduciario de W Gestión Inmobiliaria.

6. **Concierge Digital & Captación Inteligente:**
   - Botón de WhatsApp integrado.
   - Modal de engagement automático activado a los 2 minutos o al retornar al inicio: *"Nos interesa conversar. Cuéntanos si quieres más información"* con acceso directo a agendar reunión y contacto inmediato con un ejecutivo comercial.

7. **Lexicografía y Adaptación Local:**
   - Terminología 100% orientada al mercado chileno (UF, comunas, corredora, copropiedad, conserjería, tasación comercial).

---

## 🛠️ Tecnologías Utilizadas
- **HTML5 / CSS3 Moderno / Tailwind CSS**
- **JavaScript ES6+ / Anime.js**
- **Node.js HTTP Server (`server.js`)**
- **Phosphor Icons & Google Fonts (Playfair Display, Montserrat)**

---

## 🚀 Puesta en Marcha Local
```bash
# Iniciar servidor local
node server.js
```
El servidor responderá en `http://localhost:3600`.
