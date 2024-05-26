## Website Name
itinker.tech
## Project Proposal
This website is designed to provide users with a basic education of the C programming language. On the internet, there are many tutorials on how to learn the C programming language, however usually these courses are large and hard to digest, as they include large amounts of computer science jargon, or they are paid for. Also, tutorials do not always provide practice problems which means that users are not able to try and apply what they have learnt. This website is to designed to be a solution to beginners who have no idea on how to code, and have had no experience in thinking in the style of computer science. Furthermore, this website will provide a simple run down on the syntax required to make legal C code. This will be done through digestable pages of content, allowing users to absorb the information at their own pace, with actionable steps so that learners stay engaged, and improving user experience. After landing on this idea, consideration was put into how the information could be best presented. There were many options, however a blog post style website seemed to be the winner as it would be able to achieve the goal of teaching people about the C programming language the best. This is due to the fact that each blog post could be bite sized lessons that can be taken at a user's own pace. 

## Accessibility Features
Including alt text will help with people who are visually impaired. This will be easy to implement as HTML documents have a built in alt attribute, and users who use screen readers will have the alt text describing the image read out to them. To further help with accessibility, the website is entirely entirely accessible via keyboard, and users who are unable to use a mouse can navigate the pages with relative ease. This will be possible as most web browsers allows users to navigate websites using the TAB buttonand "click" on buttons with enter, and also with the menus made to be easy to navigate with keyboard only. This is to make sure that users who are unable to utilise a mouse are still able to navigate the website's menus without issue. Also, a search feature has been put in the UI, which would help users find individual blogs, however there not that many blogs, so the side menu links are good for now. This is to consider people who find it too much of a hassle to click through the menus to find the blog post they want. 

## Website Hosting Solution
Instead of using a third-party provider like Wix or Squarespace, the decision was made to set up the domain and webserver for hosting the website. This is due to multiple advantages, like more control over my website's file configuration and more freedom to customise my website. Many features that are able to be implemented through code are hiddent behind a paywall with these no-coded solution providers. Furthermore, Third party no-code website solutions are quite restricted in terms of features able to be added, and also may deal with file saving issues and latency. As Squarespace and Wix update, these providers may cause changes in the formatting for the website. By hosting the files on a cloud server and using a personal domain, the longevity of the website is extended as the files are in full control by the developer. Utilising Github's Student Developer Pack, a free domain was able to be registered for free. The web server provider that was chosen was DigitalOcean, as it came with the Student Developer Pack. Debian was installed on a web server, and then nginx was used to be able to use the web server as a host for the website. From there, pointing the .tech domain to the DigitalOcean web server was just a matter of putting the web server's IP address into .tech domains. 

## Coding Process
To get me started on the process of creating a webpage, I downloaded a premade html template from HTML5UP to get myself started with a blog post style website. 

## Reflection
To start, choosing to write the website's code by hand instead of utilising a no-code solution may have cause me to lose time and may have caused me to produce a less aesthetically pleasing website. This is due to my lack of experience in HTML. However, the advantages of editing the HTML document manually were quite significant. I was able to learn a lot more about frontend website programming languages, like HTML, CSS and Javascript. Furthermore, due to the fact that my hosting solution is my personal domain and web server, I am able to have much more control over the file configuration of my website, making it much easier for me to maintain the website in the future. The user interface was made to be as easy to navigate as possible. This was done by creating many different ways to reach a link, and an intuitive home page design. 

Although there are platforms like w3schools and other online courses, this website is designed for users who have never even hear of computer programming or coding, and have no clue where to start. With w3schools, they have a lot of programming languages, and beginners may be a bit overwhelmed with where to start. In future, to avoid this problem, a recommendation page may be created, recommending different programming languages for different types of users, potentially adding a quiz for users to find the perfect programming language for them. 

Due to the fact that the theme of my website is teaching people about the C programming language, a challenge was maintaining enough white space to ensure good user experience. This is because there is a lot of information on each of the pages, and blocks of text will decrease user engagement. To help try and alleviate this issue, it was important that images appropriately spaced out the text in a way that each paragraph was digestable. Other elements like forms and tables also helped with this issue. 

This website is able to relate to the trend of blog posts that was quite common for the early ages of the internet, and maintained significance until recently, when social media platforms developed so people no longer had to set up websites for self expression. However, the decision to style this website as a blog should help users get an idea of pace of learning, as each blog post will become "lessons" that users are able to explore at their own pace. 

## Sources
Images:
https://www.boardinfinity.com/blog/content/images/2023/02/C.png https://miro.medium.com/v2/resize:fit:640/format:webp/1*wHKe6W4opLmk6pb7sxZz6w.png 
https://media.licdn.com/dms/image/D4D12AQGxLt3lZb-3FA/article-cover_image-shrink_600_2000/0/1693882752310?e=2147483647&v=beta&t=oIqV0XAIi0Wqb8-HAFjyPP8310CE2rBd5paDKSryqcY 
https://terminalroot.com/assets/img/windows/mingw/mingw.jpg 
https://www.adslzone.net/app/uploads-adslzone.net/2019/07/logo-inicio-windows-10.jpg?x=480&y=375&quality=40 https://www.vpnanswers.com/wp-content/uploads/2015/02/Connect-to-Linux-server-from-Mac.png 
https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/C_Programming_Language.svg/380px-C_Programming_Language.svg.png?20201031132917 
https://microsoft.github.io/makecode-csp/static/010b16b23ea4e9d9474b1d6bb4969a52/518fe/ascii-table.jpg https://www.convertbinary.com/wp-content/uploads/monitor-1307227_1920-1024x723.jpg https://iq.opengenus.org/content/images/2019/08/decision-making-c-1.png 
https://media.geeksforgeeks.org/wp-content/uploads/20230302091959/Arrays-in-C.png

Information:
https://www.britannica.com/technology/C-computer-programming-language
http://www.geekswithgeeks.com/c-programming/c-programming-history-features
https://www.educative.io/blog/object-oriented-programming
https://www.codecademy.com/resources/blog/object-oriented-programming/
https://hackr.io/blog/difference-between-c-and-cplusplus
https://medium.com/@isaac_70614/how-c-source-code-becomes-an-executable-program-f2e00ecf5c5c
https://code.visualstudio.com/docs/cpp/config-mingw
https://www.wikihow.com/Compile-a-C-Program-Using-the-GNU-Compiler-(GCC)
https://cs50.harvard.edu/x/2024/
https://w3schools.com/