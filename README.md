# dismathportfolio-Samantha Dianne Samson EK
dismathportfolio-SamSamson987 created by Classroom for GitHub

#WEEK 1

  ➤ Orientation about the course **DISMATH** (Discrete Mathematics)
  
  ➤ Introduction of some applications of Dismath in certain word problems
  
      E.g. Knights and Knaves
 
  ➤ Introduction to **Logical Operations**

| Logical Symbol  |  Logical Operator | Shorthand | Logical Expression |
| :-----: |:-------:|:-----:| :-------: |
| ¬ |Negation | not | ¬p |
| ∧ | Conjunction | and | p ∧ q |
| v | Disjunction | or | p v q |
| ⊕ | Exclusive Disjunction | xor |  p ⊕ q |
| → | Conditional | if, then | p → q |
| ↔ | Biconditional | iff | p ↔ q |
  
  ➤ The truth table for **Conjunction**, **Disjunction**, **Exclusive Disjunction**, **Conditional**, **Biconditional** (T & F) or (1 & 0)
  
| p | q | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q |
| :-----: | :-----: | :-----: |:-------:|:-----:| :-------: | :-------:|
| F | F | F | F | F | T | T |
| F | T | F | T | T | T | F |
| T | F | F | T | T | F | F |
| T | T | T | T | F | T | T |

  ➤ **Propositional Logic:** (p → q)
  
    ∙ is the area of logic dealing with propositions.
  
       ✓ Inverse: ¬p → ¬q
  
       ✓ Converse: q → p
  
       ✓ Contraposition: ¬q → ¬p 
  
#WEEK 2

  ➤ **Logical Equivalences** are the rules that can help in simplifying a given proposition
  
    ∙ Identity Law
        ✓ p ∧ T ≡ p
        
        ✓ p ∧ F ≡ p
    
    ∙ Domination Law
    
        ✓ p v T ≡ T  
        
        ✓ p ∧ F ≡ F 
        
    ∙ Idempotent Law
    
        ✓ p v p ≡ p 
        
        ✓ p ∧ p ≡ p 
    
    ∙ Double Negation Law
        
        ✓ ¬(¬p)≡ p 
        
        
    ∙ Commutative Law
    
        ✓ p v q ≡ q v p
        
        ✓ p ∧ q ≡ q ∧ p 
    
    ∙ Associative Law
        
        ✓ (p v q) v r ≡ p v (q v r) 
        
        ✓ (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)
        
    ∙ Distributive Law
        
        ✓ p v (q v r) ≡ (p v q) v (p v r)
        
        ✓ p ∧ (q ∧ r) ≡ (p ∧ q) ∧ (p ∧ r) 
        
    ∙ De Morgan's Law
        
        ✓ ¬(p ∧ q) ≡ ¬p ∧ ¬q
        
        ✓ ¬(p v q) ≡ ¬p v ¬q 
        
    ∙ Absorption Law
        
        ✓ p v (p ∧ q) ≡ p 
        
        ✓ p ∧ (p v q)≡ p 
        
    ∙ Negation Law
        
        ✓ p v ¬p ≡ T
        
        ✓ p ∧ ¬p ≡ F 

  ➤ **Rules of Interference** are used to test the validity of arguments.
  
|          Name              |            Equivalent          |
|:--------------------------:|:------------------------------:|
|       Modus ponens         |            p, p→q ∴q           |
|     Modus tollens          |           ¬q, p→q ∴ ¬p         |
|     Hypothetical syllogism |       p → q, q → r ∴p → r      |
|      Disjunctive syllogism |           p ∨ q, ¬p ∴q         |
|       Addition             |            p ∴p ∨ q            |
|      Simplication          |            p ∧ q ∴p            |
|      Conjunction           |          p, q ∴p ∧ q           |
|        Resolution          |       p ∨ q, ¬p ∨ r ∴q ∨ r     |

 ➤ **Quantifiers**
 
    • Universal Quantifier
   
      - "for all"
   
      - Symbol: ∀(x)
   
    • Existential Quantifier
   
      - "there exist"
   
      - Symbol: ∃(x)

