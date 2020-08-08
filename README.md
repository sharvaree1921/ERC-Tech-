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

'' What we did was combine a small amount of labelled data so that we do not get a hit on the performance, while we were also able to exploit the structures in the unlabelled data.''

Check it out in action in the video:  https://youtu.be/GTP7mQ-_wno

If you’re still not convinced that a robot surgeon trained on YouTube should be stitching up your wounds, you can relax — for now. Tanwani admits that the system needs a lot of work before it’s sewing up the operating theatre.
He now plans to integrate the needle with different kinds of tissues so the system can adapt to different situations — like an unexpected eruption of blood.
The next big milestone for Tanwani is semi-automated remote surgery. He envisions the robot providing assistance to a physician: snapping to their target, correcting any inaccurate movements, or even sticking stitches to a wound.

Tanwani compares this approach to driver-assist features in semi-autonomous cars:
" The surgeon is in total control of the surgery. But at the same time, we want to provide features that can take care of some mundane tasks, to reduce the cognitive load on the surgeons and increase their productivity to potentially focus on more patients and complex cases as well."

Just like the transition towards autonomous vehicles, these incremental advances should help gain the trust of users. Ultimately, Tanwani believes the self-supervised approach could bring AI to a range of real-world applications:
" The internet is filled with so much unstructured information in the form of videos, images, and text. The idea here was that if the robots can mine useful content from it to make sense of this data in the same way as humans do, robots can fulfill the long-standing goal of AI: to provide assistance in performing everyday life tasks."

### Ballie
Ballie : Samsung introduced its vision of robots as "life companions" at this year's Consumer Electronics Show(Jan 2020) – a tiny, ball-shaped AI device that rolls around the house and responds to commands like a pet dog. The small, yellow Ballie robot is designed to act as a personal assistant for the home.
The device uses a mobile interface, on-device artificial intelligence (AI) capabilities, voice activation and an in-built camera to recognize and respond to its users, and help them with various household tasks.It responds to spoken demands as a pet might, but can be used as a wake up call, a fitness assistant, to record moments or to manage other smart devices in the home like TVs and vacuums.According to the company, Ballie carries out all of these tasks while adhering to strict data protection and privacy standards.

