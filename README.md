# A Rotary Aquatic Propeller Which Is Not a Screw

There are many ways to move through water. Nature has developed the jet (squids), thunniform swimming (cetaceans and tuna), carangiform swimming (trout and catfish), and whatever it is that octopuses and manatees and lobsters do.

Yet the rotary screw propeller remains the dominent way humans move most watercraft, whether staffed or, increasingly, unstaffed (autonomous.) Human being have motors which produce rotary power efficiently and controllably.

Yet the screw has the disadvantage that may be unsafe to aquatic life (and swimming humans). Additionally, it may be susceptible to fouling with lines and weeds which wrap around it.
For this reason, autonomous aquatic vehicles often put the propeller in a duct or shroud, which limits direct contact 
with large objects. However, small objects and animals that can fit inside the duct are jeopardized by such propellers, in part because they tend to be drawn into them.

In addition to safety concerns, a new principle of aquatic motion is intellectually interesting apart from any actual 
advantage it may obtain. Based on a single experiment, we believe we have developed a novel means of producing aquatic
thrust which may be safer than screw-based propellers.

# The Unscrew Propeller

In November of 2022 I developed this idea and ordered three-d printed parts, which arrived in January 2023. After making a test apparatus, I was surprised that it seemd to actually work on the first try. My apparatus was powered by a 
rotary battery-powered drill with the trigger zip-tied down.

The idea was to make a shape that was as little like a screw as possible. Inspired by the Coanda effect
and the fact that jets of rapidly moving fluid tend to stay in contact with objects that change shape slowly,
I imagined a rotating shape that would produce thrust by moving a stream of water axially to the rotation. 
Furthermore, I wanted the shape to have no sharp edges, but rather to be as close to globular as possible.
Of course, if you spin any shape in water, it will tend to impart a spin to the water. Spinning wanter is
subject to centrifugal force, yet also feels a force keeping it in contact with the object.
Thus the idea was to design a shape such that water spinning away from the object would have at least
some radial motion, and therfore thrust.

A cone would accomplish this, but in a way that is not obviously useful. Instead, we imagine a 
hemisphere, which is a good beginning of a hydronymaic shape. By adding gentle "lobes" to this shape,
themselves roughly hemispheric, we could create a shape with no abrupt edges, but which would exert rotational
force on the water.

The resulting shape generated by the program GentlePropulsion.scad in this repo looks like this:
![Screen Shot 2023-01-29 at 5 33 58 PM](https://user-images.githubusercontent.com/5296671/215362352-fbff4d67-07c0-47a0-9120-3c9d9937424f.png)

If we think of the streamlines (the lines of flow) that this shape would naturally produce, it is clear
that water would be drawn away from the axial center at the "top" of the rounded hemisphere. This 
water would naturally be replaced by water in front of the object; this "pull" would exert a force
on the object.

A natural hydrodynamic shape is created by pairing a hemisphere with a cone to make an ice-cream 
cone shape. If this object were spun axially, it is unclear if the streams of water flowing away
from the top of the hemisphere would be moving more forcefully than the streams moving on the cone.
It appears from our experiment that they do---that these streams move "backward" enough to overcome
whatever force is on the cones, producing streamlines which in gneral move backward, producing a
thrust on the "ice cream cone" in the directon of the ice cream ball (and away from the cone.)

# Experiment

Building an experimental apparatus to measure the thrust produced by rotary propulsion mechanism is non-trivial.
Even more difficult is to measure the power efficiency of the "propeller", although in the end that is a very
interesting question. 
I designed an experiment to measure only if it provides a thrust at all.

I cut a long drill bit and glued it to the square wooden shaft that I had fitted into the unscrew propeller. 
Then I found a piece of styrofoam and duct-taped a battery-powered rotary drill to foam, creating a simple
boat, which a "propeller" shaft projecting down into the water with the unscrew propeller attached.

Then using a hot-tub, which is about 6 feet across, I zip-tied the trigger of the drill down and placed the boat
in the water. It appeared to move in the direction of the propeller with moderate force until it smacked into the 
"seat" of the hot tub. After being pulled back and moving forward three times, drill bit became unglued from the 
wooden shaft.


A [video of the experiment](https://youtube.com/shorts/lgh7gO7JHxQ) is avaible at our channel on YouTube.

![Screen Shot 2023-01-29 at 5 56 25 PM](https://user-images.githubusercontent.com/5296671/215363424-7c9254d9-e2df-47a0-98e2-966799cd4397.png)

# Possibility of use as a Turbine

[Christina Cole](https://github.com/christinacole)  suggested something I had not thought of---the possibility that this could be reversed to 
create a generator. This is strange because it is not clear which way it would spin. I thank her for this idea and it 
is definitely worth exploring.

# A Risk

It is just barely possible, but unlikely that the propulsion observed only occured because it was tested in a closed vessel
(which support weird currents and reflections in ways that deep open water would not.) Testing in a larger pool
should elimininate this risk. I consider unlikely.

# Seeking Collaborators

As the Head Invention Coach of Public Invention, I am very busy. The goal of Public Invention is to in in the public---
that means you, gentle reader, are invited to collaborate. I would love for a mechanical engineer to assit me in
fully exploring this idea. A start would be to measure thrust as a function of rotational velocity.

No doubt the shape which I started with, which was easy to create in OpenSCAD, is not the optimal shape for this purpose.

Measuring the actual power efficiency of the unscrew propeller require measuring thrust at various speeds (via towing)
or a Computational Fluid Dynamics simulation. I am capable of learning CFD but have other priorities on my time.

This work would certainly produce a good academic paper, I think.

# License

This text is licensed under Creative Commons By Attribution. The Hardware Designs herein are licensed under the CERN OHL Strongly Reciprocal V2.  The OpenSCAD code is licensed under Affero GPL v. 3.
