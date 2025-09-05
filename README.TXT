Project: better-ticket-machine
Authors:

52.
The code still compiles and the ticket still prints without inserting any money.
55.
saving=price*discount;
56.
mean=total/count;
59.
It doesn't work because we removed the int in the code.
60.
It shows error when i try to compile it, the error: unreachable statement
61.
The difference in that version is the type int;
the editor: price cost;
instruction version: int price=cost;
Yes, it does compile. 
When creating a a newTicketMachine and inserting a price, the value of the price field in the inspector still shows 0, no matter which 
price we put in, because of the type int we added in the editor: int price=cost;
