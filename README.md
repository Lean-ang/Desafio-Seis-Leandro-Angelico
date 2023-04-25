#Desafio

### Roles:

  * Admin: para los usuarios con privilegios de admin
  * User: para los usuarios que no tienen privilegios de admin
  
### Vistas 

  * / -> esta vista nos llevara a la pestaña de login en donde colocaremos nuestras credenciales de acceso
  * /register -> en caso de no contar con credenciales, deberemos crear una cuenta
  * /profile -> aqui podremos ver informacion (no sensible) del usuario


## A tener en cuenta

  * Hay que tener un carrito en la coleccion 'cart' de la BD, crearlo con el ID 1 para verlo /cart/1


## API Endpoints:

Base URL: http://localhost:8080/

API URL: http://localhost:8080/api/

Endpoints de productos
  - products/   - products/:pid ** ✅ **
 
Endpoints del carrito:
  - cart/
  - cart/:cid 
  - cart/:cid/product/:pid

Endpoints con vistas (HTML):
  - /
  - /cart/:cid 

### Endpoints con vistas (HTML)

#### Products View 

URL: [Link a products view -> http://localhost:8080/](http://localhost:8080/)

#### Cart View 

URL: [Link a cart view (del carrito 1) -> http://localhost:8080/cart/1](http://localhost:8080/cart/1)
