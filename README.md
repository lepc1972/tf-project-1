
![terraform](https://github.com/user-attachments/assets/6421dbcb-b73b-4cc8-bc1c-cfd75ac25705)

# tf-project-1
## Repo for terraform project

### Este repo contiene archivos terraform para creacion de infraestructura, segun instrucciones bootcamp mintic

----------------------------------------------------------------------------------------------------------------

# Descripcion archivos

## variables.tf

### contiene las variables que van a ser usadas en el codigo

-----------------------------------------------------------------------------------------------------------------

## terraform.tfvars

### contiene valor variables que van a ser usadas, y que tambien estan relacionadas con variables.tf

------------------------------------------------------------------------------------------------------------------

##  terraform.tfstate  y  terraform.tfstate.backup

### archivos creados directamente por terraform al iniciar codigo

------------------------------------------------------------------------------------------------------------------

## rds.tf

### archvo configuracion de un bd mysql aurora en aws con multizona

-------------------------------------------------------------------------------------------------------------------

## providers.tf

###  En Terraform, los "providers" son plugins que permiten a Terraform interactuar con diferentes plataformas,
servicios y APIs. Básicamente, son los que le dan a Terraform la capacidad de crear, modificar y eliminar recursos en 
diferentes entornos.

---------------------------------------------------------------------------------------------------------------------

##  nginx-deployment.yaml

### este es un .yaml que ejecuta un deployment de  servidor nginx en el cluster aws, es una forma de hacerlo manual,
ahora mismo esta haciendo el deploy automaticamente con terraform.

----------------------------------------------------------------------------------------------------------------------

## network.tf

### contiene configuracion de vpc y suredes

----------------------------------------------------------------------------------------------------------------------

## eks.tf

### contiene todo lo relacionado con la configuracion del cluster en aws

-----------------------------------------------------------------------------------------------------------------------

#                                                     MODO USO

## clonar el repositorio, debes tener instalado terraform, tener una cuenta en aws y tenerla configurda en tu cli, verificar 
que tu usuario,tenga todos los permisos necesarios para ejecutar el codigo, y poder manipular recursos creados en aws.

## COMANDOS TERRAFORM

## terraform init

### El comando terraform init es el primer comando que debes ejecutar en un directorio que contiene archivos de configuración 
de Terraform. Esencialmente, prepara tu directorio de trabajo para que puedas usar Terraform para crear, modificar y gestionar
tu infraestructura.

---------------------------------------------------------------------------------------------------------------------------

## terraform fmt

### El comando terraform fmt formatea tu código Terraform para que siga las convenciones de estilo estándar. Esto ayuda a mantener 
la consistencia y la legibilidad en tus archivos de configuración.

-----------------------------------------------------------------------------------------------------------------------------------

## terraform validate

### El comando terraform validate en Terraform se utiliza para verificar la validez de tus archivos de configuración. Realiza una 
serie de comprobaciones para asegurarse de que tu código esté escrito correctamente y sea internamente consistente, sin llegar a 
conectarse a ningún servicio externo o aplicar cambios reales.

------------------------------------------------------------------------------------------------------------------------------------

## terraform plan

### El comando terraform plan en Terraform es esencial para comprender qué cambios se realizarán en tu infraestructura antes de 
aplicarlos realmente. Crea un plan de ejecución que detalla las acciones que Terraform tomará para que tu infraestructura coincida con 
tu configuración 
actual.

----------------------------------------------------------------------------------------------------------------------------------------

## terraform apply

### El comando terraform apply es uno de los comandos más importantes en Terraform. Se utiliza para aplicar los cambios que has definido 
en tu configuración y crear, modificar o eliminar recursos en tu infraestructura.





