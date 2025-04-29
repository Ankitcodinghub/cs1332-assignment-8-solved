# cs1332-assignment-8-solved
**TO GET THIS SOLUTION VISIT:** [CS1332 Assignment 8 Solved](https://www.ankitcodinghub.com/product/cs1332-important-solved-8/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109381&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1332 Assignment 8 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. All submitted code must compile under JDK 8. This includes unused code, so don’t submit extra files that don’t compile. Any compile errors will result in a 0.

2. Do not include any package declarations in your classes.

3. Do not change any existing class headers, constructors, instance/global variables, or method signatures. For example, do not add throws to the method headers since they are not necessary.

4. Do not add additional public methods.

5. Do not use anything that would trivialize the assignment. (e.g. don’t import/use java.util.ArrayList for an ArrayList assignment. Ask if you are unsure.)

6. Always be very conscious of efficiency. Even if your method is to be O(n), traversing the structure multiple times is considered inefficient unless that is absolutely required (and that case is extremely rare).

7. You must submit your source code, the .java files, not the compiled .class files.

8. Only the last submission will be graded. Make sure your last submission has all required files. Resubmitting will void all previous submissions.

9. After you submit your files, redownload them and run them to make sure they are what you intended to submit. You are responsible if you submit the wrong files.

Sorting

For this assignment you will be coding 6 different sorts: selection sort, insertion sort, cocktail shaker sort, merge sort, quick sort, and LSD radix sort. In addition to the requirements for each sort, to test for efficiency, we will be looking at the number of comparisons made between elements while grading.

Your implementations must match what was taught in lecture and recitation to receive credit. Implementing a different sort or a different implementation for a sort will receive no credit even if it passes comparison checks.

Comparator

Each method (except radix sort) will take in a Comparator and use it to compare the elements of the array in various algorithms described below and in the sorting file. You must use this Comparator as the number of comparisons performed with it will be used when testing your assignment. See the Java API for details about how the Comparator works and the meaning of the returned value.

Generic Methods

Most of the assignments for this class so far have utilized generics by incorporating them into the class declaration. However, the rest of the assignments will have you implement various algorithms as static methods in a utility class. Thus, the generics from here on will use generic methods instead of generic classes (hence the &lt;T&gt; in each of the method headers and javadocs). This also means any helper methods you create will also need to be static with the same &lt;T&gt; in the method header.

In-Place Sorts

Some of the sorts below are in-place sorts. This means that the items in the array passed in should not get copied over to another data structure. Note that you can still create variables that hold only one item; you cannot create another data structure such as an array or list in the method.

Stable Sorts

Some of the sorts below are stable sorts. This means that duplicates must remain in the same relative positions after sorting as they were before sorting.

Adaptive Sorts

Some of the sorts below are adaptive sorts. This means that the algorithm takes advantage of existing order in the input array.

Selection Sort

Selection sort should be in-place, unstable, and adaptive. It should have a worst case running time of O(n2) and a best case running time of O(n2). You can implement either the minimum version or the maximum version; both are acceptable since they will both yield the same number of comparisons.

Insertion Sort

Insertion sort should be in-place, stable, and adaptive. It should have a worst case running time of O(n2) and a best case running time of O(n).

Note that, for this implementation, you should sort from the beginning of the array. This means that after the first pass, indices 0 and 1 should be relatively sorted. After the second pass, indices 0-2 should be relatively sorted. After the third pass, indices 0-3 should be relatively sorted, and so on.

Cocktail Sort

Cocktail sort should be in-place, stable, and adaptive. It should have a worst case running time of O(n2) and a best case running time of O(n). Note: Implement cocktail sort with the optimization where it utilizes the last swapped index. Remembering where you last swapped will enable some optimization for cocktail sort. For example, traversing the array from smaller indices to larger indices, if you remember the index of your last swap, you know after that index, there are only the largest elements in order. Therefore, on the next traversal down the array, you start at the last swapped index, and on the next traversal up the array, you stop at the last swapped index. Make sure that both on the way up and on the way down, you only look at the indices that you do not know are sorted. Do not make extra comparisons.

Example of one pass of cocktail sort with last swapped optimization: Start of cocktail sort:

1 2 6 5 3 4 7 8 9

Start going up the array:

Compare 1 (at index 0) with 2 (at index 1) and don’t swap

1 2 6 5 3 4 7 8 9

Compare 2 (at index 1) with 6 (at index 2) and don’t swap

1 2 6 5 3 4 7 8 9

Compare 6 (at index 2) with 5 (at index 3) and swap

1 2 5 6 3 4 7 8 9

Compare 6 (at index 3) with 3 (at index 4) and swap

1 2 5 3 6 4 7 8 9

Compare 6 (at index 4) with 4 (at index 5) and swap

1 2 5 3 4 6 7 8 9

Compare 6 (at index 5) with 7 (at index 6) and don’t swap

1 2 5 3 4 6 7 8 9

Compare 7 (at index 6) with 8 (at index 7) and don’t swap

1 2 5 3 4 6 7 8 9

Compare 8 (at index 7) with 9 (at index 8) and don’t swap

1 2 5 3 4 6 7 8 9

Start going down the array:

Note: Skip over indices 5 – 8 since no swaps occurred there.

Compare 4 (at index 4) with 3 (at index 3) and don’t swap

1 2 5 3 4 6 7 8 9

Compare 3 (at index 3) with 5 (at index 2) and swap

1 2 3 5 4 6 7 8 9

Compare 3 (at index 2) with 2 (at index 1) and don’t swap

1 2 3 5 4 6 7 8 9

Compare 2 (at index 1) with 1 (at index 0) and don’t swap

1 2 3 5 4 6 7 8 9

Finished one pass of cocktail sort.

Note: Next time going up, skip over indices 0 – 2 since no swaps occurred there.

Merge Sort

Merge sort should be out-of-place, stable, and not adaptive. It should have a worst case running time of O(nlogn) and a best case running time of O(nlogn). When splitting an odd size array, the extra data should go on the right.

Quick Sort

Quick sort should be inplace, unstable, and not adaptive. It should have a worst case running time of O(n2) and a best case running time of O(nlogn). Your implementation must be randomized as specified in the method’s interface.

LSD Radix Sort

LSD Radix sort should be out-of-place, stable, and not adaptive. It should have a worst case running time of O(kn) and a best case running time of O(kn), where k is the number of digits in the longest number. You will be implementing the least significant digit version of the sort. You will be sorting ints. Note that you CANNOT change the ints into Strings at any point in the sort for this exercise. The sort must be done in base 10. Also, as per the forbidden statements section, you cannot use anything from the Math class besides Math.abs(). However, be wary of handling overflow if you use Math.abs()!

Grading

Here is the grading breakdown for the assignment. There are various deductions not listed that are incurred when breaking the rules listed in this PDF, and in other various circumstances.

Methods:

selectionSort 10pts

insertionSort 10pts

cocktailSort 10pts

mergeSort 15pts

quickSort 15pts

lsdRadixSort 15pts

Other:

Checkstyle 10pts

Efficiency 15pts

Total: 100pts

JUnits

If you need help on running JUnits, there is a guide, available on Canvas under Files, to help you run JUnits on the command line or in IntelliJ.

Style and Formatting

Javadocs

Vulgar/Obscene Language

Any submission that contains profanity, vulgar, or obscene language will receive an automatic zero on the assignment. This policy applies not only to comments/javadocs, but also things like variable names. Exceptions

When throwing exceptions, you must include a message by passing in a String as a parameter. The message must be useful and tell the user what went wrong. “Error”, “BAD THING HAPPENED”, and “fail” are not good messages. The name of the exception itself is not a good message. For example:

Bad: throw new IndexOutOfBoundsException(‘‘Index is out of bounds.’’);

Good: throw new IllegalArgumentException(‘‘Cannot insert null data into data structure.’’);

Generics

If available, use the generic type of the class; do not use the raw type of the class. For example, use new LinkedList&lt;Integer&gt;() instead of new LinkedList(). Using the raw type of the class will result in a penalty.

Forbidden Statements

• package

• System.arraycopy()

• clone()

• assert()

• Arrays class • Array class

• Thread class

• Collections class

• Collection.toArray()

• Reflection APIs

• Inner or nested classes

• Lambda Expressions

• Method References (using the :: operator to obtain a reference to a method)

• Anything besides Math.abs() in the Math class (for this homework only)

• String class (for this homework only)

If you’re not sure on whether you can use something, and it’s not mentioned here or anywhere else in the homework files, just ask.

Debug print statements are fine, but nothing should be printed when we run your code. We expect clean runs – printing to the console when we’re grading will result in a penalty. If you submit these, we will take off points.

Provided

The following file(s) have been provided to you. There are several, but we’ve noted the ones to edit.

1. Sorting.java

This is the class in which you will implement the different sorting algorithms. Feel free to add private helper methods but do not add any new public methods, inner/nested classes, instance variables, or static variables.

2. SortingStudentTests.java

This is the test class that contains a set of tests covering the basic algorithms in the Sorting class. It is not intended to be exhaustive and does not guarantee any type of grade. Write your own tests to ensure you cover all edge cases.

Deliverables

You must submit all of the following file(s). Make sure all file(s) listed below are in each submission, as only the last submission will be graded. Make sure the filename(s) matches the filename(s) below, and that only the following file(s) are present. The only exception is that Canvas will automatically append a -n depending on the submission number to the file name(s). This is expected and will be handled by the TAs when grading as long as the file name(s) before this add-on matches what is shown below. If you resubmit, be sure only one copy of each file is present in the submission. If there are multiple files, do not zip up the files before submitting; submit them all as separate files.

Once submitted, double check that it has uploaded properly on Canvas. To do this, download your uploaded file(s) to a new folder, copy over the support file(s), recompile, and run. It is your sole responsibility to re-test your submission and discover editing oddities, upload issues, etc.

1. Sorting.java
