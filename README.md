# Simple Telegram Bot for Task Management
A telegram bot that is used for scheduling and managing tasks. It can add new tasks for specific dates and display all the tasks scheduled for the selected date.

### Requirements
• Python 3.x

• telebot library

• telebot_calendar library
You can install the libraries using pip:
```
pip install pyTelegramBotAPI
pip install telebot-calendar
```

### Setup
1. Clone the project with git clone ``` https://github.com/<username>/<project> ```
2. Open the cloned folder and install the required packages with the command ``` pip install -r requirements.txt ```
3. Create a new Telegram bot and obtain its token from __BotFather__.
4. Insert your bot token in the __token__ variable in the code.
5. Run the code with the command ``` python main.py ```

### Usage
The bot has several commands:

• ``` /start ``` - start the bot and display the main menu.

• ``` /help ``` - show help message.

• ``` ✅ Add task ``` - add a new task for the selected date.

• ``` Show tasks ``` - show added tasks for selected date.

• ``` Help ``` - show help message.

When you click on the "Add task" button, a calendar will appear, where you can select the date for which you want to add a task. After selecting the date, enter the task text and it will be added to the list of tasks for the selected date.

To delete a task, click on the ❌ button next to it in the list of tasks for the selected date.

### Conclusion

This Telegram bot is a simple task manager that can be customized and extended to meet your needs. It's easy to use, and you can easily add new features to it. Feel free to contribute to the project if you have any ideas or suggestions.
    
