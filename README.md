# ERC-Tech Stuff
Electronics and Robotics Club Posts -

## TechThursdays-
### Kilobots-
How does a group of animals -- or cells, for that matter -- work together when no one’s in charge? Tiny swarming robots--called Kilobots--work together to tackle tasks in the lab, but what can they teach us about the natural world?
About Kilobots
How do you simultaneously control a thousand robots in a swarm? The question may seem like science fiction, but it’s one that has challenged real robotics engineers for decades.
In 2010, the Kilobot entered the scene. Now, engineers are programming these tiny independent robots to cooperate on group tasks. This research could one day lead to robots that can assemble themselves into machines, or provide insights into how swarming behaviors emerge in nature.
In the future, this kind of research might lead to collaborative robots that could self-assemble into a composite structure. This larger robot could work in dangerous or contaminated areas, like cleaning up oil spills or conducting search-and-rescue activities.
What is Emergent Behavior?
The universe tends towards chaos, but sometimes patterns emerge, like a flock of birds in flight. Like termites building skyscrapers out of mud, or fish schooling to avoid predators.
It’s called emergent behavior. Complex behaviors that arise from interactions between simple things. And you don’t just see it in nature.
What’s so interesting about kilobots is that individually, they’re pretty dumb.
They’re designed to be simple. A single kilobot can do maybe... three things: Respond to light. Measure a distance, sense the presence of other kilobots. 
But these are swarm robots. They work together.
How do Kilobots work?
Kilobots were designed by Michael Rubenstein, a research scientist in the Self Organizing Systems Research Group at Harvard. Each robot consists of about $15 worth of parts: a microprocessor that is about as smart as a calculator, sensors for visible and infrared light, and two tiny cell-phone vibration units that allow it to move across a table. They are powered by a rechargeable lithium-ion battery, like those found in small electronics or watches.
The kilobots are programmed all at once, as a group, using infrared light. Each kilobot gets the same set of instructions as the next. With just a few lines of programming, the kilobots, together, can act out complex natural processes.
The same kinds of simple instructions that kilobots use to self-assemble into shapes can make them mimic natural swarming behaviors, too. For example, kilobots can sync their flashing lights like a swarm of fireflies, differentiate similar to cells in an embryo and follow a scent trail like foraging ants.

