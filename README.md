Java Streams – Sample Input Data (Question‑wise)

🔹 Level 1: Basics (Warm‑up)
1. Convert a List<String> to List<Integer> (length of each string)

List<String> words = List.of("Java", "Spring", "Boot", "Microservices");

2. Filter even numbers from a list

List<Integer> numbers = List.of(12, 7, 9, 20, 33, 40, 55);

3. Count elements greater than 50

List<Integer> marks = List.of(45, 60, 30, 90, 75, 20, 100);

4. Convert all strings to uppercase

List<String> technologies = List.of("java", "spring", "docker", "kubernetes");

5. Find the first element greater than 10

List<Integer> values = List.of(3, 5, 8, 12, 15, 20);

🔹 Level 2: Intermediate (Most asked)
6. Find sum of all numbers

List<Integer> expenses = List.of(100, 200, 300, 400);

7. Remove duplicates from list of strings

List<String> languages = List.of("Java", "Python", "Java", "C", "Python", "Go");

8. Find maximum and minimum number

List<Integer> primeNumbers = List.of(2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 13);

9. Sort integers (asc & desc)

List<Integer> unsortedNumbers = List.of(45, 12, 89, 23, 7, 90, 34);

10. Skip first 2 and limit next 3 elements

List<Integer> sequence = List.of(10, 20, 30, 40, 50, 60, 70);

🔹 Level 3: map() vs flatMap()
11. Convert List<List<Integer>> into single list

List<List<Integer>> nestedList = List.of( List.of(1, 2, 3), List.of(4, 5), List.of(6, 7, 8) );

12. Extract all unique words from sentences

List<String> sentences = List.of( "java is powerful", "streams are powerful", "java streams simplify code" );

13. Convert List<String> to flattened List<Character>

List<String> names = List.of("Ram", "Sam", "Tom");

🔹 Level 4: Matching & Finding
14. Check if any number divisible by 5

List<Integer> checkNumbers = List.of(11, 22, 33, 40, 55);

15. Check if all numbers are positive

List<Integer> positives = List.of(5, 10, 20, 30);

16. Check if none of the numbers are negative

List<Integer> nonNegative = List.of(0, 4, 6, 9, 12);

17. Find any element greater than 100

List<Integer> bigNumbers = List.of(10, 20, 50, 150, 200);

🔹 Level 5: Reduce (Very Important)
18. Product of all numbers

List<Integer> multiplyNumbers = List.of(1, 2, 3, 4, 5);

19. Maximum number using reduce()

List<Integer> salaryFigures = List.of(45000, 60000, 75000, 90000);

20. Concatenate list of strings

List<String> alphabets = List.of("J", "A", "V", "A");

🔹 Level 6: Collectors
21. Convert list of strings to Set

List<String> cities = List.of("Hyderabad", "Bangalore", "Hyderabad", "Chennai");

22. Group numbers by even and odd

List<Integer> evenOddNumbers = List.of(1, 2, 3, 4, 5, 6, 7, 8);

Employee data (used for multiple questions)

class Employee { int id; String name; String dept; double salary; Employee(int id, String name, String dept, double salary) { this.id = id; this.name = name; this.dept = dept; this.salary = salary; } }

List<Employee> employees = List.of( new Employee(1, "Kumar", "IT", 75000), new Employee(2, "Ravi", "HR", 45000), new Employee(3, "Anita", "IT", 90000), new Employee(4, "John", "Finance", 80000), new Employee(5, "Priya", "HR", 60000), new Employee(6, "David", "Finance", 120000) );

🔹 Level 8: String‑based Problems
31.Frequency of each character

String input = "java streams";

32. First non‑repeating character

String value = "swiss";

33. Count number of words

String sentence = "Java streams simplify data processing";

34. Find duplicate characters

String duplicateInput = "programming";

🔹 Level 9: Tricky / Advanced
35. Second highest number

List<Integer> scores = List.of(10, 20, 30, 40, 50);

36. Longest string

List<String> frameworks = List.of("Spring", "Hibernate", "Microservices", "JPA");

37. Partition prime & non‑prime

List<Integer> numbersForPrimeCheck = List.of(2, 3, 4, 5, 6, 7, 8, 9, 10, 11);

38. Convert stream to Map

List<String> countryCodes = List.of("IN", "US", "UK");

39. Handle empty stream safely

List<Integer> emptyList = List.of();

40. Use peek() to debug

List<Integer> debugNumbers = List.of(10, 15, 20, 25, 30);
