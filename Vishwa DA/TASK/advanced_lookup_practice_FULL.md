#  Advanced Lookup Practice (VLOOKUP • HLOOKUP • XLOOKUP)

---

##  Dataset 1: Student Table

| Student_ID | Name   | Class | Subject | Marks | Region |
|------------|--------|-------|---------|-------|--------|
| S101       | Asha   | 10    | Math    | 85    | North  |
| S102       | Rahul  | 10    | Science | 78    | South  |
| S103       | Meena  | 11    | Math    | 92    | East   |
| S104       | John   | 11    | English | 74    | West   |
| S105       | Priya  | 10    | Science | 88    | North  |

---

##  Dataset 2: Fee Structure Table

| Class | Tuition_Fee | Exam_Fee | Library_Fee |
|------|------------|----------|-------------|
| 10   | 12000      | 1500     | 800         |
| 11   | 15000      | 2000     | 1000        |

---

##  Dataset 3: Subject Marks Matrix (HLOOKUP Table)

| Subject | Asha | Rahul | Meena | John | Priya |
|--------|------|--------|--------|------|--------|
| Math   | 85   | 0      | 92     | 0    | 0      |
| Science| 0    | 78     | 0      | 0    | 88     |
| English| 0    | 0      | 0      | 74   | 0      |

---

#  TASKS

---

##  TASK 1: VLOOKUP (Basic Level)

### Requirements:
Use VLOOKUP to fetch fee details from Dataset 2.

### Output Columns:
- Student_ID
- Name
- Class
- Tuition_Fee
- Exam_Fee
- Library_Fee

### Instructions:
- Use exact match
- Class column should be lookup key
- Use absolute reference for table range

---

##  TASK 2: VLOOKUP (Intermediate Level)

### Requirement:
Create a column **Total_Fee**

### Formula Logic:
Total_Fee =
- Tuition_Fee + Exam_Fee + Library_Fee

---

##  TASK 3: HLOOKUP (Core Task)

### Requirement:
Fetch Marks from Dataset 3 using HLOOKUP.

### Inputs:
- Subject
- Student Name

### Output:
Marks for that student in selected subject

---

##  TASK 4: HLOOKUP (Advanced Matrix Use)

### Scenarios:
1. Find Marks of Rahul in Science
2. Find Marks of Meena in Math
3. Find Marks of John in English

---

##  TASK 5: XLOOKUP (Modern Replacement)

### Requirements:
Replace ALL VLOOKUP tasks using XLOOKUP.

### Must Fetch:
- Tuition_Fee
- Exam_Fee
- Library_Fee

### Conditions:
- Exact match
- If not found → return "Not Found"

---

##  TASK 6: XLOOKUP (Cross Lookup Challenge)

### Requirement:
Fetch Marks using XLOOKUP only.

### Input:
- Student Name
- Subject

### Output:
Marks

---

##  TASK 7: Error Handling Task

### Requirement:
Modify all XLOOKUP formulas.

### Output Rules:
If data missing → show:
"Data Not Available"

---

##  BONUS TASK (HIGH LEVEL)

### Student Report Generator

Create a dynamic report using ONLY lookup functions.

### Input:
- Student_ID

### Output:
- Name
- Class
- Subject
- Marks (from matrix)
- Tuition Fee
- Exam Fee
- Library Fee
- Total Fee

---

#  SKILLS TESTED

- VLOOKUP (table lookup)
- HLOOKUP (matrix lookup)
- XLOOKUP (advanced dynamic lookup)
- Cross table referencing
- Error handling
- Report building logic

---

