TERRAFORM

Se contruye una infraestructura completa 

Creacion de IAM Role (Que tendra la policy para poder comunicarse con el servicio SSM)
Creacion de VPC y subredes (VPC, subred privada y 2 subredes publicas)
Creacion de NAT GATEWAY para conexion a internet de vpc privadas y el internet gateway par salida a internet de vpc publicas
Creacion de Secuirty Group (1 security group para que el ALB permite conexiones entrantes al puerto 80 y otro security group para las instancia que permitan se accedidas 
al puerto 80 solo desde el ALB)
Creacion de ALB
Creacion de Target Group 
Creacion de Auto Scaling Group

