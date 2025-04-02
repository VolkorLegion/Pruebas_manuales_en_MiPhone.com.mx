# Pruebas_manuales_en_MiPhone.com.mx
 Se realiza una suite de pruebas de humo para el proceso de registro y el proceso de compra del sitio MiPhone.com.mx

# Como amante de la tecnología me encuentro constantemente alerta a las nuevas tiendas digitales que distribuyen productos como accesorios, electrónicos de audio, gadgets, laptops y, principalmente, Smartphones.
# El sitio mexicano Miphone.com.mx es uno de ellos, con 8 años operando, el sitio celebró sus primeros 40,000 pedidos el pasado 29 de marzo de 2025 reforzando la confianza de nosotros los consumidores hacia el portal alrededor de la República Mexicana
# Mercadeando en redes sociales buscando al cliente entusiasta con smartphones de gama alta y para fanáticos utilizando un gran sentido del humor en su manejo de redes sociales.

# Por estas razones decidí realizar unas pruebas de humo en el sitio como mi primer proyecto independiente para agregar a mi portafolio de pruebas manuales de un sitio web.

# Se realizaron pruebas en el apartado de registro de usuario, cuenta del usuario y sobre el proceso de seleccionar productos, agregarlos a un carrito de compras, designar una dirección de envío y seleccionar uno de los diversos métodos de pago que maneja el portal.

## Se adjunta la tabla de comprobación correspondiente: https://docs.google.com/spreadsheets/d/1i_W9Mf_3jpvppip-ImTt0bK9pjrgo8fTswaIfqxLhm0/edit?usp=sharing

### Resultados

# Al realizar las pruebas se detectó una serie de fallos que este analista considera serios, los cuales deberán de atenderse a la brevedad ya que pueden limitar el flujo de las ventas del sitio, así como la retención de los clientes.
# El proceso de registro consiste en ingresar al apartado de “Mi cuenta” en la esquina superior derecha de la página principal haciendo click izquierdo en el icono con forma de persona, esto abre la ventana de registro. Aquí hay dos formularios, uno para iniciar sesión y uno para registrarse, es en este último donde alimentamos el correo deseado a registrar en el único campo que presenta. Posteriormente la página “Inicia sesión” y nos indica que un correo electrónico se envía a la dirección que indicamos, sin embargo, dicho mensaje nunca se refleja. Esto se intentó en múltiples ocasiones con diferentes correos pero el proceso continuó fallando.
# Este defecto previene a los usuarios de crear su perfil correctamente y seguir consumiendo en repetidas ocasiones en el sitio ya que su historial, direcciones, lista de deseos, método de pago y carrito de compras no se guardan de manera exitosa al no poder entrar a un perfil registrado.

# El siguiente error a reportar es con el uso del método de pago “Creditea.” Al seleccionar este método, dirigirse al portal y regresar sin realizar el pago, el pedido procede con normalidad sin confirmar el pago por parte de Creditea, Asumo que  aun así MiPhone.com.mx cuenta con un proceso interno para verificar si los pagos se han realizado, sin embargo, puede significar un inconveniente para los clientes al confundirlos cuando el proceso no se complete de manera exitosa.

# Adicionalmente, al seleccionar el método de pago “OXXO” y hacer click en el  botón “Realizar el pago” no se genera ninguna ficha de pago y el sitio solo muestra un error. Esto puede limitar las ventas al no permitir compras de contado a clientes que no manejan tarjetas bancarias ni son elegibles para uno de los métodos de pago alternativos.

# El último error importante que se detectó con estas pruebas fue con el método de pago con tarjeta. El sitio por alguna razón habilita un modo de pruebas llamado Sandbox Mode, y provee indicaciones de utilizar una tarjeta bancaria con número 4111 1111 1111 1111 con CVV al azar y una fecha de vencimiento válida. Esta leyenda no debería de presentarse en producción ya que está diseñada solo para testers que utilicen un sitió que está en periodo de pruebas.
