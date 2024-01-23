### Ingresar a github y crear repositorio

### En la terminal agregar la carpeta donde vamos a trabajar (se puede crear con anticipación o desde la terminal)

### Realizar archivo .gitignore    /.venv


# Agregar entorno virtual
    python -m venv .venv
# Activar Entorno Virtual
    .venv\Scripts\activate

# Iniciar GIT
    git init

# Enlazar con GITHUB
    git remote add origin (copiar de la pagina del repositorio)
    git branch -M main

# Para guardar cambios

    git add . 

### (agregar nombre del cambio posterior al -m entre comillas)

    git commit -m  

# Subir Cambios
    git push -u origin main

# Instalar pandas / jupyther

# Instalar jupyter
pip install jupyter

# Instalar Pandas
python -m pip install pandas

# Instalar matplotlib
python -m pip install matplotlib

# Instalar seaborn
pip install seaborn


python pip install -r requeriments.txt
python -m pip freeze> requirements.txt

jupyter notebook
import statistics
