SortingAnimation
================

An animation written in Java to demonstrate the time complexity of 6 different sorting algorithms on a list of 10,000 integers. We used 6 different threads to optimize the performance of the animations.

Team: Long Tran, Chuong Trinh

I- Contribution: 
			1. Long Tran: Bubble Sort, Shell Sort, Quick Sort 			
			2. Chuong Trinh: Insert Sort, Merge Sort, Heap Sort 
II - Compiling: Compile the AnimateSorting with javac or any Java IDE.
 
III - Using the program
 * Upon the start of the program, users will be prompted to enter the size of the array to be sorted.
 * Theorically, the size of the array is only limited to the size of the computer memory. However, to limited size of the
 * computer's screen, we found the animations work best on an array with less than 15 items. 
 
V - Implementation: 
 * In this program, we used 6 independent threads for 6 sorting algorithms. Meanwhile, the animations will be done in the
 * main thread using 6 different timers. The timers will also interrupt the sorting threads to pause/resume the thread after
 * each swap.
 
V - Known Bugs
 *	1. The pause/resume buttons have not been implemented.
 *  2. Animation for heap sort has a bug which we could not find upon to the submission of this assignment.

VI- Reference: 
 * 		1. Oracle Java Document.
 * 		2. "Data Structures & Algorithms in Java" - Robert Lafore	
 */


