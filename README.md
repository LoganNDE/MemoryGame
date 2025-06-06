# 🧠 MemoryGame

## 🎮 Cómo funciona

- Se genera un tablero con cartas mezcladas por duplicado.
- El jugador puede levantar hasta dos cartas al mismo tiempo.
- Si las dos cartas coinciden, permanecen visibles.
- Si no coinciden, se giran de nuevo automáticamente.
- El juego continúa hasta emparejar todas las cartas.

## 🛠️ Tecnologías utilizadas

- **React 19** – Lógica de componentes y estado.
- **Vite** – Entorno de desarrollo rápido.
- **Tailwind CSS 4** – Estilos utilitarios y responsivos.
- **js-confetti** – Efectos visuales al ganar.

## 📂 Estructura del proyecto

```
src/
├── App.jsx          # Componente principal con la lógica del juego
├── components/
│   └── Card.jsx     # Representación visual de una carta
├── logic.js         # Cartas disponibles y configuración inicial
└── App.css          # Estilos base con Tailwind
```

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio y entra en la carpeta:

```bash
git clone https://github.com/tuusuario/05-memory-game.git
cd 05-memory-game
```

2. Instala las dependencias:

```bash
npm install
```

3. Ejecuta el servidor de desarrollo:

```bash
npm run dev
```

4. Abre tu navegador en [http://localhost:5173](http://localhost:5173)

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
