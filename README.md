# House-Search
This is a group work for Data Structure and Algorithm class
The main goal of this project is to create a C++ application that sorts houses based on various criteria such as price, number of bedrooms, and price range. Also, the program uses  SFML/Graphics.hpp library to implement the user interface.  

# Live Demo
https://www.youtube.com/watch?v=z3McFIm7oEE

# Description
  1. Database
 The program effectively stores and manages household data by using a CSV (Comma-Separated Values) database that take from Zillow website.
  2. Sorting Algorithm:
 This project uses both Merge Sort and Quick Sort algorithms. Additionally, the program utilizes a timer function to measure the execution time of each sorting algorithm, enabling a comparison of their efficiency.

    📌 Merge Sort:
    
    Merge Sort is a divide-and-conquer algorithm that recursively divides the array into smaller subarrays, sorts each subarray, and then merges them back together in sorted order.
  
    📌 Quick Sort:
    
    Quick Sort is another efficient sorting algorithm that works by partitioning the array into two subarrays based on a chosen pivot element. It then recursively sorts the subarrays, placing elements less than the pivot to its left and elements greater than the pivot to its right.
  3. Features:
     - Input Criteria: Number of beds (from 1 to 5), State, Price Range
     - Search by City or search by price
     - Sorting from low to high or from high to low
