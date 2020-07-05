# Om Shanker: bdd using python, behave and selenium
This is the implementation of behave along with selenium for bdd development
# Installation
## I suggest to create a virtual environment by creating new project in PyCharm that internally creates a virtual environment for you
+ `pip install behave`
- `pip install selenium`

That's it once we have our virtual environment the next very important thing is to do is setup the `chromedriver`. 
On mac machine you can run `brew cask install chromedriver`

A much easier way for mac would be download chromediver from official link (https://sites.google.com/a/chromium.org/chromedriver/) and unzip and 
copy the executable to `cp chormedriver /usr/local/bin`. 

For Windows and Linux environment my suggestion would be to follow steps given in chromedriver link given above.

Once we have done the setup it's now time to run our cases with behave.

In this project I have created one feature **flight_search.feature** which has **5 steps** and to run this all you need to go to project folder in terminal and run

`behave`

You will get the result
