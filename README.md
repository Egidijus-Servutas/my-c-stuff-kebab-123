# My programming standard for the c projects


- Unless something is going to have a complicated type, the name of that thing will usually have a type at the start of the name
- Lowercase will be used for the first letter in the first word in a name, every other word in the name will start with a capital letter
- Underscores mean something is associated with something
- Randomised name that doesn't follow naming convetions, that isn't meant to be used at all or is only meant to be used by something specific
- Pointers will be declared next to the type not next to the name
- Whenever possible, align things to make it more readable unless it becomes unreadable
- Use new lines in sitatuions like using an or (||), for each or
- Use one lines where code shouldn't ever need to be read again or the code doesn't affect readability by being on one line and improves the rest of the code's readability
- Arrows or something that looks like syntax shouldn't be used in comments unless needed or can easily be distinguished between code and comment

To show my standard as examples:


   int intPlayer_health;        // obviously player health
void** voidActivePointers_list; // supposed to be for a pointer that points to a list of pointers
  void voidPlayer_actions ();   // a function
   int a89cry798012c91p02;      // an example of one of the randomised names

// Example one of the standard
if (cheese == food
    || cheese != rock
    && cheese != vegetable
    || cheese != water) {
    printf("Bacon");};

// Example of another
if (voidActivePointers_list == NULL) {return 0;};
