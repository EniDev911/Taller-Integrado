# Proyecto crosam

Para crear el proyecto desde inicio ejecuta los siguientes comandos:

Crear un nuevo proyecto mvc con autenticación Individual e ingresar al directorio
```bash
dotnet new mvc -n crosam --auth Individual 
cd crosam
```
Agregar un archivo gitignore al proyecto
```bash
dotnet new gitignore 
```
Inicializar el repositorio y hacer commit
```bash
git init 
git add add .
git commit -m "Versión Inicial"
```
Eliminar la base de datos
```bash
dotnet ef database drop
```
Eliminar Migración
