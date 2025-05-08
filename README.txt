#include <stdio.h>

int main() {
    // Define a string
    char *str = "\\Hello World";

    // Print the original string
    printf("Original string: %s\n", str);
    printf("Each character XOR with 0:\n");

    // Loop through each character in the string
    int i;
    for (i = 0; str[i] != '\0'; i++) {
        char ch = str[i];          // Current character
        char result = ch ^ 0;      // XOR with 0 (no change in value)

        // Print the character and the result of XOR
        printf("Character: %c\tXOR Result: %d\n", ch, result);
    }

    return 0;
}
