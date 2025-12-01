# Manual de Uso

Nos descargamos un dataset desde Kaggle. En este caso para seguir con la temática usamos uno de duolingo.
[link](https://www.kaggle.com/datasets/aravinii/duolingo-spaced-repetition-data).
Lo subimos dentro de la ruta data del repositorio. Es tán pesado que qeudpo excluido del commit


correr en la terminal:
```pip install pyarrow pandas```

correr el [notebook](./notebooks/demo_arrow.ipynb)


# Manual de uso notification system

### 1. Crear y activar el entorno virtual
```powershell
# Crear el entorno virtual
python -m venv venv

# Activar el entorno virtual
.\venv\Scripts\activate
```

### 2. Instalar dependencias
```powershell
pip install -r requirements.txt
```

### 3. Levantar los servicios con Docker
```powershell
docker compose up -d
```

Esto levantará Redis en el puerto 6379.

### 4. Ejecutar el notebook
Ejecutar el [notebook](./notebooks/notification_system.ipynb) para ver el sistema de notificaciones con Redis.




