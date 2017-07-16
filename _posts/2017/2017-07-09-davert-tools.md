---
layout: post

permalink: tools-davert/

real_title: "What Tools Does The PHPrince Of Persia Use In His Daily Adventures?!"

title: "[It’s The Tools Talking] - What Tools Does The PHPrince Of Persia Use?!"

description: "As a PHP Developer you should be curious about what tools others are using, especially the php experts. Come learn what PHP tools Michael Bodnarchuk aka The Prince of Persia, is using."

keywords: "php tools Michael Bodnarchuk uses, expert php tools used by Michael Bodnarchuk, php tools, expert php tools"

date:   2017-07-09

image:
  path: images/posts/2017/davert-bgphpconf.jpg
  width: 900px
  height: 600px
  
banner_image: 2017/davert-bgphpconf.jpg
img_type: jpg

tags: [davert, Michael Bodnarchuk, Interview, "2017", PHP]
categories: [The Tools Talking]
toc: true
author:
    name: 7php
post_quote: "I really like building stuff and PHP helps me with that."
post_quote_person: "Michael Bodnarchuk"
tweet_quote: "https://ctt.ec/696Ba"
---

## Purpose Of This Interview | The `3rd` One

This is the 3rd edition in a series of "[It's The Tools Talking]({{ site.site_url}}{{ site.data.categories.tools_talking }})". Something which I kickstarted right on the 1st of Jan to start off the year 2016. I am continuing with it, [breaking my 1yr Hiatus as I announced last week]({{ site.url }}{% link _posts/2017/2017-07-01-7php-v3.md %}).

