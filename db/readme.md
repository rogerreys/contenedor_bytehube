# Informacion de tablas 

# TABLA PARA POST
### NOMBRE post = post_name
### ID post = ID
### Habilitar comentarios = comment_Status
select * from IOtpQposts


# TABLA PARA CATALOGOS
### ID catalogo = term_id 
### NOMBRE catalogo = slug
IOtpQterms

# TABLA RELACION POST Y CATALOGO
### ID post = object_id
### ID catalogo = term_taxonomy_id
select * from IOtpQterm_relationships where object_id = 1745