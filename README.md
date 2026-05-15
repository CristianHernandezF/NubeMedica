# NubeMedica
Projecto Fullstack
Se utiliza SpringBoot 3.5.14
Se utiliza Java version 21

Les Microservicios entregados en esta experiencia de aprendizaje seran 6


Api-GateWay -> port 8081
Service-Login -> port 8082
Service-Direccion -> port 8083
Service-Calendario -> 8086
Service-RegistroDoctor -> port 8085
Service-Pacientes -> port 8084
Service-EstadoCita -> port 8087


El MicroServicio Direccion sirve para mantener todas las Direcciones creadas en un solo lugar para poder recuperarlas o crear nuevas.

El MicroServicio RegistroDoctor Sirve para poder Registrar a los Doctores(Usuarios) de este producto

El MicroServicio Pacientes Sirve para poder que un Doctor(Usuario) pueda crear a su paciente.

El MicroServicio Calendario Sirve para que el usuario pueda Ver tanto sus Citas medicas como Actividades Personales.

El MicroServicio Login Sirve para que el usuario tenga una manera de ingresar a el sistema de manera segura.

El microServicio EstadoCita Sirve para Otorgarle un Tipo de estado a las citas medicas (Agendado,Cancelado,Realizado) para que el usuario sepa si las citas ocurrieron o no.

El modelo de base de datos se encuentra dentro de la carpeta Documentos para poder hacer las verificaciones correspondientes.

