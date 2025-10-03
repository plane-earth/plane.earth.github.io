# PlaneEarthMap - Proyecciones Cartográficas Innovadoras para la Era Digital

🌍 **[Deutsch](README.de.md)** | 🇺🇸 **[English](README.md)** | 🇪🇸 **[Español](README.es.md)**

## 🌍 Visión del Proyecto

PlaneEarthMap revoluciona la cartografía digital a través de proyecciones terrestres alternativas que eliminan las distorsiones tradicionales de la proyección Mercator. Nuestro sistema de renderizado acelerado por GPU permite cálculos en tiempo real de algoritmos de proyección complejos y ofrece la primera navegación bidireccional sin límites del mundo.

## 🚀 Características Principales

- **🗺️ Proyecciones Alternativas**: Modelos terrestres planares, convexos y cóncavos para representación sin distorsiones
- **🔄 Navegación Continua**: Primera navegación infinita bidireccional del mundo (Norte-Sur + Este-Oeste)
- **⚡ Renderizado GPU**: Representación cartográfica de alto rendimiento en tiempo real con servidores GPU externos
- **🌐 Arquitectura Federada**: Infraestructura de mapas descentralizada vía protocolo ActivityPub
- **📱 Optimizado para ARM64**: Diseño mobile-first para arquitectura moderna de smartphones
- **🔓 Código Abierto**: Desarrollo comunitario bajo licencia AGPL v3

## ⚖️ El Problema de la Distorsión

Las proyecciones cartográficas tradicionales conducen a distorsiones significativas de tamaño:
- **Rusia** aparece aproximadamente el doble de grande que **África**, aunque África es en realidad 1.3 veces más grande
- **Groenlandia** parece más grande que continentes enteros
- Estas distorsiones pueden llevar a **malentendidos geopolíticos**

PlaneEarthMap corrige estos problemas a través de proyecciones planares precisas en área.

## 🎓 Fundamento Científico

### Base de Psicología del Desarrollo
Estudios de la **Universidad de Illinois** muestran que los niños perciben naturalmente la Tierra como una superficie plana. PlaneEarthMap apoya este desarrollo espacial natural a través de:
- Representaciones cartográficas planares apropiadas para la edad
- Transición gradual a conceptos geométricos más complejos
- Promoción del entendimiento geográfico sin disonancia cognitiva

## 🏗️ Arquitectura Técnica

### Diseño de Infraestructura
```
[VPS de Alto Rendimiento] ←→ [Entorno de Desarrollo ARM64]
            ↓                          ↓
[Servicios en Contenedores]     [Optimización Móvil]
            ↓                          ↓
[Pipeline de Renderizado GPU]   [Pruebas Multi-Plataforma]
```

### Tecnologías Principales
- **Backend**: Microservicios basados en contenedores con Docker/Podman
- **Frontend**: Aplicación Web Progresiva con renderizado WebGL
- **Renderizado**: Algoritmos de proyección acelerados por GPU
- **Federación**: Protocolo ActivityPub para servicios de mapas descentralizados
- **Desarrollo**: Forgejo en çō.de para URLs Git ultra-cortas
- **Infraestructura**: Pipeline de construcción optimizado para ARM64

## 🔧 Entorno de Desarrollo

### Arquitectura de Dominios
```
plane.earth              # Presencia pública
├── map.plane.earth     # Aplicación PlaneEarthMap
├── api.plane.earth     # Servicios REST API
├── docs.plane.earth    # Documentación para desarrolladores
└── federation.plane.earth # Hub ActivityPub

çō.de                   # Infraestructura de desarrolladores
├── planeearthmap-core  # Repositorio del motor principal
├── planeearthmap-web   # Repositorio frontend
└── algorithms          # Algoritmos de proyección
```

### Ventajas del Dominio çō.de
- **URLs Git Ultra-Cortas**: `git clone https://çō.de/planeearthmap-core`
- **Amigable para Desarrolladores**: Fácil de escribir y recordar
- **Innovación Unicode**: Demuestra estándares web modernos

## 📊 Estado de Desarrollo

### Fase Actual: Desarrollo de Prototipo
El proyecto está en desarrollo activo con infraestructura funcional:

✅ **Completado:**
- Instalación de Forgejo en çō.de (estable)
- Documentación básica del proyecto
- Arquitectura de dominios establecida
- Entorno de desarrollo ARM64

