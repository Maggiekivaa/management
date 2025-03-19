Library Management System

This is a simple library management system where users can choose to borrow or read a book. The system allows users to input their information, select a book, and either borrow the book (with a fee) or select a table to read it.
Features:
- Borrow books with a borrowing fee.
- Choose a payment method (Credit card, M-Pesa, or Cash).
- Select a table (1-10) to read the book.
- Record book borrowing details, including borrow date and return data.
Running the Program:
    python startfile.py
 Follow the on-screen prompts to:
   - Enter your name.
   - Choose if you want to borrow or read a book.
   - If borrowing, provide the return date and choose a payment method.
   - If reading, select a table number between 1 and 10.
Example Usage:
$ python startfile.py
Welcome user, what's your name?
Enter Name: John
Nice to know you, John!
Do you like reading books? (yes/no): yes
Enter a book you like: Harry Potter
Who is the author of the book? J.K
Author of the book: J.K
Would you like to borrow or read the book? (borrow/read): borrow
When do you want to borrow the book? (e.g., today, tomorrow): today
When will you return the book? (e.g., in 1 week, in 2 days): in 7 days
