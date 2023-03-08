|![Logo de Microsoft: la historia y el significado del logotipo ...](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.001.png)|<p>Taller Power Apps – Low Code</p><p></p><p>Roberto Corella</p><p>Pregunta a chatGPT</p>|![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.002.png)|
| :- | :-: | -: |

**Escenario**

Queremos aprovechar la conocida herramienta de openAI que nos permite realizar consultas a la inteligencia artificial y para ello usamos su API con una aplicación de Power Apps

**Abrir entorno de desarrollo de Power Apps**

1 - Abrir navegador

2 – Ir a la web <https://make.powerapps.com>

3 – Introducir el usuario suministrado y pulsar **Siguiente**

<cta01@M365B804054.onmicrosoft.com>

4 – Introducir en “**Escribir contraseña**” la contraseña suministrada y pulsar “**Iniciar sesión**”

5 – Si nos indica ¿Quiere mantener la sesión iniciada? 

Marcar la opción “No volver a mostrar”

Pulsar Sí.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.003.png)

6 – Información de contacto

Poner como número de teléfono 976976976 y pulsar enviar

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.004.png)

Si, aparece un asistente, pulsar “Omitir”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.005.png)

7 – En el menú lateral seleccionar ‘+ Crear’ y seleccionar “Aplicación vacía”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.006.png)

8 -  De las tres aplicaciones que nos aparecen, seleccionamos “Aplicación de lienzo en Blanco” y pulsamos “Crear”.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.007.png)

9 – Ponemos un nombre a nuestra App (XX PreguntaApp) donde XX serán nuestras iniciales y seleccionamos el formato de Tableta.

![Graphical user interface, application, Teams

Description automatically generated](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.008.png)

10 – Nos aparecerá un mensaje de Bienvenida.  Marcar la opción de “No volver a mostrar” y pinchar sobre “Omitir”:

![Graphical user interface, text, application, email

Description automatically generated](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.009.png)

Los controles se añaden a nuestro lienzo desde el menú superior “+ Insertar”.

11 – Insertar un control “Rectángulo” desde el menú “+ Insertar” y colocarlo cubriendo la parte superior de la pantalla a modo de título

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.010.png)

12 – Insertar un control “Etiqueta” desde el menú “+ Insertar” y ponerlo centrado sobre el rectángulo creado previamente para escribir el título de nuestra aplicación.

Para modificar el tamaño de los controles usaremos los puntos que nos aparecen al pinchar sobre ellos, arrastrando.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.011.png)

Si prefieres, puedes utilizar las propiedades del menú lateral para ponerlo en el lugar adecuado, seleccionando la etiqueta y rellenando los valores siguientes:

- Posición X : 38
- Posición Y : 23
- Tamaño Ancho: 1124
- Tamaño Alto: 53

13 – Con la etiqueta seleccionada, vamos a cambiar el texto, para poner el título, el color del Font, el tamaño del font y la alineación centrada para que se vea mejor sobre fondo oscuro, para ello modificaremos las propiedades:

- Texto:  PreguntaApp
- Tamaño de fuente: 24
- Alineación: Centrada
- Color: Blanco

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.012.png)

14- A continuación, insertaremos un control de imagen a nuestra App, para poner un logotipo.  Para ello, iremos a ‘+ insertar’ y en la casilla de buscar escribimos “imag” y seleccionamos “imagen”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.013.png)

15 – colocamos el control en la parte derecha del título y lo ajustamos para que nos quede alineado al rectángulo creado previamente:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.014.png)

16 – Crear una carpeta en el disco c:\ y llamarla “Recursos”

17 – Guardar la imagen del siguiente link, en la carpeta “Recursos”, pulsando el botón derecho

sobre la imagen y seleccionado “Guardar imagen como”

https://pruebasformacion.blob.core.windows.net/power/hotels-logo.png

18 – Seleccionando el control de imagen, en las propiedades seleccionamos “Imagen” y ‘+ Agregar un archivo de imagen”:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.015.png)

19 – Seleccionamos el archivo de imagen descargado previamente pulsando “Abrir”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.016.png)

