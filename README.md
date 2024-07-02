# demo-docker-python
Demo de un docker con pytohon

- Crear la imagen
docker build -t test:latest .

- Iniciar el contenedor
docker run -p 127.0.0.1:8000:8000 test:latest

- Comprobar el funcionamiento
http://localhost:8000