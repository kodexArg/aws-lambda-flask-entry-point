# aws-lambda-flask-entry-point
Flask/Telegram Bot using AWS Lambda.

## Install
- ```pip install -r requirements.txt```

### Para agregar más paquetes al Lambda:
- instalar package con pip install ...
- actualizar requirements.txt ```pip freeze > requirements.txt``` (no es obligatorio para este paso pero necesario luego)
- crear el directorio package con los paquetes instalados (probablemente los mismos del .venv si se usa virtual environment) ```pip install --target ./package -r requirements.txt```
- enviar a zip ```zip -ur deploy.zip * -x '*package*'```
