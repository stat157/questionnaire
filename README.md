Stat 157 Questionnaire Data Wrangling
=====================================

Due Date
--------
This assignment is due on Monday, Oct 7th by 11:59pm.

The following day (Tuesday) in class you will present your work.

Turn in your homework with a final `git push` of all materials by the
deadline noted above.

Your presentations will be alloted no more than 3 minutes and you will
*not* present using your own laptop. Your presentation must be in a
form that can be displayed on your instructor's system in an open
format: either the IPython Notebook or an HTML5-based presentation is
preferred: <https://www.google.com/search?q=html5+presentations>.


Objective
---------

You will use the Stat 157 Questionnaire data that you will access
using the Google API. Your primary objective is to visualize data from
two columns of the spreadsheet data: 1) the column labeled "What is
your learning style?" and 2) any other column of your choosing that
you feel helps give us insight into the people in the class.

The data that we have available in the spreadsheet comes from the real
world, which means the data is **dirty**. Your job before you
visualize the data is to clean it up and transform it into a form that
the analyzers and visualizers in your group can use.

Specifically, this is the data that YOU submitted via the Google Form
as part of the Questionnaire for this course so we can better
understand you, your skills, and where you're headed after you
graduate. All identifying data has been redacted from this data!


Grading
-------

You will be graded based on both **the product AND the process** of
your veritcal (4 person) groups.

We will be able to see what you produce, so examining your end product
will be our method of determing the portion of your grade based on the
end-product itself.

The other portion of your grade will depend on the process of how you
arrived at your end-product. Your process should be reproducible by
someone else *without* further instructions or help from you. If you
cannot fully automate the process, then provide step-by-step
instructions.


Preliminary Setup Steps
-----------------------
You'll need to follow these steps on your virtual machine to do data
wrangling for this assignment:

    sudo apt-get install ipython ipython-notebook python-pip
    pip install gspread

Then copy the example config file to your home directory, but named
`stat157.cfg` like this:

    cp example.cfg ~/stat157.cfg

Use a programming text editor to edit the example config file
`~/stat157.cfg` such as:

    vi ~/stat157.cfg

Edit the `~/stat157.cfg` config file so it will use your full
@berkeley username, e.g.: `foobear@berkeley.edu`. The password should
be your [bConnected key](https://kb.berkeley.edu/campus-shared-services/page.php?id=27226).

NOTE: Do **NOT** put your actual password into example.cfg! And
definitely **DO NOT** check it into github!

Use `example.py` in this repository as a starting point to access the
Google Spreadsheet data.

QUESTIONS?!?!?!?!
-----------------
You will probably have a lot of questions. You may also find a few
bugs. Please use the Github Issue Tracker for this repository to ask
questions and submit bugs:

https://github.com/stat157/questionnaire/issues

Hints For Success
-----------------
To be successful you will need to collaborate within your horizontal
(11 person) AND vertical (4 person) groups.

You have a better chance of succeeding with this assignment by running
`git commit` frequently on your local system and by running `git push`
often. If you're not sure what this means or

Use resources such as GitHub Help, StackOverflow, IRC, and other
resources that we configured in the first weeks of the class.

Keep notes about your process. If you are not able to make your
process reproducible by the deadline then you should be able to
provide notes about the errors, confusions, and other roadblocks that
you encountered.

Also, keep track of those "Aha!" moments and share those with others
in the class.
