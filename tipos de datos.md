# Programacion_Basica
package com.mycompany.tipos_datos;

import java.util.Scanner;

/**
 *
 * @author prestamo
 */
public class Tipos_Datos {

    public static void main(String[] args) {
       
        var consola = new Scanner(System.in);
        System.out.print("Ingresa tu edad: ");
        var edad = consola.nextInt();
        System.out.println("edad = " + edad);
        
        System.out.print("Ingresa tu altura: ");
        var altura = consola.nextDouble();
        System.out.println("altura = " + altura);
        
        consola.nextLine();
        
        System.out.print("Ingresa tu nombre: ");
        var nombre = consola.nextLine();
        System.out.println("nombre = " + nombre);
        
        
    }
}
