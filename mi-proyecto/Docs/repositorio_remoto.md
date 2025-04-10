# <span style="color: blue;">Repositorio remoto</span>


Para crear un repositorio remoto en GitHub y sincronizarlo con tu repositorio local, primero inicia sesión en GitHub y haz clic en "New" para crear un nuevo repositorio, asignándole un nombre y eligiendo si será público o privado.

![alt text](../images/image23.png)

 Luego, obtén la URL del repositorio recién creado (por ejemplo, https://github.com/tu-usuario/mi-proyecto.git). En tu terminal, navega a la carpeta de tu proyecto local y conéctalo al repositorio remoto con el comando git remote add origin <URL>. 
 
![alt text](../images/image14.png)

 Verifica la conexión con git remote -v. Después, sube los cambios locales al repositorio remoto usando git add ., git commit -m "mensaje" y git push -u origin main. A partir de ese momento, cualquier cambio local puede sincronizarse con el repositorio remoto usando git push origin main. Si necesitas clonar el repositorio en otro equipo, usa git clone <URL>. ¡Y listo! Tu repositorio local y remoto estarán sincronizados.

 ![alt text](../images/image65.png)

 ![alt text](../images/image54.png)