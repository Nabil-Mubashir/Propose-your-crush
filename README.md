#include <stdio.h>
#include <string.h>

int main() {
    char answer[10];

    while (1) {
        printf("Do you love me? ");
        scanf("%s", answer);

        if (strcmp(answer, "yes") == 0) {
            printf("I also love you, cutie! ❤️\n");
            break;
        } else {
            printf("You entered the wrong answer. Try again. 😢\n");
        }
    }

    return 0;
}
