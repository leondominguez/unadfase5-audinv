# unadfase5-audinv
# Universidad Nacional Abierta y a Distancia - UNAD
### Nombre: leon Dominguez
### Programa: Ingenieria de sistemas
### Curso: Fundamentos de Programación
### Fase 5 - Evaluación Final POA

---

## 📋 Descripción del problema

**Problema 3: Auditoría de inventario y reabastecimiento**

Se requiere una herramienta para auditar el inventario y decidir qué artículos necesitan ser reabastecidos.  
La información se encuentra en una matriz con el formato:


### Requisitos de desarrollo:
- **Matriz:** Crear una matriz con al menos 5 artículos.  
- **Módulos:** Se requiere una función para determinar la cantidad exacta a pedir para un artículo.  
- **Lógica de negocio:**  
  - Si el Stock Actual es menor al Stock Mínimo, la cantidad a pedir es la diferencia (`Mínimo Requerido - Stock Actual`).  
  - Si el Stock Actual es suficiente (mayor o igual al Mínimo), la cantidad a pedir es cero.  
- **Salida:** Imprimir una lista de pedidos que muestre el nombre del artículo y la cantidad exacta que debe ser solicitada.  

---

## 📊 Diagrama de flujo

![Diagrama de flujo del inventario](Diagramaaudinv.png)

---

## 📂 Contenido del repositorio

- `problema3_inventario.py` → Código fuente en Python con menú interactivo y validaciones.  
- `Informe_Fase5.pdf` → Documento con tabla de requerimientos, pruebas de escritorio y explicación del código.  
- `Diagramaaudinv.png` → Imagen del diagrama de flujo del programa.  
