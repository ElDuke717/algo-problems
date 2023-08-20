## Algorithms

### Sorting

#### Bubble Sort

Here's an example of the Bubble Sort algorithm implemented in JavaScript:

```javascript
function bubbleSort(arr) {
	const n = arr.length;

	for (let i = 0; i < n - 1; i++) {
		for (let j = 0; j < n - i - 1; j++) {
			if (arr[j] > arr[j + 1]) {
				// Swap elements if they are in the wrong order
				[arr[j], arr[j + 1]] = [arr[j + 1], arr[j]];
			}
		}
	}
}

const unsortedArray = [64, 34, 25, 12, 22, 11, 90];
console.log('Unsorted array:', unsortedArray);

bubbleSort(unsortedArray);

console.log('Sorted array:', unsortedArray);
```

In this example, the `bubbleSort` function takes an array as an input and sorts it using the Bubble Sort algorithm. The algorithm works by repeatedly stepping through the list of elements to be sorted, comparing each pair of adjacent items and swapping them if they are in the wrong order. This process is repeated for each element until the entire array is sorted.

The `unsortedArray` contains the elements to be sorted. After applying the `bubbleSort` function, you'll see the sorted array in the console output.

Please note that Bubble Sort is not very efficient, especially for large arrays, as it has a worst-case time complexity of O(n^2). There are more efficient sorting algorithms available, such as Quick Sort, Merge Sort, and Heap Sort.

#### Selection Sort

#### Insertion Sort

#### Merge Sort

#### Quick Sort

#### Heap Sort

### Searching

#### Linear Search

#### Binary Search
