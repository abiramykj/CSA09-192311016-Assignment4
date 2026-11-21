# Programming in Java - Assignment 4 (CO4)

**Student Name:** Abiramy K J  
**Register Number:** 192311016  
**Course:** CSA09 - Programming in Java  
**Course Outcome:** CO4 - Event-Driven GUI Design

## Java Version

```text
Java 26
javac 26.0.2.1
```

## Repository Structure

| Task | Requirement | Result |
|---|---|---|
| Task01 | Fee-window diagnosis and separation of UI/service logic | Diagnoses defects, defines `FeeService`, and provides a working Swing repair |
| Task02 | Hospital appointment event-driven design | Provides event table, hierarchy, pseudocode trace, and a working appointment demo |
| Task3 | Library search layout | Provides a nested Swing layout and a resizeable library screen |
| Task4 | Drawing-pad event forensics | Provides a repaired `paint()`-based drawing pad |
| Task5 | Four currency-converter listener styles | Provides frame, named inner, anonymous inner, and lambda implementations |
| Task6 | Campus event registration GUI/JDBC design | Provides layered classes, MySQL script, paging and worker-based registration application |

## Compile and Run

Open a terminal in `assignment_4_codes` and compile with:

```powershell
javac Task01_FeeWindow\*.java
javac Task02_HospitalDesk\*.java
javac Task03_LibrarySearch\*.java
javac Task04_DrawPad\*.java
javac Task05_CurrencyConverter\*.java
javac -d Task06_CampusEvents Task06_CampusEvents\src\com\campus\event\model\*.java Task06_CampusEvents\src\com\campus\event\dao\*.java Task06_CampusEvents\src\com\campus\event\service\*.java Task06_CampusEvents\src\com\campus\event\ui\*.java
```

Run examples:

```powershell
java -cp Task01_FeeWindow FeeWindow
java -cp Task02_HospitalDesk HospitalAppointmentDesk
java -cp Task03_LibrarySearch LibrarySearchScreen
java -cp Task04_DrawPad DrawPad
java -cp Task05_CurrencyConverter LambdaConverter
java -cp Task06_CampusEvents com.campus.event.ui.EventRegistrationApp
```

## Task Outputs

Each task folder contains source code and a task-specific README with its design evidence and result. Screenshots taken during GUI execution should be stored in that task's `output` folder.
