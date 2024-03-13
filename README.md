Muhammad Yusuf Haikal </br>
NPM 2206081490 </br>
https://eshop-ternaksapi.koyeb.app/<br>

# Refleksi Tutorial 6

## Reflection 1

### What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
With JMeter, the performance testing is used to measure how the application perform under a number of scenarios, such as high traffic loads or concurrent user interactions. Meanwhile, profiling tools such as the Intellij Profiler is used to measure and analyze the behaviour of an application, such as identifying bottlencks, memory leaks, and performance issues.

## Reflection 2

### How does the profiling process help you in identifying and understanding the weak points in your application?
By using Intellij's Profiling, we can see the resource allocations from the flame graph, how much does each method inside the application uses the resource and from there, you can identify where the weak points are and how you can improve the performance by making changes to those weak points.

## Reflection 3

### Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
Definitely, the Intellij Profiler makes it easy to spot where the bottlenecks are just by looking and analyzing which part can improvements can be done.

## Reflection 4

### What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
Personally, I found understanding and interpreting what each measurements that resulted from the performance and profiling testing can be quite hard to understand. To help with this, doing a lot of googling and trying to read guides on how to read and analyze the measurements help quite a bit.

## Reflection 5

### What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
The first thing that i think is quite a big benefit of using Intellij's Profiler is how efficient and easy to use the tool is, since the tool is build within the IDE, you don't need to install other extension to run the profiler. Other than that, the profiler has some very intuitive tools that makes it easier to analyze the bottlenecks and issues within the application.

## Reflection 6

### How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
Looking at where the inconsistency happens, then trying to make changes to the part where the inconsistency occur and seeing which of the two does the changes affect the result. From there, we can conclude which of the testing is wrong.


## Reflection 7

### What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
Since optimization is mostly about how to reduce the program complexity, I try to see where there are excess use of resources from the testing and profiling result. From there, we can do modification towards the part where the excess use of resource happens, either by reducing the complexity of the code if for example there are too many unnecessary loops happening inside the code or by changing the data structure to a more memory and process efficient data structure, while at the same time making the functionality doesn't change.

## Documentation

### `/all-student-name` endpoint Performance Test, from GUI
![82130dfd-c054-4a6b-9059-6fdc7b255c86](https://github.com/ternaksapi/exercise-profiling/assets/116947973/f2644ea0-d3bf-4cca-95b4-80be08968ced)

### `/highest-gpa` endpoint Performance Test, from GUI
![2c6ee03d-e559-431f-876a-e4ede185777c](https://github.com/ternaksapi/exercise-profiling/assets/116947973/973964f0-4e24-4dbe-802f-e817cd549d8e)

### `/all-student-name` endpoint Performance Test, from CLI
![23cbef8a-9ea5-40e5-9b84-279357699483](https://github.com/ternaksapi/exercise-profiling/assets/116947973/7ff9e35c-3b67-4636-95eb-744cedb62d0e)

### `/highest-gpa` endpoint Performance Test, from CLI
![40683526-06fa-4c95-90ca-8c7246d7bbdc](https://github.com/ternaksapi/exercise-profiling/assets/116947973/cf6e10d8-6aea-48a5-ab04-d386ea72b778)

### `/all-student-name` endpoint Performance Test, from GUI after refactorization.
![2e0cca8c-6da3-49ce-bcad-eb11833dd435](https://github.com/ternaksapi/exercise-profiling/assets/116947973/6493a04b-fb5f-496f-bd03-9e64418afc0b)
This results show a huge gap in Sample Time compared to the previous one, more then tenth of the sample time before refactorization is done.
