<!--
author:   Your Name
email:    your@email.com
version:  0.1.0
language: en
narrator: US English Female

comment:  This simple description of your course.
          Multiline is also okay.

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js
 
import: https://raw.githubusercontent.com/liaScript/mermaid_template/master/README.md
 
import: https://raw.githubusercontent.com/liascript-templates/plantUML/master/README.md

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/markjjacob/UNIcertIII/blob/main/concept_maps.md)

# Today's session

@mermaid(`flowchart LR\nid1(This is the text in the box)`)


## Concept map
 

```text @mermaid
flowchart LR
    A[Microscopy] --> |One| B[Solution]
    A --> |Two| C[Problem]
    style A fill:#F99
    B --> D[Stefan Hell]
    style D fill:#FF0
    B --> E[W. E. Moerner]  
    B --> F[Eric Belzig]
        style F fill:#6FF
    D --> |Key concept| I[<br/><p/>Individual molecules <br/><br/> can be fluoresced<br/><p/>]
    E --> |puts into <br/> practice| I
    F --> |Key concept| I
    I --> J[Stimulated emission <br/> depletion]
    style J fill:#FF0
    style K fill:#9C6
    I --> L[Single molecule <br/> microscopy]
        style L fill:#6FF
    J --> K
    I --> K[Nanoscopy] 
    L --> K
    C --> |Abbe's diffraction limit| M[Resolution > 0.2 µm]
    M --> |impossible <br/> to| N[discern small <br/> objects]
    M --> |possible <br/> to| O[see cell <br/> organells]
```
 
## next one
 
```text
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me
```
@mermaid_eval

## Last one

```text @plantUML
@startuml
start
if (condition A) then (yes)
  :Text 1;
elseif (condition B) then (yes)
  :Text 2;
  stop
(no) elseif (condition C) then (yes)
  :Text 3;
(no) elseif (condition D) then (yes)
  :Text 4;
else (nothing)
  :Text else;
endif
stop
@enduml
```

## vv

```text @plantUML
@startgantt
[Prototype design] lasts 15 days
[Test prototype] lasts 10 days
-- All example --
[Task 1 (1 day)] lasts 1 day
[T2 (5 days)] lasts 5 days
[T3 (1 week)] lasts 1 week
[T4 (1 week and 4 days)] lasts 1 week and 4 days
[T5 (2 weeks)] lasts 2 weeks
@endgantt
```



## vvv
	
```text @plantUML
@startwbs
* IUZ "Alexander von Humboldt"
 -_ Task 2.2.1 To the left boxless
** International Office
*** Complete Stakeholder Research
*** Initial Implementation Plan
** Design phase
*** Model of AsIs Processes Completed
**** Model of AsIs Processes Completed1
**** Model of AsIs Processes Completed2
*** Measure AsIs performance metrics
*** Identify Quick Wins
** Complete innovate phase
@endwbs
```

## text 1

