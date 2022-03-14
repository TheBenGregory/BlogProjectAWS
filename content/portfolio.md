---
title: "Portfolio"

---



### gigAgent


[gigAgent on gitHub](https://github.com/TheBenGregory/gigAgent)

##### Overview

gigAgent was my first ground-up client side build. I utilized React.js and CSS for the styling to create a peer-to-peer platform for real estate agents. The intent is to connect busy agents with available agents to perform showings, freeing up time and travel for the busy agent, and providing an income opportunity for the available agent.

It utilizes a JSON server built and served locally to store user data. The users can be one of two types (gigAgent or a requesting agent) and requests can be generated via form by the requesting agent and accepted and completed by the gigAgent. 





{{< image src="/gigAgentSS.jpg" alt="gigAgent Screenshot" position="center" style="border-radius: 8px;" >}}


##### Learning Experience

gigAgent is the project where React really came into focus for me. Hooks took hold in my mind and I was able to really affect the data being moved around the application. I utilized hooks, event targeting, a variety of fetch calls, and made it all dance in JSX. 

At the end of the two week sprint there were some lessons learned:
* an apiManager module would have allowed for much cleaner, more readable code
* I planned a lot, but I did not plan enough. Plan, plan, plan.
* There is a difference between enjoying application design/styling and being good at application design/styling. I could not have been more sick of the color scheme I had landed on in the beginning. :)



### Muirist

[Muirist on Github]()

### Overview

Muirist is my first full-stack application that I built in React and Python/Django on the backend. It is designed to allow users to freely share brief packets of info relating to US National Parks. The .gov websites are a wealth of information, but they can be too much sometimes, particularly with a park you are already quite familiar with. Muirist is a resource for the lesser-known, off-the-beaten-path things to do and see in the park.


{{< image src="/muirist.png" alt="Muirist Screenshot" position="center" style="border-radius: 8px;" >}}

My backend serves as a repository for users to submit and request data about individual parks and they are able to save the snippets they are interested in in a "backpack" that is in essence a shopping cart. This allows a user to further review an item later. 

The api was created with Python and Django and utilizes both POST from users, as well as external api information seeded directly into the database. 

##### Learning Experience

When I started working on this I had a much better handle on the planning process and I used [Balsamiq](https://balsamiq.com) for my wireframing. 


{{< image src="/balsamiq.png" alt="Hello Friend" position="center" style="border-radius: 8px;" >}}

I found the Balsamiq software to be very clean and easy to use. I think it might not be as useful on a significantly more complex application, but Muirist was always intended to be a low-drag, simple UI.

I utilized the [National Parks API](https://www.nps.gov/subjects/digital/nps-data-api.htm) to seed my database with park information, storing that data in my own backend for quick reference to the local db. I also used this api to make front end calls and constructed a photo randomizer for the front page that returns an official photo from the parks API. 

The font that I selected for this project is teh [National Park Typeface](https://nationalparktypeface.com/) from teh [Design Outside Studio](https://jeremyshellhorn.com/Design-Outside-Studio). It is a typeface intended to copy the wooden router-made signs seen in parks across the country. 

{{< image src="/typeface.png" alt="OD Studio Typeface Example" position="center" style="border-radius: 8px;" >}}





