#include <stdio.h>
#include <string.h>

int main() {
    char str[100], rev[100];
    printf("Enter a string: ");
    scanf("%s", str);
    strcpy(rev, str);
    strrev(rev);

    if (strcmp(str, rev) == 0)
        printf("%s is a palindrome.\n", str);
    else
        printf("%s is not a palindrome.\n", str);

    printf("\n\n\nRoshan    192210659\n");
    return 0;
}![Screenshot 2024-09-10 131946](https://github.com/user-attachments/assets/18fdc43a-3e3e-43ad-8a07-97b8878043d8)