Trio win physics Nobel for work deciphering chaotic climate
October 5, 2021
STOCKHOLM, Oct 5 (Reuters) - Japanese-born American Syukuro Manabe, German Klaus Hasselmann and Italian Giorgio Parisi won the 2021 Nobel Prize in Physics on Tuesday for work that helps understand complex physical systems such as Earth's changing climate.
In a decision hailed by the U.N. weather agency as a sign of a consensus forming around man-made global warming, one half of the 10-million Swedish crown ($1.15 million) prize goes in equal parts to Manabe, 90, and Hasselmann, 89, for modelling earth’s climate and reliably predicting global warming.
The other half goes to Parisi for discovering in the early 1980s "hidden rules" behind seemingly random movements and swirls in gases or liquids that can also be applied to aspects of neuroscience, machine learning and starling flight formations.
"Syukuro Manabe and Klaus Hasselmann laid the foundation of our knowledge of the Earth’s climate and how humanity influences it," the Royal Swedish Academy of Sciences said in a statement. "Giorgio Parisi is rewarded for his revolutionary contributions to the theory of disordered materials and random processes."
Hasselmann, who is at the Max Planck Institute for Meteorology in Hamburg, told Reuters from his home that he did not want to wake up from what he described as a beautiful dream.
"I am retired, you know, and have been a bit lazy lately. I am happy about the honour. The research continues," he said.
The Academy said Manabe, who works at Princeton University in the United States, had laid the foundation in the 1960s for today's understanding of Earth's climate after moving to the United States from Japan to continue his research.
Interviewed by U.S. and Japanese journalists at his home, Manabe said he believed his award reflected the Academy’s recognition of climate change, which he said will continue to intensify with more droughts, torrential rains, warming of land masses and melting of polar ice.
"Already, as you know, there are many phenomena showing climate change is happening," he said in Japanese. "And I think that is the reason why the theme of climate change was selected for the award this time."
Asked in English how he would address climate change sceptics, he smiled and replied, “That problem is about a million times more difficult than understanding climate change. It is very mysterious to me.”
Hasselmann, the Academy said, had developed models about 10 years later that became instrumental in proving that mankind's carbon dioxide emissions cause rising temperatures in the atmosphere.
Parisi, who dialled into the media briefing announcing the winners, was asked for his message to world leaders due to meet for U.N. climate change talks in Glasgow, Scotland, from Oct. 31.
"I think it is very urgent that we take real and very strong decisions and we move at a very strong pace," said the 73-year-old Nobel laureate, who works at Sapienza University of Rome.
Scientists have spent decades urging climate change action on an often reluctant society, Hasselmann said in a recording published on the Nobel Prize's website.
"It is just that people are not willing to accept the fact that they have to react now for something that will happen in a few years," he said.
GLOBAL WARMING
Work on climate change has been recognised by Nobel prizes before.
Former U.S. Vice President Al Gore and the U.N. climate panel received the Peace Prize in 2007 for galvanizing international action against global warming. William Nordhaus won one half of the 2018 Economics prize for integrating climate change into the Western economic growth model.
Swedish climate activist Greta Thunberg is also seen as a strong contender for this year's Peace Prize, due to be announced from Oslo on Friday. 
"Sceptics or deniers of scientific facts...are not so visible anymore and this climate science message has been heard," World Meteorological Organization Secretary-General Petteri Taalas said of this year's award.
Physics is the second Nobel to be awarded this week after Americans David Julius and Ardem Patapoutian won the prize for medicine on Monday for the discovery of receptors in the skin that sense temperature and touch.
The Nobel prizes were created in the will of Swedish dynamite inventor and businessman Alfred Nobel and have been awarded since 1901 with only a handful of interruptions, primarily due to the two world wars.
Like last year, there will be no banquet in Stockholm because of the COVID-19 pandemic. The laureates will receive their medals and diplomas in their home countries.
The physics prize announcement will be followed in the coming days by the awards for chemistry, literature, peace and economics.
($1 = 8.7290 Swedish crowns)
Ludwig Burger reported from Frankfurt; Additional reporting by Terje Solsvik in Oslo, Supantha Mukherjee and Anna Ringstrom in Stockholm, Johan Ahlander in Gothenburg, Kirsti Knolle in Berlin, Emma Farge in Geneva, Peter Szekely in New York, Andrew Hofstetter in Princeton and Angelo Amante in Rome; Editing by Timothy Heritage, Jon Boyle and Mark Heinrich

## Text 2

