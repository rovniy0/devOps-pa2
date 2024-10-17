## Requirements

### 1. Create GitHub Repository:
- Create a new GitHub repository and clone it to your local directory.

### 2. Implement the initial version of the function:
- Create a C++ source code suite:
  - Implement a class with a public function `FuncA()` in `FuncA.cpp` and `FuncA.h`.
  - The initial implementation of `FuncA` should return `0`.
  - Create a `main.cpp` file that instantiates the class and calls the function.
- Push the code to the `master` branch.

### 3. Branch out and work on the sequence sum:
- Create a new branch called `branchA`.
- In `branchA`, update the implementation of `FuncA` to calculate the sum of the first `n` elements of an infinite sequence (where `n` is passed as a function argument).
- Stash your changes.

### 4. Hotfix branch:
- Branch out from `master` and create a new branch named `hotfix`.
- In the `hotfix` branch, update the implementation of `FuncA` to return the sum of the first 3 elements of the infinite sequence.
- Commit the changes and push them to the repository.

### 5. Merge Hotfix to Master:
- Merge the `hotfix` branch into the `master` branch.

### 6. Finalize changes in branchA:
- Switch back to `branchA` and pop your stashed changes.
- Complete the implementation of the function. Add comments explaining the parameter meaning (e.g., `n` is the number of elements to sum).
- Commit and push the changes.

### 7. Resolve Merge Conflicts:
- Switch to the `master` branch, pull the latest updates, and attempt to merge `branchA` into `master`.
- Resolve any conflicts that arise, ensuring the changes from `branchA` take priority.
- Take a screenshot of the `vimdiff` or 3-way merge view when resolving conflicts.

### 8. Final Log:
- Take a screenshot/photo showing the history log of all branches.