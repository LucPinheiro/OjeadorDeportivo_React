# Ojeador Deportivo: App React ⚽️

Aplicación web (React) pensada para conectar **ojeadores** y **familias de jóvenes futbolistas**.  
Las familias crean perfiles de jugadores con características, historial, fotos y vídeos; los ojeadores pueden consultar perfiles y **enviar solicitudes de contratación**. :contentReference[oaicite:1]{index=1}

---

## 🚀 Descripción

- **Ojeadores** y **familias** se registran para ponerse en contacto. :contentReference[oaicite:2]{index=2}  
- Las **familias** pueden crear perfiles individuales de sus hijos (jugadores), incluyendo:
  - características del jugador
  - historial de clubes
  - fotos y vídeos :contentReference[oaicite:3]{index=3}  
- Los **ojeadores** pueden acceder al detalle del perfil, visualizar el contenido y enviar una **solicitud de contratación**. :contentReference[oaicite:4]{index=4}  

---

## 👥 Tipos de usuario y permisos

### Usuario anónimo
- Puede ver la landing y **realizar búsquedas** de jugadores.
- No puede acceder al catálogo de vídeos ni contactar con el jugador. :contentReference[oaicite:5]{index=5}  

### Usuario Ojeador (registrado)
- Completa su perfil con sus datos.
- Perfil **privado** (no visible para otros usuarios registrados).
- Puede buscar jugadores desde su perfil y ver resultados en “Buscar” con filtros.
- Acceso a fotos y vídeos del jugador.
- Puede **enviar solicitud de contratación** al jugador. :contentReference[oaicite:6]{index=6}  

### Usuario Familia (registrado)
- Completa sus datos.
- Tras completar el proceso, puede añadir perfiles.
- Cada familia puede mantener **hasta 3 perfiles** de jugadores. :contentReference[oaicite:7]{index=7}  

### Perfil Jugador
- Formulario de características + avatar.
- Fotos y vídeos sujetos a requisitos (tamaño, duración, formato…).
- Opción de **editar perfil** (formulario y descripción). :contentReference[oaicite:8]{index=8}  

---

## 🔎 Búsqueda de jugadores
- Muestra un resumen de jugadores con perfil activo.
- Incluye opciones para **filtrar resultados**.
- Permite acceder al detalle de cada perfil. :contentReference[oaicite:9]{index=9}  

---

## 🧩 Estructura sugerida del proyecto
## 📁 Estructura recomendada del repositorio
```text
/
├── src/                 # Código fuente
│   ├── assets/          # Imágenes, vídeos y recursos estáticos
│   ├── components/      # Componentes reutilizables de la aplicación
│   ├── pages/           # Vistas principales (Landing, Perfil, Búsqueda, etc.)
│   ├── services/        # Lógica de acceso a datos y servicios (API, auth, etc.)
│   ├── styles/          # Hojas de estilo (CSS / SCSS)
│   ├── App.jsx          # Componente raíz
│   └── main.jsx         # Punto de entrada de la aplicación
├── public/              # Archivos públicos (index, iconos, etc.)
├── package.json         # Dependencias y scripts
├── package-lock.json    # Lock de dependencias (si aplica)
├── README.md            # Documentación del proyecto
└── .gitignore           # Archivos ignorados por Git





