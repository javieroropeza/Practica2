using System.IO;

using System;


class Practica2

{
    
	public static void Main()
    
	{
        
            
		double producto1,producto2,producto3,re1,re2,re3;
 
           
            
		Console.WriteLine( "Introduce el precio del producto 1" );
       
     		producto1 = double.Parse(Console.ReadLine());
    
        
           
		Console.WriteLine( "Introduce el precio del producto 2" );
    
        	producto2 = double.Parse(Console.ReadLine());
   
         
            
		Console.WriteLine( "Introduce el precio del producto 3" );
 
  		producto3 = double.Parse(Console.ReadLine());
  
          
            
		re1 = producto1*16/100;
            
		re1 = producto1 + re1;
      
      
           
 		re2 = producto2*16/100;
            
		re2 = producto2 + re2;
             
            

		re3 = producto3*16/100;
            
		re3 = producto3 + re3;
            
            

		Console.WriteLine( "Producto 1= " + re1 );
            
		Console.WriteLine( "Producto 2= " + re2 );
            
		Console.WriteLine( "Producto 3= " + re3 );
            
            

		re1 = re1+re2+re3;
            
		Console.WriteLine("Total " + re1);
            
    
	}

}
