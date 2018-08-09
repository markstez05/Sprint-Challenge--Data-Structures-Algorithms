Add your answers to the Algorithms exercises here..

A. O(n^3)
B. O(log n)
C. O(n^3)
D.
E. O(n^3)
F. O(n)
G. O(n)

2. a. function maxDiff(arr) {
    let min = arr[0];
    let maxDiff = 0;

    arr.forEach(val => {
        min = Math.min(min, val);
        maxDiff = Math.max(maxDiff, val - min);
    });
    return maxDiff;
}