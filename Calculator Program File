public class BasicCalculator {

    public BasicCalculator() {} // constructor

    public int addition(int a, int b){ // addition calclulation
        return a+ b;
    }

    public int subtract(int a, int b){ // subtraction calculation
        return a - b;
    }

    public int multiply(int a, int b){ // multiplication calculation
        return a * b;
    }

    public float divide(int a, int b){ // division calculation
        if(b == 0){
            System.out.println("Error: You cannot divide by 0"); // clarifies that you cannot divide by 0 and will give a error message when some one trys
            return 0;
        } else{
            float c= ((float) a / b);
            return c;
        }
    }

    public static void main(String[] args){

        BasicCalculator myCalculator= new BasicCalculator();

        StdOut.print("Enter the first number for your computation: ");

        int a = Integer.parseInt(StdIn.readLine());

        StdOut.println();

        StdOut.print("Enter the second number for your computation: ");

        int b = Integer.parseInt(StdIn.readLine());

        StdOut.println();

        String[] computations = {"addition", "subtraction", "multiplication", "division"};

        StdOut.println("What computation would you like to make?");
        for(int i=0; i < 4; i++){ // iterates through the different computation possiblilities
            StdOut.printf("%d. %s\n", i+1, computations[i]); // displays all the different possibilities
        }

        StdOut.println();

        StdOut.print("Enter the number corresponding to your choice here: ");
        Integer option= StdIn.readInt();

        StdOut.println();

        if(option == 1){
            StdOut.println("Your answer is: " + (myCalculator.addition(a, b)));
        }

        if(option == 2){
            StdOut.println("Your answer is: " + (myCalculator.subtract(a, b)));
        }

        if(option == 3){
            StdOut.println("Your answer is: " + (myCalculator.multiply(a, b)));
        }

        if(option == 4){
                    StdOut.println("Your answer is: " + (myCalculator.divide(a, b)));
                }
    }
}
