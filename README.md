## Sama school
in todays world all of us for such skills like reading , writing  and an important ability like math attend a place called "school" here there are small school that its name is sama . sama is a small school with several options that you can control it 


At sama school we have the professional techers who taught specific courses in different classrooms to our students . by the way truth is you are our manager after a bad accident you forget all of your responsibilities you can hire your choice in any position 

you also forget averyone in sama school my suggestion for you is ```print```  you can see your teachers name family grade and other information about them and students too 
see former courses and classrooms with their own options like unit it is what it is

if you want to add a new course you must hire a specific teacher who can teach that course in this school maneger can add new student or kick them he also can do this for teacher and he can add and delete course too before do this do some research about them

- ### for a former manager who has recently developed Alzheimer

- ## course


| property | deccribtion |
| --- | --- |
| id | unique identifier for each course, e.g.1001
|name | course name, e.g. "ali"
| unit | number of course units/credits, e.g. 3

- ## student


| property | deccribtion |
| --- | --- |
| id | unique identifier for each student, e.g.2001 |
|name | student's first name e.g. "reza |
| family | student's last name e.g. "ahmadi" |
|courses | list of courses |

- ## teacher


| property | deccribtion |
| --- | --- |
| id | unique identifier for each teacher, e.g.3001 |
|name | teacher's first name |
| family | teacher's last name |
| grade | teacher's grade/rank e.g. "HTP"
|courses | list of courses |

- ## classroom


| property | deccribtion |
| --- | --- |
| id | unique identifier for each classroom, e.g.4001 |
|name | classroom's name |
|courses | list of courses |
|students | list of students |
|teachers | list of teachers |

- ## school


| property | deccribtion |
| --- | --- |
|name | school's name |
|courses | list of courses |
|students | list of students |
|teachers | list of teachers |
|classrooms | list of classrooms |

# How it works

When you run the program, a main menu is printed to the console. The user picks an option by typing a number and pressing Enter

```
1.student
2.teacher   
3.courses   
4.classrooms
5.save      
0.exit      
```

| option | action |
| --- | --- |
|1 | open students menu |
|2 | open teachers menu |
|3 | open courses menu |
|4 | open classrooms menu |
|5 | save |
|0 | go back / exit |

Pressing 0 anywhere takes you back to the previous menu

Example: User presses 1 (Students)

The Students submenu is printed with the following options

```
1.print students
2.add student   
3.edit student  
4.delete student
5.select student
0.back
```
| option | action |
| --- | --- |
|1 | show info __ print students |
|2 | Add Student — create a new student record |
|3 | Edit Student — modify an existing student |
|4 | Delete Student — remove a student |
|5 | Select Student — view/search student details |
|0 | Back — return to the main menu |

- The program is fully menu-driven — no command-line arguments needed; just run it and follow the prompts.
- very submenu (Teachers, Courses, Classrooms) follows the same 1–4 pattern: Add → Edit → Delete → Select, with 5 as Back
- Input is read line-by-line from stdin, so the user just types a number and hits Enter.
- nvalid input is expected to be handled gracefully (re-print the menu or show an error) — otherwise the program might crash like a drama queen.
- Option 5 on the main menu saves everything (e.g., to a file or database) so your data doesn't vanish into the void when the program closes
- The design is intentionally simple: a loop prints the menu, reads a choice, dispatches to the right function, and repeats until the user exits



