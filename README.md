[README.md](https://github.com/user-attachments/files/25216032/README.md)
# 🧪 Tabla Periódica - Juego de Símbolos

Un juego interactivo educativo para aprender y practicar los símbolos de los elementos químicos de la tabla periódica.

![Tabla Periódica](https://img.shields.io/badge/Elementos-89-blue)
![React](https://img.shields.io/badge/React-18-61dafb)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Descripción

Este proyecto es una aplicación web interactiva que permite a estudiantes y entusiastas de la química practicar el reconocimiento de los símbolos químicos de los elementos de la tabla periódica. El juego presenta una tabla periódica con casillas en blanco donde los usuarios pueden escribir los símbolos y recibir retroalimentación inmediata sobre sus respuestas.

## ✨ Características

- 🎯 **89 elementos químicos** de los períodos 1 al 7
- ✅ **Validación en tiempo real** de respuestas
- 📊 **Estadísticas detalladas** (correctas, incorrectas, porcentaje de acierto)
- 🎨 **Interfaz visual intuitiva** con código de colores:
  - Azul: sin responder
  - Verde: respuesta correcta
  - Rojo: respuesta incorrecta (muestra la respuesta correcta)
- 🔄 **Función de reinicio** para practicar múltiples veces
- 📱 **Diseño responsivo** que se adapta a diferentes tamaños de pantalla
- 🌐 **Sin dependencias externas** - funciona completamente offline

## 🚀 Inicio Rápido

### Opción 1: Descarga Directa

1. Descarga el archivo `tabla_periodica.html`
2. Abre el archivo con tu navegador web favorito
3. ¡Comienza a jugar!

### Opción 2: Clonar el Repositorio

```bash
git clone https://github.com/tu-usuario/tabla-periodica-juego.git
cd tabla-periodica-juego
```

Luego abre `tabla_periodica.html` en tu navegador.

## 🎮 Cómo Jugar

1. **Escribe los símbolos**: En cada casilla vacía, escribe el símbolo químico correspondiente al elemento (por ejemplo: "H" para Hidrógeno, "Au" para Oro)

2. **Verifica tus respuestas**: Haz clic en el botón "Comprobar Respuestas" cuando hayas terminado

3. **Revisa los resultados**: 
   - Las casillas verdes indican respuestas correctas
   - Las casillas rojas muestran respuestas incorrectas y el símbolo correcto
   - Visualiza tus estadísticas en el panel de resultados

4. **Intenta de nuevo**: Presiona "Reintentar" para practicar otra vez

## 🛠️ Tecnologías Utilizadas

- **React 18** - Biblioteca de JavaScript para construir la interfaz de usuario
- **Tailwind CSS** - Framework de CSS para el diseño
- **Babel Standalone** - Transpilador de JSX en el navegador
- **HTML5** - Estructura del documento

## 📁 Estructura del Proyecto

```
tabla-periodica-juego/
│
├── tabla_periodica.html    # Archivo HTML principal (standalone)
├── tabla_periodica.jsx     # Componente React (opcional)
└── README.md              # Este archivo
```

## 🎓 Uso Educativo

Este proyecto es ideal para:

- **Estudiantes** que están aprendiendo química
- **Profesores** que buscan herramientas interactivas para sus clases
- **Autodidactas** que quieren mejorar su conocimiento de la tabla periódica
- **Competencias** y olimpiadas de química

## 🔧 Personalización

El código es fácilmente personalizable. Puedes modificar:

- Los elementos incluidos en el array `elements`
- Los colores y estilos en las clases de Tailwind
- El texto de las instrucciones
- Agregar más funcionalidades (temporizador, modos de dificultad, etc.)

## 📝 Ejemplo de Modificación

Para agregar más elementos, simplemente añade objetos al array `elements`:

```javascript
{ 
  symbol: 'Uuo', 
  name: 'Ununoctio', 
  number: 118, 
  group: 18, 
  period: 7 
}
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto:

1. Haz un fork del repositorio
2. Crea una rama para tu característica (`git checkout -b feature/nueva-caracteristica`)
3. Haz commit de tus cambios (`git commit -am 'Agrega nueva característica'`)
4. Push a la rama (`git push origin feature/nueva-caracteristica`)
5. Abre un Pull Request

## 🐛 Reportar Problemas

Si encuentras algún bug o tienes sugerencias, por favor abre un [issue](https://github.com/tu-usuario/tabla-periodica-juego/issues) en GitHub.

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor

Creado con ❤️ para estudiantes de química de todo el mundo.

## 🌟 Agradecimientos

- A la comunidad de química educativa
- A todos los contribuidores de React y Tailwind CSS
- A los estudiantes que hacen que proyectos como este tengan sentido

---

⭐ Si este proyecto te fue útil, ¡considera darle una estrella en GitHub!

## 📸 Capturas de Pantalla

### Vista del Juego
*(Aquí puedes agregar capturas de pantalla del juego en acción)*

### Resultados
*(Aquí puedes agregar una captura mostrando las estadísticas)*

## 🔮 Futuras Mejoras

- [ ] Modo de práctica por grupos (metales alcalinos, gases nobles, etc.)
- [ ] Sistema de puntuación y rankings
- [ ] Temporizador para medir velocidad
- [ ] Modo multijugador
- [ ] Soporte para múltiples idiomas
- [ ] Agregar lantánidos y actínidos completos
- [ ] Modo oscuro
- [ ] Guardar progreso en localStorage

## 📞 Contacto

Si tienes preguntas o sugerencias, no dudes en contactarme:

- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- Email: tu-email@ejemplo.com

---

**¡Feliz aprendizaje! 🎉**
