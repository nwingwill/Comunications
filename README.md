# XD 06/10/2022

> Simbologia  
> ```⚠️ Sin Interacciones```  
>
> ```⛔️ No funciona```  
>
> ```✅ Requerimiento de la lista Cumplido```
>
> ```❌ Requerimiento de la lista Pendiente```  
>
> #### Importante algunas navegaciones no llevan a la vista anterior ya que en el prototipo no hay manera de realizar validacion de. la vista anterior de donde se encontraba
  
## Navegacion

- [x] Ingresa.
  - [x]  Iniciar Session
  - [x]  Registrarme
  - [x]  Ir a Inicio
- [x]  Inicio Sin Auth ✅
  - [x]  Inicio (Deshabilitado por que ya esta en la vista de inicio)
  - [x]  Perfil (Muestra Alerta para iniciar sesion)
  - [x]  Notificaciones (Muestra Alerta para iniciar sesion)
  - [x]  Noticias y Anuncios
    - [x] Lista de eventos
  - [x]  Busqueda en Mapa
    - [x] Resultados de busqueda en mapa
  - [x]  Recursos
    - [x] Podcast(Sin Interacciones ⚠️)
    - [x] Lives (Sin Interacciones ⚠️)
    - [x] Videos (Sin Interacciones ⚠️)
    - [x] Favoritos (Sin Interacciones ⚠️)
    - [ ] Biblia Integrada (⛔️ Falta esta opcion)
- [x]  Inicio de session
  - [x]  Iniciar session (Lleva a vista de Usuario Autenticado)
  - [x]  Registrate ahora (Lleva a formulario de registro)
  - [x]  Atras (Lleva a la Vista de Usuario sin Autenticar)
- [x]  Registro
  - [x] Registrar Ahora (Lleva a la vista de 2FA)
