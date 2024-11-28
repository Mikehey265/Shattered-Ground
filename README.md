# Shattered-Ground
This is a comprehensive overview of my biggest game project made in Futuregames. It also marks my first project where I had the opportunity to showcase my techncial UI skills.

## Table of contents
* [General info](#general-info)
* [My contribution](#my-contribution)
* [Links](#links)

## General info

Shattered Ground was our attempt to recreate the widely beloved first-person shooter genre. For inspiration, we drew from iconic series like Battlefield and Call of Duty, as well as other leading games in the genre such as Delta Force and Tom Clancy's Rainbow Six Siege. Our goal was to introduce players to all core mechanics through a simple tutorial section, then immerse them in the battlefield to test their skills against real enemies. Additionally, we aimed to capture the cinematic single-player experience, some of these games are known for. This was our final project at Futuregames, and we aimed to showcase our abilities as a team—this is the result.

## My contribution

I will split this section into two parts. Since there were only two programmers on this project (myself included), I had to take on a variety of tasks. The first section will focus on my contributions as a gameplay programmer, while the second will highlight my role as a UI-focused programmer and designer.

### Gameplay

Our team consisted of nine incredibly talented individuals. As a gameplay programmer, I was responsible for almost every aspect of the game. I primarily worked alongside our Gameplay Designer, implementing character movement, gunplay mechanics, and providing the necessary tools to ensure the gameplay felt as polished and engaging as possible for the player. In addition to this, I laid the groundwork for the game by creating core systems such as the objectives system, player states, save system (which, admittedly, still has some bugs), and the pickup system, among others. My work spanned nearly every part of the project, and with only four weeks to complete it, the experience was both challenging and intense. However, looking at the finished product now, it feels incredibly rewarding.

### UI

I was determined to create a comprehensive and visually appealing UI that felt exactly as it should for the game. From the research phase to prototyping, implementation in the engine, and testing, I followed a thorough process to achieve this. Since I was often busy with other tasks, I frequently stayed late to work on the UI. I began by researching HUD designs from other FPS games, gathering elements that caught my attention. Using Figma, I compiled and organized these elements, aiming to design a cohesive HUD that both looked great and enhanced the player's experience. This was my first time using Figma, but I quickly grew to enjoy it. The final HUD prototype I created in Figma became the foundation for our game and remained largely unchanged through to jury day: <br><br>
![Game HUD](https://github.com/user-attachments/assets/36824322-7379-4f3f-ae89-939d4ebf7d08)<br><br>

After finalizing the HUD design, I shifted my focus to implementing it into our game. I created every single UI element, integrated it with our character blueprint, refined its visual design, and added animations using the sequencer. Seeing everything come together and function seamlessly was incredibly rewarding. Although we decided to scrap the minimap I had also worked on, that’s just part of the development process, right? This is how the HUD looked on jury day, after nearly four weeks of development:<br><br>
![Gunz_dont_delete Screenshot 2024 11 28 - 19 32 31 98](https://github.com/user-attachments/assets/86649ab8-c1f9-4548-8c82-2f8d2e804094)<br><br>

We received very positive feedback on our game, but there were some key issues with the UI I had created. First, after scrapping the minimap, the left side of the screen felt empty and somewhat unbalanced. Secondly, there were instances where text was barely visible, making it difficult for players to read. We also received feedback that manually picking up ammunition disrupted the gameplay's pace and felt unnecessary. Additionally, some players found the reload prompt hard to notice. There was also a significant bug with the damage indicator, which stayed on the screen for too long. Developing a game in just four weeks naturally resulted in a host of bugs. After the official Game Project 4 phase ended, I spent several more weeks focusing solely on improving the HUD. During this time, I worked on fixing bugs and enhancing the visuals, allowing me to refine the UI to a much higher standard. <br><br>

I went back to Miro, taking all the feedback into consideration. I started researching, gathering references, and creating new drafts in Figma. This is what the updated version looked like:<br><br>
![Game HUD v2](https://github.com/user-attachments/assets/d4d01b5b-7e1d-4453-93c8-155c541e97e2)<br><br>

I filled the empty space on the left side of the screen with a health bar and a more informative objective widget, which added more composition and balance to the layout. I completely redesigned the ammo widget by removing the grenade counter (which we weren’t using), and instead, I split the ammo and health information, adding the weapon name underneath. To improve text visibility, I decided to use a shadow effect. It was simple but effective. I also redesigned the reload and low ammo warnings, moving them from the ammo widget and positioning them right underneath the crosshair so players could immediately see when their weapon needed reloading. I removed the necessity for manually picking up magazines and made sure players could easily identify what they were picking up. To address this, I created a completely new pickup notification widget that stacked notifications based on how many pickable items the player collected. Here are some screenshots and GIFs showcasing how the updated HUD looks:<br><br>
![screen](https://github.com/user-attachments/assets/7c041c38-ff68-4791-909d-d82e5e07b052)
![gif3](https://github.com/user-attachments/assets/3f793e5d-9ee6-4306-810c-75a82f264219)
![Gunz_dont_delete2024 11 28-20 19 54 04-ezgif com-optimize](https://github.com/user-attachments/assets/2b37d7d9-2ae2-474a-acc8-1a82e470daea)
![gif2](https://github.com/user-attachments/assets/781febf8-517f-4d0f-aa94-2335a125131c)<br><br>


Since we didn't have a dedicated UI artist, I decided to create some materials myself using Unreal Engine's material graph. I used this approach for creating simple assets like a waypoint material and a basic circle indicator to show players when a pickable object was nearby. Additionally, I improved the UI animations to give them a more modern and polished look.<br><br>

My current goals are to create an options menu and explore Unreal Engine in greater depth, focusing on UMG, Sequencer, Materials, and Slate.

## Links

Trailer: https://youtu.be/yzujcoD1xUQ <br>
Itch.io: https://futuregames.itch.io/shatteredground <br>
LinkedIn: https://www.linkedin.com/feed/update/urn:li:activity:7255270391646945280/
