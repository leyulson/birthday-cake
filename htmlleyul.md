#include <iostream>
#include <stdio.h>



void drawCake() {
    std::cout << "             i\n";
    std::cout << "            |~|\n";
    std::cout << "           |~~~|\n";
    std::cout << "         |~~~~~~|\n";
    std::cout << "       |~~~~~~~~~~|\n";
    std::cout << "     |~~~~~~~~~~~~~~|\n";
    std::cout << "    |~~~~~~~~~~~~~~~~~|\n";
    std::cout << "  |~~~~~~~~~~~~~~~~~~~~~|\n";
    std::cout << "|~~~~~~~~~~~~~~~~~~~~~~~~~|\n";
    std::cout << "-----------------------------\n";
    std::cout << "      Happy Birthday!\n";
}

int main() {
    drawCake();
    
    char s[100];
        
    
    printf("\n");
    printf("Enter your name : ");
    scanf("%s", &s);
    printf("\n");
    printf("So, You are %s ?\n", s);
    printf("Hmmmmmmmm, Happy Birthday!\n");
    printf("\n");
    printf("I hope all your wishes come true today, %s!!\n", s);
    printf("I think you're supposed to get finer and wisher with age?\n");
    printf("Well, that's okay, there's always next year :D\n");
    printf("\n");
    
    printf("Apa lagi ya... udah deh, HBD pokoknya. please bngt ya, jngn lupa temen :v\n");
    printf("Sukses dan kuat di dunia kedokteran, i'll always be here to hear your stories.\n");
    printf("\n");
    printf("Bye, %s from tepho!",s);
    return 0;
}
