# C++

Historical C++ coursework and personal practice projects covering programming fundamentals, data structures, algorithms, and a Tic-Tac-Toe experiment. Original work by [David Tom](https://github.com/davidtomofficial).

**Status: Historical educational examples.** The setup notes and project descriptions reflect the original work; compatibility and correctness have not been revalidated against current environments.

## File descriptions

The descriptions below record original learning objectives and intended features. Build behavior, memory use, and performance figures have not been revalidated.

- Vowel Counter: [midtermB.cpp](../../coursework/cpp/csn/cs135/2023/midtermB/midtermB.cpp)
    - file streams
    - selection statements

- Book Cipher: [pa08.cpp](../../coursework/cpp/csn/course-unconfirmed/2023/pa08/pa08.cpp)
    - functions
    - arrays
    - file streams

- Grade Calculator: [pa09.cpp](../../coursework/cpp/csn/course-unconfirmed/2023/pa09/pa09.cpp)
    - functions
    - structs
    - command line arguments

- Grade Report: [finalB.cpp](../../coursework/cpp/csn/course-unconfirmed/2023/finalB/finalB.cpp)
    - functions
    - arrays
    - file streams
    - structs

- Pointer and DNA Nucleotides: [pa13a.cpp](../../coursework/cpp/csn/cs202/2023/pa13/pa13a.cpp)
    - Makefile
    - stream overloads
    - pointers
    - vectors
    - arrays
 
 - Pointer and Grade Calculator: [pa13b.cpp](../../coursework/cpp/csn/cs202/2023/pa13b/pa13b.cpp)
    - Makefile
    - pointers
    - vectors
    - arrays
  
- Pointer and Word Counter: [pa14.cpp](../../coursework/cpp/csn/cs202/2023/pa14/pa14.cpp)
  - Makefiles
  - stream overload functions
  - pointers
  - vectors
  - structs
  - no memory leaks
  - selection statements
  - selection sort algorithm

- Recursive Demonstration: [pa15.cpp — reference archive](../../RIGHTS-AND-PROVENANCE.md#material-retained-in-reference-archives)
  - proper code documentation
  - proper implementation of Makefiles
  - recursive functions
  - pointers
  - vectors
  - no memory leaks
  - selection statements
  - selection sort algorithm
  - and an appropriate output based on the validity of the program's operation.

- Iterators, Sorting, and Searching Algorithms: [pa16.cpp](../../coursework/cpp/csn/cs202/2023/pa16/pa16.cpp)
  - proper code documentation
  - proper implementation of Makefiles
  - iterators
  - sorting algorithms (ie. bubble sort, selection sort, insertion sort, and std::sort)
  - searching algorithms (ie. sequential sort & binary sort)
  - pointers
  - vectors
  - structs
  - no memory leaks
  - and an appropriate output based on the validity of the program's operation.

- Linked Lists and Templates: [pa17b.cpp](../../coursework/cpp/csn/cs202/2023/pa17b/pa17b.cpp)
    - proper code documentation
    - proper implementation of Makefiles
    - linked lists
    - template files
    - no memory leaks
    - and an appropriate output based on the validity of the program's operation.

- Stacks and Infix/Postfix Notation: [pa18.cpp](../../coursework/cpp/csn/cs202/2023/pa18/pa18.cpp)
    - proper code documentation
    - proper implementation of Makefiles
    - iterators
    - linked lists
    - stacks
    - infix/postfix notations
    - no memory leaks
    - selection statements
    - and an appropriate output based on the validity of the program's operation.

- Personal Projects - Tic Tac Toe: [Tic-Tac-Toe.cpp — reference archive](../../RIGHTS-AND-PROVENANCE.md#material-retained-in-reference-archives)
  - proper code documentation
  - AI vs AI, AI vs Human, and Human vs Human
  - AI Algorithms: Minimax with Alpha-Beta Cut Off & Random Selections
  - dynamic game board size
  - customizable AI game counts
  - benchmarking function
  - bounds checking and input verification
  - pointers
  - vectors
  - structs
  - no memory leaks
  - and an appropriate output based on the validity of the program's operation.

## Getting Started

Clone/download the files and any dependencies for your project then compile and run the programs using the linux command:
  - "$ c++ $CXXFLAGS [programName.cpp] -o [programName]"
  - "./[programName]

### Prerequisites

In order to run any C++ based programs you must first have installed C++ and its dependencies on a device that can compile
and run the program.  You can install the appropriate software many ways:
1. Visual Studio
2. Geany
3. Repository: Most if not all linux distros have a repository containing the necessary software that can be accessed using the
   below example commands (more information can be found by accessing the manual/help page for your operating system):
   - For Debian/GNU Linux:
         - "$ sudo apt install build-essential"
   - RHEL
         - "$ sudo dnf install build-essential"

Occasionally programs may require dependencies; the easiest way to properly install them is by searching GitHub repositories
and cloning/downloading the appropriate files for your project.  This can be done in:
    - a web browser
    - **or**
    - through the "git clone ssh://git@github.com/[username]/[repository-name].git" command
Once downloaded, import the library and restart your IDE.

### Example installation
1. Download the appropriate dependencies and software
2. Install as needed
3. Import any libraries/dependencies for your project (most projects will state this in the first few lines)
4. Clone the files from the repository
5. Upload the code to your device (laptop, Desktop, etc.).
6. Contribute to further developments.
7. Repeat as needed

## Contributing

See the repository-local [contribution guide](CONTRIBUTING.md) for reporting issues and submitting focused pull requests while preserving the educational context.

## Authors

* **David Tom** - *Initial Work* - [davidtomofficial](https://github.com/davidtomofficial)

The [source manifest](../../SOURCE-MANIFEST.json) records original revisions and paths. Full original history remains in the reference archives. Additional authors and course-provided material remain credited in their respective files.

## License

The existing licensing statement is retained:

> This project is licensed under the GNU General Public License Version 3.

Read the [GNU GPL version 3 text](https://www.gnu.org/licenses/gpl-3.0.html). This repository currently has no local `LICENSE` file. Earlier READMEs linked to a license in the separate GitHub profile repository; that file is not a project-local license.

Some bundled material has separate attribution: [linked-list tests — reference archive](../../RIGHTS-AND-PROVENANCE.md#material-retained-in-reference-archives) and [stack tests — reference archive](../../RIGHTS-AND-PROVENANCE.md#material-retained-in-reference-archives) credit Kevin Mess, and [Vector.h — reference archive](../../RIGHTS-AND-PROVENANCE.md#material-retained-in-reference-archives) describes material adapted from the CSN CS202 shared directory. Those attributions must be preserved; this update does not establish permission to relicense third-party material.

Existing file-specific notices and third-party attribution remain unchanged. The maintainer still needs to document the scope of the repository-level statement, confirm the version wording where file-specific notices do not already settle it, and add the appropriate local license text. This documentation update does not change existing licensing terms.

## Acknowledgements

* A big thanks to any and all contributors, no matter how big or small the contribution it all helps.
