# full-stack-journey
**Document my full-stack journey**

# Day 1
***# HTML***
HTML, which stands for Hypertext Markup Language, is a markup language for creating web pages. 
When you visit a website and see content like paragraphs, headings, links, images, and videos.

I started HTML on freeCodeCamp platform. I learnt about tags-opening and closing tags. 
(e.g <html>...</html>, <p>...</p>, etc) while some tags don't need closing tags like the break line 
tag (<br>: does not need a closing tag.)

Tags are very essential in building the web page, they are literally like functions you use to build the website.
Examples of tags include: <h1> tag which is used for the main header in a webpage-
the header tag goes from <h1> to <h6>, <p> Used to write a paragraph</p> (By the Tags have opening and closing tags, 
but there are others that have exceptions like the line break tag <br> it does not have a closing tag.

Tags also have attributes in them and attributes includes "key and values" for example the image tag <img/>;
An attribut can be added like this: <img src="image-link"/>, and it can include more than one attribute 
i.e the first link can have an alternate link just incase the first did not work it will use the second or alternate.
<img src="image-link" alt="an-alternate-link"/>
The alt attribute is not required, but it is recommended for accessibility purposes. Accessibility means making sure that everyone, 
including those with disabilities, can use and understand things like websites, apps, and physical spaces.

An attribute is a value placed inside the opening tag of an HTML element. 
Attributes provide additional information about the element or specify how the element should behave.
The a element, also known as the anchor element, is used to create hyperlinks.
The text between the opening and closing a tags is the clickable part users select to navigate.
<a href="https://www.freecodecamp.org/news/" target="_blank">Visit freeCodeCamp</a>
Without the href attribute, the link would not work because there would be no destination URL. 
So you must include this href attribute to make the link functional. 
The target="_blank" enables the link to open in a new browser tab. 
here are several common boolean attributes you will encounter in HTML, such as disabled, readonly, checked, and required. 
These attributes are used to specify the state of an element, such as whether it is disabled, read-only, or required.



<img width="1911" height="1056" alt="image" src="https://github.com/user-attachments/assets/2fe47141-c89e-4421-8b6e-da95269bf1c7" />
This is my second project on freeCodecamp



I also learn about the use of "Link" element in HTML tag.
The "link" element is used to link to external resources like stylesheets and site icons.
e.g <link rel="stylesheet" href="./styles.css" /> the rel shows relationship between linked resource and the HTML document. 
It is considered best practice to separate your HTML and CSS in different files. 

HTML boilerplate: It's like a ready-made template for your webpages.
<!DOCTYPE html>: It tells browsers which version of HTML you're using.
<!DOCTYPE html>
<html lang="en">
  <!--All other elements go inside here-->
</html>: 
This wraps around all your content, and can specify the language of your page.

# My first Workshop
<img width="1900" height="1058" alt="image" src="https://github.com/user-attachments/assets/479faf0f-bb5b-43dd-abea-3f933c322065" />




# Day 2

I learnt about how to use the div and section elements.
Section tells browsers that this is a distinct section in the web page.
while div is most used when styling i.e CSS.
div element can also include some attributes like the "id" and "class" attributes.
the "id" attribute adds a unique identifier to the an HTML element, and it needs to be unique
Classes are best used when you want to apply a set of styles to many elements. 
If you want to target a specific element, it is best to use id because those values need to be unique.
I also learn about the use of HTML entities such as named, decimal, and hexadecimal. Entities when you need to add some symbols that HTML use in its syntax e.g <p>&lt;p&gt;learning is fun&lt;/p&gt;</p>

<img width="1919" height="1159" alt="image" src="https://github.com/user-attachments/assets/a5da409c-f642-47f2-a890-9a6f4348b71c" />

**Workshop 2**








<img width="1919" height="1091" alt="image" src="https://github.com/user-attachments/assets/b4e6e7de-3ea5-4e9d-9403-19b7cc1113dc" />
**Lab 3**
This one will go down as one of the first exercise that I actually struggled to solve. 
so after creating a section for the images, each image must have a tag called figure, 
you will add an anchor tag as the first child of the figure tag, 
then you will now add the image before closing the tag. 
I had to do it 3 times to be able to understand it, it made the image clickable like a link.

<img width="1906" height="1149" alt="image" src="https://github.com/user-attachments/assets/d57ad33f-5971-47ec-8c0a-f98d1ffa14b7" />
# Lab 4



# Day 3

I learnt about media formats like png, jpg, and svg; png is a lossless format in the the sense 
that when compressed it doesn't lose quality, while jpg is lossy. 
svg is store in the form of xml it mostly used for icons on the webpage or 
the web logo display on the tab in the browser.

This is an exercise I just completed on svg.
<img width="1919" height="1106" alt="image" src="https://github.com/user-attachments/assets/56d7d34c-7b5a-4bfb-9cb1-2676cbb65136" />


I also learnt about The Replace Elements: A replaced element is an element whose content is 
determined by an external resource rather than by CSS itself.
With replaced elements, you can control the position, or layout of an element. 
But your CSS cannot directly modify the content of that element. 
examples include: img, video, audio, & iframe(inline Frame) elements; 
the iframe element allows you to add resources from another website like videos from YouTube, map etc.
CSS can't modify it but it can only change the positioning.
I also learnt that If you want to embed direct HTML within the iframe element you 
have to use the srcdoc attribute instead of src.


<img width="1913" height="1148" alt="image" src="https://github.com/user-attachments/assets/565f4dbf-5649-4bfe-87b1-105d774464e0" />

# Lab 5



I continued with HTML Semantics: Semantics are the meaning of words, 
or phrases, in a language; while Syntax is talking about the structure of the programming language.
I learnt that using the right semantics help with a lot of things such as SEO, 
instead of the browser to start thinking or assigning what you page does you already did 
that using the right semantics which is good practice.

I continued with description elements: dl, dt, dd (Description lists are perfect 
for presenting terms and definitions in an organized and easy-to-read format, 
like in a glossary, or real dictionary, where you can find words with their corresponding definitions.)
dl-description data; dt-description term; dd-description data



# Day 4

We use code element to represent code in the HTML code.
The code element is meant to represent a single line of code. If you want to represent multiple lines of code, 
you will need to place a code element inside a preformatted text element.
When using the pre element, you will need to be mindful of spacing because it will display exactly as written 
inside the HTML document.

The unarticulated annotation element, or u element for short, is used to represent inline text that has 
non-textual annotation applied.
The strikethrough element, or s element for short, should be used to represent when text is no longer accurate or relevant. 
The ruby element represents small text shown above or below the main text. It is typically used to show the 
pronunciation of East Asian characters.
The rp element, or ruby fallback parenthesis element, is used as a fallback for browsers lacking support for 
displaying ruby annotations.
The rt element, or ruby text element, is used to indicate text for the ruby annotation. 
This text is usually used for pronunciation, or translation details in East Asian typography.


# Workshop
<img width="1910" height="1105" alt="image" src="https://github.com/user-attachments/assets/c368f433-5d51-4e88-ace0-565d3e3a5ef1" />



# Day 5
I completed this lab (**Lab 6**)
<img width="1912" height="1103" alt="image" src="https://github.com/user-attachments/assets/4c68805e-4953-448c-be42-abfbc84017de" />

I learnt how to work with forms, labels, and inputs(user inputs).
The form element in HTML is used to gather user information, such as names and email addresses.
input elements are void elements and do not have closing tags. The type attribute defines the 
data type expected from the user.
To add a label for the input, you would use a label element.
I also learnt the use of the button element; The button element is used to perform a particular action when it is activated. 
This is one of the important things i learnt today; When a user fills out a form on your website, it is important that they
fill out all of the necessary information in the correct format. HTML form controls, like inputs, have a lot of built-in
validation that you can use to check for invalid data. This will help ensure that the user fixes these mistakes before the
information is submitted and processed by the server.

The term "client-side" refers to everything that happens on the user's computer or device, like the part of a website or app
you interact with directly. This includes the layout, design, and any interactive features.

The term "server-side" refers to everything that happens on the server, the computer, or system, that hosts the website or
app. This includes processing data, running applications, and handling requests that come from the user's device.

While client-side validation is important, you also need server-side validation for added security. Malicious users can
bypass client-side checks, so robust server-side measures are essential. You'll learn more about this in a later module. For
now, let's take a look at some examples of client-side form validation.


# Workshop
<img width="1901" height="1102" alt="image" src="https://github.com/user-attachments/assets/a235f331-8563-4237-a59e-3c2aaffc8976" />





# DAY 5

HTML Tables and what they are used for: 
Table element
tr-table row
td-table details
tbody-table body
tfoot-table foot
thead-table head
# Workshop 7
<img width="1914" height="1107" alt="image" src="https://github.com/user-attachments/assets/2e71350d-2b30-4217-9fb4-8ec56bf77e5e" />

# Lab 7
<img width="1899" height="1102" alt="image" src="https://github.com/user-attachments/assets/952b22cb-49b1-4bd7-b337-bb15b13ce27d" />


# Day 6
Today, I officially learnt that HTML is a very forgiving language – elements still render even when you make mistakes, 
like forgetting to include a closing tag.
To avoid making those errors, you need an HTML validator; An HTML validator is a tool that checks the validity of your HTML 
code against the standard HTML specifications. It helps you identify errors and warnings in your HTML code, 
ensuring your web pages are correctly structured and compliant with web standards.
The most popular validator to use is https://validator.w3.org/, another one is this https://jsonformatter.org/

I also learnt about tools developers use to debug their HTML codes, one of them is DOM (Document Object Oriented); 
The DOM inspector allows you to inspect the HTML structure of the page you are on.

HTML Form Elements and Attributes
**form element**: used to create an HTML form for user input.
**action attribute**: used to specify the URL where the form data should be sent.
**method attribute**: used to specify the HTTP method to use when sending the form data. The most common methods are GET and POST
**input element**: used to create an input field for user input.
**type attribute**: used to specify the type of input field. Ex. text, email, number, radio, checkbox, etc.
**placeholder attribute**: used to show a hint to the user to show them what to enter in the input field.
**value attribute**: used to specify the value of the input. If the input has a button type, the value attribute can be used to set the button text.
**name attribute**: used to assign a name to an input field, which serves as the key when form data is submitted. 
For radio buttons, giving them the same name groups them together, so only one option in the group can be selected at a time.
**size attribute**: used to define the number of characters that should be visible as the user types into the input.
**min attribute**: can be used with input types such as number to specify the minimum value allowed in the input field.
**max attribute**: can be used with input types such as number to specify the maximum value allowed in the input field.
**minlength attribute**: used to specify the minimum number of characters required in an input field.
**maxlength attribute**: used to specify the maximum number of characters allowed in an input field.
**required attribute**: used to specify that an input field must be filled out before submitting the form.
**disabled attribute**: used to specify that an input field should be disabled.
**readonly attribute**: used to specify that an input field is read-only.
**label element**: used to create a label for an input field.
**for attribute**: used to specify which input field the label is for.
**Implicit form association**: inputs can be associated with labels by wrapping the input field inside the label element.
**Explicit form association**: inputs can be associated with labels by using the for attribute on the label element.
**button element**: used to create a clickable button. A button can also have a type attribute, which is used to control the behavior of the button when it is activated. Ex. submit, reset, button.
**fieldset element**: used to group related inputs together.
**legend element**: used to add a caption to describe the group of inputs.


# Day 7

Website Accessibility
Accessibility involves creating products and services that everyone can use. In the context of web development, 
it's making websites that everyone can understand and interact with, including people with visual, auditory, motor, and cognitive disabilities.

To help you create accessible websites, the World Wide Web Consortium, known as W3C, developed a set of international standards that 
you can follow to make your websites more accessible and easier to use for people with disabilities.

These standards are known as the "Web Content Accessibility Guidelines" (WCAG).
These guidelines are designed with four core principles in mind, known as POUR.

**P** stands for Perceivable. Users must be able to perceive the information that you are presenting. For example, 
you can provide alternative text for images, so users who access your website with a screen reader can understand them.

**O** stands for Operable. Users must be able to interact with the user interface. For example, you can make sure that all 
functionality is accessible through the keyboard too, not just the mouse.

**U** stands for Understandable. Users must be able to understand the information. For example, you can avoid complex 
sentences and use simple language as much as possible.

**R** stands for Robust. A wide range of browsers and other tools, including assistive technologies, must be able to interpret the content.

I also learnt about Screen readers in HTML
Screen readers are assistive technology programs that help blind and visually impaired people use computers and mobile devices.

Screen readers are not just tools for the blind and visually impaired to access computers and mobile devices.

They empower these individuals to access education, work opportunities, and social media. This ensures digital inclusion 
and enhances their ability to participate fully in society.

There's a common misconception that screen readers are text-to-speech devices.

However, text-to-speech is just one of the features of a screen reader. Some screen readers even render the text to braille output instead of speech.

Apart from text-to-speech and braille output, other notable features of screen readers are navigation aids and web browsing assistance.

Screen reader programs are also not only made for the blind and visually impaired. Dyslexic individuals and people with 
cognitive disabilities also use screen readers. All the popular operating systems out there have screen readers built into them.
To access it on windows is WIN + Ctrl + Enter while in macOS is CMD + F5.
Android phones have TalkBack built-in. You can turn it on by accessing Settings > Special Function > Accessibility > Talkback.
Linux has Orca for the desktop environment and Speakup for the Linux terminal.
