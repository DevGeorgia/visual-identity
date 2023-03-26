# visual-identity

Visual-identity is a little web page template to present yourself during your job search. It sums-up everything you want to tell to a company and everything she wants to know about you.

The project is built with Spring Boot and [Thymeleaf](https://www.thymeleaf.org/) Fragments, you are free to use any fragments you want or remove any fragments you don't want.
This template is neutral (black/white), you are free to customize the design to be unique and more like you.

The CSS is based mostly on Bulma CSS framework : [Bulma](https://bulma.io/)

## Overview

![Visual-identity-overview](/screen/visual-identity-template.png)

## Spring Classes

* PortfolioApplication : Main SpringBootApp class
* MyController : Call the "about.html" templates containing all your desired fragments
* MyConfiguration : contains the configuration to manage the internationalization of the application

## Thymeleaf Fragments

If you don't want to use all the fragments you can remove them in the "about.html" template.

* head : contains the <head> tag of the page
* footer : contains the <footer> tag of the page
* jobs : contains the list of the jobs you are looking for
* location : contains the information regarding the location of the job you are looking for and your remote preferences
* lookingfor : contains the key points you are looking for in a company
* redflags : contains the key points you want to avoid in a company
* skills : contains a list of your main skills
* social : contains a little description about yourself, your picture and your social links (linkedin/github/twitter)
* strengths : contains your key strengths to stand out
* projects : contains a list of your main side projects in little cards

## Spring Internationalization

Web page is based to the web browser language.
There is no hard coded text in the html fragments, everything is in the Resource Bundle "Messages".
Two languages are managed in this template : EN and FR
Feel free to add any other language you need by creating another file messages_lang.properties

## Credits

Icons used from Flaticon :
- Twitter icon created by [Freepik](https://www.flaticon.com/free-icons/twitter-social-badge")
- Linkedin icon created by [Google](https://www.flaticon.com/free-icons/linkedin)
- Github icon created by [Pixel perfect](https://www.flaticon.com/free-icons/github)

Images used from Freepik :
- [Image by vectorjuice on Freepik](https://fr.freepik.com/vecteurs-libre/bloguer-amusant-creation-contenu-streaming-ligne-blog-video-jeune-fille-faisant-selfie-pour-reseau-social-partage-commentaires-strategie-auto-promotion_11669170.htm#query=blog&position=0&from_view=search&track=sph)
