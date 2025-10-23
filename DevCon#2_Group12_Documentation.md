**Digital Prototype Development - GAME-10016 - Rapid Prototype 2** - Group 12 - Jake, Blair and Sergio

**“_The King and the Fool_” - Design Documentation**

---

**Overview:**

_The King and the Fool_ is a puzzle platformer game with a new twist on the typical conventions of the genre, in that it offers the player the ability to possess a wide range of household objects in their quest to escape the place they are trapped within, and reunite the fragments of their shattered soul. As a fragment of the soul of a Divine Emperor, you do not have a corporeal body, but who's to say you can't utilize the objects around you to get things done? After all, you still have _some_ divine power, and the High Lords would sooner destroy Jantris than wait until you return to force them into submission. 

---

**Objective:**

![poltergeist](https://media.githubusercontent.com/media/Blairskii/Posession_Proto_Team12_DevCon2/refs/heads/Jake_Documentation/Assets/poltergeist.png)

We seek to create a puzzle platformer game that tasks the player with utilizing not just the toolset of _one_ character, but the varied toolsets offered by the _variety_ of household objects that you can possess and manipulate. Each object will provide different abilities, and will play a different role in the player's escape, so the player must use the different objects creatively to solve various problems that will culminate with their escape from the house they are initially trapped in. What we are really trying to test here is: How does shifting between objects change player engagement and level navigation, and does possession encourage creative solutions and strategies compared to conventional models of control with just one character. 

One single character is straightforward, and provides a solid, defined set of options for the player, but having multiple different "bodies" that the player can inhabit - that also remain in the world when not actively in use - provides a range of new options, even beyond the sum of the individual abilities or functions of the objects. We think this could provide some very interesting possibilities with regards to level design, and freeform problem solving, and so this prototype serves to explore the potential present in these ideas. 

---

**Design Rationale**

Most games tend to lock players into one "body" or one way of experiencing the world of the game. Even when they give players some variety, it's usually in the form of switching between characters who mostly play the same way (ie; If you're playing a hack 'n' slash game, chances are that the alternate characters also play similarly to the starting character, even if they have a different playstyle or role, gameplay-wise). 

