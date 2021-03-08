# Tarea
segunda actividad
/*
 * Created by SharpDevelop.
 * User: M
 * Date: 03/03/2021
 * Time: 09:22 a.m.
 * 
 * To change this template use Tools | Options | Coding | Edit Standard Headers.
 */
using System;

namespace Nuevo
{
	class Program
	{
		public static void Main(string[] args)
		{
			           string Datos ="";
            int edad = 0;
            double altura = 0.0;

            
            Console.WriteLine("Bienvenido, por favor ingresa tu edad:");
            Datos = Console.ReadLine();
            edad = Convert.ToInt32(Datos);

            
            if (edad>=25)
            {
                Console.WriteLine("Disculpe debido a su edad no puede ingresar al parque");
            }
            else
            {
                
                
                Console.WriteLine("Hola, Me indicas tu estatura");
                Datos = Console.ReadLine();
                altura = Convert.ToDouble(Datos);

                
                if(altura < 1.6)
                {
                Console.WriteLine("Solo puedes subir a Carros chocones, el gusanito y los columpios voladores");
                }
                else
                {
                    
                Console.WriteLine("Puedes acceder a todas las atracciones del parque");
                }
                
                //
            }
            
            
            
            
            Console.ReadKey();
        
        }
    }

		}
