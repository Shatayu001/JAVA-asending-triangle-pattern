\\JAVA asending triangle pattern

public class Main {
    public static void main(String[] args) {
        int i,j,k,n = 20; 

        for (i = n; i >= 1; i--) {
            for (j = 1; j <= n - i; j++) {
                System.out.printf(" ");
            }
            for (k = 1; k <= i; k++) {
                System.out.printf("*");
            }
            System.out.println("");
        }
    }
}
