# ~~FOSSboard~~ ~~QuadCore~~? Hover Cruiser!
An open source off-road electric longboard/mountainboard/crosscountry hybrid thingimabop made out of upcycled parts from old unused hoverboards!  
Designed to be repairable, Open Source, easy to build and modifiable to your liking.  
NGL I'm maybe overhyping it, feel free to make this project better by raising issues ans making PRs.  

While dissasembling a few hoverboards and flashing them I've thought of ways on how to recycle old hoverboars and the thought oh making some kind of PEV came into my mind. And yeah a stable and powerfull one. Atleast after trying to make a OneWheel clone.  

![](/images/BoardIso.png)  
![](/Electronics%20diagram.drawio.png)  
![](/battery.png)  
![](/Bad%20sketch.png)  

## Design consideration
- ~~Custom designed powerfull VESC~~
- ~~intuitive controller with readout of all of the important values~~
  - These went right out of the window because of price
- High power custom designed LiFePo4 battery pack with powerfull BMS.
  - Prismatic cels fall into this category as they have smaller internal rezistance and have better current carying capacity.
  - I need atleast 15A from my testing with vehykl.

## Safety
- the LiFePo4 battery is at low risk of battery explosions and fires
- Off the shelf BMS as it's the only thing I don't want to mess with 🎇
- ~~DIY VESC is not proven and a bit dangerous lol.~~
- Upcycled ESC from old hoverboards.
- ~~Important values right on the controller so you can monitor while riding~~
- XT90 yaink out loop when shit goes bad - hopefully not 🤞

## Mostivation
I've been obsesed with electric vehycles for a long like. I've got an electric scooter like four years ago, but it died recently and I don't have a way to get around quickly. :(  
So I've began making my own onewheel out off hoverboard motors (For this purpuse this repo was supposed to be) but after watching a few reviews of onewheels I've found out that there are so many flaws and that's why I have opted to making an electric skateboard!  
Also this is my last hackclub program I can take part in, so I've opted for a super challanging and long term project to test my skils!  

## Inspiration
FOSSwheell  
https://www.kocian.info/blog_RKMBe.html  
https://pehrsona.com/projects/hardware,skateboard/electric-skateboard/  
https://www.youtube.com/watch?v=1y4zh5mAdzA  
https://www.wildcircuits.com/2016/10/electric-mountain-board.html  
https://www.thingiverse.com/thing:4819536  

## BOM - overview
| Item                     | QTY | Price | Link |
| ------------------------ | --- | ----- | ---- |
| Frame, Deck              | -   |
| Aluminium extrusion      |
| CNCed / 3D printed parts |
| HW & bits and bops       |
| Hoverboard wheels        | 4   |
| ESC      | 2   |
| Cables, Connectors       |
| BMS, LiFePo4 Batteries   |

## cloning the repo
This repo contains submodules.  
`git clone https://github.com/Tomas-Kuchta-FPV/FOSSwheel.git`  
`git submodule init`  
`git submodule update`  

