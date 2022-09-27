# DT-PHP-Laravel-Developer-Test
La prueba consiste en realizar, de forma totalmente libre, un proyecto que cumpla con los requisitos definidos a continuación:
- Laravel 9.X
- Subida de los diferentes commits del proceso de desarrollo
- Fork del proyecto
- No hace falta una GUI/frontal
- Deberán de existir los modelos: `User`, `Product`, `Image`. Se deberá de crear la respectiva migración de cada modelo y decidir cómo se relacionarán, teniendo en cuenta que un Product tendrá varias Image y que un User puede ser el propietario de Product e Image.
- Deberá de existir un sistema de permisos para los User, con los roles: `admin`, `mod` y `user`. Puede realizarse mediante librerías existentes.
- CRUD de las diferentes entidades API (REST).
- Las `Image` deberán de almacenarse.
- Uso de middleware.

Valoración extra:
- Relaciones polimórficas entre los modelos.
- Valoración de principios SOLID y clean code.
- Arquitectura hexagonal.
- Uso de Tests (PHPUnit) a modo de ejemplo
