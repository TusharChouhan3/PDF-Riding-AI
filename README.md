# PDF-Riding-AI
Ai

#include <stdio.h>   // Includes input and output functions

// Function to display the application menu
void showMenu()
{
    printf("\n");
    printf("====================================\n");
    printf("       PDF READING TEACHER AI       \n");
    printf("====================================\n");

    printf("1. Read Study Material\n");
    printf("2. Ask AI Teacher\n");
    printf("3. Search Topic\n");
    printf("4. Save Notes\n");
    printf("5. Practice MCQ\n");
    printf("6. Exit\n");

    printf("====================================\n");
}

// Main function: execution starts here
int main()
{
    int choice;  // Stores the user's selected option

    // Keep showing the menu until the user exits
    do
    {
        showMenu();  // Display the application menu

        // Ask the user to enter a choice
        printf("\nEnter your choice: ");
        scanf("%d", &choice);

        // Check which option the user selected
        switch(choice)
        {
            case 1:
                printf("\nOpening Study Material...\n");
                break;

            case 2:
                printf("\nWelcome to AI Teacher!\n");
                break;

            case 3:
                printf("\nTopic Search Selected.\n");
                break;

            case 4:
                printf("\nNotes Section Selected.\n");
                break;

            case 5:
                printf("\nPractice MCQ Selected.\n");
                break;

            case 6:
                printf("\nThank you for using PDF Reading Teacher AI!\n");
                break;

            default:
                printf("\nInvalid choice! Please try again.\n");
        }

    } while(choice != 6);  // Repeat until option 6 is selected

    return 0;  // End the program successfully
}
