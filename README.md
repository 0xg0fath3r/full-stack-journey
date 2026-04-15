# full-stack-journey
**Document my full-stack journey**

# Day 1
***#HTML***
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





