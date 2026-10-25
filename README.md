# SmartShelf - Library Management System

SmartShelf/
  report/part1.tex     Part 1 report (schedule, UML, interface) - submit this first
  report/main.tex      Full proposal template (later parts) (edit the personal-info block at the top, then run pdflatex twice)
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
