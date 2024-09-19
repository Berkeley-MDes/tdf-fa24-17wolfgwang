# Hello, I'm Josh. Welcome to my place!

## List
[week 1](README.md#week-of-09052024)

[week 2](README.md#week-of-09112024)

[week 3](README.md#week-of-09182024)

---
## Week of 09/19/2024

This week, I had an assignment to create a video alongside 3D printing. While brainstorming ideas, I found myself unconsciously sketching something on my rattling tablet. I often thought it was something I really needed while drawing, and this project made me realize it was time to create it.

<img width="1108" alt="Screenshot 2024-09-12 at 10 13 01 AM" src="https://github.com/user-attachments/assets/b9befb78-adae-4de1-8056-9ae02ebc2c51">

Studying Rhino was quite challenging. I learned by clicking on each node, understanding its meaning, and making adjustments as I went along.

<img width="1073" alt="Screenshot 2024-09-19 at 2 09 44 PM" src="https://github.com/user-attachments/assets/3082b9c2-3ddb-4116-9db9-981ae62fdd3d">

As I was following each node, wondering, "What makes this better compared to typical 3D modeling tools?", I realized something. I was logically thinking through how the design was constructed, step by step. While I’m not sure if this was the original intention or the main advantage of the tool, for me, it was a method that allowed me to easily understand the design process.

<img width="1031" alt="Screenshot 2024-09-19 at 2 11 29 PM" src="https://github.com/user-attachments/assets/061e01dc-60c0-4619-809c-bad7fcf3c636">

I, too, started creating and connecting nodes one by one in a similar logical manner. As a result, the brep union that had previously failed was successfully completed.

<img width="787" alt="Screenshot 2024-09-19 at 2 12 42 PM" src="https://github.com/user-attachments/assets/9c824b11-3a14-40f0-885e-c7548dfe132c">

I also learned how to fillet and modify edges using Rhino. Ultimately, I was able to create the following model.

<img width="733" alt="Screenshot 2024-09-19 at 2 14 16 PM" src="https://github.com/user-attachments/assets/06bfe607-6afc-48db-8e43-7f0e438258f5">

3D printing was another challenge. I had to learn how to use a slicer for the 3D printer, set it up properly, and understand the roles of features like brim and infill.

<img width="1257" alt="Screenshot 2024-09-19 at 2 16 00 PM" src="https://github.com/user-attachments/assets/5133f1a9-19d0-4fc5-a9df-e40ffb733601">

At one point, I failed due to incorrect settings, but with some help, I was able to successfully print it as shown here.

<img width="1194" alt="Screenshot 2024-09-19 at 2 16 18 PM" src="https://github.com/user-attachments/assets/e5d68e4c-519b-41b5-8a64-a69d6ecf24df">
<img width="1169" alt="Screenshot 2024-09-19 at 2 21 07 PM" src="https://github.com/user-attachments/assets/99b0317c-bc76-4bf6-be4b-f2d1be482d5d">
<img width="711" alt="Screenshot 2024-09-19 at 2 21 15 PM" src="https://github.com/user-attachments/assets/53368f65-1b5a-4bcb-a8fc-8453e9217fed">

Working on this project made me realize how challenging it can be, and it gave me a deep sense of appreciation for the everyday items I use. At the same time, I feel like I've developed the ability to understand and reflect on the design process and background of products on my own.

The video project is uploaded at the following link!
https://youtu.be/VX8ORQbAnoM

---
## Week of 09/11/2024
First, I tried to understand about the structure of grasshopper. I reviewed the given example and created a diagram.
![grasshopper drawio](https://github.com/user-attachments/assets/6e73c1ec-0a7c-4123-8eef-cb0e11b3cd22)

And I start to make my own. I tried to build my own box.

<img width="1108" alt="Screenshot 2024-09-12 at 10 13 01 AM" src="https://github.com/user-attachments/assets/5a321ce8-f8f0-4b87-b5b8-d19268197a7c">

I found that this node seemed to act as the origin point for the shape I was creating.

<img width="1133" alt="Screenshot 2024-09-12 at 10 15 16 AM" src="https://github.com/user-attachments/assets/01184f2c-b53e-4e3f-bf81-49f7da8ad668">

So I build a rectangle based on this point and extrude it.

However, the position wasn’t where I wanted it to be. So I put move node with Units. 

<img width="1169" alt="Screenshot 2024-09-12 at 11 01 06 AM" src="https://github.com/user-attachments/assets/ead1050d-f8ae-4119-9847-82f602be5114">

Now it move to the center.

And then, I tried to brep with the phone from cellphone stand exapmle.

<img width="1275" alt="Screenshot 2024-09-12 at 11 44 06 AM" src="https://github.com/user-attachments/assets/bbb6bb18-264e-426d-a49f-4c71ef9d2ba4">

The problem is that the result is just a common line of box and phone.

For better understanding, I follow Youtube video and make box like this.
<img width="1397" alt="Screenshot 2024-09-12 at 3 07 02 PM" src="https://github.com/user-attachments/assets/2c895c66-0cf2-4404-9448-f5725fdafdd7">



---
## Week of 09/05/2024

I have experience with 3D printing, but laser cutting is new to me, so I decided to give it a try. I thought it would be nice to highlight the natural color of the wood, so I considered making something like a Welsh Corgi that matches the color.

![5180633_0](https://github.com/user-attachments/assets/5a030097-98fe-43a8-bd64-2f8c5481e53d)
<img width="1009" alt="Screenshot 2024-09-12 at 11 24 05 AM" src="https://github.com/user-attachments/assets/285499b2-4475-4e5f-84be-bf510d0802b1">

There were specific rules for laser cutting. Lines that needed to be cut were set in red, and areas that needed to be lightly engraved were set in blue, with a line thickness of 0.001. Although the colors can be adjusted depending on the settings, it’s generally recommended to follow the commonly used conventions.

<img width="446" alt="Screenshot 2024-09-12 at 11 17 25 AM" src="https://github.com/user-attachments/assets/c554d2b0-0caf-41af-a549-966e729f8578">

After setting the material thickness and other parameters on the laser cutter, I was able to create this cute Corgi!

<img src="https://github.com/user-attachments/assets/b613fca0-bbc2-4ef8-aecb-76e28b6848f1" alt="Description of the image" width="500" height="500"/>

While waiting for the cutting, I also learned that QR codes can be engraved, which I think could be useful for future projects, so I made a note of it.

<img src="https://github.com/user-attachments/assets/b2cf6d3c-b406-41e5-9d9f-3a9d71b7578a" alt="Description of the image" width="500" height="500"/>


---

# Github Background Information & Context
If you’re new to GitHub, you can think of this as a shared file space (like a Google Drive folder, or a like a USB drive that’s hosted online.) 

This is your space to store project files, videos, PDFs, notes, images, etc., and (hopefully, neatly) organize so it's easy for viewers (and you!) to navigate. That said, it’s super easy for you to share any file or folder with us (your TDF instructional team) - just send us the link!  As a start, feel free to simply add images to the `/assets` folder, which is located [here](/assets). 

The specific file that I’m typing into right now is the **README.md** for this repo. 
##### (💡 TIP: The .md indicates that we’re using [Markdown formatting.](https://www.markdownguide.org/cheat-sheet/)) #####
<h6> (💡 TIP 2: GitHub Markdown supports <a href="https://gist.github.com/seanh/13a93686bf4c2cb16e658b3cf96807f2"> <em>HTML formatting</em> too, including emojis 😄</a>, in case that helps!) </h6>

### :star: Whatever you write in your **README.md** will show up on the “front page” of your GitHub repo. This is where we’ll be looking for your [weekly progress reports](https://github.com/Berkeley-MDes/24f-desinv-202/wiki/3.0-Weekly-Submissions#weekly-progress-report). They might look something like this: ###

# Week 1: Example Report 1 #
## Week of 09/05/2024

This week, I designed a cool phone stand made of rocks. Check out all my cool sketches and progress photos from this week below, etc., etc....

<img width="200" alt="Cool Phone Stand made of rocks" src="assets/exampleimg.png">

---

It's time to start making this space your own! If you want to save these instructions, make a copy.  Also, feel empowered to delete everything in this README.md and start documenting! 

Excited to work with you,
your TDF teaching team

PS: let us know if you have any questions!!

PPS: 

## Quick Links, compiled here for your convenience: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
