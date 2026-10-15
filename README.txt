Scope Technologies - Online Exam Portal
=======================================
Open index.html. The header has 'Student' and 'Admin' buttons (default admin password: admin123).
The Admin button is hidden while a student is on the exam pages (details, exam, thank-you),
and it never shows on personal student links.

Folder:
  index.html      -> student page
  css/style.css   -> design and colours (see :root)
  js/script.js    -> all logic (change ADMIN_PASSWORD here)
  images/logo.png -> Scope Technologies logo

Admin: create exams (or import questions from an Excel .xlsx / .csv file - see sample-questions.xlsx and sample-typed-answers.xlsx; question types: multiple choice or typed answer), edit or delete saved exams, add students, view results.
Editing an exam changes it for new links. Links already sent keep the old questions,
so copy/send a fresh link after editing.

Sending exam links to students:
  Admin -> 'Students & Links' -> select an exam, enter the student's name/roll/class/phone -> Add.
  Then click 'Copy Link' or 'WhatsApp'. The student's details are pre-filled when the link opens.
  After the exam the student taps 'Send Result on WhatsApp'; paste the Result Code you receive
  into Admin -> Results -> 'Add Result'.
  (Links work on other devices only when the site is hosted online, e.g. Netlify.)

Note: data is stored in the browser (localStorage).
