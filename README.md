#include <stdio.h>

int main()

{ int ruta;
  char dia;

printf("Bienvenido a la sección de rutas urbanas:\n");
printf("seleccione el día en que desea realizar el recorrido\n");
printf("1. Lunes\n"
       "2. martes\n"
       "3. Miercoles\n"
       "4. jueves\n"
       "5. viernes\n"
       "6. sabado\n"
       "7. domingo\n"
       ":");
       
       
       if 
           (dia == "lunes,martes,miercoles,jueves,viernes")
         {
             printf ( "la ruta disponibles es:", ruta=46);
         }
      
scanf("%c", &dia);

scanf("%d",&ruta);
printf("ruta asignada %c",ruta);

 if(ruta == 46)
{
    printf("KR 4 - CL 30 Soacha, KR 7 - CL 33 Soacha, TV 7 - CL 47 Soacha, TV 7 - CL 55 Soacha, Autopista Sur- 65A Sur, Autopista Norte - CL 97, Autopista Norte - CL 134, Autopista Norte - CL 165, Autopista Norte - CL 172A");
} 
if (ruta == 75)
{
    printf(" Portal de Usme, Molinos, Consuelo, Socorro, Santa Lucía, Calle 40 Sur, Quiroga, Olaya, Restrepo, Fucha, Nariño, Hortúa, Hospital, Tercer Milenio, AV. Jiménez (AV. Caracas), Calle 19, Calle 22, Calle 26, Calle 34, AV. 39, Calle 45 - American School Way, Marly, Calle 57, Calle 63, Flores - Areandina, Calle 72, Est. Calle 76 - San Felipe, Héroes - Gel´hada, Calle 85, Virrey, Calle 100 - Marketmedios, Calle 106, Pepe Sierra, Calle 127, Prado, Alcalá, Calle 142, Calle 146, Mazurén, Calle 161, Toberín - Foundever, Portal del Norte, Calle 187, Terminal");
}
else {
    printf("no hay ruta asignada");
}
printf("seleccione el día en que desea realizar el recorrido\n");
printf("ingrese su ruta de preferencia:\n");
