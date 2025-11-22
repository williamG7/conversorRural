# Conversor Rural 

[![MakeCode Arcade](https://img.shields.io/badge/MakeCode-Arcade-orange?style=for-the-badge&logo=microsoft)](https://arcade.makecode.com)
[![Python](https://img.shields.io/badge/Python-MakeCode-blue?style=for-the-badge&logo=python)](https://arcade.makecode.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

Un juego interactivo desarrollado en **MakeCode Arcade** que enseña conversiones de unidades a través de un sistema de intercambio de productos rurales por leña.

## Descripción

**Conversor Rural** es un juego donde los jugadores aprenden sobre proporciones y conversiones matemáticas mediante el intercambio de productos agrícolas (gallinas, patatas, cabras, huevos, caballos) por leña. El juego simula un entorno rural con NPCs (personajes no jugadores) que facilitan diferentes tipos de conversiones.

---

## Vista Previa del Prorgama

La siguiente imagen muestra la pantalla de inicio del programa:

![Vista del programa]()

---

## Características

- **Sistema de conversión bidireccional**: Convierte productos a leña o leña a productos
- **5 productos diferentes** con sus propias tasas de conversión
- **Interfaz visual intuitiva** con menús desplegables
- **Validación de entradas** (números enteros para animales, decimales para otros productos)
- **Efectos visuales y sonoros** al completar intercambios
- **Tabla de referencia** accesible en cualquier momento

---

## Controles

| Tecla | Acción |
|-------|--------|
| **Flechas/WASD** | Mover personaje |
| **A** | Interactuar con NPC / Confirmar selección |
| **B** | Ver tabla de conversiones / Cancelar |

---

## Tabla de Conversiones

| Producto | Equivalencia en Leña |
|----------|---------------------|
| 🐓 **1 Gallina** | 6 kg de leña |
| 🥔 **1.5 kg de Patatas** | 2 kg de leña |
| 🐐 **1 Cabra** | 5 kg de leña |
| 🥚 **12 Huevos** | 3 kg de leña |
| 🐎 **1 Caballo** | 12 kg de leña |

---

## Cómo Jugar

1. **Inicio**: El juego comienza con una pantalla de bienvenida
2. **Movimiento**: Usa las flechas o WASD para mover tu personaje
3. **Interacción con NPCs**:
   - **NPC Izquierdo**: Convierte productos a leña
   - **NPC Derecho**: Convierte leña a productos
4. **Realizar conversión**:
   - Acércate a un NPC
   - Presiona **A** para abrir el menú
   - Selecciona el producto
   - Ingresa la cantidad
   - Confirma el intercambio
5. **Consultar tabla**: Presiona **B** en cualquier momento para ver las equivalencias

---

## Tecnologías

- **Lenguaje**: Python (MakeCode Arcade)
- **Plataforma**: MakeCode Arcade
- **Librerías**: 
  - `sprites` - Manejo de personajes
  - `controller` - Control de entrada
  - `miniMenu` - Sistema de menús
  - `game` - Lógica del juego
  - `scene` - Gestión de escenarios

---

## Características Técnicas

### Validación de Datos
-  Validación de cantidades positivas
-  Validación de números enteros para animales
-  Soporte de decimales para productos como patatas

### Cálculos de Conversión

**Productos a Leña:**
```python
gallina: cantidad × 6
patatas: (cantidad × 2) ÷ 1.5
cabra: cantidad × 5
huevos: (cantidad × 3) ÷ 12
caballo: cantidad × 12
```

**Leña a Productos:**
```python
gallina: kg_leña ÷ 6
patatas: (kg_leña × 1.5) ÷ 2
cabra: kg_leña ÷ 5
huevos: (kg_leña × 12) ÷ 3
caballo: kg_leña ÷ 12
```

---

## Instalación y Uso

### Opción 1: Jugar en línea (Recomendado)
1. Visita [MakeCode Arcade](https://arcade.makecode.com)
2. Crea un nuevo proyecto
3. Copia y pega el código del archivo `main.py`
4. Presiona **Play** para jugar

### Opción 2: Clonar repositorio
```bash
git clone https://github.com/williamG7/conversorRural.git
```
Luego abre el proyecto en MakeCode Arcade e importa el archivo del proyecto.

### Opción 3: Importar URL
1. Abre MakeCode Arcade
2. Haz clic en **Import**
3. Pega la URL de este repositorio: `https://github.com/williamG7/conversorRural`

---

## Compatibilidad

El juego funciona en:
-  Navegadores web (Chrome, Firefox, Edge, Safari)
-  Emulador de MakeCode Arcade
-  Dispositivos hardware compatibles con MakeCode Arcade
-  Dispositivos móviles

---

## Propósito

Este juego fue diseñado para:
- Enseñar **conversiones de unidades**
- Practicar **operaciones matemáticas** (multiplicación, división)
- Comprender **proporciones y razones**
- Desarrollar **pensamiento lógico**
- Aprender a través del **juego interactivo**
  
---

## Autor

<div align="center">
  <img src="https://github.com/williamG7.png" width="100" style="border-radius: 50%;" alt="williamG7"/>
  <br>
  <strong>William García</strong>
  <br>
  <a href="https://github.com/williamG7">
    <img src="https://img.shields.io/badge/GitHub-williamG7-181717?style=for-the-badge&logo=github" alt="GitHub williamG7"/>
  </a>
</div>

---
  
⭐ **Si te gusta este proyecto, no olvides darle una estrella en GitHub** ⭐
