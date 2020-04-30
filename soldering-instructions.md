SMD Soldering 101 / build instructions
======================================

SMD first timer? Cool :D ! Don't worry, getting started with this kit with the "tiny stuff" is 
pretty easy with this kit! 

As you don't have any or much experience with soldering SMD we'll go through some of the lowly basics here.

Safety first: 

- be careful with the soldering and melted solder. They can cause severe burns!
- don't inhale the soldering fumes. 
- wash your hands after soldering. Solder can contain lead, zinc, other metals and flux, neither of which you should ingest!


To solder this board you'll need:

- a soldering iron / most will make do for this job.
- some tweezers
- solder / 1mm with flux/rosin core or anything you're comfy with
- some fire proof surface to solder on

> Note: about the work table you're going to solder on: clean it up and have some space to work.
> Don't have any easy to burn material or substance close. If you don't mind having a burnt trace on it
> most furniture will be *fine* but you may want to add some throw-away-able layer on top ;)
>
> There are some amazing and cheap soldering mats available, otherwise a scrap wood panel will do.

![Properly hold your soldering iron](./assets/soldering-guide-holding-the-iron.jpg)

Power up your soldering iron (if it's regulated set the temperature to anywhere between 260°C and 350°C - depending on your solder) and wait for it to be at the right temperature. 

![Soldering kit parts](./assets/soldering-guide-ils-smd.jpg)

While the soldering iron is heating up, prepare your first part. We'll start with the 1206 (that's a size indication, which in this case is on the *huuuuge* side of SMD things) resistor because it's the easiest one!

Start by removing the cover tape of the carrier (that's the thin clear plastic film which holds the component in the paper or plastic carrier tape). The easiest way is to use the tweezers and slide on side under the cover tape and twist a little bit to loosen one edge, like so:

![Removing the cover tape](./assets/soldering-guide-removing-smd-cover-tape.jpg)

Be careful once you've removed the cover tape: one flick and the resistor will be gone! It's tiny an lightweight.

By now the soldering iron should be up to temperature! You can check this by holding a bit of solder to the tip (keep your fingers at least a couple of centimeters away from the tip though). If the solder niceley melts and flows on the tip you're ready to go! 

If you ended up with a huge blob of solder on the tip of the iron, you can get rid of it by using some solder wick. Alternatively you can gently tap the soldering iron (the whole unit, not the tip) on the work surface to make to molten solder drop off. Be careful with the projections though! It's *hot and molten* metal!

> Note: if the solder makes crackling noises and/or you have flux projections that means that your iron is too hot! 
> If the solder does not melt, then it's either set too low or not yet fully heated up.

Resistors are a great first component to solder because you can't really go wrong with over-heating or melting them, so take your time! 

As SMDs don't have any lead to hold them in place you'll have to solder to metalized pads on the component:

![Making a solder joint](./assets/soldering-guide-SMD-vs-TH.jpg)

One common way to do this is to slide the component in a pre-wetted solder pad. This means applying a bit of solder to one of the pads of the footprint on the PCB before even grabbing the component with the resistor:

![Wetting a single PCB pad](./assets/soldering-guide-wet-smd-pad.gif)

Once you have a nice small solder blob on the pad, grab the resistor with the tweezers (make sure to grab the sides without contact pads). Re-heat the solder blob on the pcb and slide the resistor in place (the second contact should align nicely with the second pad on the PCB):

![Soldering that resistor](./assets/soldering-guide-solder-resistor.gif)

It's not a problem if you didn't get the alignment right the first time. As long as the second pad isn't soldered it's really easy to change the alignment: just re-flow the solder on the first pad and push the resistor around as you like. Even taking it off the PCB is easy with the tweezers.

Once you're happy with the alignment (you should see enough of the PCB pad to be able to touch it with the tip of the soldering iron basically) flow a bit of solder on the second pad.

This is how it could look like:

![Soldering that resistor](./assets/soldering-guide-resistor-soldered.jpg)

> work in progress / to be continued....

Troubleshooting
===============

Doesn't work? Don't panic and have a look at the troubleshooting section in [README](./README.md)