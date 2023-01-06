# Register form
## Description
You are given the task to create a registration form for new users, this form should ask the user for the following information:

- First name
- Last name
- Age
- Email
- Address
At the end of the program, you should print all the information added from the user in a friendly way

## Solution
```python
Algoritmo registerForm
	Imprimir "[------NEW USER------]"
	Imprimir "First name: ";
	Leer firstName;
	Imprimir "Last name: ";
	Leer lastName;
	Imprimir "Age: ";
	Leer age;
	Imprimir "Email: ";
	Leer email;
	Imprimir "Address: ";
	Leer address;
	Imprimir "[------USER DATA-----------]";
	Imprimir "Full name: ", firstName, " ", lastName;
	Imprimir "Age: ", age;
	Imprimir "Email: ", email;
	Imprimir "Address: ", address;
	Imprimir "[--------------------------]";
FinAlgoritmo
```