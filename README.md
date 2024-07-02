# demo-docker-python
Demo de un docker con pytohon

- Crear la imagen
docker build -t test:latest .

- Iniciar el contenedor
docker run -p 127.0.0.1:8000:8000 test:latest

- Comprobar el funcionamiento
http://localhost:8000

RESUMEN GIT
--cambias a rama main
git checkout main
--actualiza la rama main en el equipo de trabajo
git pull origin main
--creao un branch otraFeature
git branch otraFeature
--cambia a la nueva rama
git checkout otraFeature
--Sube a staging todos los archivos con cambios
git add -A
--realiza el commit
git commit -m "Descripción del cambio"
--subimos la rama a la nube
git puhs origin otraFeature
--camabiamos a la rama master
git checkout main
--vemos que la rama master está actualizada
git pull origin main
--vemos las ramas realizadas merge
git branch --merged
--hacemos merge los nuevos cambios en main
git merge otraFeature
-- subimos los cambios a git
git push origin main
--eliminanos la rama 
git push origin --delete otraFeature