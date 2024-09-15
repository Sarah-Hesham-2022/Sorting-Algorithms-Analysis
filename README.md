# Sorting-Algorithms-Analysis
Understanding of various sorting algorithms by implementing them on randomized data sets, analyzing and comparing the performance of these algorithms based on two key metrics: execution time and memory usage.

# Sorting Algorithms: Performance Analysis

## 📜 Overview
This project is a comprehensive comparison of five widely-used sorting algorithms: **Quick Sort**, **Heap Sort**, **Count Sort**, **Radix Sort**, and **Bucket Sort**. The algorithms are analyzed based on two key metrics: **Execution Time** and **Memory Usage** across a range of dataset sizes, from small arrays to large, computationally demanding datasets.

The implementation was done in Python and includes detailed performance evaluations using graphical visualizations, all generated from real-world, randomized datasets.

## 🧠 Objective
The primary goal of this project is to provide a deep understanding of the efficiency, scalability, and limitations of these algorithms. By comparing their performance, we can identify the optimal sorting algorithm for different types of data and use cases.

## 🔥 Sorting Algorithms Implemented
- **Quick Sort**: A divide-and-conquer algorithm known for its average-case \(O(n \log n)\) efficiency.
- **Heap Sort**: A comparison-based sorting algorithm using a binary heap data structure with \(O(n \log n)\) time complexity.
- **Count Sort**: A non-comparison integer sorting algorithm that operates with linear time \(O(n+k)\), where \(k\) is the range of the input data.
- **Radix Sort**: A non-comparative integer sorting algorithm that sorts digit by digit with \(O(nk)\) complexity.
- **Bucket Sort**: A distribution-based sorting algorithm that works by dividing elements into buckets and sorting each bucket individually, performing best with uniformly distributed data.

## 📊 Performance Metrics
The algorithms are evaluated based on the following criteria:
- **Execution Time** (in seconds): Measures the time taken to sort the datasets.
- **Memory Usage** (in MB): Tracks the memory consumed during the execution of each algorithm.

## ⚙️ Methodology
1. **Data Generation**: Random datasets were generated with increasing sizes (from 10,000 to 300,000 elements).
2. **Execution Time Measurement**: The `time.perf_counter` function was used to measure the precise execution time of each algorithm.
3. **Memory Profiling**: The `memory_profiler` module was used to measure memory consumption during execution.
4. **Visualization**: Results are visualized using `Matplotlib` in three different plots:
   - Average Execution Time for all algorithms.
   - Memory Usage for all algorithms.
   - Combined Performance Analysis with Execution Time and Memory Usage on a single graph.

## 📈 Results
- **Quick Sort**: Showed efficient performance with logarithmic growth in execution time but exhibited higher memory usage due to recursion.
- **Heap Sort**: Consistently slower than Quick Sort, though predictable, with higher execution times across larger datasets.
- **Count Sort**: Demonstrated constant-time performance, making it the fastest for integer sorting, with minimal memory usage.
- **Radix Sort**: Scaled well with dataset size, offering stable performance.
- **Bucket Sort**: Excelled with uniformly distributed data but showed variability with non-uniform data.

For more detailed insights, you can check out the performance plots and data in the repository.

## 🖼️ Visualizations
### Average Execution Time Plot
![Execution Time](https://github.com/user-attachments/assets/d5736d4d-a4ca-4be1-9aae-466c5710dc22)

### Memory Usage Plot
![Memory Usage](https://github.com/user-attachments/assets/126dec6c-053b-4d7b-8bb7-099649db6184)

### Combined Performance Analysis
![Performance Analysis](https://github.com/user-attachments/assets/f0ce89d1-9e70-4b0f-be2f-21a334b50bbf)


## 📚 Documentation
- **[Detailed Report](./Report.pdf)**: In-depth analysis of the performance metrics, methodology, and conclusions.

- **Data Tables**: 

![Execution Time Table](https://github.com/user-attachments/assets/3c121a56-8320-43d5-a298-e445feb7152e)

![Memory Usage Table](https://github.com/user-attachments/assets/e514cdaa-8f05-4b1e-afd6-5964120635f8)


