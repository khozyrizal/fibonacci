fibonacci
=========
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

package javaapplication1;
import java.util.Scanner;
/**
 *
 * @author Asisten
 */
public class JavaApplication1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner scan=new Scanner(System.in);
        int data=scan.nextInt();
        
        int a=0, b=1;
        System.out.println("Hasilnya: ");
        for (int i=0; i<data;i++){
            System.out.println(a+" ");
            a=a+b;
            b=a-b;
            
        }
        
    }
    
}
