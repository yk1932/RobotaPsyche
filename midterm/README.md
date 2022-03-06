# Midterm: Ecosystem Project #

## Concept #

<p>An deep underwater ecosystem consisting of 4 creatures (Seabugs that separate when in collision with each other, flock of eels, whales, and a human diver).</p>

![alt text for screen readers](https://github.com/yk1932/RobotaPsyche/blob/main/midterm/Screen%20Shot%202022-03-06%20at%204.26.14%20PM.png)

## Creatures #

<p>There are four creatures inhabiting the ecosystem that I have created</p>

<p><b>1. Seabug</b></p>
<p>These creatures are small round entities that separate when within close proximity to each other. They collide into each other as a result. They remain stagnant most of the time unless there a collision. They are eated by eels for food.</p>

<p><b>2. Eels</b></p>
<p>These a long creatures that swim in flocks. There are couple of eels in the ecosystem by default. The user can press the mouse to give birth to more eels. The eels eat the seabugs when the seabugs are in their way. The vertex of the eels is updated to give an animated look to them. </p>

<p><b>3. Whales</b></p>
<p>These large round creatures swim independently from each other. They eat eels and are hunted by human divers. Every time the whale group eats 100 eels, they give birth to new whales. The size of the whales set within a randomized range to create variety within the species.</p>

<p><b>4. Human Divers</b></p>
<p>There is one diver (white circle) in the ecosystem that hunts for whales. The user can use the keys WASD to change the direction of their acceleration to swim around and hunt for whales.</p>

<p>The DNA shared by the entities encompasses the creature velocity, acceleration, size, maximum force, speed, mass.</p>

## Features #

**Onscreen text**

The onscreen text shows the number of entities in each species at all times along with how much of the entities have been eaten by their predators.

**Interactions**

1. mousepressed: leads to more eels reproduction.
2. keypressed “WASD”: moves the diver around the screen to hunt for whales. 

**Reproduction**

- Eels reproduce when user clicks the mouse
- Whales reproduce everytime they eat 100 eels collectively.

**Challenges**

- One of the biggest frustrations I had while coding for this project was the recognition of how complex the ecosystem we inhabit in is. Individually coding the attributes and physics system of an ecosystem made me realize the little things that I have never realized before. Finding the right number to set the attributes as was a process of implementing random numbers and finding the right one through running the code every time.
- However, these challenges also made me appreciate the “already coded” attributes of the world we inhabit in. It also made me appreciate the complexities and varieties within each and every species. 