For this episode `#3`, I’m honored and much delighted to host tonight The PHPrince of Persia a.k.a Michael Bodnarchuk (also known as @Davert online). I have had the priviledge to meet Davert in person and enjoying [the bgphp trip in the special PHP Bus during our stay](https://twitter.com/hashtag/bgphp16?f=tweets&vertical=default&src=hash){:target="_blank"} with The Amazing @bgphpconf 2016 in Sofia. I must say Davert is an incredible human being, full of creativity, very friendly, always willing to help and above all very very very passionate about what he does, specially testing with @codeception - a php testing tool which he created and gaining so much traction during the recent years.

I will not say more about this (PHP)Prince of Persia, as I will be introducing him again in another `#7PHP PHP Interview` soon enough. So let's dive straight into what tools he tames for his daily coding adventures.

## And Now The Interview | It's The Tools Talking With Davert

#### >> Hi Michael, Please tell us a bit about yourself and your involvement with The PHP Community

My name is **Mykhailo Bodnarchuk** (that's how the Michael is spelled in Ukraine) or just Davert.

I'm working on [Codeception testing framework](http://codeception.com/){:target="_blank"}, which is a framework that simplifies testing of complex applications.

I started Codeception in 2011 because I wanted to write tests effectively without spending time on configuring, and writing bolierplate code for my tests. PHPUnit was the most popular tool. But it was not efficient for something bigger than a unit: there was no effective way to write a single test for an application with controllers, database, and all the inner pieces. However, such tests seem to be the most efficient, because one test can indicate the visibility of the application.

Also, I wanted my tests to be readable so my CTO could read them, so I asked him for a week to work on a testing framework on my own. After I built the prototype I started to think how to scale this solution for browser tests, framework tests, to make it usable for others. That's how I started to work on Codeception. I hope PHP developers enjoy using it, lots of good developers help to develop it and make it better. I must say I'm so thankful for our core team, without them, I'd probably lost in all the issues and pull requests :)

I really like building stuff and PHP helps me with that. Unfortunately, I'm not so lucky to sell my products, so I do it for free :)



#### >> How does your workstation look like

{% capture img_url %}{{site.url}}/images/posts/2017/davert-workstation.jpg{% endcapture %}
{% include image_caption.html imageurl=img_url title="The workstation of Davert" caption="The workstation of Davert" %}

Right now I'm using Lenovo S440 as my primary notebook. And this big one laptop for music, TV series and Unreal Tournament. You know, I discovered that playing 20 minutes in UT before working makes me more productive. Fast deathmatch makes me concentrated, focused, and I can work better without procrastinating.

Also, I need to say I prefer portable workstation so I can work from any place. Sometimes I move from my room to kitchen to get faster connection to the teapot :)



#### >> The OS that you have used & which one you prefer to work with

I worked with Windows but now completely switched to Ubuntu. Making PHP, Ruby, MySQL, and other stuff work on Windows make you so god damn cool hacker that MacOS and Linux users can't even imagine. However, being a Windows hacker is not so profitably nor cool. In this case, Ubuntu is much better (esp for last 5 years) for development. Linux is cool because you develop in the same environment as your server will be. No need to learn about virtualization or "brew" magic. Everything you need can be installed by apt-get, what can't be done with apt-get is easily retrieved with docker pull. And yes, having native Docker containers is a killer feature of Linux.

Also, I really like the UI of Ubuntu, the software is also pretty good. Everything I'd probably need for development is already there. I think with the rise of Electron apps we will get more and more cross-platform apps targeting Linux platform as well. For example, I'm really happy with [Nylas Mail app](https://www.nylas.com/nylas-mail/){:target="_blank"}. I use [Vivaldi](http://vivaldi.net/){:target="_blank"} browser which I recommend to everyone, it is constantly improving and highly customizable because it is a browser built inside a browser.



#### >> What VM software you use or have used.

VM is a pain. I used Vagrant but I hate it. For most setups, I can get it running on Linux natively. If not - in Docker container.

Right now I'm using Android Emulators to test the mobile testing of my side-project CodeceptJS.



#### >> Your database management tool

`Emma` (simple stuff on Ubuntu)



#### >> Your Testing Tool (Unit testing & functional testing)

Codeception :)

But I work not only with PHP so I'd extend this to: `Mocha` in **JavaScript** and `Minitest` in **Ruby**.



#### >> Your Debugger / Debugging Tools arsenal

`var_dump`, console.log, puts, WTF, screaming, hitting walls, voodoo dolls with a curse to all software developers, and If nothing of those helps I configure PhpStorm debugger.


#### >> Your deployment tools

`Capistrano` (for Rails), `Ansistrano` (with Ansible) and `Robo` for my opensource projects.



#### >> Version Control Systems you use & which you tend to prefer

S... V.. GIT! Does it sound unexpectedly?



#### >> Frameworks that you use & which you tend to prefer the most

Rails (that sounded unexpectedly, right?). I prefer Rails because it has stable ecosystem and API, its concepts didn't change dramatically since Rails 3 released 7 years ago. Most of the solutions for common problems are already solved and packed into gems. Big opensource projects like GitLab or Discourse provide a solid knowledge base of current good practices. For startups, SaaS application I'd definitely choose Rails.

For a current project (in which I work with a team of PHP developers) we've chosen Laravel Spark. I need to say Laravel is highly inspired by Rails, so it's pretty easy to get in with it. We also had experience working with Symfony but no one knew how to start fast with Symfony. Yes, Laravel is much better for startups.

I had to learn a bit of Symfony, Zend, Yii, Phalcon and other frameworks because Codeception supports them all. They are all pretty good, but they are just translating HTTP requests into the business code. So I prefer framework-agnostic business code. That's what makes PHP different from Ruby. PHP by itself, its frameworks, tools are constantly changing so it is better not to rely on current framework realization.



#### >> IDEs that you have used or Your "Programmer’s IDE" of choice

PhpStorm (for PHP), SublimeText (for Ruby), Visual Studio Code (for JavaScript). Yes, I prefer to have an editor per language.



#### >> Your Documentation Tool?

I use [GenerateMarkdown](http://robo.li/tasks/Development/#generatemarkdowndoc){:target="_blank"} task from [Robo](http://robo.li/){:target="_blank"}. It translates all docblocks into markdown files. This is used by Codeception, AspectMock, and Robo project itself.



#### >> PHP Code Beautifier?

I don't really bother about it. I just run `robo code:fix` from time to time.



#### >> In-Browser Tools (Firefox or Chrome add-ons)

I use [Voblet](https://chrome.google.com/webstore/detail/voblet/jgnennkfpahpjpbmbbodaipgoilccmco){:target="_blank"} to save interesting GitHub projects. I started to use [Grammarly](https://chrome.google.com/webstore/detail/grammarly-for-chrome/kbfnbcaeplbcioakkpcpgfkobkghlhen){:target="_blank"} to quick-fix my writing.



#### >> Web Hosting service you have used and which one you recommend/prefer

@DigitalOcean is the best.



#### >> Do you use any software you use for the following:
##### >>> time management
##### >>> todo list management
##### >>> managing your calender & events

I'm so irrational person so nothing helps me to manage time and tasks. I keep everything that is important in my head, as well as important events. However, I work only on things I feel passionate about. Whenever I try to start using ToDos I'm putting into it the most boring tasks, and as a result, I never open that todo app again. I can't plan my time as well because my life is not my work: I like spending time with friends, I like hiking, and If someone calls me to some strange adventure, I'd probably drop everything and go for it. Luckily I always return because I like PHP and its community.



#### >> Your tools for communicating / handling communication?

Skype is my primary tool for business communication, for some projects I use Slack. But to be honest I don't like Slack as it is pretty hard to keep up with lots of chat windows. I'd really like to participate more in community chats (like in those on Gitter or in IRC), but I always feel like they drain my time and energy.



#### >> Two community tools that stood out for you & why.

I really like the [WebDriver](https://github.com/facebook/php-webdriver){:target="_blank"} implementation by Facebook. Once Facebook published it I was so happy to discover its API. It was so nice and fully compatible with Java clients. Finally, PHP becomes a first-class player for writing browser tests with it. I really hope more and more people would discover that PHP is not just about WordPress or web sites. PHP can be used for acceptance testing, for scripting, for deploying... You name it!

And I cannot ***not*** mention [Composer](https://getcomposer.org/){:target="_blank"}. That's impressive and well-made solution. Thanks to Jordi and Nils for making it. Thanks for making it stable and cheap, without vendor locking. I really hope they will turn their Private Packagist into a profitable business, as they truly deserve this.



#### >> The tool that has given you the worse experience

VIM :) I could manage to quit it but I couldn't live with it :)



#### >> The tool that has given you the best experience or been your life-savior / has impacted your DEV life.

PhpStorm (thanks, JetBrains), Visual Studio Code, Docker, Ansible, Capistrano. So much of those!



#### >> Any other tools you use that you want to share with us?

I'd really like to recommend [Robo task runner](http://robo.li/){:target="_blank"}. It can easily replace bash scripts, deploy scenarios and some basic asset management. Robo helps me to run all my projects. Look how this code is better than common bash-scripts! Yes, this is true PHP!

{% highlight ruby %}
public function publishFrontend()
{
  $this->taskExec('ember build')
    ->dir('frontend')
    ->printed(false)
    ->run();

  $this->_copy('frontend/dist/assets/frontend.js', 'backend/app/assets/javascripts/frontend.js');
  $this->_copy('frontend/dist/assets/vendor.js', 'backend/app/assets/javascripts/vendor.js');

  $this->taskGitStack()
    ->add('backend/app/assets/javascripts')
    ->commit('updated frontend scripts')
    ->push()
    ->run();      
}
{% endhighlight %}



## Your Questions On Twitter

That's it folks. Hope you've learned some new stuffs today. If you have any question, direct them on Twitter by mentioning @7php & @davert


## Credits

- Main featured pic credit goes to @bgphpconf
- All other pics in this posts are from Michael aka @davert