Steps to Run the Script:

Ensure Correct File Content:

Make sure balance.txt on your desktop contains only the numeric balance value.

For example:

1000

Run the Script:

Open a terminal or command prompt.
Navigate to the directory where your script is located.
Run the script:
bash

python Tracker.py
or just run it using an IDE exmp (pycharm/visual studio etc...)

Edit the Balance to Test:

Open balance.txt in a text editor.

Change the balance value to 400 and save the file:

400

The script should detect the change and send an email with the subject "Balance Warning" and body "Warning! Your balance is $400... 100$ LEFT."
Change the balance value to 300 and save the file:

The script should detect the change and send an email with the subject "Balance Alert" and body "You have arrived to $300."
By following these steps, you should be able to securely send emails using your Gmail account with the script.
