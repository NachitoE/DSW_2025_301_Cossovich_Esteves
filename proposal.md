# Propuesta - Avistandoo

## Grupo
### Integrantes
* 51530 - Cossovich, Noah
* 50345 - Esteves, Ignacio
### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
*Web de identificación de aves, filtrando diferentes características físicas (ej; forma pico, patas, plumaje, etc.) utilizando lógica difusa.*

## Modelo

![Avistandoo drawio(1)](https://github.com/user-attachments/assets/d0a61280-da6c-45ba-b656-21a73dc030a4)

---

## Alcance Funcional

### Alcance Mínimo

Regularidad:

| Req | Detalle |
|-----|---------|
| **CRUD simple** | 1. `Usuario` <br> 2. `CaracteristicaVisual` |
| **CRUD dependiente** | 1. `Ave` (dependiente de características)<br> 2. `Comentario` (dependiente de usuario y ave) |
| **Listado + detalle** | 1. Listado de aves filtrado por características visuales → Detalle CRUD Ave |
| **CUU / Epic** | 1. Buscar aves aplicando filtros de características <br> 2. Comentar en la publicación de un ave, adjuntando (opcional) imágenes y/o información sobre el avistamiento |

Adicionales para Aprobación:

| Req | Detalle |
|-----|---------|
| **CRUD completo** | 1. `Usuario` <br> 2. `CaracteristicaVisual` <br> 3. `Ave` <br> 4. `CaracteristicaAve` <br> 5. `Comentario` <br> 6. `ImagenComentario` <br> 7. `Avistamiento` <br> 8. `MatrizSimilitud` |
| **CUU / Epic** | CUU 1: Buscar aves con lógica difusa aplicada a características visuales <br> CUU 2: Comentar una ave incluyendo imágenes o avistamiento |

---

### Alcance Adicional Voluntario

A definir...


