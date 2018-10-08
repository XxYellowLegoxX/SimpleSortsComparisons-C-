//Here is the code for the exchange sort
void exchangeSort(int a[], int s) {
	for (int k = 1; k < s; k++) {
		for (int i = 0; i < s - k; i++) {
			if (!compareElements(a, i, i + 1)) {
				swapElement(a, i, i + 1);
			}
		}
	}
}
//Here is the code for the insertion sort and its overload
//void insertionSort(int a[], int s) {
//	insertionSort(a, 0, s - 1);
//}
//void insertionSort(int a[], int i, int j){
//	
//}
//Here is the code for the selection sort
void selectionSort(int a[], int s) {
	int temp = 0;
	for (int i = 0; i < s; i++)
	{
		for (int j = i + 1; j < s; j++)
		{
			if (a[i] > a[j])
			{
				swapElement(a, i, j);
			}
		}
	}
}
