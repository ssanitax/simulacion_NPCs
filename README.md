# 🟢 Shrek-Colisiones: Simulación de NPCs 16:9

Simulación visual de alto rendimiento desarrollada íntegramente con **HTML5, CSS3 y JavaScript Vanila**. Este proyecto traslada una lógica compleja de colisiones y trigonometría originalmente escrita en Python al entorno del navegador, permitiendo ejecutar 500 agentes simultáneos de forma fluida.

---

## 🚀 Demo en Vivo
Puedes ver la simulación funcionando aquí:  
👉 https://ssanitax.github.io/simulacion_NPCs/

---

## 🛠️ Características Principales

* **Lógica de Movimiento**: Cada NPC calcula su trayectoria usando funciones trigonométricas ($Math.cos$ y $Math.sin$) y posee una variación de ángulo aleatoria para simular un comportamiento errático natural.
* **Contenedor cinemático**: La simulación está restringida a un "Viewport" con relación de aspecto **16:9** centrado, que actúa como zona de colisión.
* **Optimización GPU**: 
    * Uso de `requestAnimationFrame` para sincronización con los hercios del monitor.
    * Uso de `transform: translate()` para reducir la carga de CPU y delegar el renderizado a la tarjeta gráfica.
* **Cero Dependencias**: No requiere servidores, APIs externas ni librerías como jQuery o React.

## 📂 Estructura del Proyecto

```text
└── ssanitax-colisiones/
    ├── juegoshrek.html
    └── shrek.jpg
