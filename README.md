# ![UDA Logo](https://uda-ejie.github.io/images/imgwikis/uda-mini-micro.png) UDA - Utilidades de Desarrollo de Aplicaciones

[![License: EUPL v1.1](https://img.shields.io/badge/License-EUPL%20v1.1-blue.svg)](https://joinup.ec.europa.eu/community/eupl/og_page/european-union-public-licence-eupl-v11)
[![GitHub stars](https://img.shields.io/github/stars/UDA-EJIE/uda-ejie.github.io.svg)](https://github.com/UDA-EJIE/uda-ejie.github.io/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/UDA-EJIE/uda-ejie.github.io.svg)](https://github.com/UDA-EJIE/uda-ejie.github.io/network)

> **UDA** es un conjunto completo de [utilidades, herramientas, librerías, plugins, guías y recomendaciones](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Componentes) que acelera significativamente el desarrollo de aplicaciones Java empresariales.

## 🚀 ¿Qué es UDA?

UDA tiene como **principal objetivo aumentar la productividad del desarrollador** sin limitar su creatividad ni libertad para crear software. Automatiza las tareas repetitivas y de bajo valor añadido que, aunque imprescindibles, consumen tiempo valioso del desarrollo.

## ✨ Características Principales

- **🎯 Curva de aprendizaje mínima**: No reinventa la rueda, adopta frameworks consolidados y aprovecha el conocimiento existente
- **🌐 Patrones de usabilidad web**: Implementa mejores prácticas con tecnologías [RIA](https://es.wikipedia.org/wiki/Rich_Internet_Application) y [Ajax](https://es.wikipedia.org/wiki/AJAX)
- **⚡ Generación automática de interfaces**: Crea automáticamente [interfaces CRUD](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Patrones#14._Mantenimiento_con_formulario) y componentes comunes
- **🏗️ Generación de código**: Produce código base para arquitecturas en capas con patrón [MVC](https://es.wikipedia.org/wiki/Modelo%E2%80%93vista%E2%80%93controlador)
- **🔧 Flexible y configurable**: Adaptable a estándares organizacionales específicos
- **🧩 Modular y extensible**: Arquitectura desacoplada que permite ampliar o sustituir tecnologías
- **🎨 Múltiples opciones**: No impone un único modelo de uso
- **♿ Accesible**: Cumple con estándares [WCAG 2.0](http://www.w3.org/TR/WCAG20/) y [WAI-ARIA](http://www.w3.org/TR/wai-aria/)

## 🎬 Demo: Aplicación en 5 minutos

[![UDA Demo Video](http://img.youtube.com/vi/5T7VHQeNyuk/0.jpg)](http://www.youtube.com/watch?v=5T7VHQeNyuk)

*Haz clic en la imagen para ver cómo crear una aplicación completa en solo 5 minutos*

📺 [Ver más videos demostrativos](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Videos)

## 🚀 Inicio Rápido

### Prerrequisitos
- Java 8 o superior
- Eclipse IDE
- Maven 3.x

### Instalación

1. **Descarga** la última versión desde [Google Drive](https://drive.google.com/folderview?id=0B2jWuJHnBpz_VFVLU2ZoREQ2Q1E&usp=sharing#list)
2. **Instala** siguiendo la [guía de instalación](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Instalar)
3. **Crea** tu primera aplicación con los asistentes incluidos

### Ejemplo básico

```java
// Ejemplo de controlador generado automáticamente
@Controller
@RequestMapping("/usuario")
public class UsuarioController extends BaseController {
    
    @Autowired
    private UsuarioService usuarioService;
    
    @RequestMapping(method = RequestMethod.GET)
    public String index(Model model) {
        return "usuario/usuario";
    }
    
    // Métodos CRUD generados automáticamente...
}
```

## 📚 Documentación

| Recurso | Descripción |
|---------|-------------|
| [🏠 **Página Principal**](http://uda-ejie.github.io/) | Información general y novedades |
| [📖 **Wiki**](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki) | Documentación completa |
| [🏗️ **Arquitectura**](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Arquitectura) | Guías técnicas y conceptuales |
| [🧩 **Componentes**](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Componentes) | Catálogo de herramientas |
| [🎨 **Patrones**](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Patrones) | Patrones de usabilidad web |
| [🎓 **Formación**](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Formación) | Materiales de aprendizaje |

## 🔄 Versiones y Actualizaciones

### Última versión: UDA 6.3.0 (15 Oct 2024)

- ✅ [Asistente v6.3.0](https://github.com/UDA-EJIE/udaPlugin/releases/tag/v6.3.0)
- ✅ [Plantillas v6.3.0](https://github.com/UDA-EJIE/udaTemplates/releases/tag/v6.3.0)
- ✅ [Componentes RUP v6.3.0](https://github.com/UDA-EJIE/udaRUP/releases/download/v6.3.0/rup-v6.3.0.zip)
- ✅ [Librerías v6.3.0](https://github.com/UDA-EJIE/udaLib/releases/tag/v6.3.0)

📋 [Ver todas las versiones](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Versiones-6.x.x) | 🔄 [Guía de actualización](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Actualizar-6.x.x)

📋 [Guía de actualización 6.x.x](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Actualizar-6.x.x) | 📁 [Todas las descargas v6.x.x](https://drive.google.com/drive/folders/1HpefoKbCBW3ymCfb5BevpcIeEJyzIVEz)

### UDA 5.4.2 (21 Ene 2025)

**Descargas disponibles:**
- ✅ [Plantillas v5.4.2](https://github.com/UDA-EJIE/udaTemplates/releases/download/v5.4.2/templates-v5.4.2.zip)
- ✅ [Componentes RUP v5.4.2](https://github.com/UDA-EJIE/udaRUP/releases/download/v5.4.2/rup-v5.4.2.zip)
- ✅ [Librerías v5.4.2](https://github.com/UDA-EJIE/udaLib/releases/tag/v5.4.2)
- ✅ [Hdiv v5.2.0](https://github.com/UDA-EJIE/udaHdiv/releases/tag/v5.2.0)

📋 [Guía de actualización 5.x.x](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Actualizar-5.x.x) | 📁 [Todas las descargas v5.x.x](https://drive.google.com/drive/folders/1GVDxDsi8dkbxrfP35XC5BHJYk_QMFsrJ)

### UDA 4.5.4 (30 Sep 2025)

**Descargas disponibles:**
- ✅ [Plantillas v4.5.4](https://github.com/UDA-EJIE/udaTemplates/releases/download/v4.5.4/templates-v4.5.4.zip)
- ✅ [Componentes RUP v4.5.4](https://github.com/UDA-EJIE/udaRUP/releases/download/v4.5.4/rup-v4.5.4.zip)
- ✅ [Librerías v4.5.4](https://github.com/UDA-EJIE/udaLib/releases/tag/v4.5.4)
- ✅ [Eclipse 2020-03](https://drive.google.com/file/d/1VL0p1olViNZ2oyhDMask3p7lmj2sT3TC/view) (con plugin v4.5.0 y plantillas v4.5.4)

📋 [Guía de actualización 4.x.x](https://github.com/UDA-EJIE/uda-ejie.github.io/wiki/Actualizar-4.x.x) | 📁 [Todas las descargas v4.x.x](https://drive.google.com/drive/folders/1lGMFN6CiVUOvlN4Vvfq6c6bDPPAjktXF)

---

## 🌟 Mantenerse Actualizado

Para recibir notificaciones sobre actualizaciones:

- ⭐ **Star** este repositorio
- 👀 **Watch** el proyecto para recibir notificaciones
- 📖 **Fork** para contribuir al desarrollo

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencias

### Documentación
[![Creative Commons License](http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/3.0/)

La documentación se ofrece bajo [Creative Commons BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/)

### Software
[![EUPL License](https://img.shields.io/badge/License-EUPL%20v1.1-blue.svg)](https://joinup.ec.europa.eu/community/eupl/og_page/european-union-public-licence-eupl-v11)

El plugin UDA, extensiones, plantillas, librerías y componentes RUP se distribuyen bajo [European Union Public Licence (EUPL) v1.1](https://joinup.ec.europa.eu/community/eupl/og_page/european-union-public-licence-eupl-v11)

## 🔗 Enlaces Útiles

- 🌐 [Sitio Web Oficial](http://uda-ejie.github.io/)
- 🎮 [Aplicación Demo](http://www.ejie.eus/x21aAppWar/)
- 📥 [Descargas](https://drive.google.com/folderview?id=0B2jWuJHnBpz_VFVLU2ZoREQ2Q1E&usp=sharing#list)
- 📧 [Soporte](https://github.com/UDA-EJIE/uda-ejie.github.io/issues)

---

<div align="center">

**Desarrollado con ❤️ por [EJIE](https://github.com/UDA-EJIE)**

*Acelera tu desarrollo Java con UDA*

</div>
