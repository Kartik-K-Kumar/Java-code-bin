import java.util.Scanner;
class Main{
   public static String names = "Hello";
   
   public static int[][] values = {{1,2,3}, {4,7,4}, {2,3}};
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Whats the entery, A or B?");
        String entry = sc.nextLine().toUpperCase();
        System.out.println(names);
        
        for (int i = 0; i<values.length; i++) {
            for (int J = 0; J<values[i].length; J++) {
                System.out.println(values[i][J]);
            }
        }
        
        //array search list linear only//
        int[] NumberList = {2, 3, 8, 6};
        int target = 3;
        
        
        for (int k = 0; k<NumberList.length; k++) {
            if (NumberList[k] ==  target) {
                System.out.println("Found " + target + " at the index " + k );
            }
        }
        System.out.println("No here!");
        
        System.out.println("Whats your name? ");
        String called = sc.nextLine();
        
        Greet("Shallong");
            
        
        
        
        if(entry.equals("A")){
            System.out.println("You Selected A");
            System.out.println(Danger());
        } else if (entry.equals("B")) {
            System.out.println("You selected B");
            Happy();
        } else {
            System.out.println("Unrecgonised selection");
        }
    }
    
    
    
    public static String Danger() {
        String woah = "UR NAME IS DANGER";
        Scanner sc = new Scanner(System.in);
        System.out.println("Are you a screaner yes or no");
        String SCREAMING = sc.nextLine().toUpperCase();
        
        switch (SCREAMING) {
            case "YES":
                woah = "BRO WHAT SO UR SCREAMING AAAAAA";
                return woah;
            case "NO":
                
                woah = "OH SO UR NOT SCREAMING? " + Screaming();
                return woah;
            default:
                return woah;
        }
            
    }
    
    public static void Greet(String name) {
        System.out.println("Hiii " + name);
    }
    
    public static String Screaming(){
        String poot = "LOL";
        return poot;
    }
    public static void Happy() {
        System.out.println("UR NAME IS NEVER GOING TO BE DANGER");
    } 
    
}
