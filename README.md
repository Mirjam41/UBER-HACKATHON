# UberCare
UberCare is an application that aims to provide inclusive modes and services of transport for the citizens of Uberland. We recognize that the existing transportation systems do not cater to all income and social segments in our society and have thus taken the initiative to provide an appropriate solution to this issue. With UberCare we’re promoting inclusivity, goodwill, and generosity by empowering those that are disabled, elderly or are struggling financially.  


## Features
### Uber Assistance
Those that have a mental or physical disability will be allocated volunteers that will accompany them throughout their entire journey. These will be specialists that will ensure that the customer reaches their destination safely and that they will guide them in case they get lost. Similarly, for elders, the helpers will guide them to the correct terminal and assist them with carrying their belongings.

### Low income individuals
users can pay for two or more rides while only going on one. This allows those of low income to order a free ride that has been funded already through these charity donations. If unavailable, there would be subsidized costs sourcing from the company’s earnings or the user’s points, this will help alleviate their financial burdens.

### Priority
Due to the scarcity of resources, it is very possible that the business may face a shortage of supply. At all times, users are ordered in a priority list that will determine the urgency of their ride based on the information they input.

### Point System
The purpose of the point system is to promote the less admired transportation methods (usually public transport) and facilitate the inhibition of congestion during peak hours.


## How the code works
### Code 1
This JavaScript code defines a function called calculatePoints that calculates points based on a chosen transportation option and the distance traveled in kilometers. The function uses a switch statement to determine the points awarded for different options. If the chosen option is either "payForSomeoneElse" or "carPool," the code multiplies the distance traveled by 10 to calculate the points earned. If the option is "lessUtilizedRoute," it assigns 8 points per kilometer. In case the option doesn't match any of these, it logs "Invalid option" to the console. The code then returns the calculated points. In an example usage, it calculates the points earned for a 15-kilometer trip with the "payForSomeoneElse" option and displays the result as a message, such as "You earned 150 points for choosing payForSomeoneElse." This code provides a simple way to reward users for their transportation choices based on distance traveled and the chosen option.

### Code 2
This JavaScript code defines a function called calculatePriority that assesses the priority level for customers based on three parameters: elderly, disabled, and lowIncome. Using a series of conditional statements, the code evaluates these parameters to determine the appropriate priority level. If a customer is elderly and not disabled or low-income, they receive 'Low priority.' Customers who are either disabled or low-income, or both, but not elderly, are categorized as 'Medium priority.' The code also identifies 'High priority' for customers who fall into multiple categories: disabled and low-income, elderly and disabled, or elderly and low-income. Finally, if a customer qualifies for all three categories, they receive the highest priority, labeled as 'Very high priority.' If none of these conditions apply, the code returns 'Invalid input.' The code demonstrates its functionality with example customer objects and logs the calculated priorities for each, providing a flexible tool for prioritizing customers based on their specific characteristics and needs.

### Code 3
This JavaScript code defines a function named assignAssistanceWorker that categorizes individuals into different types of assistance workers based on three boolean parameters: isLowIncome, isElderly, and isDisabled, which represent a person's specific characteristics. The function employs a series of conditional statements to make the assignment. If a person is either low-income or elderly (but not both) and not disabled, they are classified as a "Volunteer worker." If the person is solely disabled, they are labeled as an "Amateur worker." Persons who are elderly and either low-income or disabled, or who belong to all three categories, are designated as "Experienced workers." If none of these conditions apply, the function assigns the worker type as "Unknown worker." The code illustrates its functionality through example usage, displaying the assigned assistance worker type to the console. This code offers a versatile tool for tailoring assistance worker assignments to individuals' unique circumstances and requirements.


## How to install and run the project
1. Set Up Your Development Environment: Ensure you have Node.js installed. Use a code editor like Visual Studio Code.
2. Clone the Project Repository: If using version control, clone the repository with git clone <repository_url>.
3. Navigate to the Project Directory: In your command-line interface, use cd to go to the project directory: cd project_directory.
4. Install Project Dependencies: If there's a package.json file, run npm install to install dependencies.
5. Run the Project: Execute npm start or follow project-specific instructions for launching.
6. Configure Environment Variables: Set up any necessary environment variables.
7. View the Project: Access the project in a web browser using the specified URL or port.
8. Interact with the Project


## How to interact with the Project
1. Install and set up the project following README instructions.
2. Configure project settings if required.
3. Start the project using the specified command.
4. Access the application through a web browser or CLI.
5. Interact with the UI, submit data, and navigate as needed.
6. Follow data entry and retrieval information
