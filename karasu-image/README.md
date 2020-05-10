# Karasu image

> Complemento para manipular el tamaño de las imagenes alojadas en blogger de forma sencilla basado en **atributos data**

## Instalación

En nuestro **panel » diseño » editar HTML** buscamos `</body>` y agregamos lo siguiente
```html
<script src="./dest/krs-image.min.js"></script>
```
*Recuerda reemplazar la ruta por la real.*

### Modo de uso

En alguna imagen a la cuál queramos modificar sus dimensiones, agregamos el atributo **data-krsImage** el cuál debe contener un **objeto json** con las siguientes propiedades:

| propiedad  | Uso   | tipo |
| ------------ | ------------ | ------------ |
|  w |  Ancho de la imagen | number
|  h |  Alto de la imagen | number

###### ejemplo:

```html
<img src="{{url_image}}" data-krsImage='{"w": "200", "h": "100"}'/>
```

### Licencia
**Karasu-image** is licensed under the MIT License.