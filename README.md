# MSc-Creative-Making-Advanced-Final-Project

MSc Creative Making: Advanced Final Project in UAL CCI .

<br> 

Student:Zhiying Hong

Student ID:21020261

<br> 

Supervisor: Yadira Sanchez Benitez

MSc Computing and Creative Industry（Modular）

University of the Arts London: Creative Computing Institute

<br>

video link：

Note: use "test photo"(Table_Web AR demo/test photo.JPG) for webAR demo test.

<br> <br> 

# Table — Virtual Imprints: Individual Expression and Social Connection in Augmented Reality

* the weekly document of my iterative development and my project progress.

<br> 

## Summer term:

<br>

- project proposal：

As an international student, living in the UK has often given me the unrealistic feeling that I just like living in another game world and the people around me were like NPCs. After thinking I realised that this feeling might not only due to language and cultural differences. As a newcomer to this city, I have yet to establish deeply relationships and connections with environment here.Therefore, I have an idea for a platform that I would like to design for the general public (not only limited to professionals) to design their own AR works. Users could place their AR work in a specific location and others could come to that location and view and interact with the work. The location of each work will be fixed (the details and regulations are yet to be worked out).I hope through this platform, people will be able to more fully express the world on their eyes and this platform can give a new connections to users (with people or with the environment). 

<br> 

- project timeline and Milestones:

<img width="1563" alt="截屏2023-11-24 09 08 27" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/ff75a447-fe47-4797-b1e2-46cae2809d4c">

I had the first meeting with my supervisor on July 7th, during which we clarified the research direction of the entire project and completed the work plan and timeline. The initial plan was to complete the platform design in five weeks, and another five weeks to create augmented reality digital works as user cases for the platform. I also provided a moodboard for the general direction of the AR cases.

<br>

- Supervisor feedback:

  
<img width="387" alt="截屏2023-11-24 09 14 21" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/063f0ccb-21b6-4f6d-bb86-b588ba900a49">

<img width="381" alt="截屏2023-11-24 09 14 12" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/97e723e2-6a23-403b-bac7-9b7d9915724f">


In addition, my supervisor and I discussed the community and game aspects of the entire platform. We explored how to make the platform interesting enough and how to attract new users to join. I have started thinking about these two questions.

<br>


## Summer Independent Study Period

