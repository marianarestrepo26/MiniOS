# MiniOS - Sistema Operativo Web

MiniOS es un prototipo de sistema operativo web desarrollado únicamente con HTML y CSS, sin utilizar JavaScript. Simula la experiencia de un sistema operativo básico con múltiples aplicaciones que se cargan dinámicamente mediante iframes.

## 🎯 Propósito del Proyecto

Este proyecto demuestra cómo crear interfaces de usuario complejas e interactivas utilizando únicamente tecnologías web fundamentales (HTML y CSS), sin depender de JavaScript para la funcionalidad básica. Es ideal para:

- Aprender los fundamentos del desarrollo web
- Comprender el poder de CSS moderno
- Practicar diseño responsive
- Explorar arquitecturas de aplicaciones modulares

## 📁 Estructura del Proyecto

```
mini-os/
├── index.html
├── apps/ 
│   ├── notes.html
│   ├── homeworks.html 
│   └── weather.html
├── styles/
│   └── main.css 
│   ├── notes.css 
│   ├── homeworks.css 
│   └── weather.css  
├── README.md 
```

### Descripción de Componentes

#### 🖥️ **index.html** - Interfaz Principal
- Actúa como el "escritorio" del sistema operativo
- Contiene la barra de tareas superior
- Panel de navegación lateral con botones de aplicaciones
- Área principal donde se cargan las aplicaciones mediante iframes
- Sistema de navegación basado en radio buttons y CSS

#### 📱 **Aplicaciones (Directorio /apps/)**

1. **notes.html** - Aplicación de Notas
   - Gestión de notas personales
   - Categorización por tipo (personal, trabajo, estudio, etc.)
   - Sistema de prioridades (alta, media, baja)
   - Formulario para crear nuevas notas

2. **homeworks.html** - Gestor de Tareas
   - Control de tareas y actividades
   - Estados: pendiente, en progreso, completada, vencida
   - Barras de progreso visual
   - Estadísticas de productividad
   - Categorización por tipo de actividad

3. **weather.html** - Centro Meteorológico
   - Información climática actual
   - Pronóstico extendido de 7 días
   - Selector de ciudades colombianas
   - Alertas meteorológicas
   - Detalles completos (humedad, viento, presión, etc.)

#### 🎨 **styles** - Sistema de Diseño
- Grid Layout para la estructura principal
- Sistema de colores consistente
- Diseño responsive con breakpoints
- Animaciones y transiciones suaves
- Componentes reutilizables

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y formularios
- **CSS**: 
  - Grid Layout y Flexbox
  - Custom Properties (variables CSS)
  - Pseudo-selectores (:checked, :hover)
  - Media queries para responsive design
  - Gradientes y efectos visuales
  - Backdrop-filter para efectos de cristal

## 📋 Navegación y Uso

### Navegación Principal
- **Radio Buttons**: Utiliza los botones en el panel lateral para cambiar entre aplicaciones
- **Responsive**: El diseño se adapta automáticamente a diferentes tamaños de pantalla
- **Iframes**: Cada aplicación se carga en un iframe independiente

### Funcionalidades por Aplicación

#### Notas
- Completa formularios para crear notas
- Selecciona categorías y prioridades
- Visualiza notas existentes con diferentes estados visuales

#### Tareas
- Revisa estadísticas de productividad
- Crea nuevas tareas con fechas límite
- Monitorea el progreso visual de actividades

#### Clima
- Cambia entre diferentes ciudades
- Consulta pronósticos extendidos
- Revisa alertas meteorológicas

## 🎨 Características de Diseño

### Responsive Design
- **Mobile**: < 768px (diseño vertical)
- **Tablet**: 768px - 1024px (diseño híbrido)
- **Desktop**: > 1024px (diseño completo)
