# WPF Register Student Project Reflection

**Briefly summarize the requirements and goals of the application you developed. What user needs was this application designed to address?**
The goal of this application was to create a program where students could register for IT courses while following specific business rules. It addressed the need for a simple system that prevents double booking and caps the maximum number of credits a single student can take.

**What did you do particularly well in developing this application?**
I did a good job of organizing the logic inside the button click event so that the program checks all the business rules before confirming the registration.

**Compare and contrast the Console and WPF application designs. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**
The Console app was entirely text-based and ran linearly, whereas the WPF app uses a graphical interface and waits for the user to click buttons (event-driven). The WPF app needed a dropdown for easy class selection, a listbox to show what was already selected, and a label to provide instant feedback. These designs kept the user in mind by making the process visual and preventing them from typing in invalid course names, which made the program much more successful and user-friendly.

**How did you approach the process of debugging and coding your application? What techniques or strategies did you use? How could you use those techniques or strategies in the future?**
I approached coding by breaking down the requirements and tackling the validation rules one by one using simple `if` statements. When things didn't work, I reviewed the logic flow and made sure my variables were updating correctly. In the future, I can use this step-by-step strategy to slowly build up more complex software without getting overwhelmed.

**Where did you have to be innovative to overcome a challenge in the full application development process?**
I had to be innovative when making sure the error messages were noticeable to the user. I decided to change the label's foreground color to red for errors and black for successful confirmations, which provided much clearer feedback than just changing the text alone.