🔄 **En Desarrollo:**
- Motor de proyección planar
- Pipeline de renderizado GPU
- Algoritmos de navegación bidireccional

### Hoja de Ruta
1. **Fase 1**: Motor de proyección planar (actual)
2. **Fase 2**: Implementar navegación bidireccional
3. **Fase 3**: Modelos de proyección convexos y cóncavos
4. **Fase 4**: Federación ActivityPub para servicios descentralizados
5. **Fase 5**: Aplicaciones móviles y herramientas comunitarias

## 🌐 Navegación Innovadora

### Navegación Infinita Bidireccional
PlaneEarthMap introduce capacidades de navegación revolucionarias:
- **Continuidad Horizontal**: Como OpenStreetMap (Este-Oeste)
- **Continuidad Vertical**: Primera capacidad Norte-Sur jamás vista
- **Transiciones Perfectas**: Sin límites de mapa visibles
- **Coordenadas Adaptivas**: Puntos de referencia dinámicos

### Innovación Técnica
- Transformación topológica de datos cartográficos
- Cálculos en tiempo real basados en GPU
- Estabilidad numérica en coordenadas extremas
- Procesamiento de datos paralelo basado en contenedores

## 🎯 Audiencias Objetivo

### Sector Educativo
- **Escuelas**: Educación geográfica libre de distorsiones
- **Universidades**: Investigación cartográfica científica
- **Plataformas E-Learning**: Materiales de aprendizaje interactivos

### Ciencia e Investigación
- **Cartógrafos**: Métodos de proyección experimentales
- **Geógrafos**: Representaciones precisas de áreas
- **Psicólogos Educativos**: Desarrollo espacial apropiado para la edad

### Comunidad Técnica
- **Desarrolladores Open Source**: Innovación impulsada por la comunidad
- **Expertos en Computación GPU**: Optimizaciones de renderizado
- **Entusiastas de la Federación**: Infraestructuras descentralizadas

## 🔮 Visión Futura

### Cartografía Descentralizada
PlaneEarthMap establece una nueva generación de infraestructuras cartográficas:
- **Propiedad Comunitaria**: Sin control central por corporaciones tecnológicas
- **Científicamente Abierto**: Algoritmos reproducibles y transparentes
- **Disponible Globalmente**: Arquitectura federada para resistencia mundial

### Innovación Tecnológica
- **Ecosistema ARM64**: Optimización para el futuro móvil
- **Integración IA**: Claude Code para desarrollo automatizado
- **Edge Computing**: Renderizado GPU en el borde de la red

## 🤝 Contribuir

PlaneEarthMap es un proyecto de código abierto que prospera con contribuciones comunitarias:

### Incorporación de Desarrolladores
```bash
# Clonar repositorio
git clone https://çō.de/planeearthmap-core

# Leer documentación
curl -s https://docs.plane.earth

# Issues y pull requests en çō.de
```

### Oportunidades de Contribución
- **Código**: Algoritmos de proyección, shaders GPU, frontend
- **Documentación**: Tutoriales, documentación API, papers científicos
- **Pruebas**: Optimización ARM64, compatibilidad multi-plataforma
- **Diseño**: UI/UX para interfaces cartográficas complejas

## 📄 Licenciamiento

**Licencia Principal**: AGPL v3 (GNU Affero General Public License)
- Protección contra integración en servicios cloud propietarios
- Asegurar retorno de contribuciones a la comunidad
- Amigable para educación y compatible con investigación

**Licenciamiento Modular**:
- **Motor Principal**: AGPL v3
- **APIs de Plugins**: Apache 2.0
- **Documentación**: CC BY-SA 4.0

## 🌟 Propuestas de Valor Únicas

1. **Primera navegación cartográfica bidireccional sin límites del mundo**
2. **Proyecciones terrestres alternativas aceleradas por GPU en tiempo real**
3. **Representación cartográfica basada en psicología del desarrollo**
4. **Infraestructura de mapas completamente descentralizada y federada**
5. **Rendimiento móvil optimizado para ARM64**
6. **URLs Git ultra-cortas a través de dominio Unicode**

---

*PlaneEarthMap: Cartografía revolucionaria para una percepción mundial más precisa*

**Contacto**: [Información del Desarrollador]  
**Repositorio Principal**: https://çō.de  
**Sitio Web del Proyecto**: https://plane.earth  
**Licencia**: AGPL v3 (Código Abierto)
