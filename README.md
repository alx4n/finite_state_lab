# finite_state_lab
Exploring finite state machines through a "Choose your own adventure" game about going through a school day as a music student.

## Technical Frawework
I used the open-source Twine model to create my state project.

## Running the Project
To run the project, either download the html or twee file to your computer. If downloading the html file, simply open the file in a web browser. Alternatively, download the twee file and import it into Twine to run it.

## Nodes
Nodes are stored using Twine's Passages, with the title of each node being its name and the way it is referenced by other nodes. Markup is then used to connect nodes using brackets to create hyperlinks.

## Lessons
Doing this project, I noticed the importance of reusability in managing state. The state was not changed by tons of if statements, but instead by the same structure of node that could be manipulated to make different states that could then be moved between. I am most proud of hwo I implemented a few variables to change the outcome of the game. However, I wish I had implemented this in a programming language instead to better understand what is happening on the backend of a project like this.