After conducting research and brainstorming on the general direction, I initially thought it would be better to build a website to comprehensively showcase the platform. However, since I have no experience in website building and lack a foundation in frontend knowledge, I started organizing my own portfolio website during the summer independent study period. I learned frontend knowledge while working on the website (my personal website:https://hhzying.cargo.site/ ). I also moved the creation of the AR cases ahead of the platform architecture. I spent about five to six weeks learning frontend knowledge and then about two weeks creating AR cases.

However, after learning frontend knowledge, I realized that it was almost impossible for me to design and develop a platform website alone. Even if I could, it would take too much time to learn the basics, which would deviate from my initial project concept and plan. Therefore, I decided to use Figma to create a high-fidelity prototype of the app instead, as I felt it could better present my ideas. Additionally, the user base on the app side is wider.

At the same time, I conducted research on the psychological phenomenon of "derealization" or "depersonalization" which I mentioned as the inspiration for my project. I found that it is a manifestation of a psychological disorder.

* AR Example 1 - Spiral Line/Spiral Tower
It was inspired by the Third International Tower.

<img width="1500" alt="截屏2023-11-24 19 10 07" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/b9922527-2241-46dd-b499-0e74dff824a8">

![截屏2023-11-24 19 18 03](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/19afc173-69a7-4c5e-808a-19a304ee48ad)


<br>


<br>


## Fall Term


### Week 1

During this week, I researched the principles, technologies, and existing market applications of AR. I discovered ar.js (an open-source code) which can be used to build simple web AR, with its main directions being image tracking, location-based, and marker-based. I also realized through platforms like Unity and Kivicube that the success of this platform relies on targeting a wider audience. For a user who has no experience in creating AR works or professional knowledge in 3D modeling, this platform would involve a high learning cost.

![截屏2023-11-24 19 20 53](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/940e4a22-3506-427b-813e-a94a06421227)


In the subsequent research process, I added research on the principles of 3D modeling technology.



### Week 2

During this week, I researched the principles of 3D modeling and conducted user research through questionnaires and interviews. I divided the target users into those with AR creation experience and those without, and those with and without basic 3D modeling knowledge. I also conducted a feature analysis of common social platforms on the market.

### Week 3

Through brainstorming, I clarified the platform's functions and general workflow, and considered how to simplify the process and create a functional architecture (flowchart). I also created a low-fidelity prototype.

![IMG_3202](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/9e2d53d9-6876-41b4-8c41-84ebc80ca09b)

![IMG_3110](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/ceed510c-5736-466e-8697-5cfcef0a27e1)


<img width="807" alt="截屏2023-11-24 19 35 26" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/cc5f19f0-e5a0-4dc5-935b-a9c4b1f45e22">

<img width="399" alt="截屏2023-11-24 19 35 47" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/c77c3591-35f0-4a39-b29d-e6d0ef493335">

### Week 4

After completing the initial prototype, I contacted three users who expressed interest during the questionnaire and interview process. I explained the project to them and observed their responses to gauge their interest in the functions. Through these conversations, I found that for ordinary users, the relatively high learning cost of creating AR works discouraged them from trying, even if they found it interesting. On the other hand, users with AR creation experience and basic 3D modeling knowledge would not choose to create models on a platform that is not very specialized. For the target users without a foundation, they are also averse to opening a very complex operating interface.

Based on this observation and conclusion, I added the functions of "using existing models" and "creator community". Through the "creator community" function, users can choose to download materials published by the system or templates uploaded and shared by other users, such as 3D models, materials, and environment spheres, etc. I felt that this would create a better user ecosystem as compared to a system-designated material library, as it better suits the users' actual needs.

Furthermore, I found that focusing solely on location-based AR functionality is too limited. Therefore, I conducted research on image-tracking-based AR technology and used AR.js to build a local web AR portal for showcasing the created AR cases.

- Web AR demo testing:

![IMG_3114](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/1c9b3d8f-d3ba-44ff-b049-f4684e400e7c)

![IMG_3132](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/12e505d7-8469-4954-8675-8e8ac6e41261)

  

### Week 5

- AR example - "Spore Infestation"

- ![截屏2023-11-24 19 50](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/fe553a74-0258-4c3b-9870-316d4a1d8f3c)



- Creating AR example - "Butterfly Bones"
- 
![截屏2023-11-24 19 49 36](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/b5593d0a-f81b-4df7-911d-8d2b1d812808)

- 


### Week 6

- Platform logo and UI style determined
  
![IMG_3203](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/3633371e-4fd0-4fbc-93f8-ca4d4fc36648)

<img width="356" alt="截屏2023-11-24 19 38 06" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/f3f6a724-1b2d-424c-9aa0-63ad1822c255">

The origin of the name "Table" actually came from a conversation I had with friends. I was introducing this project to them, and one of them asked me what this model could bring, whether it was just for fun.

In order to explain it more simply, I gave them an analogy. I said, "When we talk about a table, what do you think is on your table?"

He said he would think of a table full of delicious food (we were eating at that time).

I said, "My first reaction might be to think of a very organized workstation, some stationery, my notebook, a high-end desktop computer, and a large external display. There should also be a very comfortable ergonomic chair next to it, and preferably a shelf with books and decorations."

At this point, another friend who was eating with us said, "On my table, there would be a book and a vase, but no flowers. The table is by the window. I can look up and see the tree outside."

I said, "Then I think my table must be by the window, preferably with a sea view."

"Yeah, so the meaning of my project is to make people 'materialize' their thoughts in a more three-dimensional way, just like drawing."

To make thoughts exist in the real world in a more concrete and tangible way.

At the same time, allow people to use the table to display their thoughts and creativity, becoming a platform for communication and sharing.

- Create AR example - Information Cocoon

![截屏2023-11-24 19 49](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/e09e8872-a026-4590-ab60-25a1b5139ba0)




### Week 7

- User interface design
- Prototype creation
- Motion design


<img width="1124" alt="截屏2023-11-24 19 36 20" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/91eea295-3094-4cf9-9c13-4d73aee09f20">
![截屏2023-11-24 19 36](https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/b74ffb88-1971-44f0-8c5d-237c3b708b5d)
<img width="1079" alt="截屏2023-11-24 19 36 55" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/e618e76d-a621-41f5-94ec-4784f283b6fd">
<img width="1014" alt="截屏2023-11-24 19 45 14" src="https://github.com/hhzying/MSc-Creative-Making-Advanced-Final-Project/assets/119880764/78b4393e-c8cd-49ae-a170-69e016546714">


### Week 8

- Organize all materials
- Organize research process and thesis outline, start writing the thesis (introduction and Research Method section completed)

### Week 9

- Continue writing the thesis
- Conceptualize/shoot/edit videos
- Prepare for the final project presentation and submission




<br>


<br>


<br>


<br>


<br>


<br>


<br>


<br>


<br>


<br>












