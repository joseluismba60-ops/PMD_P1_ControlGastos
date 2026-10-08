# ControlGastos · Práctica 1 PMDM

Aplicación móvil desarrollada en Android Studio (Java / XML) para la gestión y registro de gastos diarios, cumpliendo con los requisitos de diseño de interfaz, externalización de recursos, internacionalización y emulación multiplataforma.

---

## 📱 Descripción del Proyecto
**ControlGastos** es una aplicación diseñada para facilitar el control financiero personal de forma rápida e intuitiva. Permite introducir conceptos, registrar cantidades monetarias, seleccionar categorías de gasto y visualizar los totales de manera adaptativa.

### Características Técnicas:
* **Entorno de desarrollo:** Android Studio.
* **Lenguaje:** Java (Lógica de Actividades) y XML (Layouts y Recursos).
* **Versión mínima de Android:** API 24+ (Nougat en adelante).
* **Internacionalización:** Soporte completo en Español (por defecto) e Inglés (`values-en`).
* **Diseño adaptativo:** Utilización de unidades de medida independientes de densidad (`dp`) y tipografía escalable (`sp`).
* **Iconografía:** Icono de lanzador adaptativo personalizado y recursos gráficos vectoriales y de mapa de bits.

---

## 📂 Estructura del Proyecto
```text
ControlGastos/
├── app/src/main/
│   ├── java/es/medac/BechiroMifumu/   # Código fuente en Java (MainActivity)
│   ├── res/
│   │   ├── drawable/                 # Recursos gráficos y vectores (ic_moneda)
│   │   ├── layout/                   # Diseños de interfaz XML (activity_main.xml)
│   │   ├── values/                   # Recursos centralizados (strings.xml, colors.xml, styles.xml)
│   │   ├── values-en/                # Recursos traducidos al inglés (Internacionalización)
│   │   └── mipmap/                   # Iconos adaptativos de la aplicación
│   └── AndroidManifest.xml           # Configuración global y permisos de la app
└── docs/
    └── memoria.pdf                   # Memoria técnica completa de la práctica
