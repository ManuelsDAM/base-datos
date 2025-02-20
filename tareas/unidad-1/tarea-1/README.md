<div align="justify">

# Comparación de Sistemas Gestores de Bases de Datos (SGBD)

 - PostgreSQL es un sistema de gestión de bases de datos relacional (RDBMS) que ofrece cumplimiento ACID (Garantiza que las transacciones cumplan con Atomicidad, Consistencia, Aislamiento y Durabilidad, asegurando la integridad de los datos), extensibilidad mediante plugins, soporte para JSON y replicación maestro-esclavo (La replicación maestro-esclavo es un sistema donde una base de datos principal (maestro) envía copias de sus datos a otras bases de datos secundarias (esclavos). El maestro maneja las escrituras y los esclavos las lecturas, lo que mejora el rendimiento y da redundancia). Sus principales ventajas incluyen excelente integridad de datos, soporte para tipos de datos avanzados y ser open source. Sin embargo, tiene un mayor consumo de recursos y una curva de aprendizaje pronunciada. Es ideal para aplicaciones empresariales, sistemas que requieren integridad de datos y análisis geoespacial.

 - MongoDB es un SGBD NoSQL de tipo documental caracterizado por su esquema flexible, escalabilidad horizontal, consultas ad-hoc e indexación. Destaca por su alta velocidad de lectura/escritura, fácil escalabilidad y manejo de datos no estructurados. Sus limitaciones incluyen la falta de garantías ACID, limitaciones en joins y mayor uso de almacenamiento. Es óptimo para aplicaciones web en tiempo real, Big Data y contenido generado por usuarios.

 - Neo4j es un SGBD orientado a grafos que utiliza el lenguaje Cypher, ofrece cumplimiento ACID, traversal nativo e índices full-text (Permite búsquedas rápidas en texto completo dentro de las propiedades de nodos y relaciones). Sobresale en el manejo de relaciones complejas y consultas conectadas, con visualización intuitiva. Sus desventajas son una curva de aprendizaje alta, limitaciones en sharding y altos costos de hardware. Es ideal para redes sociales, sistemas de recomendación y detección de fraude.

 - Amazon Aurora es un SGBD en la nube de tipo relacional, compatible con MySQL/PostgreSQL, con auto-scaling (Ajusta automáticamente los recursos según la demanda), backups automáticos y capacidad Multi-AZ (Distribuye la base de datos en diferentes zonas geográficas para alta disponibilidad y recuperación ante desastres). Ofrece alta disponibilidad, mantenimiento automatizado e integración con AWS. Sus limitaciones incluyen vendor lock-in, costos variables y menor control. Es apropiado para aplicaciones cloud-native, sistemas empresariales y aplicaciones escalables.

 - ObjectDB es un SGBD orientado a objetos que ofrece persistencia directa de objetos, compatibilidad JPA, caché integrada y transacciones ACID. Sus ventajas son la integración perfecta con Java, alto rendimiento y ausencia de mapping O/R. Está limitado a Java, tiene una comunidad pequeña y opciones de hosting limitadas. Es ideal para aplicaciones Java empresariales, sistemas de caché e IoT.

:tm: :es: :recycle:
</div>