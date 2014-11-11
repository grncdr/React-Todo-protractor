React-Todo-protractor
=====================

This repo has tests written for a react Todo which are written in protractor

Prerequisites
1. Please make sure that python is installed and be found in the path .

2. Install nodejs on the system 

3. Please make sure that bower is installed in the system , this can be installed by ```npm install -g bower```

4. Install protractor using ```npm install -g protractor```

5. Install the webdriver manager using ```webdriver-manager update --standalone```

Running the tests
1. Download the repository on repo

2. Start the http server using ```python -m SimpleHTTPServer``` (Or any other HTTP server like apache would do)

3. If it's not already running, run `webdriver-manager start` in another terminal window to start up the webdriver manager.

4.  Once the server is started navigate to the react folder using a web browser.

5.  Open test.js and update the ```browser.driver.get('Please update the URL from where the app is accessible');``` with the   URL where the app is accessible.

6.  Open a command line interface and run the tests using ```protractor conf.js```

 
  
