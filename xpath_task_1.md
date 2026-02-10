# 1) XPath for main h1 element
//h1[@id='mainTitle']

# 2) XPath for About Us navigation link
//a[normalize-space()='About Us']

# 3) XPath for Graphic Design dropdown link
//a[@href='#graphicdesign']

# 4) XPath for team member’s name Jane Smith
//h4[normalize-space()='Jane Smith']

# 5) XPath for description paragraph of SEO Services
//div[@class='service-item']//h3[normalize-space()='SEO Services']/following-sibling::p

# 6) XPath to select all service items in "Our Services" section
//section[@id='services']//div[@class='service-item']

# 7) XPath for email input field in the contact form
//form[@id='contactForm']//input[@id='email']

# 8) XPath to select the entire contact form
//form[@id='contactForm']

# 9) XPath for footer paragraph element
//footer//p

# 10) XPath for the first team member's name (h4)
(//div[@class='team']//h4)[1]

# 11) XPath for description of the second service item
(//div[@class='service-item']//p)[2]

# 12) XPath for "Contact Us" section header (h2)
//section[@id='contact']//h2

# 13) XPath for all links inside the Services dropdown
//li[a[normalize-space()='Services']]//ul[@class='dropdown']//a

# 14) XPath for the first <li> under the "Our Team" section
//div[@class='team']//ul/li[1]

# 15) XPath for "Send Message" button
//form[@id='contactForm']//input[@type='submit']
