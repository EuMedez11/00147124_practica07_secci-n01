# 00147124_practica07_secci-n01

¿Cuál es la diferencia entre autenticación y autorizacion?

La autenticación se encarga de confirmar la identidad del usuario, es decir, comprobar que realmente eres quien dices ser (por ejemplo, al ingresar tu nombre de usuario y contraseña). En cambio, la autorización ocurre después de autenticarse y consiste en determinar qué acciones tienes permitido realizar o qué recursos del sistema puedes acceder.

¿Cuál es la función del token JWT en la guía?
El token JWT sirve para conservar la sesión del usuario sin necesidad de volver a iniciar sesión cada vez. Este token contiene información sobre el usuario y sus privilegios, y el sistema lo utiliza para verificar si el usuario sigue autenticado y qué operaciones tiene permiso de realizar.