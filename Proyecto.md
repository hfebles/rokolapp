# RockolAPP

La idea es vender coins para que la gente pueda seleccionar canciones.

Seria una playlist por defecto del bar y los clientes pueden comprar los coins para hacer el su seleccion musical.

### Como acceder:

#### Opcion 1: Sin registro

- El cliente escane el codigo QR en la mesa, este codigo QR tiene la informacion de la mesa, si el cliente desea pagar la seleccion musical, puede solicitarte a la caja, que le cargue al QR las coins que pague, La cuenta estaria asociada la mesa.

#### Opcion 2: (Registros)

- RRSS: El cliente se puede registrar con su correo o cuentas de RRSS y se genera un usuario y el cliente puede solicitar en la barra que se le recargue coins a su cuenta
- Usuario y password: Un registro basico sencillo funciona igual que el anterior, pero solo se solicita usuario y passwors y correo.

> Si el posee uenta, solo debe escanear el QR del bar y automaticamente lo dirige a las listas / colas de ese bar, porque la otra opcion, es las opciones de geolocalizacion, pero hay que revisarla.

### Infracestructura:

#### Backend:

- Framework Serverless
- NodeJs
- Websockets y ApiREST
- Dynamodb
- S3

#### Frontend:

-

## Cosas a considerar:

- Debe contener un dashboard de para que la caja del bar pueda asignar los coins y pueda a su vez setear las listas de reproduccion y adminstrar.
- Se debe tener una lista de canciones para ofrecer.
- Las suscripciones deben ser por paquetes
- Las canciones se deben filtrar, por nombre, genero, artista.
- Crear la posibilidad de fichas premiun o vip, que adelanten la posicion de las canciones en la lista.
- La comunicacion entre el reproductor y el backend debe ser por sockets.