for more interesting stuff about kilobots,click [here](https://youtu.be/QXNVZJ3KUsA)

![kilobots](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/kilobots.jpeg)

## TechThursdays
### LOVOTS-
LOVOT : A Combination of Love+Robot!
Want to be loved by someone? Want to enhance your mood?
Here comes your companion named 'Lovot', an excellent example of Emotional Robotics!

Lovot will react to your moods, has facial expressions and do all it can to fill you with joy and re-energize you.This 4.2 kilogram weighing bot, a Japan based model, has 10 or more CPU cores, 20 or more MCUs, and 50 or more sensors, which can create behaviour that is much like a living being.
Lovot uses Machine-Learning to understand the behaviours of Human beings.An application in the mobile is used to keep its track, change its eye-color and to check its daily routine via a calender.Lovot's actions are pre-programmed through deep-learning, so that they can take actions in real time.There are foldable wheels, flexible shoulders and a smooth skin comprising of pressure sensors, 360-degree half sphere camera, thermal camera, posture sensors,etc to detect human touch and its responses.Lovot's reactions are cute and warming.

![lovot](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/lovot.jpg)

Want to know more? 
[click here](https://lovot.life/en/technology/)
  
Check out the video here-
1-[video 1](https://www.youtube.com/watch?v=PoxdaQzdx3I)
2-[video 2](https://www.youtube.com/watch?v=U_kijW18EVU)

### Sketch to Image
A team of researchers from the Chinese Academy of Sciences and the City University of Hong Kong has introduced a local-to-global approach that can generate lifelike human portraits from relatively rudimentary sketches.

Recent deep image-to-image translation techniques have enabled the prompt generation of human face images from sketches, but these methods tend to suffer from overfitting to their inputs. They thus achieve the most realistic results only when the source drawings have high-quality artistry or are accompanied by edge maps.

Unlike most deep learning based solutions for sketch-to-image translation that take input sketches as fixed, ‘hard’ constraints and then attempt to reconstruct the missing texture or shading information between strokes, the key idea behind the new approach is to implicitly learn a space of plausible face sketches from real face sketch images and find the point in this space that best approximates the input sketch. Because this approach treats input sketches more as ‘soft’ constraints that will guide image synthesis, it is able to produce high-quality face images with increased plausibility even from rough and/or incomplete inputs.

The system consists of three main modules — CE (Component Embedding), FM (Feature Mapping), and IS (Image Synthesis). The CE module adopts an auto-encoder architecture and separately learns five feature descriptors — left-eye, right-eye, nose, mouth, and remainder — from the face sketch data. The FM and IS modules together form another deep learning sub-network for conditional image generation, and map component feature vectors to realistic images.

The researchers also provide a shadow-guided interface, implemented based on CE, that makes it easier for users to refine the input sketches. Their system can produce high-quality realistic face images — with resolution of 512 × 512 — that faithfully respect and reflect the input sketches.

Both qualitative and quantitative evaluations show that the method produces visually more pleasing face images, according to the researchers. The system’s usability and expressiveness were also favourably confirmed in a user study.

The researchers say their tool is easy to use, even for non-artists, while still supporting fine-grained control of shape details. They are working on releasing the source code soon.

![dl1](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/dl1.jpg)
![dl2](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/dl2.png)

### Ultrasound haptic system projects readable Braille into thin air -
For people who rely on Braille, reading displays and signs in public can be a challenge, but a new system could help make things easier. HaptiRead is a haptic feedback device that uses ultrasound pulses in precise patterns to reproduce Braille text in midair.
Braille is often used in public places as fixed nodes on a sign, or more dynamically as Refreshable Braille displays that use lines of pins that rise and fall to change texts. But there are plenty of problems with both of these. It can be difficult to direct users to begin interacting with them in the first place, limited information can be presented, the moving parts can clog up over time, and, of course, there are hygiene concerns with many people touching the same surface.
HaptiRead is designed to address all of those issues. The system is a panel made up of 256 ultrasound transducers, emitting frequencies of up to 200 Hz – strong enough for a user to feel the pressure on their skin. This kind of technology has previously been put to work to create things like holograms you can touch.
But HaptiRead has an arguably more noble goal in mind. This device projects up to eight haptic points in the air as far as 70 cm (27.6 in) away, which can be arranged to represent different characters in the Braille alphabet.
A built-in Leap Motion depth-sensing camera figures out where a user’s hand is and directs the ultrasonic points towards it. That can help guide a user towards the device in the first place. Plus, there are no moving parts to clog up, and users don’t need to actually touch a surface, removing hygiene issues. The system can also be set up to display more complex information, such as charts and graphics.

The researchers experimented with how to best present the text. They ran through three different methods – constant, where all dots in a cell were presented at the same time, row-by-row, where rows of dots were projected sequentially, and point-by-point, where only one dot was displayed at a time.

The team tested HaptiRead on 18 sighted and 11 blind participants, asking them to feel a projected Braille cell and identify which character was represented. In both sets of participants, the point-by-point method had the best results – the sighted group scored an average accuracy of 94 percent, while the blind group scored 88 percent. The participants also reported that point-by-point was less mentally demanding than the other methods.

![haptic](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/haptic.png)

[New ultrasound research creates holographic objects that can be seen and felt ](https://newatlas.com/ultrasound-3d-haptic-hologram/35032/)

### Pazzi Robot-
Like any good pizzaiolo, Pazzi prepares, bakes, slices and boxes pizza after pizza after pizza. It properly churns them out: sometimes 80 or so an hour. And yet unlike most, it will guarantee your margherita or fiorentina isn’t touched by a single human hand. 

Pazzi is a robot – the first to run a pizza restaurant with no human supervision. Set up in the Val d’Europe shopping centre 30 minutes east of Paris, the machine was designed by entrepreneurs Cyrill Hamon and Sébastien Roverso, who last year raised more than €10 million (£9 million, $11 million or A$16 million) in startup funding to develop the world’s first ‘robot pizzaiolo’ technology.

The first bricks-and-mortar Pazzi establishment opened for business late last year, but abruptly had to close in March as lockdown set in. Now, as France reopens and demand grows for more contact-free solutions to dining out, the company plans to open four more restaurants throughout the country later this year. 

Customers simply order via (disinfected) terminals or via an app, choose their pizza and pick a collection time. The dough is made according to a recipe by Thierry Graffagnino, using flour from local mill The Moulins Familiaux Paul Dupuis, and each pizza takes around five minutes to prepare and bake.

Pazzi then slices the pizza, places it in a box and puts this in a secure locker only the customer can access. Aside from the payment terminals, this is the only stage at which diners will have to touch any potentially contaminated surface. Rest assured that hand sanitiser is available, and social-distancing measures are currently in place.

The robot is named for the Italian phrase Cose da pazzi! (rough translation: ‘Incredible!’) That it certainly is, but in these fraught, physically-distanced times, we wouldn’t be surprised if robot chefs of Pazzi’s ilk become a much more familiar sight in malls worldwide. 

![pazzi](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/pazzi.jpeg)

### Artificial Synapses
Artificial synapses are an important step towards emulating the supercomputer that is the human brain. Now scientists have successfully bridged the gap between organic and artificial, with biohybrid synapses that let living cells communicate with electronic systems, not with electrical signals but with neurotransmitters like dopamine.
This is a remarkable breakthrough, the team says. Similar devices usually still communicate using electrical signals, but this biohybrid artificial synapse is using the same electrochemical signals that an organic brain uses.
The study was conducted by researchers at Stanford University, the Italian Institute of Technology and Eindhoven University of Technology. The research was published in the journal Nature Materials.
Read more at:
[here 1](https://news.stanford.edu/press-releases/2020/06/15/artificial-synaprks-living-cells/)
[here 2](https://newatlas.com/computers/artificial-synapses-living-cells-communicate-dopamine/)

![artificial_synapses](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/artificial_synapses.jpeg)

### 3D Artificial Eye
The human eye is an incredibly complex piece of equipment, so it’s no wonder that we’ve had a hard time reverse-engineering it. Now, researchers have unveiled the world’s first 3D artificial eye, which can not only outperform other devices but has the potential to see better than the real thing.
Bionic eyes are emerging as a way to restore vision to people who have lost their sight, and possibly even those that never had it to begin with. A team led by scientists at the Hong Kong University of Science and Technology (HKUST) has developed what they call the Electrochemical Eye (EC-Eye).
Read more at [doc](http://www.ust.hk/news/research-and-innovation/hkust-scientists-develop-worlds-first-spherical-artificial-eye-3d)
Watch  [here](https://youtu.be/8lV98kWspks)

![here](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/3D%20arrt%20eye.jpg)

### Multi-Drone Delivery 
Riding on the top of public buses could make drone delivery much more efficient.
Companies like Mercedes-Benz Vans, in partnership with Matternet, have explored the idea of using vehicles to expand the range of delivery drones. Now a group of Stanford researchers suggests delivery drones could also rely on public buses to more than quadruple their package delivery range.
Read more at [doc](https://spectrum.ieee.org/automaton/robotics/drones/delivery-drones-could-hitchhike-on-public-transit-to-massively-expand-their-range)
Watch [here](https://youtu.be/2U8jI-n9Ulk)
Delivery Drones Could Hitchhike on Public Transit to Massively Expand Their Range

![drone](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/drone.jpeg)

### Underwater Wifi...Aqua-fi
Aquatic internet that sends data through light beams could enable divers to instantly transmit footage from under the sea to the surface. 

The internet is an indispensable communication tool, connecting tens of billions of devices worldwide, and yet we struggle to connect to the web from under water. “People from both academia and industry want to monitor and explore underwater environments in detail,” explains the first author, Basem Shihada. Wireless internet under the sea would enable divers to talk without hand signals and send live data to the surface.

Underwater communication is possible with radio, acoustic and visible light signals. However, radio can only carry data over short distances, while acoustic signals support long distances, but with a very limited data rate. Visible light can travel far and carry lots of data, but the narrow light beams require a clear line of sight between the transmitters and receivers.

Now, Shihada’s team has built an underwater wireless system, Aqua-Fi, that supports internet services, such as sending multimedia messages using either LEDs or lasers. LEDs provide a low-energy option for short-distance communication, while lasers can carry data further, but need more power.

The Aqua-Fi prototype used green LEDs or a 520-nanometer laser to send data from a small, simple computer to a light detector connected to another computer. The first computer converts photos and videos into a series of 1s and 0s, which are translated into light beams turning on and off at very high speeds. The light detector senses this variation and turns it back into 1s and 0s, which the receiving computer converts back into the original footage.

The researchers tested the system by simultaneously uploading and downloading multimedia between two computers set a few meters apart in static water. They recorded a maximum data transfer speed of 2.11 megabytes per second and an average delay of 1.00 millisecond for a round trip. “This is the first time anyone has used the internet underwater completely wirelessly,” says Shihada.

In the real world, Aqua-Fi would use radio waves to send data from a diver’s smartphone to a "gateway" device attached to their gear. Then, much like a booster that extends the WiFi range of a household internet router, this gateway sends the data via a light beam to a computer at the surface that is connected to the internet via satellite.

Aqua-Fi will not be available until the researchers overcome several obstacles. “We hope to improve the link quality and the transmission range with faster electronic components,” explains Shihada. The light beam must also remain perfectly aligned with the receiver in moving waters, and the team is considering a spherical receiver that can capture light from all angles.

“We have created a relatively cheap and flexible way to connect underwater environments to the global internet,” says Shihada. “We hope that one day, Aqua-Fi will be as widely used underwater as WiFi is above water.”

![aqua fi](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/aquafi1.jpeg)

![aqua fi2](https://github.com/sharvaree1921/ERC-Tech-/blob/master/images/aquafi2.jpeg)

### Steam-Powered Peigon
The first robot, created in 400 BCE, was a steam-powered pigeon!
It’s easy to assume that robots are a relatively recent invention—but in fact, the history of robotics stretches back well over 2000 years. The first, a steam-powered “pigeon,” was created around 400 to 350 BCE by the ancient Greek mathematician Archytas.
Archytas constructed his Robo-bird out of wood and used steam to power its movements. The bird, suspended from a pivot bar, was at one point able to fly about 200 meters before it ran out of steam—which makes Archytas’ experiment, not just the first known robot, but was also one of the first recorded instances of a scientist doing research on how birds fly.

![Steam-powered peigon](https://github.com/sharvaree1921/Photos_for_repo/blob/master/104960512_3538879649472731_7637852084926400147_n.png)
Read more [here](https://www.mentalfloss.com/article/13083/first-robot-created-400-bce-was-steam-powered-pigeon?fbclid=IwAR0xV6MOBx3_1vK3aJFL7Co9RjAw8H7jBJw522UljVwD3vwFb5yOElews3s)
Check out this [video](https://www.youtube.com/watch?v=_KQhSDur1WU&fbclid=IwAR2GPYJAOqWJ-TvRdGxKwddnCHa7PcDJC3kuuVk1XjcjQvrloJQLAOg5ctw)

### AI based Stiching Robot(Surgeon)
You probably wouldn’t want a surgeon to stitch you up if they’d learned their craft by studying YouTube videos. But what about a robot?

The prospect might not be as fanciful as it sounds. Researchers from UC Berkeley, Intel, and Google Brain recently taught an AI model to operate by imitating videos of eight human surgeons at work.
The algorithm — known as Motion2Vec — was trained on footage of medics using da Vinci surgical robots to perform suturing tasks such as needle-passing and knot-tying.
The da Vinci system has been operating on patients — including James Bond on one occasion — since the early 2000s. Typically, the robot is controlled by a doctor from a computer console. But Motion2Vec directs the machine on its own.

It’s already proven its stitching skills on a piece of cloth. In tests, the system replicated the human surgeons‘ movements with an accuracy of 85.5%.

Reaching that level of precision was not an easy task. The eight surgeons in the videos used a wide variety of techniques, which made it tricky for the AI to figure out the best approach.

To overcome this challenge, the team used semi-supervised algorithms, which learn a task by analyzing partially-labeled datasets. This allowed the AI to understand the surgeons‘ essential movements from a just small quantity of labeled video data.

Dr. Ajay Tanwani, who led the UC Berkeley team, told TNW that this created a sample-efficient model:

    What we did was combine a small amount of labelled data so that we do not get a hit on the performance, while we were also able to exploit the structures in the unlabelled data.

Check it out in action in the video https://youtu.be/GTP7mQ-_wno

