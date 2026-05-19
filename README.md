
# CRUD PHP amb MySQLi

## Descripció
Aquest projecte és una aplicació CRUD desenvolupada amb PHP procedural i MySQLi.  
Permet gestionar registres d’una base de dades mitjançant les operacions bàsiques:

- Crear registres
- Llistar registres
- Editar registres
- Eliminar registres

L’aplicació està preparada per funcionar al servidor http://a21ricsaagon.dam.inspedralbes.cat/videojuegos/.

---
## Tecnologies usades
- PHP 
- MySQL
- HTML
- CSS
- GitHub
- Bootstrap

---
/Videojuegos
│
├── /css
│   └── styles.css
│ 
├── /fotos
│   ├── formulario.png
│   └── llista.png
│
├── /src
│   ├── actualizar.php
│   ├── aviso.phh
│   ├── conexion.php
│   ├── editformulari.php
│   ├── eliminar.php
│   └── index.php
│   └── insertar.php
│   ├── mostrar.php
│   ├── registrar.php
│
└── README.md

---

### Base de dades utilitzada

```sql
CREATE DATABASE a21ricsaagon_videojuegos;
```
### Estructura de la taula

```sql
CREATE TABLE `videojuegos` (
  `id` bigint(20) UNSIGNED NOT NULL AUTO_INCREMENT,
  `nombre` varchar(255) DEFAULT NULL,
  `descripcion` varchar(255) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
```

---

## Funcionalitats CRUD

### Create
Inserció de videojocs mitjançant formularis HTML/PHP.
### Read
Visualització dels videojocs registrats en format taula.
### Update
Edició de videojocs existents.
### Delete
Eliminació de videojocs de la base de dades.
