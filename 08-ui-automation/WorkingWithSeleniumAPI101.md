# Working with Selenium API 
Note: Before you start -
* Create a Java Maven project in your IDE.
* Import Selenium Library using POM
`<dependency>
  <groupId>org.seleniumhq.selenium</groupId>
  <artifactId>selenium-java</artifactId>
  <version>3.141.59</version>
  </dependency>`
  
1. [What is WebDriver?](https://www.selenium.dev/documentation/webdriver/)
2. Create a ChromeDriver Object 
   * Open a browser
   * Open an url https://www.izaanschool.com
   * Close the browser
    * Great You are doing good!!!
3. Create new method and Go to https://www.izaanschool.com/apply
    * Again go to https://www.izaanschool.com
    * Use back() method to go back to Apply page [Reference](https://www.selenium.dev/documentation/webdriver/browser/navigation/)
    * Use forward() method
    * Use refresh() method
    * It's fun, right??
    
5. It's time to learn locators. It's a way to get take your cursor to the particular
   location of the webpage so that you can do browser action like click, write text.
   Using HTML attribute, xpath, css we can catch or locate a web element
    *  What is locators? Learn from this document [Locator](https://www.selenium.dev/documentation/webdriver/elements/locators/)
    * You can also read about locator from [Here](https://docs.google.com/document/d/1yRdHoJGOkfOQn5N_Gnywa-9963_Cydrq7jEjl0X7Crg/edit?usp=sharing)
    * Well now you know how locators works
    * [Here](https://www.selenium.dev/documentation/webdriver/elements/finders/) you have more sample for your understanding 
6. Let's learn how to do some more interaction with browser. [Reference](https://www.selenium.dev/documentation/webdriver/elements/interactions/) 
    * clik()
    * sendKeys()
    * clear()
    * submit