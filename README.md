# Hello, I'm Josh. Welcome to my place!

## List
[week 1](README.md#week-of-09052024)

[week 2](README.md#week-of-09112024)

[week 3](README.md#week-of-09182024)

[week 4](README.md#week-of-09262024)

[week 5](README.md#week-of-09302024)

[week 6](README.md#week-of-10032024)

[week 7](README.md#week-of-10102024)

[week 8](README.md#week-of-10172024)

[week 9](README.md#week-of-10242024)

[week 10](README.md#week-of-10312024)


## Week of 12/05/2024
  
#### Team Task Division

	•	For the final project, tasks were divided among team members.
	•	My Responsibility: Sensor integration, motorized mechanism, and coding-related components.
	•	Objective: Ensure Arduino and Photon communicate with the server to update users’ consumed calories in the Snackbox.

#### Development Process

1. Initial Testing with Arduino

	•	Due to unstable network conditions, started testing with Arduino.
	•	Goal: Establish communication with Google Sheets API using Arduino for data storage.

2. Testing with Google Sheets API (Node.js)  
<img width="500" alt="Screenshot 2024-12-07 at 2 01 27 PM" src="https://github.com/user-attachments/assets/d9c524ef-18d8-49d2-95cc-937d9373f8be">  
  
	•	Steps Taken:
     Implemented Google Sheets API communication using Node.js.
     Tested by sending random data to Google Sheets through code.
	•	Required setup:
     Google Auth key.json file.  
   <img width="300" alt="Screenshot 2024-12-07 at 2 12 25 PM" src="https://github.com/user-attachments/assets/69c5fdfb-6fbe-4153-adf8-9ecd9746e9d8">  
     Google Sheets ID.  
   <img width="300" alt="Screenshot 2024-12-07 at 2 12 46 PM" src="https://github.com/user-attachments/assets/b00590a9-5f68-481d-bdf0-a731b1a6edcf">  
  
   Successfully sent and stored data in Google Sheets.  
  
4. Transition to Arduino (.ino File)  
<img width="500" alt="Screenshot 2024-12-07 at 2 00 04 PM" src="https://github.com/user-attachments/assets/969efe4e-99cd-4266-ae74-98178ea979b8">  
  
	•	Adapted the working Node.js code into an .ino file to enable Arduino to directly communicate with Google Sheets API.
	•	Obtained an API key using the Google Cloud Console.
	•	Successfully tested the communication between Arduino and Google Sheets, achieving expected results.  
<img width="500" alt="Screenshot 2024-12-07 at 2 00 11 PM" src="https://github.com/user-attachments/assets/4f234805-7f1e-4932-84e1-e40b0059cf5b">  
  
5. OpenAI API Integration  
  <img width="500" alt="Screenshot 2024-12-07 at 1 59 52 PM" src="https://github.com/user-attachments/assets/1837a1e7-4841-4e9d-b708-0c88b44b7636">  
  
	•	Objective: Use OpenAI API (LLM) to calculate the following:
	  1.	Approximate Basal Metabolic Rate (BMR).
	  2.	Calories in one grab (handful).
	  3.	Daily calorie limit for the user.
	•	Successfully implemented communication between Arduino and OpenAI API.  
<img width="500" alt="Screenshot 2024-12-07 at 2 00 20 PM" src="https://github.com/user-attachments/assets/c609ce61-782f-43db-afd8-61126aa39b19">
 
	•	Results obtained:
     User’s daily calorie limit.
     Calories per handful.
     Total steps required for the pump mechanism.


Outcome

	•	Arduino and Google Sheets API communication established successfully.
	•	OpenAI API utilized to perform specific calculations, providing valuable data for the Snackbox system.
	•	Final setup enables efficient calorie tracking and motorized mechanism control for the Snackbox project.



## Week of 11/21/2024
  
For the final Project 4, I conceptualized a Snack Box.  
  
The inspiration came from my own habits of snacking. I often found myself finishing an entire snack without realizing it, only to feel concerned about its health impact afterward. I tried quitting snacks altogether, but it was challenging. Instead, I wanted to find a way to enjoy snacks moderately while maintaining a healthy lifestyle.  

<img width="500" alt="Screenshot 2024-11-14 at 1 02 23 PM" src="https://github.com/user-attachments/assets/c07d12e9-ed59-4719-adce-b1da39636cf3">  

Together with Chuhua and Yule, we formed a team, each taking on the following responsibilities:  
  
Yule : Mobile app development and cloud data integration.  
Josh : Sensor and motorized mechanism integration.  
Chuhua: User interaction design and feedback systems.  
  
---
## Week of 11/14/2024

#### Final project를 정리하고 report를 제출하였다.
최종 각 링크는 다음과 같다.
- [Experiment 1](https://zerowidth.ai/c/demo/2EgtmBevxGDgas6w7f6C/draft)
- [Experiment 2](https://zerowidth.ai/c/demo/IRouVARd1zcw8NyPUq0o/draft)
- [Experiment 3](https://zerowidth.ai/c/demo/wwEwQkYHlEy8NBCff6Fv/draft)
- [Experiment 4](https://zerowidth.ai/c/demo/ordaoFNgvm31XtaxB0LV/draft)
- [Final Experiment](https://zerowidth.ai/c/demo/s7bcOyLNhS7bl9KtXpDm/draftm i Youtube Video(https://youtu.be/SjqrSGHT6Ao)

<img width="500" alt="Screenshot 2024-11-14 at 11 26 27 AM" src="https://github.com/user-attachments/assets/5c28cc80-ff73-4b6d-ab81-27038e0b2e4c">

#### Process
1. Set Knowledge : Subjects, Words -> 2. Set Instruction -> 3. Set Model : GPT-4o -> 4. Write Input -> 5.Check Output
<img width="500" alt="Screenshot 2024-11-14 at 1 02 23 PM" src="https://github.com/user-attachments/assets/3af9667a-0838-45c9-9b4d-48167cc1d84c">

#### Result

The goal of this project was to create an agent that could respond naturally and provide helpful information. I focused on improving its understanding, designing an easy interaction flow, and adding a knowledge-based feature to give relevant information. These efforts helped create a responsive and user- friendly agent

I ran experiments to improve the agent’s abilities. First, adjusting the “temperature” showed that higher settings made responses creative but less consistent, while lower settings made them more predictable. I also tested different question styles to see how they impacted responses and added a knowledge-based feature for faster, accurate answers

These experiments shaped the final design. Temperature testing helped balance creativity and accuracy, and the knowledge-based feature made the agent’s responses more relevant. Simplifying questions also made interactions clearer. These changes led to a prototype that meets project goals with a smooth, accurate experience.

#### Conclusion

This project allowed me to explore foundational aspects of building an AI agent using Zerowidth, providing valuable hands-on experience. I developed two distinct projects: a word-guessing game with variable difficulty levels and an AI-powered assistant that uses Google Voice API for voice input. Positive feedback highlighted the projects’ functionality, creativity, and clarity. Reflecting on the process, I’m pleased with how each project demonstrated unique interaction methods and potential. Moving forward, I plan to continue using Zerowidth in my projects beyond the course, further enhancing interactive features like adding text-to-speech to deepen user engagement and immersion.

---
## Week of 11/07/2024

#### What is ZeroWidth?

: ZeroWidth is an AI tool that enables interaction through an API, designed for customized AI conversations based on the specific needs of the user.

#### What is an AI Agent?

: An AI Agent is a system designed to simulate human-like conversations, often using natural language processing to interact and respond based on user inputs. Unlike standard AI chatbots like ChatGPT or Claude, an AI Agent can be tailored to utilize specific data, allowing for more customized responses.

#### Experiments

Through the experiments provided in the assignment, I was able to understand differences between models and the variations in performance across different stages.  
<img width="500" alt="Screenshot 2024-11-12 at 3 16 11 PM" src="https://github.com/user-attachments/![Uploading Screenshot 2024-11-12 at 3.19.53 PM.png…]()
assets/7ca27cea-ed3c-4c2b-a812-a1444fb76638">

<img width="500" alt="Screenshot 2024-11-12 at 3 20 12 PM" src="https://github.com/user-attachments/assets/442bea18-6109-45ab-9a5d-5a22b6a1093f">

#### How can this be applied?

One of the strengths of an AI Agent compared to ChatGPT or Claude is its ability to operate based on data that I provide. I considered using it to create a simple game inspired by “20 Questions.” The idea is to create a game where the AI can understand and respond to questions based on a set of predefined word data.

Data  
<img width="1041" alt="Screenshot 2024-11-12 at 3 19 03 PM" src="https://github.com/user-attachments/assets/367e5155-c91b-476c-8e8a-bc36abf0d012">  

<img width="500" alt="Screenshot 2024-11-12 at 3 18 29 PM" src="https://github.com/user-attachments/assets/be7a4f23-10d3-4378-a23d-5abe19f15613">  


Additionally, I utilized APIs to bring the AI agent into a web-based setting. In the Bay Area, there are often valuable opportunities through Zoom events. However, I’ve missed some due to class or other commitments. This inspired me to create an agent that could attend Zoom meetings on my behalf, participate in the sessions, and provide a summary of the meeting afterward for me to review.

I considered the following five stages, though I could only proceed up to stage two due to time constraints.  

<img width="500" alt="Screenshot 2024-11-12 at 3 16 51 PM" src="https://github.com/user-attachments/assets/b6105011-745e-4f34-ad52-ede0e3a8b51b">  
<img width="500" alt="Screenshot 2024-11-12 at 3 16 43 PM" src="https://github.com/user-attachments/assets/88a9caf3-58ee-432e-97fb-b127725fde04">  

<img width="800" alt="Screenshot 2024-11-12 at 3 17 58 PM" src="https://github.com/user-attachments/assets/f465cb3f-dcb5-41fb-adea-f323339cf05a">  

The final project was submitted as a video in the following format.  
[Watch the Video](https://youtu.be/SjqrSGHT6Ao)


---
## Week of 10/31/2024

Learned about Zerowidth, I was always want to learn about building AI Agent.
And It also glad to see actual founder who make this service.
<img width="500" alt="Screenshot 2024-10-31 at 4 13 29 PM" src="https://github.com/user-attachments/assets/666e0b83-2686-4a0d-852c-d9ec396071f1">

I tried sample simple Q&A flow.
<img width="500" alt="Screenshot 2024-10-31 at 4 14 08 PM" src="https://github.com/user-attachments/assets/7c398c22-b6a5-4a35-8cd3-e646b3a551ee">

And I follow things what I learned and tried to make one chatbot
<img width="500" alt="Screenshot 2024-10-31 at 4 14 22 PM" src="https://github.com/user-attachments/assets/a0eb883a-2eea-4d8a-a93e-db642ff07fe0">

I put prompt like this
<img width="500" alt="Screenshot 2024-10-31 at 4 14 33 PM" src="https://github.com/user-attachments/assets/03311742-3b1e-41c0-9cf5-6bcbe89c1fce">

And finally it works like this
<img width="500" alt="Screenshot 2024-10-31 at 4 15 07 PM" src="https://github.com/user-attachments/assets/d0f0d552-cb6e-4873-adff-f8718824e235">

quite interesting experience, get some inspriation of ideas.

---
## Week of 10/24/2024

I attached it to the backpack and performed calibration using SensorLab, as Jeff recommended.
<img width="987" alt="Screenshot 2024-10-24 at 3 55 07 PM" src="https://github.com/user-attachments/assets/5acff835-ef20-46eb-9581-55cb78f80e9b">

After that, if the posture deviates from the correct alignment, it triggers vibration and LED alerts along with the tilt detection.  

Right posture  
<img width="500" alt="Screenshot 2024-10-24 at 3 53 45 PM" src="https://github.com/user-attachments/assets/a0aceed9-bb70-4886-87dc-40c0a64ac94f">

Wrong posture(Vibration & Alarm)  
<img width="500" alt="Screenshot 2024-10-24 at 3 53 55 PM" src="https://github.com/user-attachments/assets/0e0cb95a-8f0e-47ce-a3f0-8367e80c9700">


---
## Week of 10/17/2024
We tested all of our elements first.
LED  
<img width="435" alt="Screenshot 2024-10-24 at 3 47 30 PM" src="https://github.com/user-attachments/assets/01fb1b32-4874-418c-b8bc-fa683c84668e">

Haptic sensor  
<img width="591" alt="Screenshot 2024-10-24 at 3 47 40 PM" src="https://github.com/user-attachments/assets/8dc5e643-9803-4482-aa6a-199fd0ed85d0">

Button connected to LED  
<img width="528" alt="Screenshot 2024-10-24 at 3 47 53 PM" src="https://github.com/user-attachments/assets/1564c319-0229-4242-bc2d-901a842f919a">

Gyro sensor(with data)  
<img width="570" alt="Screenshot 2024-10-24 at 3 48 50 PM" src="https://github.com/user-attachments/assets/399fb39f-7f79-4fa7-8e9d-026d0331d0ee">

Everything is working well, and I’ve assembled it all together.  

The plan is to enclose the components in a box like this and attach it to the bag using a cable tie in the back.  
<img width="570" alt="Screenshot 2024-10-24 at 3 48 50 PM" src="https://github.com/user-attachments/assets/17e2f956-d7c4-478b-945e-a2c8745b1a48">  

After calibration, the correct posture will be set, and as the user moves, the device will trigger vibration and LED notifications when necessary.

---
## Week of 10/10/2024

We have formed a team for the project. The idea, developed together with Yule, is a posture correction notification system using a gyroscope sensor.

As shown in the image below, when the back is bent or posture is poor, the gyro sensor detects the angle and triggers a notification.

<img width="500" alt="Screenshot 2024-09-30 at 3 57 17 PM" src="https://github.com/user-attachments/assets/242823bd-b355-456f-8012-0e2b3f0f6679">

The operation process is summarized as follows:

<img width="500" alt="Screenshot 2024-09-30 at 3 57 17 PM" src="https://github.com/user-attachments/assets/752656ca-fd85-4566-b212-fd5ff339357c">

The essential inputs are:

- Input 1: Button 1 – Power on/off
- Input 2: Gyroscope sensor data
- Input 3: Button 2 – Calibration process on

The outputs will be : 
- Vibrator
- LED

I'm looking forward to seeing how the project will turn out.

---
## Week of 10/03/2024

I learned a new technology, Photon2.

I had briefly worked with Arduino before, but this was my first time using Photon2. The main difference is that it can connect to the internet, while the rest is pretty much the same as Arduino.

Since I learned how to make connections during the class, I wanted to try a small project using LEDs. I found a project in the class materials that changes the LED color based on pressure, so I decided to give it a try.

<img width="878" alt="Screenshot 2024-09-30 at 3 57 17 PM" src="https://github.com/user-attachments/assets/78f00ff1-d959-4299-acb2-50765bfd744d">

I uploaded a video of it working on YouTube. Due to the unstable connection of the pressure sensor, I had to hold it by hand during the test.

https://youtu.be/qqoc9y283Ho

Next time, I plan to use an API to take advantage of its internet connectivity.

---
## Week of 09/26/2024

This is my concept map of my Work & Productivity Ecosystems

<img width="1000" alt="Screenshot 2024-09-26 at 10 42 41 AM" src="https://github.com/user-attachments/assets/15c728ae-58f2-48bb-8418-14215fcc4880">

I enjoy working. The experience of immersing myself in something and creating something from nothing is always enjoyable for me. However, I can’t dedicate all of my time to work since life involves many different aspects, including relationships. In order to perform well at work, considering productivity is essential. To live more productively, I’ve organized the concepts and tools I use into six key categories:

1. Physical Workspace

Creating a productive environment is crucial for focusing on tasks. I often use my AirPods to block out surrounding noise, which helps me concentrate no matter where I am. Additionally, when my focus starts to wane, drinking water helps me refresh and regain my concentration. At night, I use a desk light that illuminates only a small area, allowing me to focus solely on that spot. These elements help me create a physical environment that’s suited for productive work.

2. Digital Tools

I’m a big fan of Notion. I use it for recording schedules, journaling, and even taking notes. A few years ago, I used to write things by hand, but now Notion has become an indispensable tool. I also use AI tools like ChatGPT every day. It feels like having an extra assistant, helping me handle tasks more efficiently within limited time and resources, greatly boosting my productivity. Tools like Slack and Discord are also incredibly effective for team collaboration. They not only allow us to communicate but also to store and manage various resources.

3. Time Management

Time management is critical. To manage my time effectively, I use a physical timer called Time Timer Mod. I also prioritize my tasks and organize them in Notion, as mentioned earlier, while using Google Calendar to manage both my MDes schedule and personal events.

4. Professional Development

Professional growth doesn’t come just from doing the work. You need to constantly learn and develop yourself. I often use platforms like Coursera and YouTube to study more advanced or simplified versions of topics I’m learning. Additionally, I receive feedback and guidance through mentoring, which helps me evaluate my gaps and find the necessary resources. Participating in hackathons also gives me the opportunity to meet diverse people and gain inspiration.

5. Collaboration

In teamwork, the most important thing is minimizing communication loss. The less of that, the more efficient the work becomes. Figma plays a key role in bridging that gap, allowing us to work on the same thing while seeing and communicating the same ideas. When time and space constraints make team collaboration difficult, we use Zoom or Google Meet for remote meetings. Files are also shared in real-time through Google Drive, making them accessible from anywhere. This has been incredibly helpful for me.

6. Health & Wellness

Taking care of my health is just as important. I try to follow a routine and lead a more structured life every day. Although I don’t particularly enjoy vegetables, I make sure to eat at least one meal a day that includes them to maintain a balanced diet. I also drink water frequently, aiming for over 2 liters a day, which helps me feel more refreshed and energized.

This is my Work & Productivity Ecosystem. I hope to learn many interesting things from this class that will positively impact my work life!

---
## Week of 09/19/2024

This week, I had an assignment to create a video alongside 3D printing. While brainstorming ideas, I found myself unconsciously sketching something on my rattling tablet. I often thought it was something I really needed while drawing, and this project made me realize it was time to create it.

<img width="500" height="500" alt="Screenshot 2024-09-12 at 10 13 01 AM" src="https://github.com/user-attachments/assets/b9befb78-adae-4de1-8056-9ae02ebc2c51">

Studying Rhino was quite challenging. I learned by clicking on each node, understanding its meaning, and making adjustments as I went along.

<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 09 44 PM" src="https://github.com/user-attachments/assets/3082b9c2-3ddb-4116-9db9-981ae62fdd3d">

As I was following each node, wondering, "What makes this better compared to typical 3D modeling tools?", I realized something. I was logically thinking through how the design was constructed, step by step. While I’m not sure if this was the original intention or the main advantage of the tool, for me, it was a method that allowed me to easily understand the design process.

<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 11 29 PM" src="https://github.com/user-attachments/assets/061e01dc-60c0-4619-809c-bad7fcf3c636">

I, too, started creating and connecting nodes one by one in a similar logical manner. As a result, the brep union that had previously failed was successfully completed.

<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 12 42 PM" src="https://github.com/user-attachments/assets/9c824b11-3a14-40f0-885e-c7548dfe132c">

I also learned how to fillet and modify edges using Rhino. Ultimately, I was able to create the following model.

<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 14 16 PM" src="https://github.com/user-attachments/assets/06bfe607-6afc-48db-8e43-7f0e438258f5">

3D printing was another challenge. I had to learn how to use a slicer for the 3D printer, set it up properly, and understand the roles of features like brim and infill.

<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 16 00 PM" src="https://github.com/user-attachments/assets/5133f1a9-19d0-4fc5-a9df-e40ffb733601">

At one point, I failed due to incorrect settings, but with some help, I was able to successfully print it as shown here.

<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 16 18 PM" src="https://github.com/user-attachments/assets/e5d68e4c-519b-41b5-8a64-a69d6ecf24df">
<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 21 07 PM" src="https://github.com/user-attachments/assets/99b0317c-bc76-4bf6-be4b-f2d1be482d5d">
<img width="500" height="500" alt="Screenshot 2024-09-19 at 2 21 15 PM" src="https://github.com/user-attachments/assets/53368f65-1b5a-4bcb-a8fc-8453e9217fed">

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