Ya tenemos nuestro logo colocado.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.017.png)

20 – Insertamos un control “Etiqueta” y un control “Entrada de texto” (de una en una, ya que no podemos seleccionar las dos a la vez), para que nuestros usuarios hagan las preguntas a openAI:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.018.png)

21 – Los colocaremos en el lienzo y cambiaremos las propiedades:

Etiqueta “Label2”

- Texto: “Pregúntame”
- Posición X: 51
- Posición Y: 126
- Tamaño Ancho : 303
- Tamaño Alto: 45

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.019.png)

Seleccionando la entrada de texto TextInput1

- Predeterminado: Donde está la ciudad de Zaragoza
- Posición X: 382
- Posición Y: 128
- Tamaño Ancho: 747
- Tamaño Alto: 43

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.020.png)

22 – Insertamos un nuevo control “Botón” y lo colocamos a la derecha del control de entrada de texto, con las siguientes propiedades:

- Texto: Preguntar
- Posición X: 1184
- Posición Y: 128

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.021.png)

23 – Insertamos un nuevo control “etiqueta de texto” para detallar donde pondremos la respuesta, con las siguientes propiedades:

- Texto: Respuesta
- Posición X: 51
- Posición Y: 222

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.022.png)

24 – Añadiremos un control texto html, para mostrar la respuesta que nos devolverá la Inteligencia Artificial:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.023.png)

El control tendrá las siguientes propiedades:

- Texto HTML: Muestre el texto respuesta
- Posición X: 172
- Posición Y: 236
- Tamaño Ancho: 957
- Tamaño Alto: 318

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.024.png)

25 - Es un buen momento para guardar y probar nuestra aplicación.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.025.png)

Ahora que ya tenemos el diseño, vamos con la lógica.  Para conectarnos a chatGPT vamos a utilizar Power Automate para que haga la llamada y nos devuelva el resultado.

26 - En el menú lateral, seleccionar “Power Automate” y pulsar “Crear nuevo flujo”.  En caso de que nos aparezca la bienvenida, pulsar “Comenzar”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.026.png)

27 – En la siguiente pantalla pulsaremos “+ Crear desde cero”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.027.png)

Se creará un flujo instantáneo, es decir, que se ejecuta cuando nosotros le decimos.  Es decir, en un botón de “Power Apps”

**Power Automate**

Power Automate ejecuta procesos a través de diferentes pasos de acciones.

28 – Ya podemos comenzar a crear nuestro flujo añadiendo nuevos pasos, pinchando sobre “+ Nuevo Paso”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.028.png)

29 – Añadimos un paso para inicializar una variable donde guardaremos la respuesta.  Lo hacemos mediante la operación “Variable” y la acción “Inicializar variable”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.029.png)

30 – Como nombre de nuestra variable le diremos “Resultado” y como “Tipo” Cadena:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.030.png)

31 – Añadiremos un nuevo paso con el conector “HTTP” (colocarse en la pestaña premium para localizarla mejor).  Eso nos permitirá hacer una llamada a la API de chatGPT

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.031.png)

32 – Usaremos la acción HTTP

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.032.png)

33 – La llamada a ChatGPT requiere una serie de parámetros:

- Método: POST
- URI (Dirección web a la que llamar): <https://api.openai.com/v1/completions>
- Encabezados
  - Authorization 		Bearer API-KEY
  - Content-type		Application/json
- Cuerpo

{

`  `"model": "text-davinci-001",

`  `"prompt":””,

`  `"max\_tokens": 100,

`  `"temperature": 0,

`  `"top\_p": 1,

`  `"frequency\_penalty": 0,

`  `"presence\_penalty": 0

}

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.033.png)

Donde tenemos la propiedad “prompt”, y entre las comillas pondremos el texto que le queremos preguntar a ChatGPT, por lo que eso nos lo tendrá que decir el usuario de nuestra app y por tanto, no debe ser fijo.  Usaremos el contenido dinámico para solicitarle a Power Apps la pregunta:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.034.png)

Esto nos rellenará un valor dinámico:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.035.png)

