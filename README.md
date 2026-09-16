# 🚀 Guía Práctica de Markdown para ASIR

> Este documento sirve como ejemplo visual y chuleta de referencia para aprender a estructurar documentación profesional en repositorios de GitHub.

---

## 📋 Tabla de Contenidos
| Sección | Descripción | Nivel de Dificultad |
| :--- | :--- | :--- |
| **1. Sintaxis Básica** | Títulos, negritas y cursivas | Fácil |
| **2. Listas y Citas** | Organización de elementos | Fácil |
| **3. Tablas y Enlaces** | Estructuras avanzadas | Intermedio |
| **4. Bloques de Código** | Comandos de consola y scripts | Avanzado |

---

## 1. Jerarquía de Títulos
En Markdown utilizamos las almohadillas (`#`) para definir la importancia de los encabezados:

# Título de nivel 1 (H1)
## Título de nivel 2 (H2)
### Título de nivel 3 (H3)

---

## 2. Formato de Texto
Podemos destacar palabras o frases clave utilizando caracteres especiales:
* Esto es texto normal.
* Esto es **texto en negrita** (usando doble asterisco).
* Esto es *texto en cursiva* (usando un solo asterisco).
* Esto es una **_combinación de ambos_**.

---

## 3. Listas y Bloques de Cita

### Lista de requisitos (No ordenada):
* Debian 12 (VirtualBox)
* Git instalado y configurado
* Clave SSH vinculada a GitHub

### Pasos a seguir (Ordenada):
1. Crear el repositorio en GitHub.
2. Clonar o inicializar el repositorio localmente.
3. Añadir el archivo `README.md`.
4. Hacer el `git push` definitivo.

> **Nota:** Mantener una buena documentación en los repositorios es fundamental en la administración de sistemas para que cualquier compañero entienda el despliegue rápidamente.

---

## 4. Bloques de Código y Comandos
Para mostrar código o comandos de terminal de forma limpia, utilizamos comillas invertidas triples (` ``` `):

```bash
# Configurar el usuario global de Git
git config --global user.name "Tu Nombre"
git config --global user.email "tu_correo@example.com"
