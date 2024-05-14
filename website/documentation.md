# Website Name
itinker.tech/enterprise.html
## Project Proposal
This website is designed to provide users with a basic education of the C programming language. On the internet, there are many tutorials on how to learn the C programming language, however usually these courses are large and hard to digest, as they include large amounts of computer science jargon, or they are paid for. Also, tutorials do not always provide practice problems which means that users are not able to try and apply what they have learnt. This website is to designed to be a solution to beginners who have no idea on how to code, and have had no experience in thinking in the style of computer science. Furthermore, this website will provide a simple run down on the syntax required to make legal C code. This will be done through digestable pages of content, allowing users to absorb the information at their own pace, with actionable steps so that learners stay engaged, and improving user experience. After landing on this idea, consideration was put into how the information could be best presented. There were many options, however a blog post style website seemed to be the winner as it would be able to achieve the goal of teaching people about the C programming language the best. This is due to the fact that each blog post could be bite sized lessons that can be taken at a user's own pace. 

## Accessibility Features
Including alt text will help with people who are visually impaired. This will be easy to implement as HTML documents have a built in alt attribute, and users who use screen readers will have the alt text describing the image read out to them. To further help with accessibility, the website is entirely entirely accessible via keyboard, and users who are unable to use a mouse can navigate the pages with relative ease. This will be possible as most web browsers allows users to navigate websites using the TAB buttonand "click" on buttons with enter, and also with the menus made to be easy to navigate with keyboard only. 

## Website Hosting Solution
Instead of using a third-party provider like Wix or Squarespace, the decision was made to set up the domain and webserver for hosting the website. This is due to multiple advantages, like more control over my website's file configuration and more freedom to customise my website. Many features that are able to be implemented through code are hiddent behind a paywall with these no-coded solution providers. Furthermore, Third party no-code website solutions are quite restricted in terms of features able to be added, and also may deal with file saving issues and latency. As Squarespace and Wix update, these providers may cause changes in the formatting for the website. By hosting the files on a cloud server and using a personal domain, the longevity of the website is extended as the files are in full control by the developer. Utilising Github's Student Developer Pack, a free domain was able to be registered for free. The web server provider that was chosen was DigitalOcean, as it came with the Student Developer Pack. Debian was installed on a web server, and then nginx was used to be able to use the web server as a host for the website. From there, pointing the .tech domain to the DigitalOcean web server was just a matter of putting the web server's IP address into .tech domains. 

## Information gathering
The information that is on the website is based on tutorials from a multitude of websites, including w3schools and Harvard's CS50 course. 

## Coding Process
To get me started on the process of creating a webpage, I downloaded a premade html template from HTML5UP to get myself started with a blog post style website. 

## Reflection
To start, choosing to write the website's code by hand instead of utilising a no-code solution may have cause me to lose time and may have caused me to produce a less aesthetically pleasing website. This is due to my lack of experience in HTML. However, the advantages of editing the HTML document manually were quite significant. I was able to learn a lot more about frontend website programming languages, like HTML, CSS and Javascript. Furthermore, due to the fact that my hosting solution is my personal domain and web server, I am able to have much more control over the file configuration of my website, making it much easier for me to maintain the website in the future. 

Due to the fact that the theme of my website is teaching people about the C programming language, a challenge was maintaining enough white space to ensure good user experience. This is because there is a lot of information on each of the pages, and blocks of text will decrease user engagement. 

The user interface was made to be as easy to navigate as possible. 

## Sources
Images:
https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.boardinfinity.com%2Fblog%2Fall-about%2F&psig=AOvVaw358ciqU_FPdOb41Z6mF8RN&ust=1715395291284000&source=images&cd=vfe&opi=89978449&ved=0CBQQjhxqFwoTCPi7oMyHgoYDFQAAAAAdAAAAABAR
https://www.google.com/url?sa=i&url=https%3A%2F%2Fmedium.com%2F%40laura.derohan%2Fcompiling-c-files-with-gcc-step-by-step-8e78318052&psig=AOvVaw0WzpoDFMthUXBQQZbuI89Y&ust=1715686979011000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCLDMypjGioYDFQAAAAAdAAAAABAS
https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.linkedin.com%2Fpulse%2Fwhy-linux-most-popular-operating-system-prajwal-jadhav&psig=AOvVaw3HEGAU2SCIlQaCknB10C3U&ust=1715687799732000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCJi2m6LJioYDFQAAAAAdAAAAABAE
https://www.google.com/imgres?q=mingw&imgurl=https%3A%2F%2Fterminalroot.com%2Fassets%2Fimg%2Fwindows%2Fmingw%2Fmingw.jpg&imgrefurl=https%3A%2F%2Fterminalroot.com%2Fhow-to-install-gcc-gpp-mingw-on-windows%2F&docid=sv64NBNoD1kX-M&tbnid=rRXhKvvWC-69BM&vet=12ahUKEwisv7b58YuGAxX1ma8BHZd3CgEQM3oECCAQAA..i&w=800&h=450&hcb=2&ved=2ahUKEwisv7b58YuGAxX1ma8BHZd3CgEQM3oECCAQAA
https://www.google.com/imgres?imgurl=https%3A%2F%2Fwww.adslzone.net%2Fapp%2Fuploads-adslzone.net%2F2019%2F07%2Flogo-inicio-windows-10.jpg%3Fx%3D480%26y%3D375%26quality%3D40&tbnid=l1Csuo3dE9ik7M&vet=10CBYQxiAoCGoXChMIuMvM-5eMhgMVAAAAAB0AAAAAEAY..i&imgrefurl=https%3A%2F%2Fwww.adslzone.net%2F2019%2F09%2F04%2Fwindows-10-nuevos-iconos-fluent-design%2F&docid=c4DdBFhk7J0bfM&w=480&h=375&itg=1&q=windows%20logo&ved=0CBYQxiAoCGoXChMIuMvM-5eMhgMVAAAAAB0AAAAAEAY
https://www.google.com/url?sa=i&url=https%3A%2F%2Fcommons.wikimedia.org%2Fwiki%2FFile%3AC_Programming_Language.svg&psig=AOvVaw0NhRdXGMfvi72np5x56iCt&ust=1715775191840000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCJCi2OqOjYYDFQAAAAAdAAAAABAE

Information:
https://www.britannica.com/technology/C-computer-programming-language
http://www.geekswithgeeks.com/c-programming/c-programming-history-features
https://www.educative.io/blog/object-oriented-programming
https://www.codecademy.com/resources/blog/object-oriented-programming/
https://hackr.io/blog/difference-between-c-and-cplusplus
https://medium.com/@isaac_70614/how-c-source-code-becomes-an-executable-program-f2e00ecf5c5c
https://code.visualstudio.com/docs/cpp/config-mingw
https://cs50.harvard.edu/x/2024/