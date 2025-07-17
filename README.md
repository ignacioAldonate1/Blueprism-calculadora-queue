# 🤖 Calculadora RPA con Blue Prism

Este proyecto es una automatización RPA desarrollada en Blue Prism que simula una **calculadora inteligente**. Toma operaciones desde un archivo Excel, las procesa mediante una cola (*Work Queue*), y exporta los resultados a un nuevo archivo Excel. El flujo está diseñado siguiendo buenas prácticas de desarrollo, incluyendo manejo de excepciones, uso de variables de entorno y control de cantidad de operaciones.

---

## 📌 Funcionalidades principales

- ✅ Importación de operaciones desde un archivo Excel (suma, resta, multiplicación, división).
- ✅ Carga de ítems a una **Work Queue** para su procesamiento individual.
- ✅ Procesamiento controlado de hasta **100 operaciones** (configurable).
- ✅ Actualización de los resultados en la misma Work Queue.
- ✅ Exportación de los resultados finales a un nuevo archivo Excel.
- ✅ Uso de **Variables de Entorno** para facilitar la configuración del bot (como el path del Excel o el nombre de la Queue).
- ✅ Manejo de **excepciones** y logging para evitar interrupciones inesperadas.

