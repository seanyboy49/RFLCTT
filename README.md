![alt-text](https://github.com/ChesterHub/RFLCTT/blob/master/assets/Logo.png)

## Purpose
For most people, early mornings are usually a rush of activity with little time to waste. In the midst of washing up, getting dressed, and making breakfast, having to stop to check the weather or your bus schedule can be a real impediment to your momentum. 

## Enter RFLCT
Rather than build a another productivity app, we approached this problem from a place that takes up most of the morning ritual: the bathroom. And where exactly do you hack a bathroom? Why, the mirror of course. 

**RFLCT** is a voice activated smart mirror that uses facial recognition to recognize a user and display helpful information in a beautiful inteface. It was a Dev Bootcamp final project based on <a href= "https://github.com/MichMich/MagicMirror">Magic Mirror</a>, an open source modular smart mirror platform. 

## So what does it do?
RFLCTT has two modes: a default mode and a user mode. 

The default mode will load the mirror's standard modules: time, current weather, 5-day weather forecast, upcoming US holidays, a random compliment generator, and headlines from a few news sources. 

But if you say "Look at me!", RFLCT will activate its facial recognition module via built-in web-cam, snap a photo of you, run it against a database of users, and load your custom modules. 

Take a look at our live [demo](https://drive.google.com/file/d/0ByJWiiwdYyl4RlUyNDE4OGQ2RE0/view?usp=sharing)

## Team

![alt-text](https://github.com/ChesterHub/RFLCTT/blob/master/assets/team.png)

### Github links 
[Kevin McGovern](https://github.com/kevmcgovern)

[Sean Lee](https://github.com/seanyboy49)

[Chester Hoang](https://github.com/ChesterHub)

[Ken Olsen](https://github.com/kennetholson)

## Technology Stack 
From the get-go, we had two stretch features in mind: facial recognition and voice commands. We managed to achieve both with a menagerie of unfamiliar technologies and a lot of trial and error. 

![alt-text](https://github.com/ChesterHub/RFLCTT/blob/master/assets/stack.png)


## Hurdles 
- Unfamiliar tech stack (Prior to this, none of us had ever used Node, Python, Amazon Alexa or machine learning api's).
- Lack of documentation.
- Experimentation with different building materials (e.g., deciding between thick, two-way glass or thinner, two-way acrylic). 
- Building our software an Mac-OS environment and then having to port it over to a Raspberry Pi.

## Future Plans
This project exposed ourselves to several new technologies, programming languages and software design patterns. It was also an opportunity for us to work on something we were all really passionate about: combining software with raw, tangible materials in true DIY fashion. As of now, we have no plans to market or sell our mirror. But whenever we have time, we would like to build out the following features:
* Motion sensing so that the mirror activates upon motion detection
* Integration with Gmail, Google Calander, iCal and Facebook 
* Integration with favorite Youtube channels
* User interaction via hand gestures, captured through the webcam 
* A user profile onboarding process (right now, all user profiles have been hard coded in). 



