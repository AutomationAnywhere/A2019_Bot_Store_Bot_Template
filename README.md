# A2019 Bot Store Bot Template
The A2019 Bot Store Bot Template is designed to be a starter shell for developers who are interested in developing bots or custom packages for Automation Anywhere's Bot Store.

To begin using this template (The zip file):
1. Log in to your A2019 Control Room as a user with Import Bots permissions granted via a role.
1. Navigate to *Bots > My bots* and make sure that you're on the **private** My bots tab.
1. Click the *Import bots..* button in the top right corner to begin the import process.
1. On the **Import Bots** screen, click the *Browse* button to select the *BotStoreTemplate.zip*
1. Click the **Import bots** button in the top right corner.
1. The bot will be automatically imported to Bot Store\Botname-VendorName\BotShell

Notes on developing with this bot template
* Error handling, snapshots, and log management are handled by the template
* Developer code should go in the main try block of the template, and may call sub-tasks/scripts as needed
* A Finally block can/should be added to appropriately close any opened applications whether the task fails or succeeds. 

Read Me Template:
* This template is a pared-down version from the Read Me template use for v11 bots.
* A Read Me (saved as a PDF format) is required for submitting a bot or package to Bot Store through the Bot Store submission forms.
* While most developers would agree that writing detailed Read Me files is not the most fun thing to do - all would agree that being given code you aren't familiar with - but that comes with excellent documentation - makes the process of using it that much easier/faster.
* Spend the time to properly communicate what your bot/package can do and how users can engage with your component - bearing in mind that not everyone using it may be as experienced of a developer as yourself. 

