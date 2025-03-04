# What is a Formal Language?
- A **formal language** is a language that consist of words whose letters are taken from an alphabet and are well-formed according to a specific set of rules called **formal grammar**.
# What is Automata?
- Automata are the plural form of **Automaton**.Automaton is a machine which performs a range of functions according to a predetermined set of coded instructions.
# What is Automata Theory?
- Automata theory is the study of abstract computing machines.
- In 1930s Turing studied an abstract machine which is Turing machine.
- Turing aimed that to understand the capabilities of a computational machine.
- 1940s and 1950s finite automata were studied.
- Chomsky began the study of formal grammars.
## Why Study Automata?
- Because it is the core of computer science.
- We must know what a computer can do and cannot do.
- **Undecidable things** – no program whatever can do it.
- **Intractable things** – there are programs, but no fast programs.
### Alphabets
- An alphabet is a finite,non empty set of symbols.
- Symbol of alphabet is ∑.
- ∑={0,1}  -> Binary Alphabet
- ∑={a,b,...,z}  -> Lowercase letters
### Strings
 - A **string** is a sequence of symbols chosen from some alphabet.
 - It sometimes is called as word.
 - 0101 is a string from ∑={0,1}
 - The **empty string**,is a string of zero occurences of symbols.
 - **Length of string** is number of symbols in the string.
 - ∑<sup>k</sup> is the set of strings of length k from ∑.
 - The set of all strings over an alphabet is denoted by ∑<sup>*</sup>.
 - Let ∑={a,b}. ∑<sup>0</sup>={ε},∑<sup>2</sup>={aa,ab,ba,bb}
### Concatenation of Strings
  - If a and b are strings ab represents their concatenations.
  - If a=xyz,and b=cd then ab=xyzcd
  - A set of strings chosen from ∑<sup>*</sup> is called as a **language**.
  - A language over ∑ may not include strings with all symbols of ∑.
  - Empty set is a language.It is denoted by **Φ**.
  - The set {ε} is a language,**{ε} is not equal to the empty language**.
###  Set Formers
  - A **set-former** is a common way to define a language.
  - {w|sth about w},{w| w is a binary integer that is prime.}
### Decision Problem
  - It is the question of deciding whether a given string is a memberof a particular language.
  - If *∑* is an alphabet,and *L* is a lanh-guage over **,theb the decision problem is:
  - Given a string ∑<sup>*</sup>,decide whether or not w is in L.
## Finite Automata
  - **Finite Automata** are finite collections of states with transition rules that take you from one state to another.
  - A **finite automaton** has *finite number of states.*
  - The *purpose of a state* is memory.
  - In a **finite automaton**:
  - **States** are represented by circles.
  - ** Accepting states** are represented by *double circles*.
  - One of the states is a **starting state.**
  - **Arcs** represent *state trasitions* and **labels on arcs** represent *inputs*.
### Deterministic Finite Automaton (DFA)
  - A *DFA* is a quintuple.
  - **A=(Q,∑,δ,q0,F}**
     1. Q is a *finite set of states*.
     2. ∑ is a *finite set of symbols,alphabet*.
     3. Delta is a *transition function*.(q,a)->p
     4. q0 is the *start state*.
     5. F is a set of **final(accepting)states**.
  - δ(q, a) = the state that the DFA goes to when it is in state q and input a is received.
  - **Extended Delta Function** operates on *states* and *strings*.
  -**Language accepted by a DFA** A is the set of all strings that are recognized by A.
  - A language L is *regular* if it is the language **accepted by some DFA**.
  - A language is *regular* if it can be described by a regular expression.
### Non-Deterministic Finite Automaton (NFA)
  - A *nondeterministic finite automaton* can be in several states at once.
#### Extras
   - **XML** is *Extensible Markup Language* and it was designed to carry data.
   - **XML** can be used for data transmitting,web applications,documents,etc.
   - **HTML** is *Hypertext Markup Language* and it was designed to display data.
   - **BFS** is *Breadth First Search* and it is a **graph traversal algorithm**.
   - **DFS** is *Depth First Search* and it is also a **graph traversal algorithm**.We traverse all vertices one by one.
  









  









































  Resources:<br>
  - [Formal Language](https://en.wikipedia.org/wiki/Formal_language)
  - [Lecture Link](https://web.cs.hacettepe.edu.tr/~ilyas/Courses/AIN312/)
    
  
