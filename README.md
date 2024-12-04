# cap-2-tarea-2-api-sql

## Configuración del Entorno y Ejecución del Proyecto Flask

Este documento describe los pasos necesarios para configurar un entorno de desarrollo virtual, instalar las dependencias del proyecto, y ejecutar la aplicación Flask.

### Prerrequisitos

Asegúrate de tener instalados los siguientes requisitos en tu máquina:

- Python 3.x
- `pip` (la herramienta de instalación de paquetes de Python)
- `virtualenv` (para crear entornos virtuales)

### 1. Crear un Entorno Virtual, activar el Entorno Virtual com git-bash, instalar las dependencias del requirements.txt y por último ejecutar el aplicativo Flask

```bash
virtualenv .venv
source .venv/Scripts/activate
pip install -r requirements.txt
python app.py
```

### *Para desactivar el entorno virtual* `deactivate`

## (SENIOR DEVELOPER) POR FAVOR CORREGIR LOS SIGUIENTES ERRORES: 

1. No necesitamos pandas, o al menos no en esa versión.
2. Prácticamente todo el archivo app.py contiene errores; las plantillas, en su mayoría, están correctas, pero es necesario o pertinente hacer modificaciones lo puedes hacer.
3. Faltó importar correctamente la función desde el archivo db.py.
4. Crea un enlace en base.html para visualizar el favicon.ico en la aplicación; es necesario mover el archivo a la carpeta adecuada.
5. (Opcional) Agrega validación para el título; si no se llena, activa un mensaje de alerta, impidiendo el submit. 

