
---

# Informe Final del Proyecto

---

# 1. Introducción

El presente proyecto corresponde al desarrollo de una plataforma web empresarial orientada a la administración centralizada de activos tecnológicos corporativos, denominada **PAF Inventory System**.

La solución fue desarrollada utilizando tecnologías modernas de frontend y procesamiento de datos, permitiendo automatizar tareas relacionadas con:

* Gestión de inventario TI
* Control de equipos corporativos
* Administración de celulares empresariales
* Visualización de datos mediante dashboards
* Generación de estadísticas
* Lectura automática de archivos Excel
* Organización de información tecnológica empresarial

El proyecto surge como respuesta a la necesidad de centralizar la información tecnológica de la organización, reduciendo procesos manuales y facilitando el análisis del inventario corporativo.

---

# 2. Objetivo General

Desarrollar un sistema inteligente de gestión e inventario tecnológico que permita administrar activos TI empresariales mediante una interfaz web moderna, integrando lectura automática de archivos Excel, visualización de información y generación dinámica de reportes.

---

# 3. Objetivos Específicos

* Centralizar la información tecnológica empresarial.
* Automatizar la lectura de archivos Excel corporativos.
* Visualizar inventarios mediante dashboards dinámicos.
* Implementar gráficas estadísticas automáticas.
* Organizar información de equipos, celulares y accesorios.
* Facilitar la gestión de reportes tecnológicos.
* Diseñar una interfaz moderna, responsive y escalable.

---

# 4. Descripción General del Sistema

PAF Inventory System es una aplicación web desarrollada con React y Vite, diseñada para procesar automáticamente archivos Excel empresariales y mostrar información tecnológica mediante tablas dinámicas, indicadores KPI y gráficas interactivas.

<img width="1916" height="1194" alt="image" src="https://github.com/user-attachments/assets/968a505a-0950-4dc0-977b-8f185b88de49" />

El sistema permite visualizar información relacionada con:

* Usuarios
* Áreas empresariales
* Equipos asignados
* Periféricos
* Celulares corporativos
* Memoria RAM
* Procesadores
* Almacenamiento
* Versiones de software
* Evidencias fotográficas
* Actas empresariales

---

# 5. Levantamiento de Información

## 5.1 Recolección de Datos

La información utilizada en el sistema fue obtenida mediante:

* Inventario manual de equipos corporativos
* Revisión de hardware empresarial
* Registro de seriales
* Captura de datos de almacenamiento y RAM
* Registro de procesadores
* Información de celulares corporativos
* Organización documental en Excel

Posteriormente, toda la información fue consolidada en un archivo Excel corporativo denominado:

```bash
inventario.xlsx
```

---

## 5.2 Hoja Utilizada

El sistema consume específicamente la hoja:

```bash
DASHBOARD
```

correspondiente a la hoja número 4 del archivo Excel.

---

# 6. Estructura de Datos

La hoja DASHBOARD contiene las siguientes columnas:

| Campo                 |
| --------------------- |
| USUARIO               |
| AREA                  |
| EQUIPOS ASIGNADOS     |
| BASE PARA PORTATIL    |
| PANTALLA EXTERNA      |
| TECLADO               |
| MOUSE                 |
| DIADEMA               |
| OTROS                 |
| NUMERO DE SERIE       |
| EQUIPO MARCA          |
| MODELO                |
| CODIGO KAMATEQ        |
| NOTAS ADICIONALES     |
| EVIDENCIA FOTOGRAFICA |
| DATOS CELULAR MM      |
| NUMERO                |
| REFERENCIA            |
| FECHA                 |
| ALMACENAMIENTO        |
| RAM                   |
| PROCESADOR            |
| VERSION               |
| ACTAS                 |

---

# 7. Arquitectura del Sistema

## 7.1 Arquitectura General

El sistema implementa una arquitectura frontend basada en:

* React
* Vite
* TailwindCSS
* XLSX
* Recharts

El flujo general del sistema es:

```text
Excel → Lectura XLSX → Procesamiento de Datos → Dashboard → Gráficas → Reportes
```

---

## 7.2 Flujo de Funcionamiento

1. El usuario carga un archivo Excel.
2. El sistema procesa automáticamente la hoja DASHBOARD.
3. Los datos son convertidos a formato JSON.
4. Se generan estadísticas automáticas.
5. Se muestran tablas dinámicas.
6. Se generan gráficas en tiempo real.
7. El dashboard actualiza la información automáticamente.

---

# 8. Desarrollo del Dashboard

## 8.1 Interfaz Empresarial

El dashboard fue diseñado con un enfoque corporativo y moderno, incorporando:

* Panel lateral administrativo
* Tarjetas estadísticas KPI
* Indicadores visuales
* Tablas responsivas
* Botones de acciones rápidas
* Estado del sistema
* Actividad reciente

