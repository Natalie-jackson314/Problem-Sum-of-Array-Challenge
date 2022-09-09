# Problem-Sum-of-Array-Challenge
Solution for Problem: Sum of Array

public class SumOfArray {

    public static void main(String[] args) {
        int[] array1 = {1, 2, 3, 4, 5};
        //index numbers 0  1  2  3  4

        int sum = 0;

        for (int j : array1) {
            sum = sum + j;
        }
        System.out.println("Sum of all the elements of an array: " + sum);
            }
        }
