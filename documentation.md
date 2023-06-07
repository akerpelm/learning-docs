small blurb here...

- [1. For Instructors](#1-for-instructors)
  - [1.1. Courses and Classes](#11-courses-and-classes)
    - [1.1.1. Add Questions:](#111-add-questions)
      - [1.1.1.1. Multiple Choice](#1111-multiple-choice)
      - [1.1.1.2. Numerical Answer](#1112-numerical-answer)
      - [1.1.1.3. Word Phrases](#1113-word-phrases)
      - [1.1.1.4. Long Answer](#1114-long-answer)
      - [1.1.1.5. Add Topics](#1115-add-topics)
    - [1.1.2. Question Bank](#112-question-bank)
    - [1.1.3. Course Images](#113-course-images)
  - [1.2. Classes](#12-classes)
    - [1.2.1. Classlist and Gradebook](#121-classlist-and-gradebook)
    - [1.2.2. Create an assignment](#122-create-an-assignment)
      - [1.2.2.1. Questions in an Assignment](#1221-questions-in-an-assignment)
      - [1.2.2.2. Other assignment settings](#1222-other-assignment-settings)
    - [1.2.3. List of Assignments and Grading Weights](#123-list-of-assignments-and-grading-weights)
      - [1.2.3.1. Category weights](#1231-category-weights)
      - [1.2.3.2. Assignment weights within category](#1232-assignment-weights-within-category)
      - [1.2.3.4. Individual Assignments](#1234-individual-assignments)
        - [1.2.3.4.1. Show/Hide Answers](#12341-showhide-answers)
        - [1.2.3.4.2. Edit Assignment:](#12342-edit-assignment)
        - [1.2.3.4.3. Grade Assignment](#12343-grade-assignment)
        - [1.2.3.4.4. Answer Choices](#12344-answer-choices)
    - [1.2.4. Course Materials](#124-course-materials)
  - [1.3. Course Creation](#13-course-creation)
    - [1.3.1. Class Access](#131-class-access)
  - [1.4. Access Keys](#14-access-keys)
- [2. For Students](#2-for-students)
  - [2.1. Your Classes](#21-your-classes)
  - [2.2. Assignments](#22-assignments)
  - [2.3. Question Types](#23-question-types)
    - [2.3.1. Multiple Choice](#231-multiple-choice)
    - [2.3.2. Numerical Answer](#232-numerical-answer)
    - [2.3.3. Word Phrases](#233-word-phrases)
    - [2.3.4. Long Answer](#234-long-answer)
  - [2.4. Class Content](#24-class-content)
  - [2.5. Registering for a Class](#25-registering-for-a-class)
- [3. Keywords](#3-keywords)

# 1. For Instructors

## 1.1. Courses and Classes

What is the difference between a course and a class?

We use the term course to refer to an area of study. The term class refers to
the specific semester/quarter and the specific group of students to whom that
subject matter in that area of study is taught. Some examples will make this
clearer. Introduction to Physics, Calculus-A, Principles of Microeconomics etc.
are examples of courses. An instructor typically teaches a course multiple
times over their career. Any specific instance when a course is taught, such as
a semester or a quarter, is referred to as a class. For example, an instructor
may teach Calculus-A in Fall of 2021 and again in Fall of 2022. These specific
instances are referred to as classes. Some also refer to a class by the name of
section.

Some tasks are class specific whereas others are relevant to the whole course.
For example, the instructor may want to maintain a question bank that is
relevant to the course. Questions from this question bank may be drawn upon for
any class in that course. However, the set of students, quizzes, gradebook etc.
are class specific.

This section describes the various things that an instructor can do for a course.

### 1.1.1. Add Questions:

- Create questions for use in all classes specific to this course.
- When creating a question, instructors have access to a rich text editor and a form in order
  to create highly customizable questions. You can use basic LaTeX to add mathematical notation,
  as well as add images.
- All questions created by the instructor become part of a question bank for the course.
- There are currently 4 supported question types: Multiple choice, Numerical Answer, Word answer, and
  Long answer.

  #### 1.1.1.1. Multiple Choice

  - Each question can have as many choices as needed. Hence, this includes True or False questions also.
    At minimum, one answer must be marked as correct, but more than one can be marked as correct.
    As long as the student chooses any one of the answers marked as correct, they obtain full points.
    <!-- - **important**: does each selected answer need to be picked, or just one of the selected? -->
    <!-- BB: just one. I have added the response above. -->
  - Multiple choice questions are graded by the application. [on submit](#1221-initial-setup)

  #### 1.1.1.2. Numerical Answer

  - These questions require students to respond with a numerical answer.
  - The app allows the instructor to specify more than one answer as the correct answer.
  - If a student's response matches any of the answers, the question will be considered correct.
  - For each correct numerical answer, the instructor can specify a range as acceptable answers.
  - Numerical answer questions will be graded by the application. [on submit](#1221-initial-setup)

    - Consider the following example:

    ```
    How many miles are in 5 kilometers?

    Correct Answer: 3.10686
    Minimum Answer: 3.1
    Maximum Answer: 3.11
    ```

    - The above question has one correct answer, 3.10686. Any response in the range 3.1 and 3.11,
      will be considered correct and will receive full points.

  #### 1.1.1.3. Word Phrases

  - These questions expect a word or a few words as responses (as opposed to selecting a choice, or a
    numerical answer).
  - As above, the app allows the instructor to specify more than one answer as the correct answer.
  - If a student's response matches any one of the answers, the response will be considered correct.
  - When determining whether the student's response matches with the entered phrases,
    the application ignores case and any non-alphanumeric characters.
    For example, if the instructor enters "SPNE" as the correct answer, then any of the following responses will be considered
    correct: "spne", "s p n e", "Spne".
  - In addition to specifying an answer, you may specify the maximum character length a student's answer may be.
  - For answers requiring significant characters or an elaborate answer, use of the long answer question type is recommended.
    However, it should be noted that the long-answer questions will have to be graded manually.
  - Word phrase questions will be graded by the application. [on submit](#1221-initial-setup)

  #### 1.1.1.4. Long Answer

  - You may enter an answer which will be displayed to students once the answers are released, but has no impact on the correctness of student answers.

  - In addition to specifying an answer, you may specify the maximum character length a student's answer may be.

  - Long answer questions are not graded by the application. They have to be graded by the instructor.
    It is still convenient to use the application for them since they can be part of a quiz that has other question types,
    and all these questions are in a single place.

#### 1.1.1.5. Add Topics

- When creating/editing a question, you can specify one or more topics for that question.
- Topics make it easy to filter questions when searching questions to add to an assignment [creating an assignment](#1222-questions-in-an-assignment).
- Topics are not visible to students.

### 1.1.2. Question Bank

- All questions created using the "Add Question" view get added to the question bank.
- Here, you may filter questions by topic, as well as search questions [filter questions](#1222-questions-in-an-assignment).
- From the question bank page, you may choose a question to edit or delete.
- For each question that has previously been used in one or more assignments, you can also
  see the percentage of students who got it correct.

### 1.1.3. Course Images

- This is an image bank that you can pull images from when creating new questions, or for
  downloading images for any other reason.
- You can add images to this bank by uploading images directly. Further, any images that you
  add when creating a question using "Add Question" view also get added to this bank.
- The accepted formats for images are: SVG, JPEG, PNG...
  <!-- - elaborate -->
- Images are grouped by topics. If an image has not used in any question, then it is
  be placed into the unused topic on the course images page.
    <!-- BB: Can the following link be merged with the point 2 above. -->
  <!-- - If you add [a question with an image to a topic](#1115-add-topics), the image will be viewable from within that particular topic on the course images page. -->

## 1.2. Classes

What are classes...

<!-- BB: discussed above -->

### 1.2.1. Classlist and Gradebook

This view shows all students registered to a class. It also shows their grades in each assignment.
Assignment grades are organized by the category to which they belong.
The application also calculates and displays the overall grade of every student. To include grades
from a specific assignment category in this `overall grade` calculation, the instructor needs to specify
the weight of that category in the overall grade. <!--Add link to List of Assignments and Grading Weights-->
The default weight of an assignment category in the overall grade is zero.
Some examples of categories that instructors have used are:

- Exams
- Quizzes
- Homework
- Assignments

- The instructor can choose the category titles.

<!-- BB: The information appears above. We need to, however, add the link. -->
<!-- - A student's grade for a specific category, as well as their overall grade is calculated from the [Grade Weighting](#123-categories-assignments-grade-weighting) page. -->

<!-- - You may weigh grades for specific students from the [Grade Weighting](#123-categories-assignments-grade-weighting) page, which will be reflected in the gradebook. -->
<!-- - can you?? -->
<!-- BB: This, not yet. You cannot set student specific weights for categories. But I want to add this. -->

- The table is filterable. You may select specific students, assignment categories, and show grades as percentages or raw scores.

- The table is also downloadable both as an Excel (.xlsx) and CSV (.csv) file. The download will reflect all applied filters.
  <!-- is this true? -->
  <!-- BB: yes this is true -->

### 1.2.2. Create an assignment

This view is used to create a new assignment.

#### 1.2.2.1. Questions in an Assignment

- When creating a new assignment, the instructor can import all questions from any
  existing assignment (whether from a previous class or the current class) in this course
  with the click of a button.

- If importing an existing assignment, one or more of imported questions can be easily
  removed from the new assignment that is being created.

- Questions can be also added from the question bank to the new assignment being created,
  either in place of importing questions, or in addition to importing questions from a
  previous assignment.

- When adding questions from the question bank, the application indicates which questions have
  already been added to the new assignment, so that no questions appear twice.
- Further, when adding questions from the question bank
  the questions can be searched and filtered to make it easier to find relevant questions. You can filter by:
  - Question type:
    - Multiple choice
    - Numerical answer
    - Word phrase
    - Long answer
  - Topics
    - you may select questions that have one or more of specified topic(s)
    - you may select questions which have all of the specified topics (topic 1 AND topic 2)
    - for more information about topics, refer to the [Add Topics](#1115-add-topics) section

#### 1.2.2.2. Other assignment settings

- In addition to adding questions to the new assignment, this view is used to specify
  the following:
    <!--
        BB: spacing question - do we need to put a blank line before the description and the header
        -->

  - Category
    This is the category to which the assignment belongs.
    Instructor can choose one of the existing categories, or create a new one.

  - Title
    Title of the assignment that will appear in the list of assignments page.

  - Start time
    The assignment will not be visible to the students before the start time.

  - Submission deadline
    Students will not be able to submit the assignment after this deadline.

  - Time limit and duration
    Time limit can be `yes` or `no`. A time limit of `no` implies that the student
    can work on the assignment however long they want, as long as the
    assignment is submitted before the deadline.

    A time limit of `yes` requires specifying the duration (in minutes) for which
    a student is allowed to work on the assignment once the student has started it.
    A student is considered to start the assignment the first time they view it.

  - Grading option
    Here the instructor can choose between the `On submit` and the `Instructor
will determine` options. In the former case the assignment will be graded by
    the application as soon as the student submits it, and will show the grade to
    the student.
    In the `Instructor will determine` option, the instructor chooses when the
    application grades the assignments and when the grades become visible.
    Note that irrespective of which grading option is chosen, the `Long answer`
    questions have to be graded manually by the instructor.

  - Answer visibility
    Here the instructor can choose between the `After grading is complete`
    and the `Instructor will determine` options. In the former case, students will
    be able to see answers as soon as their assignment is graded. In the latter case,
    the instructor will choose when to release the answers.
    <!-- is this true? Where do we make this determination. Add links here and same for grading timing-->
    <!-- BB: yes this is true. The instructor makes this determination from the quizgrades view. -->
  - Randomize questions
    By default the questions in an assignment are presented to the students in the same order that
    they appear when the instructor creates the assignment. However, by choosing `yes` for
    this option, the instructor can choose to randomize the order in which questions are presented
    each student. That is, different students see the questions in different order.
    The randomization is seeded so that if a student exits and re-enters the assignment they
    see it in the same order everytime.
  - Number of attempts
    By default the number of attempts is set to 1. This means that once a
    student submits the assignment, they cannot change their answers. This is
    irrespective of whether the assignment is graded or not. An instructor
    can set the number of attempts to more than 1. If number of attempts is
    set to 2, for example, a student can change the answers even after the
    first submission, but not after the second submission. For example, if
    the instructor set the grading option to `On submit`, then with two
    attempts, the student can submit once, see which answers they got
    incorrect, and then change their answers to those questions.

### 1.2.3. List of Assignments and Grading Weights

On this page the instructor can:

- view all assignments for a class, organized by assignment category,
- view and change the weight of each category in the overall grade,
- view and change the weights of the different assignments within the category.

#### 1.2.3.1. Category weights

By default the category weight is zero. That is, it is not used for calculation of
the overall grade. However, by changing this number, the weight of the category
can be changed. The category weights are relative to each other.
Following two examples will clarify how the category weights work. Example 1 is a
straightforward example where the weight of each category equals the percentage weight
of that category in the overall class grade.

- Example 1: Assume there are 3 categories: Quizzes, Midterm exams, and Final exam
  with category weights 35, 40 and 25 respectively. Then in the overall
  grade calculation the average score from Quizzes will receive 35% weight,
  the average score from Midterm exams will receive 40% weight and the Final
  exam score will receive 25% weight.
- Example 2: Assume there are 3 categories: Quizzes, Midterm exams, and Final exam
  with category weights 50, 90 and 60 respectively. Note that the weights do not add
  to 100 (they add to 200) in this example.
  However, these weights are relative, so in the overall
  grade calculation the average score from Quizzes will receive 50/200 = 25% weight,
  the average score from Midterm exams will receive 90/200 = 45% weight, and the Final
  exam score will receive 60/200 = 30% weight.

#### 1.2.3.2. Assignment weights within category

By default each assignment within a category has a weight of 100. Since the weights are relative,
the default weight implies an equal weighting of every assignment
in the category. These weights can be modified in two different ways.

- Each assignment within a category can be given a weight, that is used to then calculate the
  weighted average score of the category. This can be done by modifying the `Weight in category`
  input. For example, to drop a specific assignment set its weight to 0.
- Assign special weights to the lowest scoring assignments in that category
  through use of the `Special weight on lowest scores` input.
  For example,
  - Entering a 0 into this field will drop the lowest assignment score of every student for that category.
  - Entering 0,0 will drop the two lowest assignment scores.
  - Entering 0, 10 will drop the lowest score, and weigh the second lowest score at 10.
    In this case, if other assignments within a category are weighed at 100, the
    second score will be weighed at 1/10th of the weight of other assignments in
    that category.

#### 1.2.3.4. Individual Assignments

- Clicking into an individual assignment brings up an overview of that assignment.
- This page provides the following information:

  - Number of students who have submitted the assignment.
  - Average score.
  - Score distribution, as a dot chart.

  ##### 1.2.3.4.1. Show/Hide Answers

  - Modify which students are able to see answers.
  - You may choose to:

    - Show answers to students who have submitted.
    - Show answers to all students.
    - Hide answers from students who have not submitted.
    - Hide answers for all students.

  ##### 1.2.3.4.2. Edit Assignment:

  - You may edit the assignment for the entire class. Clicking this button will take you to the [assignment creation](#122-assignment-creation) page, with details about the assignment already prepopulated. You may edit assignments as needed.
  - You may edit the assignment for an indvidiaul student. Clicking this button will take you to the [assignment creation](#122-assignment-creation) page, where you may select a paritcular enrolled student for which to modify the assignment.

  ##### 1.2.3.4.3. Grade Assignment

  - You may choose to grade submitted assignments or all assignments.
  - This will take you to a grading page, where you are able to grade assignments in order by which they were submitted.
  <!-- - unsure about this because I don't have any submissions for my class.  verify validity.-->
  - You may also attempt the assignment, which may help visualize any shortcomings or errors that may have gone unnoticed on initial creation.

  ##### 1.2.3.4.4. Answer Choices

  - Further breaks down student performance, specific to each question.

### 1.2.4. Course Materials

- You may add resources to the course materials page for access by students.
- This is a practical place to aggregate any materials needed for the course, such as useful web pages, syllabuses, and documents.
- You may group materials by sections, as well as create nested subsections for each section.
- Each section may have two layers of nesting, its direct children, as well as subsections containing children.
- An example structure looks as follows:

```js
Exam 1 Reading Materials
  a) Data Types
  // Direct child subsection of section
    1) Strings //Child of subsection
    2) Booleans // Child of subsection
    3) Numbers // Child of subsection
  b) Useful Link: Understanding Data Types
  //Direct child link of section
```

- Currently supported resources are URLs, and file uploads (JPEG, PDF **FILL LIST**)
- When uploading a file, a title must be included.

## 1.3. Course Creation

- You may create a new course at any time.
- To create a course, select a course title that is not already in use.
- If you wish to create a course with an associated class, you may enter the name of the class when creating the course.
- You may also create an course without an associated class.
  <!-- - ability to later add? -->
  ### 1.3.1. Class Access
  - Once a class has been created, the class ID will be required for a student to access the class.
  - The class ID will be generated and appear alongside the class name when creating a new class.
  - A student must also have an [access key](#14-access-keys) to register for a class.

## 1.4. Access Keys

Once a class is in place, students must use access keys to sign up for the class.

- An access key must be purchased for each individual student.
- An access key grants a student access to one class, for the entire duration of the class.
- A different access key is required for a student to access a different class.
- Access keys are purchased through Stripe Payments.
  - All transactions are secure socket layer (SSL) protected.
  - All information is securely transmitted during the processing of payment.
  - No payment information is transmitted through MyStudyBook, nor is this information stored.

# 2. For Students

## 2.1. Your Classes

- Within your class's page, you may view all available assignments
- There are various assignment types:
  - Exams
  - Quizzes
  - Homework
  - Assignments
- Each type shows a percentage grade, which is the percent of the subsection you have answered correctly.
  <!-- because the course I am registered to is ended, not sure what the various values mean, ie: PracticeQuizzes (0%)...is this my % of the total possible grade for this category? Or is this the weight of the category -->
  - These percent grades are used to calculate your total grade if your instructor, but does not account for weighting of different assignment types

## 2.2. Assignments

- Clicking an assignment title will open the assignment.
- Timed assignments will begin timing from the moment you open the assignment. If there is a `time limit` on an assignment, you will have exactly that long to complete the assignment.
    <!-- - what happens when the timer runs out? Submits what you have? submits nothing -->
- The start time is the earliest time at which you may attempt an assignment.
  <!-- - are you able to click in if the start time is in the future? -->
- The due date is the last possible time at which you may submit an assignment. After the due date, you may can still view the assignment, but cannot modify answers.
<!-- - confirm if true -->
- The grade for each assignment is determined once the assignment is complete.

## 2.3. Question Types

Assignments may have different question types, each requiring a slightly different approach.

### 2.3.1. Multiple Choice

- Select a single answer that you believe best answers the question.
  <!-- - **important**: does each selected answer need to be picked, or just one of the selected? -->
  <!-- can students answer more than one? -->

### 2.3.2. Numerical Answer

- Input a numerical value that you believe best answers the question.

### 2.3.3. Word Phrases

- Input a word or set of words that you believe best answers the question.
- A character limit may be specified. If so, your answer must be less than the character limit.

### 2.3.4. Long Answer

- Enter an answer that you believe best answers the question.
- A character limit may be specified. If so, you answer must be less than the character limit.

## 2.4. Class Content

- Your instructor may chose to provide content for the class. This may include useful links, documents, or text.
- If enabled, be sure to look through the content.

## 2.5. Registering for a Class

- In order to register for a class, you must have an access key as well as a unique class ID, provided to you by your instructor.
- Once you successfully enter the access key and class ID combination, you will be registered for a class.
- Access keys are purchased through Stripe Payments.
  - All transactions are secure socket layer (SSL) protected.
  - All information is securely transmitted during the processing of payment.
  - No payment information is transmitted through MyStudyBook, nor is this information stored.
- All classes for which you are successfully registered will appear on your home page.

# 3. Keywords

1.  Courses: a series of lectures or lessons in a particular subject. One course may have multiple classes.

- `Biology 110 - Principles of Biology 1` is the name of a biology course.

2.  Classes: A particular course, taught at a particular time.

- `BIO110-Summer22` is an arbitrary name for the biology course, taught in the summer of 2022.

3. Assignments: An umbrella term for all coursework contained within a class.

   <!-- would recommend changing this to coursework maybe to avoid assignments twice -->

   1. Exam: an event to establish a student's proficiency or knowledge of a specific subject. Typically holds the most weight in a particular course.
   2. Quiz: a test of knowledge, especially a brief, informal test given to students. Typically holds less weight than an exam.
   3. Homework: schoolwork that a student is required to do outside of class hours, typically in preparation for other coursework.
   4. Assignments: A task which must be completed outside of class hours, which typically holds more weight than a homework.
   <!-- not sure about this one. -->

4. Question Types:

   1. Multiple Choice: a question accompanied by several possible answers from which the candidate must try to choose the correct one.
   2. Numerical Answer: a question for which a candidate must provide a number value in response.
   3. Word Phrase: a question for which a candidate must provide a word or set of words in response.
   4. Long Answer: a question for which a candidate must provide a detailed answer, typically to an open-ended question.

<!-- TODO:
'getting started' (when perhaps a landing, etc is implemented)
ensuring no cheating (click away, etc). (when implemented)
change some verbeage here and there
 -->

<!-- @bharat - please search for '<!' to determine any comments that I have written, typically out of uncertaity.> -->
