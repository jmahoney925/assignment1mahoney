# assignment1mahoney
Jessica Mahoney's submission for assignment 1.

# HTML CSS Git Challenge: Code Refactor

A website owner wants to keep his/her website visually the same, but would like it to be much more accessible. As a front-end developer, it will be my job to condence this. 

## Modifying a web pages accessibility
 
Acceptance Criteria

*GIVEN a webpage meets accessibility standards
*WHEN I view the source code
*THEN I find semantic HTML elements
*WHEN I view the structure of the HTML elements
*THEN I find that the elements follow a logical structure independent of styling and positioning
*WHEN I view the image elements
*THEN I find accessible alt attributes
*WHEN I view the heading attributes
*THEN they fall in sequential order
*WHEN I view the title element
*THEN I find a concise, descriptive title

The program should look identitcal at the end of this processs 

![](./assets/images/Screen_Screenshot-JM.png)

### What was done?

To complete this challenge I took the following steps to have a final project I was happy with:
-Did a deeper dive into what code refactoring entailed
-Reviewed old assignemnts and followed lectures. 
-Tried my best.

I used the following outside online resources for refrence:
- How to write a read me? https://www.youtube.com/watch?v=E6NO0rgFub4
- Code refractoring. https://www.youtube.com/watch?v=vhYK3pDUijk
- Code refractoring. https://www.w3schools.blog/what-is-code-refactoring-and-why-need-to-you-do-it
-HTML CSS styling. https://www.w3schools.com/html/html_css.asp


## How is the code actually changed?

After gaining a better understanding of what was asked of me, these are the changes I made.

- I added comments within the code itself to break up the langage primiarly to make this easier for me to read. It is broken up between header, main body and footer.
-Within the CSS, I again added comments to break up the langauage between, header, main body and footer, but this time adding a section at the start for general code. 
- For General code, the following section was brought from the mid body to the top. This section of code is general for the whole text. 
a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}
-Within the body a few styles were identitcal so they were formed into one line of code. These styles include: 
#search-engine-optimization,
#online-reputation-management,
#social-media-marketing

and 

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {

and 

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3

and 

#benefit-lead,
#benefit-brand,
#benefit-cost

## Could this be improved further?

For furture developers who look at this code, I am sure there is more condencing that could be done for this code. 
