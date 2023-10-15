# ELAC-RUBY-CrashCourse
## CONTENT
1. Goals
2. Website Vs Web Application?
3. Installation of Ruby
4. Installing SQLite
5. Installing Rails
6. Recap

## THE GOAL
The goal of this crash course is to teach students web development using the Ruby framework. 

- In this Crash Course you will learn the basics of Ruby Framework for your web development journey.
- You will develop skills that will make you more confident tackling web development problems.
- You will learn database handling
- How to deply Ruby On Rails application



<img src = "https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/6addd90d-6e4d-4a64-a10e-10476b4d81c8" width = "650" height= "450">

## Before we proceed we have to define what a website is and how it differentiates between a web application.

To begin the development of a web application we must first understand the difference between a web application vs website is. A website is a collection of pages that provide information to the end users, to enter a website one searches it up using the website name or an URL. Websites are separated into two categories; *Dynamic Websites* and *Static Websites*. 

***Dynamic Websites*** : Dynamic websites are able to change their layout base on the users need, this websites typically required lots of user interaction. The interaction is not as obvious but users are able to interact with databases in real time. Examples of this websites are Facebook, Amazon or CNN

***Static Websites***: Static Websites on the other hand are more fixed with its contents, they don’t have the interactivity that Dynamic websites have which also makes them easier to develop and to deploy. Examples of Static Websites are blogs, small business and online portfolios.

**Conclusion**: Now that we have establish the definition of a website we must now ask ourselves what are web applications? Web applications are computer programs that are then access through the the internet, this means that web applications function on a client-server relationship. Web applications are highly customizable, they can do more tasks then typical websites such as creating documents, managing projects and sending emails.

## Installing Ruby 

Now that we establish the difference of websites and web applications, we will now begin a short introduction to web applications using Ruby On Rails. To begin we must do some simple installations for our work environment. Before we begin the installation of the Ruby we have to identify what System we are going to be using. At the moment this guide is only for Windows but I'll make sure to add both MacOS and GNU+Linux later on.


1. First we must go to the [Ruby Installer](https://rubyinstaller.org/)
   The website should look like this :
    
![ruby installer webpage](https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/7767b591-9919-4eb5-83f8-a7697b069844)

2. Once you have the page open we will then go to Download, the download page should look like this:
Make sure to download the file that ---> `Ruby+Devkit3.2.2-1(64)`

![image](https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/a49064d0-4348-49de-b713-a77a77d65707)

3. Once you have the download file, go to your downloads and run the Ruby setup page. To use Ruby we must accept the license agreement and then press 'Next'

![image](https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/a25835dd-01fe-4d78-b32d-d0512db981b3)



  

## Installing SQLite

[![Watch the video](https://img.youtube.com/vi/watch?v=5ZkC_WE2W6s/https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/7d75bf0b-eb05-4ad9-84e6-dedf9b807818)](https://www.youtube.com/watch?v=5ZkC_WE2W6s)



## Rails Installation 

To install rails we are going to use the command line and input:
`gem install rails`
![image](https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/ab86c71d-2af5-4965-8f58-a86c23b9fc67)

Once the system finishes the download, you or might not have this message. Just install the new version if it those pop up.

![image](https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/9ab842fc-a183-4003-a9c8-331375c017b9)

If you do get the msg make sure to follow the instructions and install the package. (In my case the computer is making me aware that they'res a update for RubyGems)

![image](https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/7aba4f4c-effd-4feb-9103-6f0826cc0fb6)


## Recap, before we proceed lets check installations

This steps is simple we are just going to check if we correctly installed all the programs needed. To do this we are going to open the command line and enter this command and press enter
1. `ruby --version`
2. `sqlite3 --version`
afterwards we will check for SQLite, to do that we must run 
3. `rails --version`
and to conclude we must then check for rails, to do this just run this command 

To end make sure that your results are similar to mine, 

![image](https://github.com/AngelinCS/ELAC-RUBY-CrashCourse/assets/59464059/53930aef-24e9-464b-aa9b-037cf5c8cfdd)












