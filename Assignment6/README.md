# DH110 Assignment 6: Interface Design
Carlie Huang, Spring 2023

## Introduction
My quarter-long project aims to connect family members that experience communication gaps due to language barriers via an instant-translation messaging app. The purpose of this interface design is to develop a design library and perform usability testing by stylizing and polishing a wireframe from the [low-fidelity prototype last week](https://github.com/carliehuang/DH110/blob/main/Assignment5/README.md). The end result is a finished-looking, albeit static, product. I decided to use the chats frame from my wireframes last week because it pertains to the most important feature in the app, messaging, and essentially acts as a home screen. Therefore, it is very important in establishing look and feel. Here is the wireframe that I went off of:

<img width="200" alt="wireframe" src="https://github.com/carliehuang/DH110/assets/25852597/6d87477f-de49-4aac-adb9-ea8a211d6d4c">


## Screen Design
I created my interface design on Figma, and the complete file with all the components below can be found [here](https://www.figma.com/file/3AQZ1Fj5Yg1cM31CJTvxjJ/Untitled?type=design&node-id=0%3A1&t=Sj2MD7xXPiOSE23D-1). Furthermore, the wireflow is the same as last week's and can be found [here](https://www.figma.com/file/wsijPX0GeTLQZbH0KcJxIQ/DH110-Assignment-5%3A-Low-Fidelity-Prototype?type=design&node-id=0%3A1&t=f3mcnqIjwyfpiYdR-1)— select Prototype in the right column to view.

### Layout and Spacing
The frame I chose includes the title, a search function, an add chat button, chats, and the menu. I decided to stray from my wireframe in terms of the search bar and add chat in order to make the interface resemble other messaging apps more. I thought having the search bar already present would make it more intuitive to use, and the add chat button is very easy to see and mimics other designs I've seen as well. In Figma, I used a layout grid with 4 columns with a 16px margin and 20px gutter and 7 rows with a 16px margin and 20px gutter.

<img width="720" alt="Screen Shot 2023-05-15 at 11 30 19 PM" src="https://github.com/carliehuang/DH110/assets/25852597/23ce8222-d155-4ecc-9107-f8a240f20d96">

### Typographic Variations
At first I chose a fun, standout font for the title, Modak, and a pretty standard font for the body text, Lato. While I do still enjoy Modak, I decided that it isn't super readable, which could be a problem for older demographics, and it's hard to reuse in other places. Therefore, I switched over to Inter, which has a very clean and simple look. However, it looked a little boring and bare with regular font weight, especially along with Lato. Therefore, I switched it up by making the title and subtitles bold Inter and the body text Work Sans, which is more unique than Lato. The bold title is also more cohesive with the bottom menu icons.

<img width="720" alt="Screen Shot 2023-05-16 at 12 07 00 AM" src="https://github.com/carliehuang/DH110/assets/25852597/ba5ebb75-690e-4950-a1f0-41b04b20975b">

### Shape Variations
I started by following the wireframe pretty closely, which resulted in square-shaped profile pictures. However, I didn't like how it wasn't cohesive with the circular notification symbol, and it looked to aggressive to me so I changed them to circles. Furthermore, the buttons looked a little too flat, so I added a drop shadow effect to them to make them look more appealing and clickable. Finally, I played around with the roundness of the search bar, and decided on radius 4, which I think looks rounded enough to be friendly, but not overly so.

<img width="720" alt="Screen Shot 2023-05-16 at 12 16 42 AM" src="https://github.com/carliehuang/DH110/assets/25852597/7f5c1469-bf83-415f-8a3b-1386c8e719cd">

### Color Variations
I came up with two color schemes: a light mode and a dark mode. At first, with the dark mode, I had the background color as the same dark blue of the title and menu icons, but the constrast was too high and it didn't look quite right, so I toned the blue down. Then, most of it was just switching colors. I'm pretty happy with the color scheme I came up with— I think it looks rather clean and professional. However, I do prefer the light mode to the dark mode. I think part of it might be that the drop shadow on the buttons isn't as visible in dark mode; I might have to play around with it a little more.

<img width="480" alt="Screen Shot 2023-05-15 at 11 59 19 PM" src="https://github.com/carliehuang/DH110/assets/25852597/b5f5cb40-714c-4803-99ed-f6ec7dfc0a4f">

## Impression Test
The recording of the impression test I performed is [here](https://drive.google.com/file/d/1K0Oil-qUa-LQzGsZItYm2liCzkxPIkKg/view?usp=sharing).

I think the impression test went really well. She instantly recognized it as a messaging app: this is very important because if it looks and feels similar to other messaging apps, less technologically-adept people can adapt to it easier. She also named the colors and different sections of the screen, which tells me that everything was easily noticable and laid out intuitively. Overall, she described the design as pretty minimal and said it mostly made her feel a sense of calm. I'm pretty satisfied with these results, but one small thing she didn't mention was the search bar; I may need to figure out how to make it stand out more.

## Accessibility Check
<img width="761" alt="Screen Shot 2023-05-16 at 12 55 27 AM" src="https://github.com/carliehuang/DH110/assets/25852597/64e06acf-738e-49eb-9479-4618e8c4d437">

As you can see in the screenshot, the interface design in both color schemes passes the accessibility test run through Figma's A11y plugin. I had to change a couple of things to make the test pass— at first, the last text message in the "Grandma" chat was too light grey, and the text in the search bar did not stand out enough against the search box color. However, I'm satisfied with the changes I made and agree that the text is more readable in all situations.

## Design System
To view the design in detail/full, click [here](https://www.figma.com/file/3AQZ1Fj5Yg1cM31CJTvxjJ/DH110-Assignment-6%3A-Interface-Design?type=design&node-id=0%3A1&t=Sj2MD7xXPiOSE23D-1)

<img width="794" alt="Screen Shot 2023-05-16 at 12 36 53 AM" src="https://github.com/carliehuang/DH110/assets/25852597/460b27e6-c8ed-416e-8df9-4b0b4f0c0ec7">

My design decisions were based around making the interface as minimal, intuitive, and accessible as possible; this is particularly important to the older demographic I aim to serve. Along the same lines, I wanted to make sure it resembled other popular messaging apps to minimize the learning curve for adopting Bridge. Based on these factors, I designed my menu to be almost identical to WeChat's. I used bold colors and large icons to clearly indicate where every component is located and to make it harder to mis-click. The search bar resembles pretty much any other search bar out there, and the flow of information resembles other messaging apps as well. I rounded several edges to make the interface seem more friendly. Overall, I think I created an interface that most people would be able to understand and use.

