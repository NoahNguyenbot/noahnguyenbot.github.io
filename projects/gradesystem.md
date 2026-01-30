---
layout: project
type: project
image: img/grades/grade.webp
title: "Grade Average"
date: 2024
published: true
labels:
  - Java
summary: "Grade calculator that takes average of all courses taken"
---


The purpose of this project is to allow students to enter their grades for up to six classes and calculate the average of all their grades. It begins with a menu where you can choose three options by entering a number from 1 to 3. The first option is to add a student. The second option is to view all students. The third option is to exit.

If the user enters 1, the program will start by asking for the student’s name. Then it will ask how many courses they are taking, for which they can enter a number from 1 to 6. It will then prompt the user for both the course names and the grades received. Once all courses and grades have been entered, the program will display the average grade across all courses taken. The program allows you to add as many students as you want.

This project was created very early in my programming journey, so it helped reinforce many basic Java concepts such as using ArrayLists to store custom course names, constructors to initialize new student objects, exception handling when users enter invalid input, and writing robust input-handling logic.

    Here is a code snippet when you user enters 1 to add a new student:
{% highlight java %}
  if (choice == 1) {
    System.out.print("\nEnter student name: ");
    scanner.nextLine(); 
    String name = scanner.nextLine().trim();

    int numCourses = getValidInt(scanner, 1, 6,
            "\nHow many courses for this student? (1–6): ");

    String[] courseNames = new String[numCourses];
    double[] scores = new double[numCourses];

    System.out.println("Enter course names and scores:");
    for (int i = 0; i < numCourses; i++) {
        System.out.print("Course " + (i + 1) + " name: ");
        courseNames[i] = scanner.nextLine().trim();

        
        System.out.print(courseNames[i] + " score (0–100): ");
        scores[i] = getValidDouble(scanner, 0, 100);
    }

    students.add(new Student(name, courseNames, scores));
    System.out.println("Student added successfully!\n");
    {% endhighlight %}





