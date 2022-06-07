# Ctrl-F

### Author — Elijah Harrison
### Senior Project | BYU-I CSE 499

---

Welcome to the Ctrl-F project! Ctrl-F is an open source software which is designed to assist users to select text from PDFs...right from your browser. 

The problem: https://www.tiktok.com/t/ZTdc7ecq6/?k=1 

The solution: PDFs are documents that are generally pretty good at allowing you to select the text in your document... until it doesn't. Most of the time, access to the PDF is locked or the text field is actually an image, to name a few instances. Using computer vision and OCR software is a good step to doing just that again! Thus you regain command of your Ctrl-F.

Once that solution is developed, we'll allow users to interface with this software by downloading a simple browser extension, providing very useful functionality with very little overhead. 

The second problem: Usually with OCR's, it's hard to keep things in the same formatting as what the user sees. This can cause annoyances in several different situations:
- Somebody who wants to copy a link might have to deal with an unwanted extra space being added to the URL they need to copy
- When text wraps to a newline, the OCR software generally interprets this as a new line and you're left with text that is broken up at weird intervals.

The URL fix: We'll include some automatic detection with the software that checks where a URL will start and stop and use an algorithm that retries its guess of the text until it finds a valid URL. 
The unwanted newline fix: With a little tweaking we can detect when these newlines are actually instances of text wrapping, and replace the newline indicator in the copied text with a simple space character. 

Drawing inspiration from other existing software, it's pretty evident that not only pdfs, but 

The goal: Give users access to OCR software that isn't just efficient, but is also fast and convenient to use. 

Ultimately, this project will help in lots of different applications. Another useful application is improving how certain sites would parse and import data from a PDF. I currently run into this with things like job board sites. I have a resume that I use and like the design of, but as soon as I uploaded it to a site to apply to a job, the site autofills information from weird places on my document thinking that it's somehow inline with other lines of information from a completely different section of my resume. Ultimately, this will always be a problem unless the program that exported the PDF was the same as the program that imports/parses it, but this project aims to tackle this challenge in a smarter way. 

What sets this project apart from different Chrome Extensions:

[Snap&Read](https://chrome.google.com/webstore/detail/snapread/mloajfnmjckfjbeeofcdaecbelnblden?hl=en) — Although the project is inspired by extensions like this one, this program is intended to work so that the user never has to interact with the program once enabled. The user should essentially be frustrated when they use another person's browser and this convenience isn't available to them. 

[Mercury Reader](https://chrome.google.com/webstore/detail/mercury-reader/oknpjjbmpnndlpmnhmekjpocelpnlfdi?hl=en) — This extension also really shaped what I wanted this project to be, although I wanted to preserve the original page layout of what the user tries to access. I want to solve only what I've set out to solve. Taking inspiration from this extension though, I like the fact that they can do a smart export to a different file type. I would love to add functionality to my extension to support this, so long as the user's experience remains as simple as possible. 
 
[Reader Mode](https://chrome.google.com/webstore/detail/reader-mode/llimhhconnjiflfimocjggfjdlmlhblm?hl=en) — I love the fact that they give the user the ability to adjust the font and some of the styling on the webpage, but it's a aside from our focus. We will aim for the maximum use for the minimum user interaction. 

--- 

** This project is currently being planned. 
Enjoy some donuts while you wait!
[*](https://www.google.com/search?q=donuts&oq=donuts&aqs=chrome..69i57j46i512j0i402l2j0i512l2j0i10i433j0i512j46i512j0i271.1300j0j7&sourceid=chrome&ie=UTF-8) 
The code that will be developed and its documentation will be added here when it's made. **

---

Project applications:

Go to Chrome Browser Extension project directory

Other project applications coming soon