#WEEK 3

  ➤ Introduction to **Methods of Proof**
    
    ∙ Direct Proof:
    
       First Step: Assume that "p" is TRUE
    
       Second Step: Show that "q" is also TRUE

    ∙ Indirect Proof:
    
        First Step: Assume that "¬q" is TRUE
        
        Second Step: Show that "¬p" is also TRUE
        
    ∙ Proof by Contradiction:
        
        First Step: Assume that the "antecedent" is FALSE
        
        Second Step: Using an assumption and other facts show that it is a contradiction
        
    ∙ Proof by Contraposition:
    
        First Step: Assume that the "premise" is FALSE
        
        Second Step: Using an assumption and other facts show that it is a contraposition
        
#WEEK 4

  ➤ **Mathematical Induction**
     
      - A means of proving a theorem by showing that if it is true of any particular case, it is true of the 
      
      next case in series, and then showing that it is indeed true in one particular case.
        
  
      - It is a form of direct proof, and it is done in two steps. The first step, known as the Basic Step, is 
      
      to prove the given statement for the first natural number. The second step, known as the 
      
      Inductive step,it is to prove that the given statement for any one natural number implies the given 
      
      statement for the next natural number.  
      
  ➤ **Summation**
  
      - Symbol: ∑
      
      - Is the addition of a sequence of numbers; the result is called the sum or the total. 
  
  ➤ **Recursive/Inductive**
  
      - An algorithm that solves a problem by reducing it to a simpler input.
      
      Steps:
      
      1.) Basic Step
       
          - Specify the value of a given as a function a "0" 
      
      2.) Recursive Step
      
          - Create a rule in finding its value at a certain integer from its values at smaller integers.
          
#WEEK 5

  ➤ **Program Correctness**
  
    •Includes 2 steps:
    
      1.) Partial correctness
         
          - initial assertion(input)
          
          - final assertion (output)
    
      2.) Show that the program terminates correctly
  
  ➤ **Hoare Triple**
  
      •Symbol: p{S}q
      
         note:
          
           - p = initial assertion
         
           - {S} = program segment
         
           - q = final assertion
           
      • Steps:
      
        1.) Assume tha p is TRUE
        
        2.) Substitute to the program {S}, showing that q is TRUE
  
  ➤ **Power Series**
  
      - Example: Zeno's Paradox
      
      - Can be solved using GEOMETRIC SERIES formula:
      
        a1/ 1-r
  
  ➤ **Introduction to set theory**
  
      • Set
      
         - Is an unordered collection of objects
        
            a.)Set Difference
            
                 - (A-B) or (A/B)
                 
            b.) Set Intersection
            
                 - A△B
                 
      • Power Set
      
          - Is a set containing all subsets 
  
#WEEK 6 
 
  ➤ **Cardinality**
    
    • Is the total number of distinct elements.
    
    •  New Terminology:
        
        ✓ ℵ₀ 
           
          -is pronounced as “aleph-zero"/“alephnought”/“aleph-null”
  
  ➤ **Review**
  
   • Nested Quantifiers
   
      - 2 quantifiers are nested if one is within the sccope of the other.
      
      - Examples:
      
          ✓ ∀x∀y(x≠y) 
          
          ✓ ∃x∃y(x≠y)
          
          ✓ ∀x∃y(x≠y)
          
          ✓ ∃y∀x(x≠y)
  
  ➤ **Functions**
    
    • Types:
      
       ✓ One-to-one function
       
          - each domain is assigned to a certain co-domain
          
          - no common co-domain
       
       ✓ Onto Function
       
         - each co-domain is assigned to a domain.
         
         - no co-domain is left without a partner. 

#WEEK 7

➤ No Classes for the whole week

#WEEK 8

➤ **Algorithm**

    - is a finite set of precise instruction
    
       ✓ Precondition
    
           - describes the input
    
       ✓ Postcondition
    
           - describes what the output should satisfy
    
        ✓ Properties:
      
           • Input
      
           • Output
      
           • Definiteness
      
           • Correctness
      
           • Finiteness
           
           • Generality
    
➤ **Psuedocode**

    - is a high level description of an algorithm that uses the structural conventions of programming knowledge

#WEEK 9

➤ **Seaching Algorithm**

    - The problem of locating an element in an ordered list

