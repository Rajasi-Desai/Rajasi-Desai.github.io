---
title: "Epicer"
excerpt: "Hungry? Want to eat home-cooked meals to eat healthier? Have various kinds of groceries in the fridge but don't know what to make? Wait no more! Use épicer to get some epic(er) recipes with whatever is available to you!<br/><img src='/images/projects/Epicer/Epicer_Logo.png'>"
collection: projects
---

<!-- TODO Challenges, scope contribution, pictures/screenshots-->

![Epicer Logo](/images/projects/Epicer/Epicer_Logo.png)

**Winner of Best Venture Pitch at HackUMass VIII**

## Description as a Tweet:

Hungry? Want to eat home-cooked meals to eat healthier? Have various kinds of groceries in the fridge but don't know what to make? Wait no more!
Use épicer to get some epic(er) recipes with whatever is available to you!

## Inspiration:

Cooking meals at home is something everyone does. It could be out of necessity or just because one likes to cook. Though everyone wants to eat home-cooked meals rather than takeout because it's healthier. But we don't always have the required groceries for a particular recipe. We all have been in the situation where we want to make something but the fridge just has some random ingredients in it. Even during the pandemic, it is sometimes difficult to get the groceries and we have to adjust with whatever is available to us. But putting together something from those random ingredients proves to be a challenge. So, we thought what if we could make something that gave us recipes, that actually taste great, from whatever is available. So, having an app that directly gives you recipes with whatever one has is the epitome of convenience because you can directly take pictures from your phone and the recipes are there at your fingertips.
The idea behind the name is also a funny story. We usually buy things from our grocery list depending on what recipe we are planning to make. Since the app essentially reserves that process, gives recipes based on ingredients, the name reverses the word "recipe". And to add to the fun aspect of it, the French word "épicer" means "to spice", so you are essentially spicing up your groceries.

## What it does:

épicer lets you take pictures of all the ingredients you have with your phone camera or type the list of the ingredients; whichever you prefer. Once you are done with that, it gives back a list of recipes with all the entered ingredients. You can then make any one of the recipes and enjoy your meal!

## How we built it:

We divided the project mainly into front-end and back-end, with two team members for each. Then those two were further divided into various smaller tasks and these tasks were assigned to everyone. After we were done with a good chunk of coding on both ends, we focused on integrating both, front-end and back-end, together.
The main framework of the app was made using React Native. This part was done with Rajasi and Maanya, the front-end team. The work consisted of building the actual app, designing UI/UX, and setting the navigation throughout it. Setting up the camera used to click the photos of the ingredients, and typing screen to type in the ingredients. The images were sent to the backend which was made by Walker and Tony. They used image recognition software made in Python to recognize the various ingredients. After that, the list of those ingredients was sent to get the recipes. Using web scraping in Python, the links of various recipes were obtained from the internet. Those links are stored in the Firebase Database as a JSON file. They are then retrieved by the front-end displayed to the user in the app.

## Technologies we used:

- HTML/CSS
- Javascript
- Node.js
- React
- Python
- AI/Machine Learning
- Misc

## Challenges we ran into:

Among the 4 members our team consisted of, we had to tackle 3 different time zones (as large as almost 12 hours apart). Trying to manage so that everyone was able to communicate and work efficiently was definitely a challenge. Also, all the technologies we used were relatively new to all of us. So, there we a very steep learning curving trying to figure everything out in the 36hr period of the hackathon and make something out of it. Available datasets that corresponded with our project idea were limited, with the best dataset we found having an average of 80 images per classification, to split into validation and train data. We originally wanted to put our python service on google cloud but ran into too many problems deploying our code over the platform.

## Accomplishments we're proud of:

The app we made has working elements that work the way we intended them to. We figured out all the different kinds of technologies and integrated them. We were also able to figure out image recognition and make it work. We achieved all this despite major differences in time zones and all of it being fully virtual.

## What I learned:

I was able to learn more about React Native and in general learned how to troubleshoot various things. The front-end aspect was fun to learn, despite being frustrating at times. It was also very interesting to design an app from scratch and see all the nitty-gritty behind it. I also gained more experience in communicating and collaborating with other people. And also learned more about Git and GitHub. Even though I did not exclusively work on the back-end, I picked up some interesting facts about web scraping and image recognition.

## What's next:

There is a lot of scope for this project. Given the time constraints, we had to aim for something executable in 36 hours. One of the major things is making the image recognition software more stable and implementing image segmentation. This would result in multiple items being labeled in parallel and having accuracy across a wider range of ingredient classifications. Another room to expand is having user authentication (i.e making accounts, storing usernames and passwords) to make the app more secure. Also, finding a better framework for running python in a more traditional server format such as using flask would be another place to expand.

## Built with:

The main framework of the app was made using React Native. It is used to click the photos and upload the ingredients. The images are then stored in the Firebase database on Google Cloud. They are then retrieved using Python and sent to the image recognition software made with the Keras library. Once, the app gets the list of all ingredients, using web scraping in Python, the links of various recipes are obtained. Those links are stored back again in the Firebase Database in JSON format and retrieved. This file is then used to display the corresponding recipes on the app.

## User Interface:

The following are the UI views of our application and a brief decription of them:

### Homepage

Homepage of the app.

![Homepage](/images/projects/Epicer/Epicer_main_page.png "Homepage")

### Add ingredients

Type to add ingrdients from your fridge.

![Add ingredients](/images/projects/Epicer/Epicer_my_fridge.png "Add ingredients")

### Camera to upload ingredients

Click pictures to add ingredients.

![Camera](/images/projects/Epicer/Epicer_taking_pic.png "Camera")
