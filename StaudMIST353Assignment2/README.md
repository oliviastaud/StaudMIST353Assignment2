# MIST353 Assignment 2 
## Overview

This README provides information about FloraForecast, a gardening campanion web application that has an ultimate goal of offering accurate weather information and personalized gardening recommendations.This version is the prototype, currently in its initial phase.

## Table of Contents
1. [Project Description](#project-description)
2. [Conceptual Aspects](#conceptual-aspects)
3. [Technical Aspects](#technical-aspects)
4. [Research Findings](#research-findings)
5. [Future Advancements](#future-advancements)
6. [Citations](#citations)
7. [Reflection](#reflection)

## Project Description

FloraForcast is a web application designed to assist gardeners in planning their gardening activities based on weather. Right now, the home page introduces users to the site and takes them to Planner.html, which will eventually be able to let users access accurate weather forecasts for their location, but currently only gets the user's coordinates when the button is clicked.

## Conceptual Aspects

### Home.html
- The home page provides an overview of FloraForecast.
- Contains a navigation link to Planner.html.

### Planner.html
- Allows users to give their current location for eventual accurate weather information.
- Displays a weekly weather forecast, including information like Temperature, Precipitation, and Wind Speed.

## Technical Aspects 

### Technologies Used
- HTML for creating web pages.
- CSS for customizization.
- Bootstrap for enhancing design.
- JavaScript for geolocation.

## Research Findings

### Websites
##### [1. GardenSavvy.com](https://gardensavvy.com/)
On this site, there are options given to you immediately on the homepage to locate suppliers, grow a garden, or design a garden. There’s also a search bar to search what kind of gardening items you may need. At first glance, it’s super visually appealing, not too overwhelming but colorful. One thing I don’t really like about this are the graphics used because they don’t match the format of the rest of it, in my opinion. One of the tabs at the top includes “GardenAI” which I thought was a super cool feature. For example, I asked “When is the best time to grow blueberries in WV?” and my reply gave me a very helpful and specific answer. I noticed “?” in the URL when I searched the on-site blog.
##### [2. Gardeners.com](https://www.gardeners.com/how-to/garden-planner/garden-planner-home.html)
When exploring this site, I found many features I think could be useful. It gives very clear directions as soon as the site is accessed like, “Click the Pre-Planned Gardens to get a quick start. Choose from 26 options, including many designed just for elevated raised beds. To create your own garden, click Plan Your Own Garden. Just drag and drop crops to the planting grid and the planner fills in the number of plants.” For users who may not be particularly tech-savvy, this is a great feature. There are also tabs to access a house plant or vegetable encyclopedia, and based on the zip code you type in you can get results from the rainfall calculator and zone finder.
##### [3. VegPlotter.com](https://vegplotter.com/)
On vegplotter.com, there’s a login option to make an account. There is a simple drag and drop feature for garden planning. Something unique about this site is that you are able to plan months and even years ahead of time. My favorite aspect of this particular site was the “plants” tab. There are many common plants you can click on, and when you do you’re brought to a page specifically for that plant. On that page, there is a “How to Grow,” “How/When To Harvest,” as well as a table including a planting schedule which tells you when you should sow indoors, plant out, and harvest. Overall, this site is super convenient.

### Repositories
##### [1. Garden Planner](https://github.com/phillipdupuis/garden-planner?tab=readme-ov-file)
In Garden Planner, you are able to design your own garden from a mobile device or computer. You can manipulate the layout, and drag actual graphics of different crops in each square of the garden. There are options to add/delete rows and columns so that you can alter the layout to make it personal. A really cool feature of this is that when you go to place a new crop next to an already existing one, you get options – compatible, neutral, and combative – so that you don’t have to do any research. It’s easy, convenient, and efficient!
##### [2. Yellow Book](https://github.com/sarahJDawns/yellow-book-garden-planner)
At first glance, the readability of Yellow Book isn’t as great as Garden Planner. There are plenty more words, which can sometimes be overwhelming for the user. I do like how colorful it is and the simplicity of the colors and graphics. Included in this readme is information on how it works. On this app, I really like how local weather information and plant hardiness is provided when the city and zip code are searched. Like Garden Planner, Yellow Book lets you drag and drop garden icons to create a mockup of ideal garden layout. 

## Future Advancements

- **Enhanced Interactivity:**
- **Additional Pages:**
  - **Weather Source Linking:** Get weather forecast information from a reliable weather source.
  - **Plant Information:** Add a plant database with details about different plants, their care, and more.
  - **Garden Design Feature:** Create a garden design feature allowing users to plan and visualize their garden layouts.

## Citations

To assist me with this assignment, I used [ChatGPT 4](https://chat.openai.com/) with the following prompt:
> "I want to insert the following code into my existing code. *pasted JavaScript code for geolocation* How do I add a functional button that says "Use my Current Location"?
The output gave me the information I needed. I tested it out and it worked just how I hoped.
> "How do you suggest I should write CSS for existing HTML classes?"
I got back several suggestions with added comments on what each block of code did. I tested out multiple, deciding to use a 2 of the suggestions.
> "Give me a recommendation for an outline template for a README template for class. I'd like it to be neat and not too complicated. Here are the guidelines *listed the requirement headings*
I received a nice outline template which gave me the idea for a Table of Contents.

- [W3Schools JavaScript, Bootstrap, HTML, and CSS)](https://w3schools.com)
- [Bootswatch](https://bootswatch.com)
- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github#adding-an-image-to-suit-your-visitors)


## Reflection
The usage of generative AI was a great help to me during a few parts of this assignment. It was able to generate idea with the inputs I typed in, and when tested, were mostly accurate. The biggest help for me was going back and rewatching the recorded lectures. I had some difficulty with using bootswatch and creating this README, as well as copying the links and scripts from the Layout.cshtml file. I was able to go to the lectures and review that information, being able to go through it step-by-step and correct any mistakes. Lastly, the use of recommended links, especially w3schools, was the biggest help in checking all the boxes for this assignment. Overall, I was able to gain plenty valuable knowledge during this process.


