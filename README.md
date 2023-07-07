# Task19
Task 19 Selenium Locators
Write all possible locators for given URL
https://www.guvi.in/register
//1.ID
ANS: 
1.Sign up button->
 WebElement button =drive.findElementBy.id(“google-button”)
2.firstName->
WebElement name =drive.findElementBy.id(“firstName”)
3.lastName->
WebElement lastname =drive.findElementBy.id(“lastName”)
4.Email
WebElement emailField =drive.findElementBy.id(“emailInput”)
5.Password
WebElement password =drive.findElementBy.id(“passwordInput”)
6.Number
WebElement number=drive.findElementBy.id(“mobileNumberInput”)
7.Sign Up
WebElement signup=drive.findElementBy.id(“signup”)

//2. ClassName
ANS:
1.Sign up button->
 WebElement button =drive.findElementBy.class(“btn btn-outline-google”)

//3.TagName
ANS:
First name , last name , email, mobile number,-> tagName--- input
Sign up button-> tagName—button
But we can not use tagename because it is not a exact match.

//4.CSS Selector
ANS:
1.Sign up button->
 WebElement button =drive.findElementBy.cssSelector(“a.btn.btn-outline-google”)
WebElement button =drive.findElementBy.cssSelector(“a#google-button”)
WebElement button =drive.findElementBy.cssSelector(“a[class*='btn btn-outline-google']”)
WebElement button =drive.findElementBy.cssSelector(“a.btn.btn-outline-google”)

2.firstName->
WebElement name =drive.findElementBy.cssSelector(“input#firstName”)
WebElement name =drive.findElementBy.cssSelector(“input[id*='firstName']”)

3.lastName->
WebElement lastname =drive.findElementBy.cssSelector(“input#lastName”)
WebElementlast name =drive.findElementBy.cssSelector(“input[id*=lastName']”)

4.Email->
WebElement email =drive.findElementBy.cssSelector(“input[placeholder$='Enter email']”)
WebElement email=drive.findElementBy.cssSelector(“input#emailInput”)
WebElement email=drive.findElementBy.cssSelector(“input[type*='email']”)
WebElement email=drive.findElementBy.cssSelector(“input[id*='emailInput']”)

5.Password
WebElement password =drive.findElementBy.cssSelector(“input#passwordInput”)
WebElement password =drive.findElementBy.cssSelector(“input[placeholder*='Password']”)
WebElement password =drive.findElementBy.cssSelector(“input[id*='passwordInput']”)

6.Number
WebElement number=drive.findElementBy.cssSelector(“input#mobileNumberInput”)
WebElement number=drive.findElementBy.cssSelector(“input[id*='mobileNumberInput']”)
WebElement number=drive.findElementBy.cssSelector(“input[name='mobileNumberInput']”)
WebElement number=drive.findElementBy.cssSelector(“input[placeholder='Mobile number']”)
WebElement number=drive.findElementBy.cssSelector(“input[name*='mobileNumberInput']”)

7.Sign Up
WebElement signup=drive.findElementBy.cssSelector(“button#signup”)
WebElement signup=drive.findElementBy.cssSelector(“button[id*='signup']”)
WebElement signup=drive.findElementBy.cssSelector(“button[type$='button']”)


//5.Xpath
1.Sign up button->
 WebElement button =drive.findElementBy.xpath(“//a[@id='google-button']”)
WebElement button =drive.findElementBy.xpath(“//a[@class='btn btn-outline-google']”)
WebElement button =drive.findElementBy.xpath(“//*[@id='google-button']”)


2.firstName->
WebElement name =drive.findElementBy.xpath(“//input[@id='firstName']”)
WebElement name =drive.findElementBy.xpath(“//input[@placeholder='Enter name'][contains(@id,'firstName')]”)


3.lastName->
WebElement lastname =drive.findElementBy.xpath(“//*[@id='lastName']”)
WebElement lastname =drive.findElementBy.xpath(“//input[@id='lastName']”)
WebElement lastname =drive.findElementBy.xpath(“//input[contains(@id,'lastName')]”)

4.Email->
WebElement email =drive.findElementBy.xpath(“//input[@id='emailInput']”)
WebElement email =drive.findElementBy.xpath(“//input[@type='email']”)
WebElement email =drive.findElementBy.xpath(“//input[@placeholder='Enter email']”)
5.Password
WebElement password =drive.findElementBy.xpath(“//*[@id='passwordInput']”)
WebElement password =drive.findElementBy.xpath(“//input[contains(@id,'passwordInput')]”)
WebElement password =drive.findElementBy.xpath(“//input[@placeholder='Password']”)

6.Number
WebElement number=drive.findElementBy.xpath(“//input[@id='mobileNumberInput']”)
WebElement number=drive.findElementBy.xpath(“//input[@name='mobileNumberInput']”)
WebElement number=drive.findElementBy.xpath(“//input[@placeholder='Mobile number']”)
WebElement number=drive.findElementBy.xpath(“//input[@maxlength='20']”)
WebElement number=drive.findElementBy.xpath(“//input[@minlength='10']”)

7.Sign Up
WebElement signup=drive.findElementBy.xpath(“//*[@type='button']”)
WebElement signup=drive.findElementBy.xpath(“//*[@id='signup']”)
WebElement signup=drive.findElementBy.xpath(“//button[@type='button']”)

