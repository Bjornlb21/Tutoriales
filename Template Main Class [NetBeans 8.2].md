# Tutorial 3.

Para la Versión 8.2 de Netbeans.

Editar el Template del Java Main Class para que nos aparezca el código que nosotros querramos sin tener que estar escribiéndolo cada vez que creamos un nuevo Proyecto o Archivo.

Así quedaría el Archivo nuevo cada vez que crean uno:

![image](https://user-images.githubusercontent.com/119635145/231374757-f7544269-5c60-4406-be5a-8eb87b67c43d.png)

Tools --> Templates.

![image](https://user-images.githubusercontent.com/119635145/231374918-2543bc4c-f0ba-4dc2-a6f3-1986920ffd84.png)

Buscan la Carpeta "Java" y la Despliegan --> Buscan el "Java Main Class" --> Open in Editor

![image](https://user-images.githubusercontent.com/119635145/231375203-b357d26c-0b58-455c-bf9d-71e647c47f34.png)

Borramos SOLO lo que está dentro de los Cuadrados Rojos.

![image](https://user-images.githubusercontent.com/119635145/231375570-8e499a41-ebf1-4050-ba9b-114df2bb767b.png)

Edité donde aparece nuestro Usuario, en mi caso lo agregue en 2 "//" pero no se debe borrar el "</#if>" que está arriba del Usuario o generará problemas en el código.

También agregué el "import java.util.Scanner;" debajo del Usuario.

También agregué el "Scanner leer = new Scanner(System.in);" y unos espacios.

![image](https://user-images.githubusercontent.com/119635145/231375952-e1ed6177-69e4-43a4-955e-532f8fe1c959.png)

Y cuando creen un nuevo Archivo Java Main Class ya les va a aparecer así:

![image](https://user-images.githubusercontent.com/119635145/231376645-a9999f58-4a18-4e62-bc15-de5e6a6ba880.png)

