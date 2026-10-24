# DSA Laboratory Programs

12 C programs with sample inputs and actual terminal output.

## Experiments

| No. | Program | Sample run |
| --- | --- | --- |
| 1 | [Array Operations](Experiment-01-Array_Operations/program.c) | [Output](Experiment-01-Array_Operations/output.txt) |
| 2 | [Employee Records](Experiment-02-Employee_Records/program.c) | [Output](Experiment-02-Employee_Records/output.txt) |
| 3 | [Infix to Postfix](Experiment-03-Infix_to_Postfix/program.c) | [Output](Experiment-03-Infix_to_Postfix/output.txt) |
| 4 | [Postfix Evaluation](Experiment-04-Postfix_Evaluation/program.c) | [Output](Experiment-04-Postfix_Evaluation/output.txt) |
| 5 | [Simple Queue](Experiment-05-Simple_Queue/program.c) | [Output](Experiment-05-Simple_Queue/output.txt) |
| 6 | [Priority Queue](Experiment-06-Priority_Queue/program.c) | [Output](Experiment-06-Priority_Queue/output.txt) |
| 7 | [Singly Linked List](Experiment-07-Singly_Linked_List/program.c) | [Output](Experiment-07-Singly_Linked_List/output.txt) |
| 8 | [Circular Queue](Experiment-08-Circular_Queue/program.c) | [Output](Experiment-08-Circular_Queue/output.txt) |
| 9 | [Binary Search Tree](Experiment-09-Binary_Search_Tree/program.c) | [Output](Experiment-09-Binary_Search_Tree/output.txt) |
| 10 | [BFS and DFS](Experiment-10-BFS_and_DFS/program.c) | [Output](Experiment-10-BFS_and_DFS/output.txt) |
| 11 | [Sorting](Experiment-11-Sorting/program.c) | [Output](Experiment-11-Sorting/output.txt) |
| 12 | [Hashing](Experiment-12-Hashing/program.c) | [Output](Experiment-12-Hashing/output.txt) |

## Files

Each experiment folder contains `program.c`, `input.txt`, and `output.txt`.
`output.txt` is a real interactive terminal transcript including typed input.
`All_Codes_and_Outputs.md` puts every program and its output into one readable file.

## Compile and run

Open a terminal in the experiment folder. With GCC installed:

```sh
gcc -std=c11 program.c -o program -lm
./program
```

On Windows with GCC, run `program.exe` instead of `./program`.
To use the provided input on Linux/WSL: `./program < input.txt`.
Redirected input does not echo back, so the layout differs from the interactive transcript.

## Source and scope

Transcribed from the SCSVMV Data Structures and Algorithms Laboratory Manual,
prepared by PREETHI R, Assistant Professor, Department of CSE.
PDF headers/footers were removed and wrapped strings / pointer operators repaired.
The manual's algorithms and behavior were retained. Sample output was regenerated
from the compiled code rather than copied from the PDF. In particular, the employee
program exits silently, although the PDF sample includes an exit message.

All 12 programs compiled with GCC in C11 mode and passed the included sample run.
These are teaching examples, not fully validated applications: use well-formed
inputs within array capacities. The infix example uses single-character operands
and treats repeated `^` operators as left-associative as in the manual; the postfix
example uses single-digit operands. General invalid-input behavior is not tested.

## Upload to GitHub

1. Extract the downloaded ZIP.
2. Open the extracted `DSA-Lab` folder.
3. In your GitHub repository, choose **Add file > Upload files**.
4. Drag the contents of `DSA-Lab` into the upload area and commit the changes.

If your assessment specifically requires screenshots, run the programs on your
computer and add your own terminal screenshots to the matching experiment folders.