Black hole discoveries win 2020 Nobel Prize in Physics
By Niklas Pollard, Douglas Busvine
STOCKHOLM/BERLIN (Reuters) - Three scientists who unravelled some of the deep mysteries of black holes, the awe-inspiring pockets of the universe where space and time cease to exist, have won the 2020 Nobel Prize in Physics.
Britain’s Roger Penrose, professor at the University of Oxford, won half the prize of 10 million Swedish crowns (£867,411) for his proof that black holes are a direct consequence of Albert Einstein’s general theory of relativity.
“It was an extreme honour and great pleasure to hear the news this morning in a slightly unusual way - I had to get out of my shower to hear it,” Penrose told reporters from his home in Oxford on Tuesday.
German Reinhard Genzel, of the Max Planck Institute and University of California, Berkeley, and Andrea Ghez, at the University of California, Los Angeles, shared the other half for discovering that an invisible and extremely heavy object governs the orbits of stars at the centre of our galaxy.
Ghez - only the fourth woman to be awarded the Physics prize after Marie Curie in 1903, Maria Goeppert-Mayer in 1963 and Donna Strickland in 2018 - said she hoped it would inspire others to enter the field.
Asked about the moment of discovery, Ghez said: “The first thing is doubt.”
“You have to prove to yourself that what you are really seeing is what you think you are seeing. So, both doubt and excitement,” the 55-year-old American said in a call with the committee after receiving the award.
Genzel was on a Zoom call with colleagues when the phone rang. “Just like in the movies, a voice said: ‘This is Stockholm’,” the 68-year-old astrophysicist told Reuters Television in his cluttered office on the outskirts of Munich.
He was flabbergasted by the news: “I cried a little bit.”
WHERE TIME ENDS
Scientists have wondered since the 18th century whether any object existed in the universe that would exert a gravitational pull so strong that light may not be able to escape.
Einstein predicted in 1915, in his general theory of relativity, that space and time could be warped by the force of gravity. Yet he did not actually believe in black holes, and finding a way to prove their existence baffled scientists for another 50 years.
It was not until a seminal paper in 1965 that Penrose proved that black holes can really form - describing them in detail and stating that, at their centre, there is a singularity where time and space cease to exist.
Illustrating Penrose’s insight at the awards presentation in Stockholm, Ulf Danielsson of the Nobel Committee held a black ball the size of a grapefruit in one hand and pointed at it with the finger of his other hand.
At the ball’s edge, time stands still, Danielsson said, and as his finger pushed into it, its tip moves into the future.
It would be impossible to withdraw one’s finger without tearing it apart. Instead it would be “carried all the way into the centre of the black hole, where time ends and the known laws of physics cease to apply”.
Asked by Reuters what was the biggest riddle about black holes, Penrose said: “The greatest puzzle is the singularities, because we don’t know what to do with them: You see the black holes shield us from the singularities.”
Penrose, 89, had no complaints about being recognised late in life: “It’s a good thing to get it good and old, before you’re absolutely clapped out,” he said. “Don’t get it too early - that’s my advice.”
He also paid tribute to celebrated British theoretical physicist Stephen Hawking, who died in 2018, saying he deserved to win a Nobel prize for his own work on black holes.
‘AWE-INSPIRING’ MYSTERY
Subsequent efforts to find a black hole focused on the clouds of dust in a region of the Milky Way called Sagittarius A*. Using the world’s largest telescopes to observe how stars orbited, separate teams led by Genzel and Ghez concluded that around 4 million solar masses are packed into a region the size of our solar system.
“Penrose, Genzel and Ghez together showed us that black holes are awe-inspiring, mathematically sublime, and actually exist,” said Tom McLeish, professor of natural philosophy at Britain’s University of York.
Physics is the second of this year’s crop of Nobels to be awarded, after three scientists won the medicine prize on Monday for their discovery of Hepatitis C.
The Nobel prizes were created in the will of Swedish dynamite inventor and businessman Alfred Nobel and have been awarded since 1901.
This year’s awards are taking place under the long shadow of the COVID-19 pandemic that has curtailed much of the usual festivities surrounding the prizes. ($1 = 8.9108 Swedish crowns)
Additional reporting by Johannes Hellstrom, Supantha Mukherjee, Simon Johnson, Colm Fulton, Anna Ringstrom, Daniel Trotta, Ayhan Uyanik, Marcus Nagle, Guy Faulconbridge and Alistair Smout; Editing Alex Richardson, William Maclean and Mike Collett-White

