<a href="https://github.com/CyberTrainingUSAF/05-C-Programming/blob/master/00-Table-of-Contents.md" rel="Return to TOC"> Return to TOC </a>

# Assert vs Errno

### Assert
(check for errors that should never happen)

* Valid range of values
* Specific values
* Design by contract
* non-NULL pointers (when the pointer can't be NULL)

### Errno
(Or other error handling techniques)

* Returns from system calls and library functions
* User input data
* Network input data
* File input data
* Out of the system resources or memory

# I/O Functions

I/O functions typically return useful values

Many I/O functions update ERRNO

### DEMO LAB - INPUT

Use appropriate error handling (assert vs errno) to handle I/O errors.

Replicate the error to test your implementations.

---
### COMPLETE PERFORMANCE LAB - OUTPUT

<a href="https://github.com/CyberTrainingUSAF/05-C-Programming/blob/master/15_Error_handling/Performance_Labs/Lab_output.md" rel="OUTPUT"> OUTPUT </a>
