# 📻 Echo Charlie Pad - Radio Log Manager

**Echo Charlie Pad** is a standalone web-based application for logging and visualizing radio station data. Built with React and Tailwind CSS, it offers a user-friendly interface to manage radio logs, visualize signal strength, and export/import data. Perfect for radio enthusiasts tracking frequencies and stations! 🌐

---

## 🌟 Features

- **Log Management** 📝: Add, edit, delete, and filter radio logs by band, frequency, or country.
- **Interactive Chart** 📊: Visualize signal strength vs. frequency with a dynamic scatter plot.
- **Dark/Light Mode** 🌙☀️: Toggle between themes for comfortable viewing.
- **Data Import/Export** 💾: Support for JSON and XLSX formats to save or load logs.
- **Responsive Design** 📱: Works seamlessly on desktop and mobile devices.
- **Pagination & Sorting** 🔍: Efficiently navigate logs with sorting by date or frequency.
- **Cell Color Toggle** 🎨: Enable/disable frequency cell colors for customization.

---

## 🚀 Strengths

- **Performance** ⚡: Optimized with React hooks (`useMemo`, `useEffect`) to handle thousands of logs.
- **Usability** 🖱️: Intuitive UI with ARIA labels, tooltips, and a military aesthetic via "Black Ops One" font.
- **Flexibility** 🔧: Supports kHz/MHz units, multiple bands (VLF to UHF), and SSB/AM modulation tracking.
- **Security** 🔒: Sanitizes user inputs with DOMPurify and validates data for safe JSON/XLSX imports.

---

## 🛠️ Usability

Echo Charlie Pad is designed for radio hobbyists and professionals. Key usability features include:

- **Easy Input** ✍️: Form-based log entry with real-time band detection based on frequency.
- **Filtering & Search** 🔎: Quickly find logs by band, station name, or country.
- **Chart Customization** 📈: Filter chart by band or unit (kHz/MHz) with clear tooltips.
- **Accessible** ♿: ARIA labels and semantic HTML enhance screen reader support.

---

## 🔐 Security

- **Input Sanitization** 🛡️: Uses DOMPurify to prevent XSS attacks in station names, notes, and other text fields.
- **Data Validation** ✅: Strict validation for JSON/XLSX imports ensures only valid logs are processed.
- **Local Storage** 💽: Safely stores logs in the browser with error handling for corrupted data.
- **No Server-Side** 🌍: Purely client-side, reducing risks of server vulnerabilities.

---

## 🖥️ Installation & Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/aisurf3r/EchoCharlie-Pad.git
   ```
2. **Open** `index.html`:
   - Serve via a local server (e.g., `npx serve`) or open directly in a browser.
3. **Start Logging**:
   - Add logs via the form, filter/search, and visualize data in the chart.

No dependencies needed beyond a modern browser! 🏃

---

## 🤝 Contributing

Contributions are welcome! Fork the repo, make changes, and submit a pull request. Check the issues for tasks or suggest features.

---

## 📜 License

Licensed under the MIT License. See LICENSE for details.

---

## 👨‍💻 Author

Developed by **aisurf3r**. Follow my GitHub for more projects! 🚀

---

# 📻 Echo Charlie Pad - Gestor de Registros de Radio

**Echo Charlie Pad** es una aplicación web standalone para registrar y visualizar datos de emisoras de radio. Construida con React y Tailwind CSS, ofrece una interfaz amigable para gestionar registros, visualizar la intensidad de señal y exportar/importar datos. ¡Ideal para aficionados a la radio que rastrean frecuencias y emisoras! 🌐

---

## 🌟 Características

- **Gestión de Registros** 📝: Añade, edita, elimina y filtra registros por banda, frecuencia o país.
- **Gráfico Interactivo** 📊: Visualiza la intensidad de señal frente a la frecuencia con un gráfico de dispersión.
- **Modo Oscuro/Claro** 🌙☀️: Alterna entre temas para una visualización cómoda.
- **Importar/Exportar Datos** 💾: Soporte para formatos JSON y XLSX.
- **Diseño Responsivo** 📱: Funciona en escritorios y dispositivos móviles.
- **Paginación y Ordenación** 🔍: Navega registros con orden por fecha o frecuencia.
- **Interruptor de Color** 🎨: Activa/desactiva colores en las celdas de frecuencia.

---

## 🚀 Fortalezas

- **Rendimiento** ⚡: Optimizado con hooks de React para gestionar cientos de registros
- **Usabilidad** 🖱️: Interfaz intuitiva con etiquetas ARIA, tooltips y estética militar con fuente "Black Ops One".
- **Flexibilidad** 🔧: Soporta unidades kHz/MHz, múltiples bandas (VLF a UHF) y seguimiento de modulación SSB/AM.
- **Seguridad** 🔒: Sanea entradas con DOMPurify y valida datos para importaciones seguras.

---

## 🛠️ Usabilidad

Echo Charlie Pad está diseñado para aficionados y profesionales de la radio. Características clave:

- **Entrada Fácil** ✍️: Formulario con detección automática de banda según la frecuencia.
- **Filtrado y Búsqueda** 🔎: Encuentra registros por banda, nombre o país.
- **Personalización del Gráfico** 📈: Filtra por banda o unidad con tooltips claros.
- **Accesibilidad** ♿: Etiquetas ARIA y HTML semántico mejoran el soporte para lectores de pantalla.

---

## 🔐 Seguridad

- **Saneamiento de Entradas** 🛡️: Usa DOMPurify para prevenir ataques XSS en nombres, notas y textos.
- **Validación de Datos** ✅: Validación estricta para importaciones JSON/XLSX.
- **Almacenamiento Local** 💽: Guarda registros en el navegador con manejo de errores.
- **Sin Servidor** 🌍: Totalmente del lado del cliente, reduciendo riesgos.

---

## 🖥️ Instalación y Uso

1. **Clona el Repositorio**:

   ```bash
   git clone https://github.com/aisurf3r/EchoCharlie-Pad.git
   ```
2. **Abre** `index.html`:
   - Sirve con un servidor local (ej., `npx serve`) o ábrelo en un navegador.
3. **Comienza a Registrar**:
   - Añade registros, filtra/busca y visualiza datos en el gráfico.

¡No se necesitan dependencias más allá de un navegador moderno! 🏃

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Haz un fork, realiza cambios y envía un pull request. Revisa los issues para tareas o sugiere funciones.

---

## 📜 Licencia

Licenciado bajo la Licencia MIT. Ver LICENSE para detalles.

---

## 👨‍💻 Autor

Desarrollado por **aisurf3r**. ¡Sigue mi GitHub para más proyectos! 🚀