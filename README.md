# average
public class start {
    public static void main(String[] args) {
        System.out.println("Enter an int value, the program exits if the input is 0");
        Scanner input = new Scanner (System.in);
        int h = 0;
        while (input.nextInt() == 0){
            int inp = input.nextInt();
            int j = inp;
            int i = 0;
            h = j + i;
            break;
        }

        System.out.println("The total is: "+ h);
    }
}
