## Despliegue Automatizado Utilizando Oracle Linux Automation Platform (OLAM) 

### Requerimientos:

- Cuenta de Oracle Cloud Infrastructure(test gratuito https://www.oracle.com/cloud/free/)
- Cuenta de Github (https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)

### ¿Qué vamos a hacer?

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

### Paso a Paso

0. Crear Cuenta en git, usuar correo empresarial o personal (github.com)


https://user-images.githubusercontent.com/14284928/219779574-ad656998-a63d-402a-87cd-b9658c84e401.mov




1. Crear Repositorio Git

https://user-images.githubusercontent.com/14284928/217976649-b8c72a52-9ed4-4757-a568-ea3580ccecd7.mov



2. Clonar Repositorio Git  https://github.com/whiplash0104/Race-to-the-Cloud-Infra.git


https://user-images.githubusercontent.com/14284928/217976766-5c5407ea-f329-499f-acd2-8d8b02d82e07.mov




3. Crear compartment llamado RaceToCloud

```
Menu > Identity & Security > Compartmente > New Compartment
```


https://user-images.githubusercontent.com/14284928/217977014-8c324c4f-0c7b-4781-8e6b-de335c80605d.mov




4. Login Dentro de OLAM (https://150.136.98.96/) en base a usuario y contraseña entregada. **Es un acceso por empresa**


https://user-images.githubusercontent.com/14284928/217977128-936480e4-6dd3-44f1-afe5-5c5ec1326d8d.mov




5. Crear Credencial OCI, esta permite la íntegración entre OLAM y OCI
NOMBREMPRESA: es el nombre de cada empresa, no usar espacios ej: **si mi empresa se llama "Empresa Jovial" usar el nombre EmpresaJovial**

```
Menu > Accesos > Credenciales > Añadir

Nombre: Credencial OCI *NOMBREEMPRESA*
Organización: Selecionar la organización que corresponde a la empresa
```

https://user-images.githubusercontent.com/14284928/219782010-192d2a87-2cb6-4cb9-a1a3-d7362ad8ad60.mov



6. Una vez creada la credencial OCI ir al submenu Planillas:

```
Menu > Recursos > Planillas
```

Se encontrarán con las plantillas quue se utilizarán creadas

![image](https://user-images.githubusercontent.com/14284928/219783093-8d87e1e6-b63b-4ecb-bf74-86a23355efa6.png)



7. dsdaad
8. das
9. da
10. da
11. da
12. d
13. a
14. sda
15. asd
16. das
17. sda
18. asd
19. ad
