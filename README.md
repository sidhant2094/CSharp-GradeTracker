# GradeTracker {MADE BY sidhantMalik}

**GradeTracker** is a simple C# console application that calculates and displays students' final grades based on exam scores and extra credit. It averages the main exam scores, applies bonus points, and then determines a letter grade.

---

## 📌 Features

- Calculates average score using the first 5 exam grades.
- Applies extra credit by adding 10% of each additional score.
- Converts the final average into a letter grade.
- Displays a clean report of each student's grade and letter grade.

---

## 🧮 Grading Criteria

- **Exam Assignments**: First 5 scores are treated as graded assignments.
- **Extra Credit**: Any scores beyond the first 5 add 10% of their value to the total.
- **Final Grade** = `(Exam Total + Extra Credit) / 5`

### 📊 Letter Grade Scale

| Grade Range | Letter Grade |
|-------------|--------------|
| 97+         | A+           |
| 93–96       | A            |
| 90–92       | A-           |
| 87–89       | B+           |
| 83–86       | B            |
| 80–82       | B-           |
| 77–79       | C+           |
| 73–76       | C            |
| 70–72       | C-           |
| 67–69       | D+           |
| 63–66       | D            |
| 60–62       | D-           |
| < 60        | F            |

---

## 🖥 Sample Output

```
Student         Grade
Sophia          94.2    A
Andrew          89.6    B+
Emma            87.2    B+
Logan           92.2    A-

Press the Enter key to continue
```

---

## ▶️ How to Run

1. Make sure you have the **.NET 8 SDK** installed:  
   [https://dotnet.microsoft.com/en-us/download/dotnet/8.0](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

2. Open a terminal in the project folder.

3. Run the app with:

```bash
dotnet run
```

---

## 📂 Project Structure

```
GradeTracker/
├── Starter.csproj
└── Program.cs   // Contains the full application logic
```

---

## 📘 License

This project is released for educational purposes. Free to use and modify.
