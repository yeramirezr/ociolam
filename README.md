## Desliegue Automatizado Utilizando Oracle Linux Automation Platform (OLAM) ##

### Requerimientos:###
- Cuenta de Oracle Cloud Infrastructure(test gratuito https://www.oracle.com/cloud/free/)
- Cuenta de Github (https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)

### ¿Qué vamos a hacer?###

- Clonar repositorio Github
- Configurar OLAM
- Crear Credenciales en OLAM
- Crear Proyecto en OLAM
- Crear Templates en OLAM
- Crear Workflow en OLAM
- Crear Instancia de autonomous Database
- Crear un VCN con Subnet y Security List
- Crear Container Registry 
- Despliegue de aplicación en Container Instance 

### Paso a Paso ##
1. Crear

https://user-images.githubusercontent.com/14284928/217976649-b8c72a52-9ed4-4757-a568-ea3580ccecd7.mov

2. Clonar Repositorio Git https://github.com/whiplash0104/Race-to-the-Cloud.git


https://user-images.githubusercontent.com/14284928/217976766-5c5407ea-f329-499f-acd2-8d8b02d82e07.mov


3. Crear compartment llamado RaceToCloud

```
Menu > Identity & Security > Compartmente > New Compartment
```


https://user-images.githubusercontent.com/14284928/217977014-8c324c4f-0c7b-4781-8e6b-de335c80605d.mov


4. Login Dentro de OLAM (https://158.101.114.83/)


https://user-images.githubusercontent.com/14284928/217977128-936480e4-6dd3-44f1-afe5-5c5ec1326d8d.mov


5. Crear Credencial Localhost, para realizar conexiones locales

```
Menu > Credenciales > Añadir
```

https://user-images.githubusercontent.com/14284928/217977221-54813a8c-a65b-4de2-a11f-2b1906357a50.mov

5.1. Test de credencial

```
Menu > Inventarios > Selecionar Inventario > Servidores
```

https://user-images.githubusercontent.com/14284928/217977267-cfc96121-7b95-4101-a2d6-3d99ae4e02bb.mov


6. Crear Credencial OCI, para relaizar conexión con Tenant

Importante seguir todos los pasos del video. La región para cada caso se puede encontrar en:

https://docs.oracle.com/en-us/iaas/Content/General/Concepts/regions.htm


https://user-images.githubusercontent.com/14284928/217977931-f72d80ae-f510-4f52-af31-197673bced2f.mov


7. Crear Credencial Git, para conectar con GitHub

```
Se realiza con Usuario y Contraseña de GitHub
```


https://user-images.githubusercontent.com/14284928/217978058-770a8ebb-fc63-4a8b-872b-0b20f4f4c1f4.mov


8. Crear Proyecto "Proyecto Race to the Cloud"

```
Menu > Proyectos > Añadir
```


https://user-images.githubusercontent.com/14284928/217978229-1eb7a5e7-fc7b-423c-b02c-1c38cfe41a76.mov


9. Crear Template "	Creacion ADB"

```
Menu > Plantillas > Añadir
```



https://user-images.githubusercontent.com/14284928/217978340-ef6576f1-b656-4376-b178-beda5a67d928.mov


10. Crear Template "Creacion Container Registry"

```
Menu > Plantillas > Añadir
```


https://user-images.githubusercontent.com/14284928/217978549-2f4e8c30-91ad-47bc-be99-bca765642116.mov



11. Crear Template "Creacion VNC"

```
Menu > Plantillas > Añadir
```


https://user-images.githubusercontent.com/14284928/217978589-f75b797d-0b6c-414d-974b-b7dac22f1abd.mov



12. Crear Template "Creacion Container Instance"

```
Menu > Plantillas > Añadir
```


https://user-images.githubusercontent.com/14284928/217978671-8a34b802-0bf3-4545-80c0-77ce2a5c0e5b.mov



13. ads
14. sda
15. asd
16. asd
17. asd
18. a
19. asd
20. a
21. sd
22. asd
23. asd
24. asd
25. asd
26. ads
27. sdadad

