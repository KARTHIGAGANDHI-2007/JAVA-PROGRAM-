# CSA09 – Programming in Java – Assignment 1 (Campus Smart-Parking System)

Name: <your name>   Register number: <your register number>   Java: OpenJDK 21

## Layout
| Folder | Content | Run |
|---|---|---|
| Task02 | CastDemo – integer division / casting risk | `cd Task02 && javac CastDemo.java && echo 130 \| java CastDemo` |
| Task03 | ParkingFacility (Complete the Code) | `cd Task03 && javac ParkingFacility.java && java ParkingFacility` |
| Task04–Task10 | Demos on the Task11 model | compile with `-cp ../Task11/out` (see each file) |
| Task08 | FeeDemo (Complete the Code) + OverloadDemo | `cd Task08 && javac FeeDemo.java && java FeeDemo` |
| Task11 | Full system, tests, inputs | `cd Task11 && javac -d out $(find src -name '*.java') && java -cp out parking.app.Main < input.txt` ; tests: `java -cp out parking.app.TestRunner` |
| Task12 | Extended system (e-bike, van, day pass, 5 jagged floors) | `cd Task12 && javac -d out $(find src -name '*.java') && java -cp out parking.app.Main < input12.txt` |
| bench | Micro-benchmarks for the complexity sections | `javac -cp ../Task11/out Bench.java && java -cp ../Task11/out:. Bench` |
| outputs | Captured console output of every program | |

Results: every program compiles and runs; 37/37 tests (Task11) and 20/20 tests (Task12) pass; Task 11 day total Rs 650 (hand = program); Task 12 grand total Rs 1115.
Commit one task at a time (git add TaskNN; git commit -m "TaskNN ...") so the history shows progressive work.
