**Objective:**
The objective was to develop a Lexical Analyzer using C++ that reads a source code file, identifies lexemes, and converts them into corresponding tokens based on predefined regular expressions.

**Implementation:**
**Language Used**: C++
**Approach:**

**Lexeme Identification:** The program reads the source code from input.txt line by line, and for each line, it scans for patterns that match the regular expressions provided in Table 1 of the course material.

**Token Generation**: Upon identifying a lexeme, the program converts it into the corresponding token and stores this in output.txt.

**Key Features:**

**Transition Table:** A transition table was used to manage state transitions during lexeme scanning. This table maps character sequences to specific states, allowing the analyzer to determine the correct token for each lexeme.

**Regular Expressions:** The program uses regular expressions to match specific patterns in the source code and generate tokens accordingly.

**Output:** The sequence of tokens identified by the Lexical Analyzer is written to output.txt in a format that associates each token with its corresponding lexeme.

**Testing:**
The implemented Lexical Analyzer was tested using the provided sample input, and it successfully generated the correct sequence of tokens in the output file.

**Submission:**
The transition table, source code, and the input and output files are included as part of the submission.
