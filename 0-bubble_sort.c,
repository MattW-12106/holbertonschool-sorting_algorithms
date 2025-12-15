#include "sort.h"

/**
 * bubble_sort - sorts elements of array using bubble sort
 * @array: pointer to array
 * @size: size of array
 */

void bubble_sort(int *array, size_t size)
{
	size_t i, j;
	int temp;
	int swapped = 0;

	if (array == NULL || size < 2)
		return;

	for (i = 0; i < size - 1; i++)
	{
		for (j = 0; j < size - i - 1; j++)
		{
			if (array[j] > array[j + 1])
			{
				temp = array[j];
				array[j] = array[j + 1];
				array[j + 1] = temp;
				swapped = 1;
				print_array(array, size);
			}
		}
		if (!swapped)
			break;
	}
}
