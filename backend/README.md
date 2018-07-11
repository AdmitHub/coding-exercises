# Exercise 1

Given the following multi-message "Dialog", how would you represent this in code using a Dialog and a State class?

![Sample Dialog](SampleDialog.png "Image of Sample Dialog")

_Feel free to use the programming language of your choice and do not worry about database persistence._

# Exercise 2

Write a function that takes as parameters a Dialog and a User object and returns the number of messages sent to the user.

The User class has the following relevant attributes:

 - `school_year`: a string or enum containing FRESHMAN, SOPHMORE, JUNIOR, SENIOR
 - `is_transfer`: a boolean that's `true` for transfer students
 - `current_state`: a reference to a specific `State` object in a `Dialog`

_Assume that Dialogs would be consistent with the sample Dialog from Exercise 1._

# Exercise 3

Write a function that takes a string parameter and returns the character count (in the context of SMS mesages)

More info: https://www.quora.com/Why-does-using-emoji-reduce-my-SMS-character-limit-to-70

Sample emojii from Exercise 1: ⛱🍦🌞🍉🏫🎓