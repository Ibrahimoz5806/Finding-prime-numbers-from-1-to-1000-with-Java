# Finding-prime-numbers-from-1-to-1000-with-Java

public class find_prime_number {


    public static boolean primenumber(int sayi){


        for (int i = 2; i < sayi; i++){

            if (sayi % i == 0){
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



