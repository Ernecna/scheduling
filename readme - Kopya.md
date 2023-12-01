## Courses.csv

1. The teachers of the courses are determined.
2. Their classes and when they will be are unknown.
3. Courses in the same year cannot overlap.

## Classroom.csv

1. Classes have a certain capacity, so courses can enter this class.
2. Each day has a morning and an evening, so a class can be used twice in one day. Since it is a total of 5 days per week, it can be used 10 times in total.

## Busy.csv

1. Some teachers are not available at some times, it should be adjusted accordingly.

## Service.csv

1. There are some courses available as service assigned to departments and their days are predetermined. For this reason, it is obligatory to assign those courses to that time.

---

1. All these constraints should be taken from a file. Namely from CSV files.
2. When the latest algorithms are installed, the program should be viewable on the web page.
3. There should be no intersections between courses from the same department.
4. If a possible schedule cannot be set for a course, it should print an error message as **There is no way to make a schedule for the department.**.
5. Afterwards, the user may be suggested to increase the number of classrooms via the GUI for a successful curriculum.

---

## Conditions
1. Courses in the same year should not be intersected with each other.
2. There are some service courses. The time slot of these courses is fixed and predefined. Therefore, you cannot assign different time slots for those courses other than the requested time slot. 

3. Some instructors may not be available for some time slots. Thus, your program should respect these busy time slots for the respective courses.
4. In this schedule, there should not be any intersection between courses for a year of the curriculum and respect all constraints.
5. If your program cannot find any possible schedule it will print an error message “There is no way to make a schedule for the department.”
6. You may suggest the user to increasing the number of classrooms via GUI, to find a course schedule successfully.
