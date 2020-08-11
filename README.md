# PMT-Agents
Images, PSD File and CSS code for PMT agents

-------


Agents PSD is the photoshop file. 

agents.png contains all agent images in a single one to be added to the stylesheet. The other images is just to have a list with high qualiy images

All agents images are resized to 25x25 pixels 

Each one is placed one above the other with a 4px gap.

So between each agent starting horizontal point theres a 29px difference.

So the first agent would start at 0px, 2nd at -29px, 3rd at -58, aso. 

Agents are called in posts with [xxxx](#agent-xxxx) with xxxx being the agents name 

To add the code to the stylesheet go to https://old.reddit.com/r/Valorant/about/stylesheet/ 

Add the image agents.png with the name agents.

Add the code in "css stylesheet code.txt" to anywhere in the stylesheet (preferably replace the older code for the agents if there is one). 

If the code needs to be minified due to the stylesheet being too big just paste it in https://www.cleancss.com/css-minify/ and copy the output (click on CSS minify after pasting the code)

Updates:

Added Killjoy and Names to show up in new reddit. Also shortened the code. I added this line "text-indent:-9999px" which allows to put any text in the square bracket 
when calling an agent image for the PMT so new reddit users can see the agent name and old reddit users dont see the agents name on top of the image