[Check out this amazing video](https://www.youtube.com/watch?v=GH-FD4rmxKY)
[Do read this article for more info](https://www.dezeen.com/2020/01/08/samsung-ballie-robot-ces-2020/?fbclid=IwAR3_BTGk8fyTPA4dPDc5UFRRD2xyJmj2G7wsdVC-DOqceMJ79IGo3DWr2NM)

![ballie](https://github.com/sharvaree1921/Photos_for_repo/blob/master/index.jpeg)

### Automated Sandwich Maker
Ever had the audacity to think you were the fastest at making sandwiches? Rest assured, You are NOT unless you can make a sandwich per second 😲 
US-based company Grote specializes in automating production lines that slice, fill and cut sandwiches. Until recently, the upper and lower halves of the sandwich were put together manually. Now, Grote has managed to automate this process as well, using a Stäubli TX2-60 HE six-axis robot with wash-down capability.

Learn more [here](https://roboticsandautomationnews.com/2020/06/24/grote-automates-sandwich-production-using-staubli-robot-to-make-one-per-second/33379/?fbclid=IwAR2u7wVzS8fzCEviAO8r43Mlku-CynXJo7KfLwZ7ROy-ntY4CU5DsGWIcpk)

Their range of machines includes slicers for fillings such as sausage, ham and cheese, as well as bread feeders and cutters, depositors for semi-liquid condiments and wet salads, and cutters for the final sandwich product.Grote sees itself as a technology leader in this area of food processing. The systems it supplies are always tailored to the individual requirements of the user, which means its engineering department is heavily involved.

At the heart of the assembly line is a six-axis robot, the Stäubli TX2-60 HE. A conveyor belt delivers the sandwiches to it as two halves – the bottom slice, already buttered and filled, and the top slice, which is only buttered. The robot picks up the top slice and places it on the filling on the bottom slice. The sandwich is now whole.
Next, the robot rotates the sandwich 45 degrees and positions it diagonally on the conveyor belt. It then proceeds to the last station, where the sandwich is cut in half or quarters in the desired configuration, i.e. horizontal, diagonal, etc. Now the snack is ready for packaging.
Up to 60 sandwiches per minute, per lane can be produced in this way – with twin lines available to double production up to 120 sandwiches per minute. An operation that was previously performed manually is now automated.

The robot gripper is guided to its target using 3D image processing. The gripper itself was developed in-house by Grote. It enables reliable handling of the sandwich’s top slice, which is pliable in nature and thus difficult to grasp firmly.
The entire production line complies with the principles of hygienic design. All edges are rounded, so there are no dead spaces where debris can build up, and the sandwich production line can withstand even the harshest cleaning procedures.
To ensure maximum availability, Grote opted firmly for a Stäubli HE (Humid Environment) robot. The TX2-60 HE complies with protection class IP 67, with all cables being routed inside the housing, from pedestal to gripper.

![1](https://github.com/sharvaree1921/Photos_for_repo/blob/master/105978875_3547623438598352_8513038367821736847_n.png)
![2](https://github.com/sharvaree1921/Photos_for_repo/blob/master/106099897_3547622945265068_1887868538550295105_n.png)

### Laser Raptor
Although many fossils are simply lying exposed on the soil's surface, finding all of them would require a great deal of walking over varying terrain. A new autonomous hexacopter drone could help, as it uses a laser to hunt for fossils at night.
Called the Laser Raptor, it was developed by Hong Kong University's Asst. Prof. Michael Pittman and the Foundation for Scientific Advancement's Thomas G. Kaye. It utilizes an existing process known as Laser-Stimulated Fluorescence.

Check out the video [here](https://www.youtube.com/watch?v=t79XmfPyOWA&feature=youtu.be&fbclid=IwAR0_Q-nEIClzMpLm1njGyM57_ebkJBgLtWgVhwDe9eWB5Je5qEAtf-Qg3rA)

![image1](https://github.com/sharvaree1921/Photos_for_repo/blob/master/Image_1.png)

This technique - Laser-Stimulated Fluorescence (LSF) - was codeveloped at HKU and has been highly successful in palaeontology, making fossil bones glow and revealing otherwise invisible details like skin and cartilage (note 1). The application of LSF to an aerial system is possible because of the laser’s ability to project over great distances with little loss in power.

Loaded with pre-programmed flight paths during the day, this prototype was launched at night in the badlands of Arizona and Wyoming, USA to search for fossils (Figure 1). Laser Raptor flies rapidly to search locations using its on-board navigation and then descends and maintains an altitude of 4 metres above ground so it can ‘mow the lawn’ in search of glowing targets as small as a thumbnail. After each “mission” is complete, a video of the laser scan is processed to find hot spots that are investigated the next day (Figure 2), leading to the recovery of new fossil specimens (Figure 3).

![image2](https://github.com/sharvaree1921/Photos_for_repo/blob/master/Image_2.png)

Fluorescence is extremely sensitive to differences in mineral composition. Although Laser Raptor was designed to locate fossils, it is ready to seek out a whole range of fluorescent targets including minerals e.g. to study rare and unusual geology or in search of mining materials like gemstones, certain organisms like scorpions, shellfish and cyanobacteria, and even archaeological artefacts and structures.

### Artificial Pollination(Drone with Bubble machine)
Other examples of robotic pollination that we’ve seen have involved direct contact between a pollen-carrying robot and a flower. This is a workable method, but it’s not at all efficient, requiring the robot to do what bees do: identify and localize individual flowers and then interact with them one at a time for reliable pollination. For a couple of flowers for a demo, this is workable, but the problem becomes scaling it up to cover even a single tree, let alone an entire orchard.

The researchers said,
"We accidentally found that natural pollen grains can be easily incorporated into a soap film and flown in the air using various bubble devices."

Testing showed that 4 mg of pollen per mL of 0.4 percent surfactant solution resulted in soap bubbles that were each carrying up to 2,000 individual grains of pollen, stuck to the surface of the bubble membrane. The researches were also able to optimize the pH, and mix in boron, calcium, magnesium, potassium, and a few other things in the bubble solution to make it as pollen-friendly as possible, and showed that pollen grains within the solution were able to germinate successfully.
To show that this technique was scalable, the final goal of this research was to perform robotic pollination on a larger scale using a drone with a sort of bubble machine gun (capable of generating 5,000 bubbles per minute) mounted underneath. In order to manage the downwash from the drone’s rotors, the researchers mixed a stabilizer into the bubble solution, which was so effective that some of them stuck around for 5 hours. These bubbles were smaller, and only carried about 300 pollen grains each, but if you’re generating nearly a hundred bubbles per second, that’s still a lot of pollen. And the researchers observed that it only took one single bubble landing on the pistil of a flower to result in pollination, with an overall success rate of 90 percent when the drone moved over flowers at a respectable 2 m/s at a height of 2 m.

The primary limitation at this point seems to be that the surfactants used to make the bubbles, while biocompatible, aren’t as eco-friendly as they could be. But edible bubbles are already a thing, and the researchers want to try to get those to work next. They also point out that the drone technique would need some refinement in localization and mapping and control to be commercially useful, but I think we can forgive them for that.

![Robotic Pollination](https://github.com/sharvaree1921/Photos_for_repo/blob/master/MzY1MzEzOQ.jpeg)

### Robotic Laws
Robots today serve in many roles, from entertainers to educators to executioners. As robotics technology advances, ethical concerns become more pressing: Should robots be programmed to follow a code of ethics, if this is even possible? None of humanity’s creations inspires such a confusing mix of awe, admiration, and fear. We want robots to make our lives easier and safer, yet we can’t quite bring ourselves to trust them. We’re crafting them in our own image, yet we are terrified they’ll supplant us.
This thought opens the doors to Roboethics, an area of study concerning with formulation of rules to ensure machines with artificial intelligence (AI) behave in ways that prioritize human safety above their assigned tasks and their own safety in accordance with human morality.
A pioneer in the field, the science fiction writer Isaac Asimov drafted The Three Laws of Robotics In his 1942 short story "Runaround". They are
1. Robots must never harm human beings or, through inaction, allow a human being to come to harm.
2. Robots must follow instructions from humans without violating rule 1.
3. Robots must protect themselves without violating other rules.
Later, Asimov added a fourth, or zeroth law, that preceded the others in terms of priority:
0. A robot may not harm humanity, or, by inaction, allow humanity to come to harm.
While these laws sound plausible, numerous arguments, such as robots designed for the military which challenges the first law, have demonstrated why they are inadequate. This calls for the need to revise the laws.

For more info,click [here](https://io9.gizmodo.com/why-asimovs-three-laws-of-robotics-cant-protect-us-1553665410?fbclid=IwAR1t5y3vZK_X4Pilzacv68AMT7fwNu-f0pGYgTob8edrgOlVcRrML6vhGig)
![asimov](https://github.com/sharvaree1921/Photos_for_repo/blob/master/106903750_3560761440617885_8482710906562592784_n.jpg)

### Sparrow
SPARROW, a steam-powered robotic concept, could one day take giant leaps over some of the most hazardous terrains known (and unknown) in the solar system.
A novel robotic concept being investigated at NASA’s Jet Propulsion Laboratory in Southern California would use steam propulsion to hop across the sort of icy terrains found on Jupiter’s moon Europa and Saturn’s moon Enceladus. Both are thought to host vast subsurface oceans of salty water under a thick ice crust. But while that makes them fascinating destinations for scientific study, the little we know about their surfaces could also make navigating them especially challenging.
That’s where the Steam Propelled Autonomous Retrieval Robot for Ocean Worlds, or SPARROW, comes in. About the size of a soccer ball, the robot consists of a system of thrusters, avionics and instruments encased in a protective spherical cage. To keep the environment pristine for study, SPARROW would run not on rocket fuel but on steam produced from melted ice, traveling primarily through the air via short thrusts. In the sort of low-gravity environment found on those distant icy moons, there’d be no atmospheric drag to slow it down, enabling hops of many miles over landscapes that other robots would have difficulty navigating.
![sparrow](https://github.com/sharvaree1921/Photos_for_repo/blob/master/SPARROW-Robot-777x437.jpg)
check out this amazing [video](https://www.youtube.com/watch?time_continue=68&v=nkimUw3GqLQ&feature=emb_logo)

### Spy cam

