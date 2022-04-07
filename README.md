# Tradezero-API
 A simple script to interact with the Tradezero web platform through python. Right now it only allows for Buy/Sell but will add Short allocation and Short/Cover in the Future.

## Requirement
 **Python 3.6+**

## Set Up Selenium
 *Note: I am running this on ubuntu 20.04, if you are using another OS, following instructions may not apply to you*

 First pip install selenium module
 
 ```pip3 install selenium```

 Next we need to download the web driver, here we choose Firefox but Chrome is an option as well

 ```sudo apt -y install firefoxdriver```

 If you don't have geckodriver already installed, set it up by downloading the latest tar from [here](https://github.com/mozilla/geckodriver/releases). 
 Change to the directory where the tar is located and type the following in the terminal
 ```tar -xvzf geckodriver*
    chmod +x geckodriver
    sudo mv geckodriver /usr/local/bin
 ```

 Now it should be working, insert your tradezero login info to `main.py` and run the file, a new window with the trading platform should be opened, along    with some boogey trade executions.


