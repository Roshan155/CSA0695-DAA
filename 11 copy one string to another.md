#include <stdio.h>
#include <string.h>

int main() {
    char source[100], destination[100];
    printf("Enter the source string: ");
    fgets(source, sizeof(source), stdin);
    strcpy(destination, source);
    printf("Copied string: %s", destination);
    printf("\n\n\nRoshan    192210659\n");

    return 0;
}
![Screenshot 2024-09-10 132033](https://github.com/user-attachments/assets/646429e9-15dc-49a5-952a-1dfa520e4ac4)
