## PaintEYE

- Creado para ayudar a personas con extremidades ausentes o incompletas.
<p>
**Se utilizaron herramientas como:**
</p>
- Django 
- Python  
- Numpy  
- Mediapipe 
- Pyautogu  
- OpenCV  
# Para su instalacion se necesitara:


### 1. Descargamos el proyecto del repositorio de Git
<p>
Debemos abrir la terminar en la carpeta en donde queremos clonar el proyecto.
</p>

### 2. Usamos el comando de Git para clonar el repositorio
```
git clone https://gitlab.com/aguzmanv/painteye.git

```
### 3. Abrimos el proyecto (VSCODE o PYCHARM)
### 4. Creamos el entorno virtual y lo activamos
```
python -m venv venv
Luego:
venv\Scripts\activate
```
### 4. Instalamos las dependencias correspondientes con el archivo requirements.txt
```
pip install -r requirements.txt

```
### 5. Nos ubicamos en la carpeta raiz del proyecto y realizamos las migraciones
```
python manage.py makemigrations
Luego:
python manage.py migrate

```
### 6. Finalizamos iniciando nuestro servidor
```
python manage.py runserver

```