34 – Añadimos un nuevo paso, para analizar la respuesta que nos dé la consulta.  La respuesta será JSON por lo que debemos usar la operación “Operación de datos”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.036.png)

35 – Dentro de las acciones, usaremos “Análisis del archivo JSON”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.037.png)

Como “Contenido” usaremos el contenido dinámico que viene del paso anterior “HTTP”, que será el cuerpo.

36 – Como esquema usaremos este:

{

`    `"type": "object",

`    `"properties": {

`        `"id": {

`            `"type": "string"

`        `},

`        `"object": {

`            `"type": "string"

`        `},

`        `"created": {

`            `"type": "integer"

`        `},

`        `"model": {

`            `"type": "string"

`        `},

`        `"choices": {

`            `"type": "array",

`            `"items": {

`                `"type": "object",

`                `"properties": {

`                    `"text": {

`                        `"type": "string"

`                    `},

`                    `"index": {

`                        `"type": "integer"

`                    `},

`                    `"logprobs": {},

`                    `"finish\_reason": {

`                        `"type": "string"

`                    `}

`                `},

`                `"required": [

`                    `"text",

`                    `"index",

`                    `"logprobs",

`                    `"finish\_reason"

`                `]

`            `}

`        `},

`        `"usage": {

`            `"type": "object",

`            `"properties": {

`                `"prompt\_tokens": {

`                    `"type": "integer"

`                `},

`                `"completion\_tokens": {

`                    `"type": "integer"

`                `},

`                `"total\_tokens": {

`                    `"type": "integer"

`                `}

`            `}

`        `}

`    `}

}

El esquema corresponde a la estructura de como recibiremos los datos de la API de chatGPT

37 – Añadiremos otro paso con la operación “Control” y seleccionamos “**Aplicar a cada uno**”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.038.png)

ChatGPT nos devuelve dentro del JSON un array llamado Choices, que es el que tenemos que revisar:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.039.png)

38 – Parte de lo que tengamos en ese array, lo guardaremos en la variable creada anteriormente, por lo que tenemos que utilizar otra operación “Variable”, esta vez para “Establecer variable”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.040.png)

39 -  La variable a rellenar será “Resultado” y el valor, será lo que nos viene en la propiedad “Text” de ChatGPT, obtenido en el paso anterior.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.041.png)

Ahora ya tenemos el valor del texto devuelto por ChatGPT en la variable Resultado.  Eso es lo que tenemos que devolver a Power Apps para mostrarlo al usuario.

40 – Añadiremos un último paso con la operación “Responder a una instancia de Power Apps”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.042.png)

41 – Agregaremos una salida pinchando sobre “+ Agregar una salida” y seleccionaremos que sea de tipo texto:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.043.png)

42 – Como nombre le pondremos “Respuesta” y como valor el contenido dinámico procedente de la variable “Resultado”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.044.png)

Con esto tenemos finalizado el flujo.  Solamente nos queda ponerle un nombre y guardarlo.

43 – Al flujo le llamaremos “consultaChatGPT”, escribiendo sobre la parte superior izquierda.  Después pulsaremos guardar.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.045.png)

Esperaremos a que este guardado y la web nos llevará otra vez a Power Apps, donde podremos ver nuestro flujo.

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.046.png)

44 – Ahora le tenemos que incorporar la lógica al botón “Preguntar” para que llame al flujo.  Para ello, seleccionamos el botón y en el evento “OnSelect”, introducimos la fórmula:

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.047.png)

Set(respuesta;consultaChatGPT.Run(TextInput1.Text).respuesta)

Mediante la instrucción Set, guardamos en una variable el resultado del flujo.

45 – Ahora tenemos que mostrar el resultado al usuario, en el control “Texto HTML”, para lo cual, modificaremos la propiedad “Texto Html” con el valor “Respuesta”

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.048.png)

46 -  Guardamos y probamos.

Preguntas:

Dime un slogan para un hotel de ciudad en español

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.049.png)

![](recursos/Aspose.Words.b7da1bd4-5f1e-4c7c-a978-d7831a573c9f.050.png)



09 de Marzo 2023        @rccorella
