# nginx_reverse_proxy

Proxy Inverso con Nginx (Usar el NGINX y tocar en config para que se modifique para que me redireccione)
1.	Instalamos NGINX (https://nginx.org/)
2.	Instalamos la versión más estable para Windows, que es la versión 1.24.0.zip

 ![image](https://github.com/HectorCRZBQ/nginx_reverse_proxy/assets/148070442/503b950a-b30a-449c-9a6a-6d23ff7ebcab)

3.	Descomprimimos el archivo zip
4.	Accedemos dentro de carpeta y buscamos dentro una carpeta con nombre conf.
5.	Dentro de conf buscamos el archivo de configuración con nombre nginx.conf
6.	Tenemos que modificar la dirección local para que la ruta https://paginawebhector.com nos funcione como si fuese un http://127.0.0.1:8003.
 
![image](https://github.com/HectorCRZBQ/nginx_reverse_proxy/assets/148070442/6ea9868e-cffc-424c-bfd3-75649f75376b)

7.	Accedemos a donde tengamos descargado Nginx, en la dirección de cd C:\Users\hecto\Downloads\nginx-1.24.0, en nuestro equipo por medio de la Windows PowerShell en Administrador.
8.	Dentro de esa ubicación para inicializarlo se hace con el comando start nginx o start .\nginx
9.	Una vez modificada el nginx.conf se guarda y se reinicia con .\nginx -s reload
10.	Necesitamos acceder a la ubicación C:\Windows\System32\drivers\etc\hosts, abrimos el archivo con VSCode o Lector de texto. Incorporamos una nueva direccion de localhost , en este caso es 127.0.0.1	 paginawebhector.com. (Mejor desde VSCode por permisos de administrador)

![image](https://github.com/HectorCRZBQ/nginx_reverse_proxy/assets/148070442/f152c218-e6e0-4347-b5c4-5f2c70de9172)
 
11.	Accedemos por medio del buscador al enlace: https://paginawebhector.com y se nos muestra nuestra página web

Hector de la Cruz Baquero - [Linkdedin](https://www.linkedin.com/in/h%C3%A9ctor-de-la-cruz-baquero-ba193429b/) - [Webpage](https://hectorcrzbq.github.io/)