➤ **Linear Search**

    - Precondition: ({A1,A2,...,Ai,...An})
    
      Postcondition: location of x (loc)
      
      i=1
      
      while [(x≠A)^(i≤n)]
       
          i = i+1
        
        if(i≤n)
          
          loc = i
        
        else
        
           loc = -1

➤ **Binary Search**

    -  Precondition: ({A1,A2,...,Ai,...An})
    
       Postcondition: location of x (loc)
    
          while [(i≠j) ≠ (i>j)]
              
             mid = [(i+j)/2]
             
                if x>A(mid) 
                   
                   then i = 1+mid
                   
                else j=mid
                
                if (x==Ai)
                
                    loc=i
                
                else 
                
                   loc = -1;
    
#WEEK 10

➤ **Sorting Algorithm**

    - the problem of putting elements in increasing order

➤ **Bubble sort**

    - Precondition: ({A1,A2,...,Ai,...An})
    
      Postcondition: (X1<X2<...<Xn)
      
          for j: 1 to n-1
      
             for i: 1 to n-j
        
                if(Ai > Aj+1)
          
                   swap (Ai,Ai+1)

➤ **Insertion sort**
 
    - Precondition: ({A1,A2,...,Ai,...An}) ∈ n≥2 for j= 2 to n
    
      Postcondition: (X1<X2<...<Xn)
      
          for j = 2 to n
              
              i = 1
              
          while Aj>Ai
            
              i = i+1
              
           m = Aj
           
           for k = 0 to j-i-1
           
            Aj-k = Aj-i-1
          
          Ai = m

➤ **Greedy Algorithm**
  
  - Selects the best choice instead of considering all sequences
 
  - applied in optimization problems

  - Precondition: ({C1,C2,...,Ci,...Cn})
    
      Postcondition: (C1>C2>...>Cni n ∈ Z+) 
      
          for i = 1 to 4 
      
            while(n≥Ci)
        
                n = n-Ci
          
                   n = n+1

#WEEK 11

➤ **Growth of Functions**

    - is often described using the big o notation

➤ **Big O Notation**
    
    - Let f and g be functions from R to Ri f(x) is O(g(x)) if there are constants c and k such that 
       
       |f(x)|≤ C|g(x)| whenever x>k

➤ **Big Omega**

    - lower bound of a function
    
➤ **Big Theta**

    - lower and upper bound of a function
   
➤ **Complexity of Algorithms**

    - can be expressed in term of the number of operationsused by the algorithm when the input has a particular size

#WEEK 12

➤ No Classes for the whole week

#WEEK 13

➤ **Graph Theory**

    - consist of vertices/nodes and degrees/edges

➤ **Handshaking Theorem**

    - formula: 2e = Σ(degrees)*v
    
➤ **Euler Path**

    - covers all the edges/degrees
    - is open 
    - has a different starting and ending point
    
➤ **Euler Circuit**

    - covers all the edges/degrees
    - is closed 
    - has the same starting and ending point
    
➤ **Hamilton Path**

    - covers all the nodes/vertices
    - is open
    - has a different starting and ending point
    

➤ **Hamilton Circuit**

    - covers all the nodes/vertices
    - is closed
    - has the same starting and ending point

➤ **Matrices**

    • Adjacency Matrix
       - relationship between the nodes/vertices
       
    • Incidence Matrix
       - relationship between the edges/degrees

➤ **Isomorphism**

    - is the comparison of 2 graphs

➤ **Planar**

    - is a plane that has no intersecting lines/edges/degrees

➤ **Non-Planar**

    - is a plane that has intersecting lines/edges/degrees

➤ **Euler's Formula**

    - formula: r = e(edges) - v(vertices) + 2

#WEEK 13

➤ **Graph Coloring**

    - is the assignment of colors to each node in a graph considering the adajaceny relationship between them.
    
    • Chromatic Number
    
       - is the least number of colors needed in coloring a graph
       
     • Four color Theorem
     
       - states that the chomatic number of a planar graph should not be grater than 4

➤ **Trees**

     - is simply an undirected graph
     
     - it has no circuit in it
  
     • Rooted tree
     
        - is a tree by which a node is assigned as the root and has edges that is directed away from it
        
    • Subtree
       
       - is a branch-like part of the main tree 

➤ **Language and Grammar**

     -

➤ **Finite State Machine**




