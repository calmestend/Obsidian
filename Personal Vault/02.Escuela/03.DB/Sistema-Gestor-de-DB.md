# SGBD (Sistema Gestor de Base de Datos)
Conjunto de herrramientas que suministra a los diferentes usuarios, los medios necesarios para describir, recuperar y manipular los datos almacenados en la DB, manteniendo la seguridad integridad y confidencialidad de los mismos

    Usuario -> App (Banco) -> Servidor -> SGBD (Oracle) -> DB Fisica

## Funcionalidades de un SGBD
- Define la DB en terminos de sus tipos de datos, estructuras y restricciones.
- Permite poblar los contenidos de la DB sobre un medio de almacenamiento.
- Manipular la DB (POST, GET y CRUD)
- Brindar acceso a la DB por medio de aplicaciones.
- Gestionar los diferentes tipos de usuarios (Usuario final, Administrador, Auditor, etc).

## Fases de Diseno de una DB
    Minimundo -> Recoleccion y Analisis de Requisitos -> Diseno Conceptual (esquema conceptual ER) -> Diseno Logico (esquema relacional)

### Diseno Conceptual (Modelo ER)
*Principales caracteristicas del enfoque de DB.*
- Abstraccion de datos.
- Naturaleza autodescriptiva.
- Independencia entre apps y data.
- Soporte de multiples vistas de datos.
- Comportamiento de datos y procesamiento de multiples transacciones.
### Diseno Logico (modelo relacional)

## Niveles de Abstraccion

Nivel externo -> Vista
Nivel conceptual -> Vision completa de todos los requerimientos usando un lenguaje de alto nivel.
Nivel interno -> Estructura, tipos de datos, espacios, indicies y todo lo que necesites para encriptar.

