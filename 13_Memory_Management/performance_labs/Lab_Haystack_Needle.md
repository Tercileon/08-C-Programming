<a href="https://github.com/CyberTrainingUSAF/05-C-Programming/blob/master/00-Table-of-Contents.md" rel="Return to TOC"> Return to TOC </a>


/*
Haystack Needle Lab

Purpose:
Remove the needle from the haystack
AKA: Move the substring from the string using memory operators and functions

*/

```c

// TODO: Include any needed headers

int haystack_needle(char *haystack, char *needle, char *buffer);
int main()
{
  char string[] = "This is my brand new sentence";
  char substring[] = " brand new";
  // TODO: Create a char buffer named *buffer using malloc \
  ensure it is large enough to hold string[] + a nul-terminator

  // TODO: Ensure buffer was created
  haystack_needle(string, substring, buffer);

  // TODO: Give back the memory from buffer
  // TODO: Print out the modified string

  return 0;

}

/*
Arguments:
-haystack --- pointer to string to search
-needle   --- pointer to substring to search inside of haystack
-buffer   --- pointer to a buffer

PURPOSE:
haystack_needle takes the arguments above and searches the haystack
for the needle. Once it finds the needle... it removes it from the haystack.

Return:
return 0 on success
return -1 on error .... only needed if userinput is enabled.
*/
int haystack_needle(char *haystack, char *needle, char *buffer)

{
    int needleLength = strlen(needle);

    // TODO: Using strstr() find the needle in the haystack (substring in string)\
    the pointer that is returned is pointing to the substring within the string \
    Set that pointer to a new char pointer called *mark_position

    // TODO: Using strcpy(), store the needle into the buffer... \
    you are not authorized to use the variable needle.

    // TODO: Using memmove, overwrite the haystack (string)... effectivly removing the needle \
    // HINT: start at the mark_position... that is after all where we need to start replacing.

    return 0;
}

```

---
<a href="https://github.com/CyberTrainingUSAF/05-C-Programming/blob/master/14_Structs/README.md" rel="Continue to Next Topic"> Continue to Next Topic </a>
