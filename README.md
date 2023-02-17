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



7. Dentro de Planilla (Templates) se encontrarán con uno llamado *WF Crea NOMBREEMPRESA*, a este workflow se le deben agregar los templates a utilizar y la credencial de OCI recién creada

```
Abrir WF Crea NOMBREEMPRESA
Ir a la pestaña Visualizador
![image](https://user-images.githubusercontent.com/14284928/219784197-1da5d7c3-c38c-4b5c-821c-0a65958f4841.png)

Hacer click en el botón verde Iniciar
![image](https://user-images.githubusercontent.com/14284928/219784373-e37da084-7fbd-4009-9585-5b3acccc50c6.png)

Selecionar el Template Crea ADB NOMBREEMPRESA y click en Siguiente
![image](https://user-images.githubusercontent.com/14284928/219784417-99effd9a-1868-46d7-8036-8265025b7274.png)

En el grupo Credencial ir a la categoría Oracle Cloud Infrastructure, y selecionar la credencial de OCI creada en pasos anteriores. Una vez selecionada click en Siguiente
<img width="656" alt="image" src="https://user-images.githubusercontent.com/14284928/219784594-a993b5e5-78f3-4c26-84d7-9b0c0c810ce7.png">

NO HACER NINGÚN CAMBIO EN OTRAS CREDENCIALES y click en guardar

El workflow debió cambiar a algo similar a la imágen
![image](https://user-images.githubusercontent.com/14284928/219784989-34bf61f4-217d-4267-8686-7eb26436698a.png)

Pasar el mouse sobre el nombre de la planilla agregada y hacer click en el símbolo + para agregar el siguiente template
<img width="745" alt="image" src="https://user-images.githubusercontent.com/14284928/219785222-10ae741d-8f7c-4f7f-b1ea-955a43f2b438.png">

Hacer lo mismo para los todos los template en el sioguiente orden:

  1. Crea ADB NOMBREEMPRESA
  2. Crea VCN NOMBREEMPRESA
  3. Crea Registry NOMBREEMPRESA
  4. Build Container Image NOMBREEMPRESA
  5. Crea Instancia NOMBREEMPRESA
```

https://user-images.githubusercontent.com/14284928/219785510-0b86a71a-91e0-4156-b869-0eb1c5ba459f.mov




8. Una vez creado el Workflow Ejecutarlo haciendo click en el botón Ejecutar
![image](https://user-images.githubusercontent.com/14284928/219785666-3b417e2f-cb60-4cdc-aeef-9a72a607f1f5.png)


9. aadsd
10. da
11. da
12. da
13. d
14. a
15. sda
16. asd
17. das
18. sda
19. asd
20. ad
