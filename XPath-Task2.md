# Task 2 - XPath

# 1) XPath for the highlighted profile icon/button
//header//a[contains(@href,'auth')]

# 2) Login page - https://grocerymate.masterschool.com/auth

# 2.1) Email input field
//form//input[@type='email']

# 2.2) Password input field
//form//input[@type='password']

# 2.3) Sign In button
//form//button[normalize-space()='Sign In']

# 2.4) Create a new account link
//a[normalize-space()='Create a new account']

# 2.5) Go to Home link
//a[normalize-space()='Go to Home']

# 3) Create New Account page

# 3.1) Full Name input field
//form//input[@placeholder='Full Name']

# 3.2) Email address input field
//form//input[@type='email']

# 3.3) Password input field
//form//input[@type='password']

# 3.4) Sign Up button
//form//button[normalize-space()='Sign Up']

# 4) Store page - Age Verification modal

# 4.1) Confirm button
//button[normalize-space()='Confirm']

# 5) Shop page - Oranges

# 5.1) Quantity input of Oranges
//h3[normalize-space()='Oranges']/ancestor::*[contains(@class,'product')][1]//input[@type='number']

# 5.2) Add to cart button for Oranges
//h3[normalize-space()='Oranges']/ancestor::*[contains(@class,'product')][1]//button[contains(normalize-space(),'Add')]

# 5.3) Add to wish list for Oranges
//h3[normalize-space()='Oranges']/ancestor::*[contains(@class,'product')][1]//*[name()='svg']
