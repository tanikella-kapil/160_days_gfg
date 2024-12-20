

// User function Template for Java

class Solution {
    // Function to rotate an array by d elements in counter-clockwise direction.
    static void rotateArr(int arr[], int d) {
        int n = arr.length;
        d = d % n;
        if (d < 0) {
            d = n + d;
        }
        int[] result = new int[n];
        for (int i = 0; i < n; i++) {
            result[i] = arr[(i + d) % n];
        }
        for (int i = 0; i < n; i++) {
            arr[i] = result[i];
        }
    }
}
