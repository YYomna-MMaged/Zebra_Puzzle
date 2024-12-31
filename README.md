# Logic-Based Solution to the Potter Family Puzzle

## Project Overview
This project is a solution to a simplified version of the Zebra Puzzle, involving logical reasoning about the Potter family. The solution applies Propositional Logic and First-Order Logic (FOL) techniques to represent the facts, rules, and queries related to their hobbies, favorite desserts, and dreams. The program answers questions about the family using Python and inference algorithms from the AIMA Python library.

## Problem Description
The puzzle introduces the Potter family and their relative Aunt Polly. Each family member has unique hobbies, dessert preferences, and aspirations. The solution needs to:

1. Identify who likes Napoleon cake.
2. Determine who dreams of visiting Paris.

## Logic Representations Used
1. First-Order Logic (FOL):
    - Used to model relationships among family members and their hobbies or dreams.

2. Propositional Logic:
    - Used to model binary facts about hobbies, desserts, and dreams.

## Queries
- Query 1: Who likes Napoleon cake?
- Query 2: Who dreams of visiting Paris?

## Code Implementation
The solution uses the AIMA Python library for logic representation and inference. The core components include:

1. Knowledge Base (KB):
- Initialized using FolKB for FOL and PropKB for propositional logic.
- Populated with facts and rules as clauses.
2. Inference:
- Implemented using fol_fc_ask for FOL.
- Used dpll_satisfiable and pl_resolution for propositional logic queries.