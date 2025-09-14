# Guía Técnica de Instalación - Sistema de Pagos Digitales

## Objetivo
Proveer las instrucciones necesarias para instalar, configurar y ejecutar el sistema de pagos digitales en un entorno de desarrollo o producción.

---

## Requisitos Previos
- **Sistema Operativo:** Windows 10 / Linux Ubuntu 22.04
- **Lenguaje:** PHP 8.1
- **Servidor Web:** Apache 2.4
- **Base de Datos:** MySQL 8
- **Herramientas adicionales:**
  - Composer
  - Git
  - Navegador actualizado (Chrome o Firefox)

---

## Pasos de Instalación

### 1. Clonar el repositorio
Ejecutar en la terminal:
```bash
git clone https://github.com/empresa/sistema-pagos.git
cd sistema-pagos

composer install
composer install

CREATE DATABASE pagos_db;


DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=pagos_db
DB_USERNAME=root
DB_PASSWORD=tu_clave
