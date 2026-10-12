# Laboratorio 5 - Temas Varios

**Universidad Tecnológica de Panamá**
Facultad de Ingeniería de Sistemas Computacionales
Herramientas de Programación Aplicada III (.NET)

- **Estudiante:** Christian Arce
- **Cédula:** 8-995-1506
- **Grupo:** 1IL133
- **Profesora:** Ing. Irina Fong
- **Módulo:** IV - Acceso a Base de Datos, Aplicaciones en Capas
- **Fecha de entrega:** 12 de octubre de 2026

---

## Descripción

Programa de consola en C# con un menú para ejecutar los 5 problemas del laboratorio. La base de datos es SQLite y se crea sola en memoria al ejecutar el programa, así que no hay que instalar nada.

## Tecnologías

- .NET 8.0
- C# 12
- SQLite (paquete Microsoft.Data.Sqlite 8.0.11)
- Visual Studio 2022

## Instalación y uso

1. Clonar el repositorio con `git clone` y el enlace de este repositorio.
2. Abrir el archivo `LabTemasVarios.sln` en Visual Studio.
3. Restaurar las dependencias con `dotnet restore` (Visual Studio lo hace solo al abrir).
4. Ejecutar con **F5**, o desde la terminal con `dotnet run --project LabTemasVarios`.
5. En el menú, escribir el número del problema y presionar Enter.

---

## Problema 1 - Consultas SQL

Hace 3 consultas a una tabla de estudiantes: muestra todos los estudiantes, muestra solo los mayores de
