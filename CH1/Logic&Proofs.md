# Logic  and Proofs

## Propositional Logic / Propositional Calculus

**Proposition** (命题) : A proposition is a declarative sentences that is either true or false, but not both.

**Truth Value** (真值) : The true value of a true (or false, respectively) proposition is True (or False, respectively) and denoted by T (or F, respectively).

**Propositional Variables** (or **Sentential Variables**)  are variables that represent propositions, e.g., $p,q,r,s,\cdots.$  

**Compound Propositions** (复合命题) : propositions that are formed from existing propositions using Logical Operations.

### Logical Operations

**Truth Tables** (真值表)

**Negation Operator** (否定): Let $p$ be a proposition, $\neg\ p$ (or $\overline{p}$), the negation of $p$, is the statement "It is not the case of $p$". It can be read as "not $p$".

| $p$  | $\neg p$ |
| ---- | -------- |
| T    | F        |
| F    | T        |

**Conjunction Operator** (且): Let $p$ and $q$ be propositions, $p \and q$, the conjunction of $p$ and $q$, is the proposition "$p$ AND $q$".

| $p$  | $q$  | $p\and q$ |
| ---- | ---- | --------- |
| T    | T    | T         |
| T    | F    | F         |
| F    | T    | F         |
| F    | F    | F         |

**Disjunction Operators** (或): Let $p$ and $q$ be propositions, $p \or q$, the disjunction of $p$ and $q$, is the proposition "$p$ OR $q$". 

| $p$  | $q$  | $p\or q$ |
| ---- | ---- | -------- |
| T    | T    | T        |
| T    | F    | T        |
| F    | T    | T        |
| F    | F    | F        |

**Exclusive OR** (异或): Let $p$ and $q$ be propositions, $p \oplus q$, is the proposition "$p$ XOR $q$".

| $p$  | $q$  | $p\oplus q$ |
| ---- | ---- | ----------- |
| T    | T    | F           |
| T    | F    | T           |
| F    | T    | T           |
| F    | F    | F           |

**Conditional Operator** (条件): Let $p$ and $q$ be propositions, $p\rightarrow g$, is the proposition "if $p$, then $q$" (or "$p$ only if $q$" or "$p$ implies $q$"). $p$ is called the *hypothesis* (or *antecedent* or *premise*), and $q$ is called the *conclusion* (or consequence). $p\rightarrow q \equiv \neg q\rightarrow \neg p$.

| $p$  | $q$  | $p\rightarrow q$ | $\neg p$ | $\neg q$ | $\neg q\rightarrow \neg p$ |
| ---- | ---- | ---------------- | -------- | -------- | -------------------------- |
| T    | T    | T                | F        | F        | T                          |
| T    | F    | F                | F        | T        | F                          |
| F    | T    | T                | T        | F        | T                          |
| F    | F    | T                | T        | T        | T                          |

$p\rightarrow q$ : $p$ 是 $q$ 的充分条件，$q$ 是 $p$ 的必要(necessary)条件。 $p$ is sufficient for $q$, $q$ is necessary for $p$.

**Biconditional Operator** (双条件): Let $p$ and $q$ be propositions. The biconditional statement $p\leftrightarrow q$ is the proposition "p if and only if q." $p \leftrightarrow q \equiv (p\rightarrow q)\and (q\rightarrow p)$.

| $p$  | $q$  | $p\rightarrow q$ | $q\rightarrow p$ | $(p\rightarrow q)\and (q\rightarrow p)$ | $p \leftrightarrow q$ |
| ---- | ---- | ---------------- | ---------------- | --------------------------------------- | --------------------- |
| T    | T    | T                | T                | T                                       | T                     |
| T    | F    | F                | T                | F                                       | F                     |
| F    | T    | T                | F                | F                                       | F                     |
| F    | F    | T                | T                | T                                       | T                     |

当且仅当、若且唯若

**Precedence of Logical Operator**

| operator          | prior |
| ----------------- | ----- |
| $\neg$            | 1     |
| $\and$            | 2     |
| $\or$             | 3     |
| $\rightarrow$     | 4     |
| $\leftrightarrow$ | 5     |





