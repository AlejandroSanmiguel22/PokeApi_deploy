# PokeAPI - Full Stack App

Proyecto full stack desarrollado como prueba técnica para el cargo de Desarrollador Full Stack en la Universidad CUN.

## 📦 Estructura del repositorio

Este repositorio orquesta dos aplicaciones independientes:
- `backend/`: API REST en PHP para obtener datos de Pokémon.
- `frontend/`: Aplicación Angular para búsqueda e interacción con la API.

## 🚀 Tecnologías utilizadas

- Frontend: Angular 19, TypeScript
- Backend: PHP 8
- Contenedores: Docker & Docker Compose
- Servidor web: NGINX (Angular), Apache (PHP)
- Empaquetado: Producción con ng build

## ▶️ Instrucciones para correr el proyecto

1. Clona este repositorio:
```bash
git clone https://github.com/tu-usuario/pokeapi-deploy.git
cd pokeapi-deploy
```

2. Ejecuta los contenedores:
```bash
docker-compose up --build
```

3. Accede a las aplicaciones:
   * Frontend: http://localhost:8080
   * Backend (API): http://localhost:8000/pokemon/{idPokemon}

## 📚 Repositorios independientes

* 🔗 Frontend (Angular)
* 🔗 Backend (PHP)

## 👤 Autor

**Alejandro Sanmiguel**
📧 alejandrosanmiguel0222@gmail.com