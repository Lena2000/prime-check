# prime-check
Проверка простое или составное ли введено число
package проверка.простое.число;

import java.util.Scanner;

/**
 *
 * @author LENOVO
 */
public class ПроверкаПростоеЧисло {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Vvedite chislo: ");
        int i=sc.nextInt();
        boolean f=true;

        for(int n=i-1; n>1; n--){
           if (i%n==0){ 
           f=false;
               break;
               
               }
        }
        if (f) System.out.println("prostoe");
           else{
               System.out.println("neprostoe chislo");   
           }
           }
        }
         
    
    

