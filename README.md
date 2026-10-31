## Each student should have his/her own project. Develop a the project idea. Develop the initial version of your project proposal, it should have all the things a large professional project husually has. 

## Develop UML Diagram (Data Flow Diagram, Use Case Diagram, Activity Diagram, Entiry Relationship Diagram, Class Diagram, Object Diagram)

UML Diagram : https://github.com/mohammadobayetkhan/Library-Management-System/tree/main/UML%20Diagram

## Develop a simple interface using at least 5 classes that are in the class diagrams. Highly Recommend to use the Latex Template.

INterface : https://github.com/mohammadobayetkhan/Library-Management-System/tree/main/Interfaces




# Library Management System

SmartShelf/
  report/part1.tex     Part 1 report (schedule, UML, interface)
  report/main.tex      Full proposal template (later parts)
  report/main.pdf      compiled proposal + design document
  report/figures/      diagram PDFs and interface screenshots used by main.tex
  diagrams/            Graphviz sources (.dot) + PDF/PNG for DFD, Use Case, Activity, ERD, Class, Object
  src/models.py        domain classes (Person, Member, Librarian, Category, Book, EBook, Loan, Reservation, Fine, Notification)
  src/library.py       service layer (Library facade) + SQLite persistence
  src/main.py          Tkinter interface (uses 9 of the classes)
  src/test_library.py  business-rule tests

Run:   cd src && python3 main.py          (Ubuntu: sudo apt install python3-tk)
Test:  cd src && python3 test_library.py
Edit diagrams:  dot -Tpdf diagrams/6_class.dot -o report/figures/6_class.pdf
