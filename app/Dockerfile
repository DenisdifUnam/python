# Indicar la imagen base
FROM python:3.8
# Indicar un directorio de trabajo
WORKDIR /app
# Copiar los archivos de dependencias de la aplicación
COPY requirements.txt /app/requirements.txt
# Instalar las dependencias de la aplicación
RUN pip install --no-cache-dir --upgrade -r /app/requirements.txt
# Copiar los archivos de la aplicación
COPY . /app
# Ejecutar el contenedor y mantenerlo en ejecución constante
CMD bash -c "while true; do sleep 1; done"