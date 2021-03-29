# Tabla de contenidos
- [Tabla de contenidos](#tabla-de-contenidos)
  - [Test](#test)
    - [Introducción](#introducción)
    - [Historia de usuario](#historia-de-usuario)
    - [Criterios de comprobación](#criterios-de-comprobación)
    - [Detalle](#detalle)
  - [Requerimientos técnicos](#requerimientos-técnicos)
  - [¿Cómo enviar el test?](#cómo-enviar-el-test)


## Test

### Introducción

El test de código de PeopleCloud consiste en desarrollar la siguiente historia de usuario cumpliendo con los distintos criterios de comprobación. 

### Historia de usuario

**Como** Administrador de PeopleCloud

**Puedo** visualizar las vacantes publicadas en el feed de Indeed 

**Para** conocer los detalles de cada vacante

### Criterios de comprobación

**Escenario: Listado de vacantes**

**Dado** que han sido publicadas una o más vacantes en Indeed 

**Cuando** navego a la sección de vacantes 

**Entonces** entonces se muestran las vacantes

**Y** se muestran los datos por cada registro

---

**Escenario: Detalle de vacante**

**Dado** que he navegado a las sección de vacantes

**Y** se muestra por lo menos una

**Cuando** selecciono la acción de *Ver detalle*

**Entonces** se muestra la descripción de la vacante

---

### Detalle

Datos por cada registro

- Empresa: company
- Título: title
- Fecha de publicación: date
- Lugar: city, state, country
- Acciones: Ver detalle

Descripción de la vacante

- description

Fuente de datos

- https://people-pro.com/xml-feed/indeed

## Requerimientos técnicos

- Procesar el XML en PHP y preparar la respuesta con los campos necesarios.
- Obtener los datos preparados en PHP desde JavaScript para mostrarlos en la vista. 

## ¿Cómo enviar el test?

- Crear un repositorio con tu código 
- Enviarlo el link del repositorio al siguiente correo
  - Correo: dev@people-cloud.com
  - Asunto: Test PHP | Nombre Apellido
