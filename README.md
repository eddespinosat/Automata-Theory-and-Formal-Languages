# Automata-Theory-and-Formal-Languages

This program implements a **lexical analyzer based on finite automata**, using a transition table read from a CSV file. It performs the following tasks:

1. **Normalization**: Converts the keys and values of the transition table to lowercase and adjusts certain values, such as replacing dashes with "error".
2. **String Processing**: Evaluates an input string character by character, following the rules defined in the transition table to determine whether the string is accepted or rejected by the automaton.
3. **User Interaction**: Allows users to input strings and displays the sequence of states traversed, indicating whether the string is accepted or not.

This program is useful for modeling and validating formal languages or patterns defined by a finite automaton.
