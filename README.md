## Asymptotic Upper Bound : 
Let T(n) be a function f(n) and say that the worst-case running time of a certain algorithm on an input of size n. 
##### T(n) = O(f(n)) is the same as… T(n) ≤ c · f(n)    
## Automata theory : 
the study of abstract machines and automata, as well as computational problems that can be solved by them. The word automata means “self-making” in Greek and is plural for “automaton”.  
## Automation : 
A machine, self-operating machine, or a control mechanism designed to automatically follow a predetermined sequence of operations, or respond to predetermined instructions. 
## Backtracking : 
A general algorithm for finding all (or some) solutions to some computational problems, especially constraint satisfaction problems. The algorithm will incrementally build candidates to the solutions and abandons a candidate (“backtracks”) as soon as it determines that the candidate cannot possibly be completed to a valid solution.
## Brute-force : 
A trial-and-error way of approaching an algorithm by forcefully finding a solution with an enumerated (a catalog or list) array of possibilities. Algorithms that improve substantially on brute-force search nearly always contain valuable heuristic (serving to indicate or point out) idea that makes them work; and they tell us something about the intrinsic structure, and computational tractability, of the underlying problem itself.
#### Note: Not only is this approach almost always too slow to be useful, it is an intellectual cop-out; it provides us with absolutely no insight into the structure of the problem we are studying.
## Central Processing Unit (CPU) :
Hardware components that runs a program. Its two parts are the control unit and the ALC. Throughout a running program, the cycle of operations that the CPU undergoes are fetch, decode, and execute. 
#### Control Unit : 
It retrieves and decodes a programs instructions and coordinates computer operations.
#### Arithmetic & Logic Unit (ALC) : 
It preforms mathematical operations. 
## Cursor :  
a control structure that enables traversal over the records in a database. They facilitate subsequent (:occurring later or after)  processing in conjunction with the traversal, such as retrieval, addition and removal of database records. 
Deterministic finite automation (DFA) : also known as “deterministic finite acceptor, DFA”, or “deterministic finite state automation, DFSA” that is a mathematical model of computation (or “finite-state machine”) that accepts or rejects a given string of symbols, by running through a “state sequence” uniquely determined by the string. 
## Efficiency : 
In computer science it is equivalent to the concept of polynomial time (polynomial = fast). The general goal in how to quantify the notion of a “reasonable” running time. There is a final, fundamental benefit to making our definition of efficiency so specific: it becomes negatable (not comparable). It becomes possible to express the notion that there is no (single) efficient algorithm for a particular problem. Our definition in terms of polynomial time is much more an absolute notion; it is closely connected with the idea that each problem has an intrinsic (: belonging to a thing by its very nature) level of computational tractability: some admit efficient solutions, and others do not.
#### Computational efficiency : 
The focus is primarily on efficiency in running time, but it is important that a program is efficient in the use of other resources as well. An issue that arises is the amount of space (or memory) used by an algorithm.
#### Note : If the input size increases from N to 2N, the bound on the running time increases from cNd to c(2N)d = c * 2dNd, which is a slow-down by a factor of 2d.
#### Proposed Definition of Efficiency : 
1. An algorithm is efficient if, when implemented, it runs quickly on real input instances
2. An algorithm is efficient if it achieves qualitatively better worst-case performance, at an analytical level, than brute-force search. 
3. An algorithm is efficient if it has a polynomial running time.
## Factors : 
Whole numbers that are multiplied together to produce another number. If (a x b) = c, then a and b are factors of c. 
#### Example:
The factors of 16 is (1, 2, 4, 8, 16); including all the whole number multiples of 16.  
## File : 
An object on a computer that stores data, information, settings or commands used with a computer program. More specifically, it’s a sequence of data blocks that are stored on a disk. 
Finite Automata or Finite Automaton (FA): A simple idealized machine used to recognize patterns within an input taken from some character set (or alphabet) C. The job of an FA is to accept or reject an input depending on whether the pattern defined by the FA occurs in the output. 
DFA – Deterministic Finite Automaton. 

## Iterator : 
A pointer that is used to point to container memory locations(ex: vectors, variabels, etc.). An object that enables a program to traverse(or backward) a container (variable with a value of int referring to a data location), particularly lists. Their behavior is similar to a database cursor.
```markdown
next(value, number) // is an iterator that returns... value + number;
prev(value, number) // is an iterator that returns... value - number;
```
#### Internal iterators : 
Higher order functions such as map, reduce etc., that are implementing the traversal across a container, applying the given function to every element. 
#### External iterators and the iterator pattern : 
The primary purpose of an iterator is to allow a user to process every element of a container while isolating the user from the internal structure of the container. It may be thought of as a type of pointer that has two primary operations: referencing one particular element in the object collection (called element access), and modifying itself so it points to the next element (called element traversal).
## Multiplicative : 
Tending to have the power to multiply and relating to, or associated with a mathematical operation of multiplication.
#### Example : 
The multiplicative property of 0 requires that…
    a × 0 = 0 and 0 × a = 0.
## Main Memory : 
It holds two instructions a program can initiate. 
#### Violate : 
To erase when the program terminates of when the computer turns off. 
#### Random Access Memory (RAM) : 
When the CPU accesses data and instructions from any memory location. 
## Notational Conventions : 
expression terms and factor and expression is the start symbol.  
#### Terminals : 
Lowercase letters early in the alphabet such as (a, b, c). Operator symbols like (+, -, *, /). Punctuation symbols such as (parentheses, comma, etc.). The digits (0, 1, 2). Boldface strings such as (id, if); each represents a single terminal symbol. 
#### Non-terminals : 
Uppercase letters early in the alphabet such as (A, B, C). The letter S which when it appears is usually the start symbol. Lowercase italic names such as expr or stmt. When discussing programing constructs, uppercase letters may be used to represent non-terminals for the constructs; For example, non-terminals for expression terms and factors are often represented by (E, T, and F) respectively. 
## Polynomial : 
An expression consisting of variables and coefficients that involves only the operations of addition, subtraction, multiplication, and non-negative integer exponents of variables. 
#### Non-polynomial (complexity) : 
A set or property of problems for which no polynomial-time algorithm is known. Increasing the complexity or answer to a non-polynomial problem only requires a few steps like simply increasing the input by a small amount.
#### Example: nˆ2  
## Sorting Algorithms : 
#### Bubble Sort :
```markdown
void bubble_sort (vector<int> & v, int n){
    for (int i = n-1; i > 0; i--){
        for (int j = 0; j < i; j++){
            if (v[j] > v[j+1]){
                swap(v[j], v[j+1]);
            }   
        }
    }
}
```
#### Selection Sort : 
```markdown
void selection_sort (vector<int> & v, int n){
    for (int i = 0; i < n-1; i++){
        for (int j = i+1; j < n; j++){       
            if (v[i] > v[j]){
                swap(v[i], v[j]);
            }
        }
    }
}
```
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/NoelBram/TMBN-Project/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files*)


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

.md file 
to show code '```markdown'

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

## Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/NoelBram/TMBN-Project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

## Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.




