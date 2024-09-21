# Temporal Logic

Before introducing temporal logic to those unfamiliar with classical logic, we provide a review of classical logic as follows.

## Review of Classical Logic
Briefly, when defining __logic__, it is better to say __logic__ just represents an abstraction of the world.

First, let's define some terms that will be important later.

### Logical Language
A logical language (or formal language) is a formal system consisting of symbols and rules for constructing well-formed formulas. It includes logical symbols (like "∧", "∨", "→", "∀", "∃"), non-logical symbols (predicates, functions, constants), and variables. A logical language defines how statements are written, but it does not interpret their meaning (that’s the role of models).

### Model
In logic, a model is a mathematical structure that gives meaning to the terms, symbols, and statements in a formal language. A model assigns values to variables, interprets function symbols and predicates, and evaluates whether given statements (formulas) are true or false under that interpretation.

### Statement
A statement (also called a proposition) is a declarative sentence in a formal language that can either be true or false. It is a formula without any free variables, meaning it expresses a complete idea or fact.

### Formula
A formula is a syntactically correct expression in a formal language, constructed using symbols from that language according to its formation rules. It can contain variables, constants, functions, and logical connectives. Formulae may represent statements (when they contain no free variables) or predicates (when they have free variables).

### Interpretation
An interpretation assigns meaning to the symbols and terms in a logical language. Specifically, it maps the non-logical symbols (like predicates, functions, and constants) to specific objects, relations, and operations in a model. An interpretation determines whether formulas are true or false in a particular model.

### Inference
An inference is the process of deriving a new statement from existing statements (premises) using a set of rules. In formal logic, the inference rules dictate how one can move from axioms and previously derived statements to new theorems.

### Formal System
A formal system is a set of axioms, rules of inference, and symbols that define a logical structure. It consists of:
* _Axioms_: Assumptions or basic truths within the system.
* _Inference Rules_: The rules that allow new statements (theorems) to be derived from the axioms.
* _Formulas_: Well-formed expressions within the system.


Logic has two branches:
* __Model theory__: Concerned with the interpretation of formal languages and their models.
* __Proof theory__: Focuses on the syntactic structure and formal derivations in logical systems.
