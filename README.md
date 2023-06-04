Usando Golang (net/socket) para DDOS

**Advertencia: use el comando "ulimit -n 999999" antes de usar esto en Linux**

**1 subprocesos = 1 conexión, 100 ~ 300 conexiones pueden cerrar un sitio web normal en 10 segundos (especialmente el servidor Apache LOL)**

**Esto es golang y los subprocesos son solo gorutinas, por lo que establecer subprocesos más altos como 1000-5000 está bien.**

**¿Por qué puede ejecutar más de 1000 subprocesos**

## INFO
- [x] HTTP Obtener inundación
 - [x] Inundación de publicaciones HTTP
 - [x] URL aleatoria (http recibe inundación)
 - [x] Encabezado de edición automática (puede usar "nil" para usar el encabezado predeterminado)
 - [x] Control de subprocesos mejorado
 - [x] Inundación más poderosa
 - [x] Obtención automática de dominio de formulario IP (función incorporada de golang)
 - [x] Fijo para sistemas 386
 -------------------------------------------------- ---
 Configuración de encabezado predeterminada:
 - [x] Agentes de usuario aleatorios
 - [x] Datos aleatorios (inundación de publicación de http)
 - [x] Aceptación aleatoria

## DOWLOAD
***Por favor, descargue el F\*cking golang al principio.***

Entonces:

   git clone https://absoluteb31nf/DDOS.git

Formato de encabezado.txt:

    Aceptar: texto/html
    Agente de usuario: Wget
    Referencia: http://google.com

O cualquier otra cosa del encabezado http. Si no tiene idea de esto, simplemente use "nil" para usar el encabezado aleatorio 
predeterminado.

## USAGE
```
 cd DDOS
 
    go build DDOS.go
   
./DDOS  <url> <threads> <get/post> <seconds> <header.txt/nil>
```
  
  
