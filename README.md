**ANSI Color Codes in C**


This repository provides a collection of ANSI color codes in C, allowing you to add colorful and visually appealing text and backgrounds to your console applications. The defined color codes can be used to modify the appearance of text, background, and formatting.

**Usage**

To use the ANSI color codes, include the header file ansi_colors.h in your C program. The color codes are defined as macros, making it easy to use them in your code. Here is an example:


```c
#include "color.h"
#include <stdio.h>

int main() {
    printf(RED "This text is red.\n" RESET);
    printf(BLU "This text is blue.\n" RESET);
    printf(BOLD "This text is bold.\n" RESET);
    printf(BOLD RED "This text is bold and red.\n" RESET);
    
    return 0;
}
```

The ansi_colors.h header file defines various color codes, including regular text colors, bold text colors, underline text colors, background colors, high intensity background colors, high intensity text colors, bold high intensity text colors, and reset codes.

Feel free to experiment with different combinations and styles to enhance the visual appeal of your console applications.

Enjoy. 
