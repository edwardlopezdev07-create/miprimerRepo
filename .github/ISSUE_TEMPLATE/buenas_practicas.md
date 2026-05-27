---
name: Buenas prácticas

about: Recomendaciones y buenas prácticas del proyecto

title: "[Buenas prácticas]"

labels: documentation

assignees: ""
---

# 📝 Buenas prácticas

# 📘 Buenas Prácticas del Proyecto

Gracias por contribuir a este proyecto.  
Para mantener un código limpio, mantenible y escalable, sigue las siguientes buenas prácticas.

---

# 📂 Estructura del Proyecto

- Mantener una estructura clara y organizada.
- Separar lógica de negocio, configuración y componentes reutilizables.
- Evitar archivos excesivamente grandes.
- Usar nombres descriptivos para carpetas y archivos.

Ejemplo:

src/
├── components/
├── services/
├── utils/
├── hooks/
├── tests/

---

# 🧹 Estilo de Código

- Seguir un estándar de linting (`ESLint`, `Prettier`, etc.).
- Mantener formato consistente.
- Evitar código duplicado.
- Escribir funciones pequeñas y reutilizables.
- Usar nombres claros y descriptivos.

✅ Correcto:

```js
const calculateTotalPrice = (products) => {}