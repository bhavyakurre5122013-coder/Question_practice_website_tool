Question Practice Tool Alpha is a browser-based application designed to help students systematically practice questions organized by subject, chapter, and exercise while tracking their performance over time.


Purpose


The primary purpose of the tool is to provide a structured environment where learners can practice different types of questions, review answers, and monitor correctness statistics in a focused, distraction-free interface. It also allows a “developer” or teacher to build and maintain a question bank for multiple subjects, chapters, and exercises without needing to edit code directly.


Target Audience


Students who want to practice questions for school subjects in an organized way.
Teachers, tutors, or parents who wish to create custom practice sets and track difficulty levels for their learners.
Content creators or coaching centres that need a lightweight question-management and practice platform.


High-Level Description


The application has two main modes: a learner-facing Question Practice Tool section and a Developer Options section for configuring the content and settings. The learner area focuses on selecting subjects and attempting questions, while the developer area focuses on adding, editing, and deleting subjects, chapters, exercises, and questions with detailed metadata.


Main Features


Hierarchical content structure: Subjects, Sub-Subjects, Chapters, Sub-Chapters, and Exercises are all supported so questions can be organized exactly like a textbook or syllabus.

Multiple question types: Text, Fill in the Blanks, Matching, Multiple Choice Questions, Draw the Following, Label the Following, Define the Following, True/False, Assertion and Reasoning, Answer by Diagram, Answer by Map, Answer by Case, and Answer by Graph.

Difficulty tagging: Each question can be assigned a difficulty level using a three-star selector, enabling filtering by Easy, Medium, or Hard.

Favorites and filtering: Questions can be marked as favorites and filtered so learners can revisit important or tricky questions easily.

Hint mode: An optional Hint Mode lets the user decide whether hints should be available or hidden during practice.

Random question mode: Users can practice questions in a random order based on Exercise, Chapter, Subject, or across All Subjects.

Timer: A timer display (00:00:00) supports timed practice sessions for exam-style preparation.

Progress tracker: Progress can be viewed by Exercise, Chapter, Subject, or All Subjects, helping users track overall coverage and performance.

Performance counters: The interface shows counts of Correct and Incorrect responses, giving immediate feedback about accuracy.

Notes saving: A “Save Notes” option allows learners to store personal notes related to the current question or exercise.


Developer Options and Content Management


The Developer Options menu provides a full set of tools for building and maintaining the question bank.

Subject Management

Add Subject with support for adding Sub-Subjects and “Add More” items, then Save.

Edit Subject and its Sub-Subjects with the ability to Add More and Save changes.

Delete Subject with a dedicated Delete control.

Chapter Management

Add Chapter with Sub-Chapters and “Add More”, then Save.

Edit Chapter and Sub-Chapters with Save and Add More options.

Delete Chapter when it is no longer required.

Exercise Management

Add Exercise for a given Subject/Chapter structure and Save.

Edit Exercise details and Save updates.

Delete Exercise if it should be removed from the practice list.

Question Management

Add Question by selecting Subject, Chapter, and Exercise, then specifying Difficulty and Question Type, and pressing Save.

Edit Question by selecting Subject, Chapter, Exercise, and Question, adjusting Difficulty or Question Type and content, and saving.

Delete Question by selecting the appropriate Subject, Chapter, Exercise, and Question, then using Delete.




User Navigation

Top-Level Navigation

The application displays a Menu with a clear section for Developer Options, along with switches and dropdowns for key modes such as Dark Mode, Hint Mode, Random Question Mode, Timer Mode, and Progress Tracker views. Users can quickly change their practice configuration by selecting difficulty filters, favorites filter, randomization scope (Exercise / Chapter / Subject / All Subjects), and progress display options.




Learner Workflow

Select Subject, Sub-Subject, Chapter, Sub-Chapter, and Exercise from the dropdown menus in the Question Practice Tool area.

Use the difficulty and favorites filters, and choose Hint Mode or Random Question Mode if desired.

Start the timer (if implemented) and view questions one by one using Prev and Next.

Reveal or check the answer using the Ans button, then record whether the attempt was Correct or Incorrect (reflected in the counters).

Optionally write and Save Notes for later revision.




Developer Workflow

Open Developer Options from the Menu section.

Configure the structure using Add Subject / Add Sub-Subjects / Add Chapter / Add Sub-Chapters / Add Exercise, then Save.

Use Add Question to create questions under the chosen Subject–Chapter–Exercise combination, set Difficulty and Question Type, and Save.

Use Edit Subject / Edit Chapter / Edit Exercise / Edit Question to update existing content.

Use Delete Subject / Delete Chapter / Delete Exercise / Delete Question to remove outdated or incorrect items.




Usage Scenarios

Daily practice: Students log in, select their current chapter and exercise, and attempt questions in order or using Random Question Mode while observing the timer and correctness statistics.

Exam revision: Learners filter by Hard difficulty or Favorites, enable or disable hints, and repeatedly practice tougher questions.

Content creation: Teachers build textbook-aligned structures, add various question formats (MCQ, True/False, diagrams, etc.), and assign difficulty levels.

Progress review: Users or teachers access the Progress Tracker to view coverage at the Exercise, Chapter, Subject, or All-Subjects level and identify areas needing improvement.




Design and Interaction Notes

The layout separates configuration (filters, timers, modes, developer tools) from the main question viewing area, making it clear when the user is practicing versus editing content. Buttons like Prev, Next, Ans, Save Notes, and counters for Correct/Incorrect are placed close to the question display to support fast interaction during practice sessions.