---

## 8.2 Funcionalidades Implementadas

### Gestión de Inventario

* Visualización de equipos
* Consulta de usuarios
* Información de hardware
* Gestión tecnológica centralizada

### Lectura de Excel

El sistema utiliza la librería XLSX para:

* Leer archivos `.xlsx`
* Procesar hojas específicas
* Convertir información automáticamente
* Actualizar dashboards dinámicamente

### Importación Dinámica

El usuario puede:

* Subir archivos Excel
* Actualizar inventarios
* Refrescar estadísticas automáticamente

---

# 9. Sistema de Gráficas Inteligentes

Uno de los componentes principales del proyecto es el sistema de análisis visual de datos.

Las gráficas se generan automáticamente a partir del contenido del Excel.

---

## 9.1 Gráficas Implementadas

### Distribución de RAM

Se generan gráficas de barras para visualizar:

* Equipos con 8 GB
* Equipos con 12 GB
* Equipos con 16 GB
* Equipos con 24 GB
* Equipos con 46 GB

---

### Procesadores

Gráficas circulares para visualizar:

* Intel Core i3
* Intel Core i5
* Intel Core i7
* Ryzen
* Otros procesadores

---

### Áreas Empresariales

Distribución de equipos por área:

* Sistemas
* Administrativo
* Contabilidad
* Operaciones
* Recursos Humanos

---

### Marcas de Equipos

Visualización de marcas registradas:

* Dell
* HP
* Lenovo
* Asus
* Acer
* Otras marcas

---

### Almacenamiento

Análisis de:

* 256 GB 
* 512 GB 
* 1 TB 
* Otros almacenamientos

---

### Versiones

Distribución de versiones instaladas:

* Windows 10
* Windows 11
* Otras versiones

---

# 10. Tecnologías Utilizadas

| Tecnología  | Función                |
| ----------- | ---------------------- |
| React       | Desarrollo frontend    |
| Vite        | Entorno de desarrollo  |
| TailwindCSS | Diseño UI              |
| XLSX        | Lectura de Excel       |
| Recharts    | Generación de gráficas |
| JavaScript  | Lógica del sistema     |

---

# 11. Repositorio del Proyecto

El desarrollo y organización del proyecto se encuentra estructurado dentro del repositorio:

[Repositorio GitHub del Proyecto](https://github.com/Val29Diaz/Practicas-Tecnologo/tree/main?utm_source=chatgpt.com)

Dentro del repositorio se encuentran:

* Prácticas realizadas
* Desarrollo progresivo del sistema
* Componentes frontend
* Avances del dashboard
* Implementación de inventario TI
* Integración de tecnologías utilizadas

---

# 12. Resultados Obtenidos

Durante el desarrollo se logró:

* Automatizar la lectura de inventario empresarial.
* Centralizar información tecnológica.
* Implementar dashboards dinámicos.
* Generar gráficas automáticas.
* Reducir manejo manual de información.
* Mejorar la visualización de activos TI.
* Organizar información corporativa eficientemente.

---

# 13. Problemáticas Identificadas

Durante el desarrollo se identificaron algunos desafíos técnicos:

* Lectura de hojas específicas en Excel.
* Normalización de nombres de columnas.
* Manejo de datos nulos.
* Procesamiento dinámico de gráficas.
* Compatibilidad de formatos Excel.
* Renderizado de tablas grandes.

---

# 14. Mejoras Futuras

El sistema fue diseñado para ser escalable, permitiendo futuras integraciones como:

* Base de datos MySQL
* Backend Node.js
* Sistema de autenticación
* Roles de usuario
* Exportación PDF avanzada
* Generación automática de actas
* Almacenamiento de evidencias fotográficas
* Dashboard avanzado tipo Power BI
* Filtros inteligentes
* Buscador empresarial
* Alertas automáticas
* Integración con IA

---

# 15. Conclusiones

El proyecto PAF Inventory System permitió desarrollar una solución moderna para la administración tecnológica empresarial, integrando automatización, visualización y análisis de datos.

La implementación de dashboards dinámicos y procesamiento automático de Excel mejora significativamente la gestión de inventarios corporativos, facilitando el control de activos tecnológicos y optimizando procesos administrativos.

El sistema representa una base sólida para futuras implementaciones empresariales más avanzadas orientadas a transformación digital y automatización TI.

---

# INFOGRAFIA FINAL (REPRESENTATIVA DEL PROYECTO)
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/57f92933-624b-44a1-a745-fa9334c24471" />
---

# 16. Autor

**Valentina Diaz**

Proyecto orientado al desarrollo de soluciones tecnológicas empresariales para automatización de inventarios y gestión TI.
