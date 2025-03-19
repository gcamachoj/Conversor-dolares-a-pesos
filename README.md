## 💰 Conversor de Moneda (USD a COP)

Este repositorio contiene un **ejercicio sencillo en Python** que convierte dólares a pesos colombianos. Es un ejemplo práctico para reforzar conceptos básicos de **entrada de datos, conversión de tipos y operaciones matemáticas en Python**.

### 📌 Tecnologías utilizadas
- Python 3.x

### 📄 Descripción
El programa solicita al usuario ingresar un valor en **dólares (USD)** y lo convierte a **pesos colombianos (COP)** utilizando una tasa de cambio predefinida.

### ⚙️ Instalación y ejecución
1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/conversor-moneda.git
   cd conversor-moneda
   ```
2. **Ejecuta el script**:
   ```bash
   python conversor.py
   ```

### 📝 Código de ejemplo
```python
# Conversor de dólares a pesos colombianos
tasa_cambio = 4000  # Ejemplo de tasa de cambio

usd = float(input("Ingrese la cantidad en dólares (USD): "))
cop = usd * tasa_cambio

print(f"{usd} USD equivale a {cop} COP")
```

### 🚀 Notas
- La tasa de cambio es fija en el código, pero se puede modificar o actualizar dinámicamente.
- Este ejercicio es **puramente educativo** y no refleja valores de conversión actualizados.

📌 **Este repositorio es parte de mi práctica en Python. Si te resulta útil, siéntete libre de usarlo o mejorarlo.** 😊