- [x]  2FA (Lleva a la vista de pantalla de bienvenida)
- [x]  Bienvenida (Lleva a la vista de usuario autenticado)
- [x]  Usuario Autenticado
  - [x] Inicio (Inicio (Deshabilitado por que ya esta en la vista de inicio)
  - [x] Perfil (Lleva a la vista de perfil)
    - [x] Mis Puntos de Fe (Sin Interacciones ⚠️)
    - [ ] Configuracion
      - [ ] Actualizar Imagen (⛔️ Agregar Simbolo de Lapiz para indicar que se puede modificar la image)
      - [ ] Formulario Actualizar Datos Personales (⛔️ No indica opcion de cambio de password)
      - [x] Privacidad (Sin Interacciones ⚠️)
      - [x] Ayuda (Sin Interacciones ⚠️)
      - [ ] Log out (Sin Interacciones, debe llevar a la pantalla de usuario sin autenticar ⛔️)
    - [x] Aportes (⛔️ Agregar  formulario de registro para los aportes y gastos)
      - [x] Wallet (Es una lista)
      - [x] FIAT (Es una lista)
      - [ ] Registro de Aportes (Es una lista)
      - [ ] Registro de Gastos (Es una lista)
      - [x] Metricas
    - [x] Comunidad
      - [x] Eventos
        - [x] Lista de Anuncios
      - [x] Calendario
        - [x] Lista de eventos
          - [x] Agregar Evento
    - [ ] Congregacion
      - [x] Servicios
        - [x] Lista de Fichas de Servicios
      - [x] Eventos
        - [x] Lista de Anuncios
      - [x] Conexion
        - [x] Guia Espiritual (Sin Interacciones ⚠️)
        - [x] Mis Peticiones (Sin Interacciones ⚠️)
        - [x] Versiculos (Sin Interacciones ⚠️)
        - [x] Oraciones (Sin Interacciones ⚠️)
      - [x] Cursos
        - [x] Lista de Fichas de Curso para Inscripcion
    - [ ] Estudios
      - [x] Certificaciones
        - [x] Lista de Fichas de Certificaciones
      - [x] Encuentas
        - [x] Formulario de encuentas activas
      - [x] Cursos
        - [x] Lista de Fichas de Cursos
      - [x] Actividades
        - [x]  Lista de Fichas de Actividades
  - [ ] Recursos
    - [x] Podcast(Sin Interacciones ⚠️)
    - [x] Lives (Sin Interacciones ⚠️)
    - [x] Videos (Sin Interacciones ⚠️)
    - [x] Favoritos (Sin Interacciones ⚠️)
    - [ ] Biblia Integrada (⛔️ Falta esta opcion)
  - [x] Noticias y Eventos
    - [x] Lista de Anuncios
  - [x] Busqueda en Mapa
    - [x] Resultados de busqueda en mapa
  - [ ] Notificaciones
    - [x] Mensajes
      - [x] Mensajes Individuales
        - [x] Conversacion
      - [x] Mensajes de Grupo
        - [x] Conversacion
    - [x] Eventos y Noticias
      - [x] Lista de Anuncios
    - [x] Calendario
      - [x] Lista de eventos
        - [x] Agregar Evento

## Observaciones

- [ ] Corregir texto que aparece cortado.  

> ⛔️ Corregir texto en la pantalla de Ingresa "Tu aliado en el Ministerio de Cri..." que aun aparece cortado

- [x] Darle funcionalidad a todos los botones los que no se usen ocultarlos (Sugerencia en la pantalla de inicio de usuario sin autenticar generar un alerta que indique que debe registrarse o loguearse).  
- [x] Eliminar de esta pantalla el enlace que lleva a la opción de perfil, ya que al regresar lleva a la pantalla de inicio de usuario logueado.  
- [x] En la sección de ultimas noticias y eventos mostrar data fake y mostrar un demo de una noticia.
- [x] En sección de Busca tu iglesia simular el resultado de una búsqueda y mostrar el resultado de un mapa con el pin de ubicación.  
- [ ] Tratar de habilitar los input para demo de escritura.

> ⛔️No se logro habilitar los input

- [x] Revisar la transición de pantalla de inicio sin loguearse – registrarse – atrás. Debe llevar a la pantalla de inicio sin loguear lleva a pantalla inicial.
- [ ] Corregir error en el texto.

> ⛔️ Corregir texto en la pantalla de bienvenida luego del registrarse"Tu aliado en el Ministerio de Cri..." que aun aparece cortado

- [x] En la sección de artículos colocar el mismo artículo del home.  
- [ ] Ajustar la sección de Versículo del Dia ya que se ve cortado.  

> ⛔️ Dejar un pequeño espacio entre la barra de menu principal y la ficha versuculo del dia

- [x] Al seleccionar el buscador mostrar el mapa con el pin de ubicación.  
- [ ] El icono de configuracion debe mostrar la pantalla de edición de perfil.  

> ⛔️ En la pantalla de perfil: Agregar Simbolo de Lapiz para indicar que se puede modificar la image, agregar input de cambio de contraseña

- [x] En la sección de artículos colocar el mismo artículo del home.  
- [ ] Agregar demos de eventos en el calendario.  

> ⛔️ En la vista del calendario agregar data fake de algunos eventos (Señalar varios eventos el mismo dia en horas diferentes)

- [x] En la sección calendario, Demo de como se ve un evento al seleccionarlo de la fecha en el calendario.  
- [ ] En sección calendario simular algunas fechas marcadas en el calendario.

> ⛔️ Agregar mas fechas marcadas en el calendario

- [x] Al seleccionar un mensaje de la lista debe mostrar un mensaje modelo.  
- [x] Habilitar el clic de la flecha.
- [x] En la sección de mensaje de grupo, corregir el detalle que no muestra la flecha de atrás.  
- [x] Mostrar una lista de eventos.  
- [x] Mostrar lista de anuncios.  
- [x] Utilizar la misma data.  
- [ ] Mostrar demo de un artículo para visualizar como se ve.  

> ⛔️ El modelo del anuncio se visualiza dentro de la vista de lista eventos y noticias

- [x] Calendario ir a calendario.  
- [x] Revisar acciones en los botones.
- [ ] Colocar demo de Aporte.  

> ⛔️ Agregar formulario de registro para los aportes y gastos, similar al conversado el viernes 07/10 en donde se converso los item que llevaria (Monto, Motivo, Fecha, Numero Transaccion) fue un ejemplo

- [x] Mostrar demo de lista de servicios.  
- [x] Eventos llevar a la lista de eventos en el calendario.  
- [ ] Crear formularios de muestra.  

> ⛔️ Crear modelos de formularios (Ejm, aportes, peticiones, etc)

- [ ] No sabe a qué se refieres esta sección, pero los elementos de Esta sección muestra .  

> Esta seccion muestra los cursos disponibles y realizdos por usuario.

- [ ] Formularios par registro de cursos para suma de puntos de fe.  

> Al ser una app mobil se puede manejar como cambio de status (Ejm: Lista de cursos disponibles un boton para inscribirse, al realizar el curso el promotor del curso avala la participacion del usuario y cambia el estatus a realizado y suma los puntos de fe que otorga el curso (Es una propuesta para manejarlo), pero en otras secciones como los aportes si requiere formularios de muestra

> Importante validar la accesibilidad de todos los elementos mostrados en pantalla para evitar interactuar con elementos que no funcionen.  
