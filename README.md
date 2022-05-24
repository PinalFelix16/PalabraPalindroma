# PalabraPalindroma
Verificar si la palabra ingresada es palíndroma

import java.util.Scanner;
public class pruebaasd
{
    public static void main(String arg[])
    {
        // initialise instance variables
        Scanner A=new Scanner (System.in);
        String pal=" ",totp=" ",acump=" ";acump=" ";
        int in=0,pal1=0,pal2=0;
        int des= pal.length()-1;
        
        for (int x=1;x<=5;x++){
        System.out.println("dame una palbra "+ x);
        pal=A.nextLine();
        while ((in<des) && (true)){
        if (pal.equals(des)){
            System.out.println("la palabra no es palindroma");
            pal1++;
            
        } else{
        System.out.println("la palabra es palindroma");
        pal2++;
        
        }
        }
            acump=acump+pal+" ";
            
    }
    
    System.out.println("las palabras fueron" + acump);
    System.out.println("la palabra no es palindroma"+pal1);
    System.out.println("la palabra es palindroma"+pal2);
    
    }
}
