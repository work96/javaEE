# javaEE
my first github repository
public class Test {

    public static void main(String[] args) {
        int[] arr1 = {1, 2, 3};
        int a = 1, b = 2;
        change(arr1);
        change(a, b);
        System.out.println(arr1[0]);
        System.out.println(a);
        System.out.println(b);
    }

    public static void change(int[] arr) {
        arr[0] = 10;
    }

    public static void change(int a, int b) {
        a = 10;
        b = 10;
    }
}
