# PEJ-15: Lista de postulantes a una vacante

## Historia de usuario
Como empresa, quiero ver la lista de postulantes a una vacante, para revisar sus perfiles.

## Vista: ListaPostulantes
Componente que muestra la lista de candidatos que se han postulado a una vacante publicada por la empresa.

- Se accede desde el detalle de la vacante.
- Consulta los postulantes asociados al id de la vacante.

## Campos mostrados por candidato
- Nombre del candidato.
- Perfil resumido.
- Fecha de postulación.

## Estado vacío
Si la vacante no tiene postulantes, se muestra el mensaje: "Aún no hay postulaciones para esta vacante."

## Navegación al perfil
Al hacer clic en el nombre de un candidato, se navega a su perfil completo (ruta /perfiles/{id}).
