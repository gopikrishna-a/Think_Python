# Chapter: 2 Variables, expressions and statements

### 6. Variables

**Ans:** One of the most powerful features of a programming language is the ability to manipulate variables. A variable is a name that refers to a value.
An assignment statement creates new variables and gives them values:

**Examples: Creating Variables** 

     message = 'And now for something completely different'  #string
     n = 17    #intiger
     pi = 3.1415926535897932   #float
    
**Note:** The type of a variable is the type of the value it refers to.


### 7. What is State diagram?

**Ans:** A common way to represent variables on paper is to write the name with an arrow pointing to the variable’s value. This kind of figure is called a state diagram because it shows what
state each of the variables is in (think of it as the variable’s state of mind).

![State diagram](https://i.imgur.com/8NkLynX.png)

### 8. Variable names 

Programmers generally choose names for their variables that are meaningful—they document what the variable is used for.
Variable names can be arbitrarily long. They can contain both letters and numbers, but they have to begin with a letter. It is legal to use uppercase letters, but it is a good idea to begin variable names with a lowercase letter.

### 9. keywords in Python

+ Python 2 has 31 keywords:


		and			del		from 		not 		while
		as 			elif 		global 		or 		with
		assert 		else 		if 		pass 	        yield
		break 		except 		import 		print
		class 		exec 		in 		raise
		continue 	        finally 	is 		return
		def 		        for 		lambda 		try

+ In Python 3, exec is no longer a keyword, but nonlocal is.


### 10. What is Operator?
**Ans:** Operators are special symbols that represent computations like addition and multiplication. The values the operator is applied to are called operands.

#### The operators: +, -, *, / and ** perform addition, subtraction, multiplication, division and exponentiation


### 11. Expressions and statements
#### 11.1 Expressions:
**Ans:** An expression is a combination of values, variables, and operators. A value all by itself is considered an expression, and so is a variable, so the following are all legal expressions (assuming that the variable x has been assigned a value)

#### statements:
**Ans** A statement is a unit of code that the Python interpreter can execute. 


### 12. Order of operations

**Ans:** When more than one operator appears in an expression, the order of evaluation depends on the rules of precedence. For mathematical operators, Python follows mathematical convention. The acronym PEMDAS is a useful way to remember the rules:

+ **P**arentheses have the highest precedence and can be used to force an expression to evaluate in the order you want. 
+ **E**xponentiation has the next highest precedence, so 2**1+1 is 3, not 4, and 3*1**3 is 3, not 27.
+ **M**ultiplication and **D**ivision have the same precedence, which is higher than **A**ddition and **S**ubtraction, which also have the same precedence. So 2*3-1 is 5, not 4, and 6+4/2 is 8, not 5.
+ Operators with the same precedence are evaluated from left to right


### 13. Comments

**Ans:** As programs get bigger and more complicated, they get more difficult to read. Formal languages are dense, and it is often difficult to look at a piece of code and figure out what it is doing, or why. For this reason, it is a good idea to add notes to your programs to explain in natural language what the program is doing. These notes are called comments, and they start with the **#** symbol




		
