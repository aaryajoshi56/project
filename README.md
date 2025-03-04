# Activity recommendation program 
## overview 
The Activity Recommendation Program is a Python-based application that provides users with personalized activity suggestions based on their available time and preferences. Whether you’re looking to be productive, engage in self-care, or simply unwind, this program intelligently recommends activities that fit your schedule. It also prioritizes tasks based on importance and ensures that users can manage their time efficiently.A unique feature of this program is that it can provide inspirational quotes at the beginning of each session, which equips the user with a positive attitude to perform their tasks. Considering user-defined constraints such as bedtime and activity type of interest, this program brings value addition to daily planning and helps users make the optimum utilization of their time.

###Features
 ⁠Features
*Personalized Activity Suggestions – Activity suggestions are personalized according to user input for relevance and applicability.
*	Category-Based Filtering – The user is given the option to choose a particular category of activities (e.g., work, fitness, relaxation) or general suggestions.
*	Priority-Based Ranking – More important tasks are prioritized first to promote efficient time management.
*Motivational Quotes – Inspirational quotes at the beginning of each session motivate the user and increase productivity.
* Ease of Use Interface – The CLI makes it easy to navigate and get suggestions.
*Personalizable Activity List – The users are able to customize the activities and priority levels according to their preference.

nstallation

1. Install Python

Ensure you have Python 3.x installed on your system. You can verify this by running the following command in the terminal (Mac/Linux) or command prompt (Windows):

python --version

If Python is not installed, download and install it from the official Python website: python.org.

2. Clone or Download the Repository

To obtain the program files, you can either download the ZIP file manually or use Git:

git clone https://github.com/your-repository/activity-recommendation.git
cd activity-recommendation

3. Install Required Dependencies

Some features of this program may require additional Python libraries. If a requirements.txt file is provided, install dependencies using:

pip install -r requirements.txt

This will install all necessary packages automatically.

4. Run the Program

Execute the Python script using:

python main.py

Once started, the program will guide you through the activity recommendation process.

Usage

How It Works
	1.	Start the Program – Run the main.py script in your terminal or command prompt.
	2.	Enter Your Name – The program greets you personally for a friendly experience.
	3.	Provide Your Time Constraints – Enter the current time and your bedtime. The system uses this information to suggest activities that fit your schedule.
	4.	Select an Activity Category (Optional) – You can choose a specific category (e.g., work, health, fun) or request a general recommendation.
	5.	Receive Recommendations – The program suggests activities based on your available time and prioritization rules.
	6.	End the Session – Once you receive your recommendations, you can choose to exit or restart the program.

At the start of each session, a motivational quote will be displayed to inspire productivity.

Configuration and Customization

Users can customize various aspects of the program by modifying the Python script:
*Adding New Activities – To introduce new activities, update the predefined list in activities.py.
*Changing Motivational Quotes – Modify or expand the list of quotes in quotes.py.
*Adjusting Priorities – If certain tasks should be prioritized differently, update the ranking logic in main.py.

For example, if you want to add a new activity, open activities.py and append:

activities.append({"name": "Learn a new programming concept", "category": "Education", "priority": 3})

This ensures that the activity is included in future recommendations.

Code Structure

activity-recommendation/
│── main.py               # Main script to run the program
│── activities.py         # Contains predefined activity lists
│── quotes.py             # Stores motivational quotes
│── requirements.txt      # List of required dependencies
│── README.md             # Documentation file

	main.py: Handles user interaction, scheduling logic, and recommendations.
 
	activities.py: Stores the list of predefined activities categorized by type and priority.
	quotes.py: Contains motivational quotes displayed at the start of each session.
	requirements.txt: Lists external dependencies required for the program.
	README.md: This documentation file, providing details about the project.

System Requirements
*Operating System: Windows, macOS, or Linux
*Python Version: 3.x
*Memory Usage: Minimal, as it runs in a command-line environment
*Additional Dependencies: Any external libraries specified in requirements.txt

Troubleshooting

Common Issues and Solutions
	*Python Command Not Found:
	*Ensure Python is installed and added to the system’s environment variables.
	*Try using python3 instead of python.
	*Module Not Found Errors:
	*Install missing modules using:

pip install -r requirements.txt

*Unexpected Program Crashes:
*Ensure that you enter valid inputs when prompted.
*Check for syntax errors if you modified the script.