![marioodyssey](https://media.githubusercontent.com/media/Blairskii/Posession_Proto_Team12_DevCon2/refs/heads/Jake_Documentation/Assets/marioodyssey.png)

This game would seek to use possession as a _main mechanic_, rather than as a temporary ability (as opposed to something like Mario's ability to control enemies and objects in Super Mario Odyssey), so as to give the player a _far_ greater range of options with how they can interact with the game world, how they can solve problems, or otherwise just how they can experience the game.

The range of possession targets could run the gamut, so to speak, and could provide the player with multiple different valid ways of solving a puzzle. Our main player experience goal here is to create moments where players have to think of the objects in the room as unique tools that can help them accomplish their task rather than just as useless props. 

---

**Team & Roles:** 

- Blair - Programming, Design

- Jake - Documentation, Narrative, (some) Design 
  
- Sergio - Assets, Level Design

---

**Core Gameplay:**

![chameleon](https://media.githubusercontent.com/media/Blairskii/Posession_Proto_Team12_DevCon2/refs/heads/Jake_Documentation/Assets/chameleon.png)

The core gameplay of _The King and the Fool_ involves possessing different objects, and using their unique traits and properties to solve problems, and ultimately, for what would be the first act, escape the house they are initially trapped within. The player would have to reach some goal, such as an open window, a vent, or a hole in a wall, and would have to possess a variety of different objects that would let them reach that goal when used together in the correct way (or in one of the multiple correct ways to reach a particular goal). Outside of any times where there is only one defined solution for a particular challenge, the game will allow for emergent gameplay to develop, and players will be free to experiment and devise different ways of achieving their goal. The game would automatically autosave between levels and on regular intervals within levels so that the player does not have to worry about losing progress when they exit, or if the game happens to crash.

While the first act of the game would be to escape the house that they start out within, the game's scope would grow significantly later on, into the second and third acts, as the player's ability to possess larger and more complex objects grows. While they would start off possessing household objects, the later stages of the game could have the player possessing complex electronic systems, large structures and industrial objects, or even complex machinery like vehicles, essentially having them take the role of some massively powerful anomalous spirit. 

---

**Core Mechanics:**

**Possession**

The one single main mechanic with this game is Possession, where the player can take over a range of different items that will each perform differently, and occupy different roles in the player's 'toolbox'. It is hard to describe the specifics of this mechanic, as each object will perform differently, but in general, this mechanic will allow the player to control _most_ objects that would normally be random, insignificant props in other games. Each prop will have a general behavior depending on the type of object, and then may also have different unique mechanics to them, depending on what they are and what makes sense for that object. 
 
There are generally three types of objects: Stationary Objects, Boolean Objects, and Interactible Control Objects.

- Stationary Objects: These objects can be possessed, and then used to move towards a goal. (ex: crates)

- Boolean Objects: These objects can be turned on or off through possession. (ex: lights)
        
- Interactible Control Objects: These objects can move or tip slightly when possessed, and can be used to traverse to another puzzle element. 

---

**Graphics and Aesthetics:**

![darkcloud](https://media.githubusercontent.com/media/Blairskii/Posession_Proto_Team12_DevCon2/refs/heads/Jake_Documentation/Assets/darkcloud.png)

Graphically, _The King and the Fool_ will use a low-poly retro style, reminiscent of the aesthetics of games on the PS1 and the PS2. In particular, Dark Cloud on the PS2 and King's Field IV on the PS1 were sources of inspiration for the aesthetic style of this game, and while most of the content will take place in the modern era, as it is Dark Fantasy story at heart, it will essentially depict a modern setting with a Dark Fantasy coat of paint applied over it. 

![kingsfield4](https://media.githubusercontent.com/media/Blairskii/Posession_Proto_Team12_DevCon2/refs/heads/Jake_Documentation/Assets/kingsfield4.png)

Objects will look as they are expected to look, but where possible, things will take on a grittier, darker, and more detailed appearance than is typical for low-poly games set in a modern setting (which often entirely eschew the use of textures, going for flat colors instead). _Think Mouthwashing's graphical style, but with a dark fantasy spin on the textures._

![mouthwashing](https://media.githubusercontent.com/media/Blairskii/Posession_Proto_Team12_DevCon2/refs/heads/Jake_Documentation/Assets/mouthwashing.png)

---

**Narrative Hook:**

(NOTE: Most of this is background information and lore that is not strictly necessary for the player to know, and exists mainly to provide context for the circumstances of the story, and information about the broader world that would exist beyond the confines of this prototype. Most of this would not be told directly to the player, and for all intents and purposes, the player would only really need to know the information within the README. The rest of this information would be drip-fed to the player over the course of the game, either through dialogue or through readable books, notes, or text logs.)

Ancient tales tell of sorcerors, wizards, knights, dragons and more, however these are but tall tales told to entertain children, or scare them into obedience. Few tell of the truths buried deep within these legends, and even fewer still tell the true grisly details about the dark powers that waged war upon the mortal plane long ago. While those who lived through it are long dead, the history is long forgotten, and in the modern age it is regarded as mere fiction, there are grains of truth laying within even the modern tales that paint a dark picture, laying out the reality of how the world's fate rested on the knife's edge for a time.  

Many tens of thousands of years ago, the world was dominated by a vast and powerful kingdom known as Jantris. Ruled by the Divine Emperor of Jantris, the _true_ Chakravartin, Ophiucius Tyrodin, and guided by the Seven High Lords of Jantris, each a divine being in their own right, the kingdom was prosperous, secure and stable. While conflict between the High Lords was not uncommon, Emperor Tyrodin used his sheer might to rein in the High Lords and force their submission to his divine will. Through his power, peace was maintained, and threats to the realm were vanquished one by one. Jantris would soon become the crown jewel of the mortal plane, and the true seat of power in the mortal realm. It was a perfect, unblemished utopia, was guarded and run by a benevolent divine overlord, and represented the greatest golden age ever witnessed by mortal eyes.

Unfortunately, as with anything approaching perfection, the closer one gets to achieving it, the more striking even a single blemish may appear. After ruling this perfect, idealized realm for an unfathomable length of time, without a warning or even so much as a trace, Emperor Tyrodin would shock his entire kingdom to its core by suddenly disappearing at a critical moment of strife among the High Lords. With his disappearance emerged a tremendous power vacuum, and it would not take long for the power-hungry High Lords to begin fighting over conrol of Jantris. As with all legends, there is little certainty to cling to here, but it has been said that Tyrodin was not _always_ a divine being, and rumors have long circulated that he was once a mortal man who ascended to divinity upon taking his place on the Throne of Jantris. The High Lords could not truly confirm or deny this, as Tyrodin was always a secretive individual, even among allies, but the Seven were convinced that the secret to the Emperor's might laid within the Throne itself. 

With the throne vacant, Tyrodin nowhere to be found, and the greatest power vacuum in the mortal plane beginning to form, the Kingdom would soon erupt into total, all-out warfare, with each of the Seven seeking to claim the throne for themselves. Whether it was the prideful Grand Duke of Feldspar, Ventriel, the mad lord of the Dominion of the Blade King, Excisitus, or the avaricious High Guildmaster of Syderia, Belphegor, amongst others, all sought to claim the Throne of Jantris, and were willing to raze heaven and earth to seize it for themselves. The High Lords were each gifted with supreme divine power, the power to create and shape the world as they saw fit, yet in their frenzied state, they would wield this supreme divine power in the same way a man may wield an especially sharp rock. These Wheel-Turning Kings, each a mighty lord with armies capable of laying continents to waste, once kept restrained by the presence of the Divine Emperor, ruthlessly turned their weapons on each other.

Unfortunately for all those in Jantris, the Mad Lords would not cease their fighting until either only one remained, or there was no Jantris left for them to rule. Only one would be granted divinity upon ascension to the Throne, and, in their arrogance, the High Lords would either smash the Wheel, merely perpetuating the cycle for eons longer, or one among them would ascend to become the _true_ Wheel-Turning King: _The Chakravartin._

Unbeknownst to the High Lords, however, the Emperor had not truly disappeared for good, and was instead merely acting upon the designs he had laid the groundwork for long ago. Tyrodin, above all else, desired to bring about a _true_ degree of perfection to his creation, rivalling that of the highest planes of reality.  While his utopian realm of Jantris was great, it was not _perfect._ The Emperor wished to create a realm free of suffering, pain, and flaws, and to that end, he would require power far greater than that of even the Chakravartin.

In an effort to ascend past the limitations of the Mortal and Divine planes, Tyrodin would resort to dark and obscure forms of magic, and in the process, would make a single extremely _grave_ mistake. The Divine Emperor, despite being a brilliant strategist, able to outwit and outmaneuver even the Seven, and punch above his weight at some of the entities beyond this realm, would find himself having been _tricked_. 

Having sought out numerous methods of ascension for eons himself, none of Tyrodin's methods would prove successful until he encountered an ancient-beyond-ancient tome known as _"The King and the Fool"._ Initially, the Emperor dismissed the tome as a mere story book, a fairly unremarkable tale of a King's court, but hidden deep within the particulars of the ancient language of the book existed ancient words of power that could be used to awaken the dormant strength stored within the tome. After realizing the true value of the tome he now had in his possession, he'd sneak into his palace in the heart of Jantris, and would study it extensively, hidden away from the High Lords deep within his secretly constructed quarters, far below the absolute lowest levels of the palace. Eventually, after essentially reconstructing an entire lost language, he managed to decode the words of power hidden within the tome. 

Though something in his mind kept telling him to stop, to not invoke the words of power, and to cast the tome into flame of creation itself, Tyrodin could not bring himself to stop when he believed he was so close to his goal. After all of his efforts, and the eons upon eons he had spent chasing this goal, it was practically a foregone conclusion that he would invoke the words of power, and unseal the dormant energies within the tome. 

Upon unsealing the power contained within, the Emperor was instantly hit with a strange sensation he had not felt for an unspeakably long time. _Mortality._ _Something_ had a hold of him. Moreover, something had a hold of his _soul._ A few moments later, it all clicked. As powerful as the Divine Emperor and the Seven were, they were merely the gods of the mortal plane, barely even demi-gods compared to the true deities that maintained the highest and most fundamental layers of reality. 

Tyrodin had inadvertently scorned the God of Fate, a being known by many names but most commonly _The Fool_, and _this_ was his punishment. _The Fool_ knew all along that the King would attempt to overstep his bounds, and laid a trap in advance, deciding that he needed to be taught a lesson. In an instant, what was once the single God-Soul of the Divine Emperor of Jantris became a trillion tiny shards, scattering through the cosmic winds like the leaves of a tree in the autumn breeze. 

With the Emperor's soul scattered to the cosmic winds, spreading out through space _and_ time, and all of Jantris aflame with the fires of war, the history of this time becomes murky, and nearly impossible to track. What _is_ certain is that a fragment of the Emperor's great soul has arrived in our time. What you must know is that _you_ are that fragment, whether or not you understand this at the moment. If you ever hope to reclaim the power you once wielded, you _must_ escape this place, and find a way to reunite the fragments of your soul. If you cannot, the Seven will destroy Jantris, and everything you sought to build will crumble to dust. Escape this place, reunite the fragments of your soul, and reclaim your position as the true Wheel-Turning King! 

--- 

**Sources & Citations:**

Auto Possess and Switching Between a Player and a Pawn in Unreal Engine

- https://www.youtube.com/watch?v=dgkQGUeWKSA

UE4 - Changing Characters UE4 Possession

- https://www.youtube.com/watch?v=FeHd_PibD14

Possess Pawn with Line Trace & Attach Actor in Vehicle in Unreal Engine1

- https://www.youtube.com/watch?v=g1V2MxYEVus

UE4 - Tutorial - Possession! 

- https://www.youtube.com/watch?v=RwtCfMMMt7M

Create a Multiplayer Prop Hunt Game | Unreal Engine 5.4 Beginner Tutorial

- https://www.youtube.com/watch?v=nBC0C7xrubA

How To Change A Blueprint Parent Class In Unreal Engine 4 & 5 (Tutorial)

- https://www.youtube.com/watch?v=T2W-rYcLcOM

---

**3D Assets**

**Blair:**

Furniture FREE - Low Poly 3D Models Pack

- https://www.fab.com/listings/3eca0616-aa73-4348-9af5-cb4c173f237e

**Sergio:**

- https://free3d.com/

* Flower pot 3D model
* Realistic bottle of Coca Cola 3D model
* Table and chairs 3D model
* Avonni Polyresin Table lamp 3D model 
* Rectangular Rug 3D model

