# Finding-prime-numbers-from-1-to-1000-with-Java

public class find_prime_number {


    public static boolean primenumber(int number){


        for (int i = 2; i < number; i++){

            if (number % i == 0){
                return false;
            }
        }
        return true;
    }

    public static void main(String[] args) {


        for (int i = 2; i < 1000; i++){

            if (primenumber(i)){

                System.out.println(i);
            }
        }
    }




}

