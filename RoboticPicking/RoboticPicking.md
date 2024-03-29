[Back to home](https://reubenwangrongwen.github.io/)

# Autonomous Pick-and-Place Robot

Over the course of about 9 months, a team of friends and I embarked on building an AI-robotic system that could perform general 
pick-and-place tasks. The final system was the integration of a 6-axis robotic arm from [Universal Robots](https://www.universal-robots.com/), a vision system consisting of digital and depth cameras, and an AI program that ran on an external processor. Our system was able to:

* identify and categorize objects when placed on a pre-defined palette;
* ascertain the optimal picking confguration and trajectory to move the object into a pre-defined bin.

All the code I developed was done with [*Python*](https://www.python.org/).


## Demo: Robot in Action

A short demo of the system in action is given in the GIF below. In this demo, the system has been tasked to identify and sort through an array of items, which is then to be placed into a designated bin. The robot was given no prior explicit information on what the array of items would consist of, where these items would be placed on the palette, or how it should go about carrying out this task. The robot simply does these procedures autonomously with AI algorithms we programmed into it.  

<img align="left" src="picking_sequence.gif">
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

The demo above showcases the system's ability locate and identify objects to a high degree of precision. It also demonstrates the robust and dynamic optimization processes which enable picking up objects with complex geometries. 

A unique feature of this system is that the AI was trained on a **synthetic data set**. That is, all training data was generated in a virtual environment and computer rendered, to provide the AI with photorealistic images to learn from. 


## The Team

Our team consisted of a mix of engineering and computer science majors (team picture below). 

<img align="left" src="team_photo.jpg">
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

(From left to right: [Keshigeyan Chandrasegaran](https://www.linkedin.com/in/keshigeyan-chandrasegaran/), [Judith Lim](https://www.linkedin.com/in/judith-lim/), [Aravind Kandiah](https://www.linkedin.com/in/sk-ara/), myself, [Charles Wong](https://www.linkedin.com/in/charles-wzx/) and [Canneth Ho](https://www.linkedin.com/in/canneth-ho-1bb754160/).) 

With the synethetic data technology developed, team members Charles and Aravind have founded the start-up [Bifrost](https://www.bifrost.ai/), that offers AI companies a synthetic data platform to generate their desired data sets. 



