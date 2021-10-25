using System;
					
public class Program
{
	public static void Main()
	{
		bool Ejecucion = true;
		string [] Productos = {"Arepas", "Azucar", "Pan", "Jamon", "Leche", "Tortillas", "Queso", "Panela", "Chocolate", "Jabon"};
		int [] Precios = {2000,3000,2500,4500,3000,3500,1500,500,5000,6000};;
		int Total = 0;
		int [] CarritoPrecios = new int [0];
		string [] CarritoProductos = new string [0];
		int NProductos = 0;
		uint [] CuentasClientes = {1523648972,1423657890,1243598762,1253686547};
		int [] EstadoDeCuenta = {0,0,0,0};
		int Deuda = 0;
		
		Console.WriteLine(" La tienda de Don Lucho");
		Console.WriteLine();
		Console.WriteLine("opciones");
		Console.WriteLine();
		Console.WriteLine("1. Buscar Producto");
		Console.WriteLine();
		Console.WriteLine("2. Suma Rapida de Productos");
		Console.WriteLine();
		Console.WriteLine("3. Pagar Cuenta");
		Console.WriteLine();
		Console.WriteLine("4. Consultar Cuenta del CLiente");
		Console.WriteLine();
		Console.WriteLine("5. Actualizar Cuenta de Cliente");
		Console.WriteLine();
		Console.WriteLine("6. Calcular Informe de Ventas");
		Console.WriteLine();
		Console.WriteLine("7. Calcular Cartera del Cliente");
		Console.WriteLine();
		Console.WriteLine("8. Salir");

		while(Ejecucion)
		{
			
			switch (int.Parse(Selecion))
			{
				case 1://Buscar Producto
					
					
				break;

				case 2://Suma Rapida de Productos
					
	
				break;
						
				case 3: // Pagar cuenta
					
					
					
				break;

				case 4: // consultar cuenta cliente
					
					
				break;

				case 5: // Actualizar cuenta cliente
					
					
				break;
				case 6:// Informe de ventas
					
					
				break;
				
				case 7:
					
					
					
				break;

				case 8://Salir
					
					
				break;

				default: 
					
				break;
			}
		}
	}
}
