#include <stddef.h> 

#include <stdio.h> 

#include <stdlib.h> 

#include <ctype.h> 

 

// Puntos asignados a cada letra del ABCedario 

int PUNTOS[] = {1,3,3,5,2,1,4,2,4,1,8,1,8,3,1,8,1,3,5,1,8,1,1,1,4,8,4,8}; 

 

unsigned int calcular_puntaje(char palabra[]); 

 

int main(void) 

{ 

     

       

    char palabra1[100]; 

    char palabra2[100]; 

   

    unsigned int puntuacion_jugador_A = 0; 

    unsigned int puntuacion_jugador_B = 0; 

   

    printf("Scrabble version 0.0.0\n\n");    

   

    // Obtener las palabras de cada jugador 

    printf("Jugador A:Palabra:\n"); 

    scanf("%s",palabra1); 

    printf("Jugador B:Palabra\n"); 

    scanf("%s",palabra2); 

    // Obtener el puntaje para cada jugador 

    puntuacion_jugador_A = calcular_puntaje(palabra1); 

    puntuacion_jugador_B = calcular_puntaje(palabra2); 

    printf("\n[A]:%s\t|\t[B]:%s\n",palabra1,palabra2); 

    // TODO: Determinar el ganador 

    printf("\nEl ganador es el jugador : \n"); 

    return EXIT_SUCCESS; 

     

} 

unsigned int calcular_puntaje(char palabra[100]) 

{ 

    unsigned int puntaje = 0; 

    // TODO: Calcular el puntaje para la palabra 

    return puntaje; 

} 

 
