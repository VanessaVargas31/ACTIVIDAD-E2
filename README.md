# **BIENVENIDOS A PROGRAMAS EN C++ DE VARGAS VANESSA**


**INFORMACION DEL AUTOR**
###### `Autor: VARGAS VANESSA`
######  `Enlace video:`  https://youtu.be/cctlGkTGkW4
###### `Correo: roshiitoral312@gmail.com `
# PROGRAMAS
**Compara de dos números**

###### Descripción del problema
Diagrama de flujo y programa en C++ que permita ingresar dos valores y los compara para saber cuál es el mayor en caso de que sean iguales, indique que son iguales.

1. Debe ingresar los numeros a comparar.
2. El programa realizará una comparación de los numeros ingresados
3. El programa designará cual es el mayor o si son iguales.
4. Finalmente mostrará el resultado por pantalla.
###### Funcionalidad
`float VV_x, VV_y;`
###### Salida
`if(VV_x==VV_y)  son iguales
if(VV_x<VV_y)   a es el mayor`

**Suma de varios números**
###### Descripción del programa
Diagrama de flujo y programa en C++ en C++ que permite sumar varios números el usuario debe ingresar la cantidad de número que quiere sumar y el programa debe mostrar la suma total de los números.
1. Ingresa los 2 numeros para hacer la sumarespectiva.
2. El programa realizara la suma de los numeros ingresados.
3. Finalmente el programa mostrara el resultado de aquella suma.
###### Funcionalidad
`int VV_c=0, VV_n;
    float VV_s=0, VV_x;`
###### Salida
`cout<<"Ingrese un número para sumarlo: "<<VV_s<<endl;`

**Calcula la edad**
###### Descripción del programa
Diagrama de flujo y programa en C++ que permite calcular de edad de una persona, el programa debe permitir ingresar la fecha actual, la fecha de nacimiento y mostrar cuantos años, meses y días tiene la persona.

 1.Ingresa los datos pedido por el programa.
 
 2.El programa se encargá de hacer los calculos respectivos.
 
  3.El programa mostrará el resultado del calculo realizado.

###### Funcionalidad
`int VV_AA,VV_MA,VV_DA,VV_AN,VV_MN,VV_DN,VV_A,VV_M,VV_D;`
###### Salida
`cout<<"Usted tiene "<<VV_A<<" años "<<VV_M<<" meses  y"<<VV_D<<" dias ";`

**Punto de Venta**
###### Descripción del programa
Diagrama de flujo y programa en C++ que permita ingresar el precio de varios productos y calculo el IVA a cobrar el descuento y el valor final a pagar, el programa mostrara total valor bruto, valor del IVA, valor del descuento y valor final a pagar.
1. Ingrese cuantos productos comprará.
2. Ingrese el valor de cada producto.
3. Realizará el respectivo calculo para sacar el el valor de su compra con el iva incluido.
4. Realizará otro calculo para hacerle un descuento del valor con iva.
5. El programa por ultimo mostrará el resultado del valor correspondiente a su compra
###### Funcionalidad
`float VV_A=0, VV_x, VV_Tb, VV_Piva, VV_Pdsc, VV_iva=0.12, VV_desc=0.30, ct_vt;`
###### Salida
`cout<<"El valor total es de: $"<<VV_vt<<endl;`

**Cuenta moneda**

Diagrama de flujo y programa en C++ que permita ingresar varias monedas de 2 tipos diferentes (10ctv y 25ctv) y presentara cuantas monedas de cada denominación se ingresaron, cuanto es la cantidad en dinero de cada denominación; así como la cantidad de dinero total que se ingresaron.
1. Ingresa la cantidad de monedas por contar.
2. Selecciona cuantas monedas son de 0.25 y cuantas son de 0.10.
3. El programa hará la contabilidad de las monedas ingresadas.
4. Por ultimo mostrará el resultado de todas las monedas ingresadas.
###### Funcionalidad
`int VV_n, VV_c=0, VV_c1=0, VV_c2=0;
	float VV_x, VV_a=0, VV_a1=0, VV_a2=0, VV_m=0.10;`
###### Salida
`if(VV_x==VV_m)
if (VV_c1=VV_c1+1)
if (VV_a1=VV_a1+VV_x)
while(VV_c<VV_n)`


## Instalación

### Descargar el repositorio
1.- Para descargar todos los archivos del repositorio clonamos "git clone https://github.com/'USUARIO'/'NOMBRE DE REPOSITORIO.git'"
Ejemplo:

git clone https://github.com/VanessaVargas31/ACTIVIDAD-E2.git

2.-Con el comando  "cd" podrá acceder a la carpeta contenedora de los archivos.  Ejemplo:
cd ACTIVIDAD-E2

### Compilar y ejecutar
1.-Con este comando podrás compilar el archivo requerido "g++ 'nombre del programa.cpp' -o 'nuevo nombre del programa'.
 Ejemplo:

g++  VARGASVANESSA-Compara.cpp -o VARGASVANESSA-Compara

2.-Con este comando podras ejecutar el archivo "./'nombre del programa'".  Ejemplo:

./VARGASVANESSA-Compara
