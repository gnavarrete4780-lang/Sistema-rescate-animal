Patrones de diseño

Sistema de control de rescate y adopción animal

1. Singleton

Propósito: mantener una única instancia del gestor central de casos de rescate.

Aplicación: "GestorCasos" administra el registro y la consulta de los casos para evitar múltiples gestores independientes.

Ventaja: centraliza las operaciones y facilita el control de los casos.

2. Factory

Propósito: crear expedientes según el tipo de animal rescatado.

Aplicación: "ExpedienteFactory" puede crear expedientes para perros, gatos o fauna silvestre.

Ventaja: separa la creación de objetos del resto del sistema y facilita agregar nuevos tipos de animales.

3. Observer

Propósito: notificar a los usuarios cuando ocurre un cambio relevante.

Aplicación: cuando se registra un rescate o cambia el estado de un caso, el servicio de notificaciones informa al voluntario asignado.

Ventaja: permite comunicar los cambios sin acoplar directamente el gestor de casos con cada destinatario.

Conclusión

Los patrones Singleton, Factory y Observer ayudan a organizar el sistema, facilitar su mantenimiento y mejorar la gestión de los rescates. Su implementación debe reflejarse también en el código del sistema.
