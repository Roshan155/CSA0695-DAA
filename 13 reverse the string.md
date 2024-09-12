#include <stdio.h>
#include <string.h>

void reverseString(char str[]) {
    int length = strlen(str);
    for(int i = length - 1; i >= 0; i--) {
        printf("%c", str[i]);
    }
    printf("\n");
}

int main() {
    char str[100];
    printf("Enter a string: ");
    gets(str); 
    printf("Reversed string: ");
    reverseString(str);
    printf("\n\n\nRoshan    192210659\n");

    return 0;
}
![Screenshot 2024-09-10 132229](https://github.com/user-attachments/assets/6a9a3213-85f8-4d7b-abb5-b811618bfae7)
