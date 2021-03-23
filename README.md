# Lab09
Laboratorio 09 - Diseño Web - REST API

Importante recalcar que la base de datos que utiliza se llama Lab09 y que el servidor corre en el puerto 5001 ya que estaba utilizando el 5000. 

## Creación de la base de datos

```javascript
use Lab09
db.createCollection('productos')
db.productos.insert({
    descripcion: 'Camisa',
    cantidad: 5,
    stock: true,
    talla: 'M'
})
```
