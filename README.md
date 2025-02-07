# Hola Mundo con PySide6

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PySide6](https://img.shields.io/badge/PySide6-6.5.0-green)

Una aplicación simple de "Hola Mundo" creada con PySide6 para demostrar la creación de interfaces gráficas en Python.

## 📋 Requisitos

- Git ([Descargar](https://git-scm.com/))
- Python 3.8 o superior
- pip (Gestor de paquetes de Python)
 
## 🚀 Instalación y Configuración

### 🌍 2️⃣ Crear y Activar un Entorno Virtual
Para evitar conflictos con otras dependencias, es recomendable usar un entorno virtual.

#### 🟢 Windows (CMD o PowerShell)
1. Abre la terminal y navega al directorio donde quieres crear el entorno virtual.
2. Ejecuta el siguiente comando:

```powershell
python -m venv mi_entorno
```


3. Activa el entorno virtual con:

```
mi_entorno\Scripts\activate
```


Si la activación es exitosa, en la terminal veras un prefijo así: 

```
(mi_entorno) C:\Users\TuUsuario>
```
#### 🟢 Windows (Ubuntu/Debian)
1. Abre la terminal y navega al directorio donde quieres crear el entorno virtual.
2. Ejecuta el siguiente comando:


```bash
python3 -m venv mi_entorno
```

3. Activa el entorno virtual con: 
```bash
source mi_entorno/bin/activate
```
Si la activación es exitosa verás algo así : 

```bash
(mi_entorno) usuario@PC:~$
```

Para salir del entorno virtual, usa : 

```bash
deactivate
```
### 🖥️ 3️⃣ Instalar PySide6
Con el entorno virtual activado, instala **PySide6** ejecutando:

```bash
pip install PySide6
```

Para asegurarte de que la instalación fue correcta, ejecuta el siguiente comando:

```bash
python -c "import PySide6; print(PySide6.__version__)"
```
Si todo está bien, verás la versión de PySide6 en la terminal 

### 📝 4️⃣ Crear y Ejecutar la Aplicación "Hola Mundo"
Ahora que tenemos todo configurado, vamos a crear una aplicación sencilla con **PySide6**.

1️⃣ **Crea un archivo llamado** `main.py` en la carpeta del proyecto.  
2️⃣ **Copia y pega el siguiente código en `main.py`:**

```python
import sys
from PySide6.QtWidgets import QApplication, QLabel

# Crear la aplicación
app = QApplication(sys.argv)

# Crear una etiqueta con el mensaje "¡Hola Mundo con PySide6!"
label = QLabel("¡Hola Mundo con PySide6!")
label.show()

# Ejecutar la aplicación
app.exec()

```

### Ejecutar aplicación PySide6

Podemos ejecutar desde: 
* VisualStudio 
* Desde la terminal. 

### Desde la terminal

1️⃣ **Abre la terminal** en el directorio del proyecto. 

2️⃣ **Activa el entorno virtual**:

```bash
#Comandos para activar los entornos

source mi_entorno/bin/activate  # Linux
mi_entorno\Scripts\activate  # Windows
```

Ejecutamos la aplicacion con: 

```bash
python main.py
```

### Desde Visual Visual Studio Code 

1️⃣ Abre Visual Studio Code en el directorio del proyecto.

2️⃣ Selecciona main.py en el Explorador de Archivos.

3️⃣ Abre la terminal en VS Code (Ctrl + `) y activa el entorno virtual

```bash
source mi_entorno/bin/activate  # Linux
mi_entorno\Scripts\activate  # Windows
```

