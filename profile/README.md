# Hi there 👋
![image](https://user-images.githubusercontent.com/23004551/193457353-4ef695d9-9642-4f6a-a5bf-bc094a45f590.png)

We are team Capybara and we are passionate about teaching people just like us. As life long learners, we know how it important it is for people of all ages to be enganged science, history, technology and more. In addition, we are all passionate about the rise of the Metaverse and impact on the entertainment space as a whole. We tried to combine these two goals, with a passion for performant systems and natural langauge processing, to help students become more engaged with learning.

# Our Repo's
----------
* [React/Three.js Frontend](https://github.com/HackMIT-2022-Giraffe/giraffe-frontend/tree/main/education-station)
* [Node.JS Backend](https://github.com/HackMIT-2022-Giraffe/giraffe-backend)
* [Python Algorithms and Analytics Engine](https://github.com/HackMIT-2022-Giraffe/giraffe-algo)

# Brief What is

Giraffe is a virtual reality environment to make your textbook readings more engaging. Giraffe begins with parsing the textbook for figures and facts. This content is then sent to GPT-3 which summarizes the content for the level of the user. Next in the pipeline is slide generation where the content is simplified using GPT-3. Figures scraped and bullet points are generated from the summarized materials to create slides along with the lecture itself. Lastly, the simplified speech of the textbook is passed to the facial model which takes in the speech and animates a 3d model into speaking. This speaking head is the lecturer and will help make it interactive for people studying. All of these elements are then brought together into a virtual reality lecture hall where they can feel like the lecturer is teaching them the book in the most engaging way possible.

# What is Giraffe?

Giraffe is a virtual reality environment to make your textbook readings more engaging. Often, our professors are not able to cover all the important points they test for on exams. Because of this, it’s our duty as students to complete textbook readings and know the content like the back of our hand. If you’re like us, you get lost in the mountain of words and find the immersive lecture format to be far more engaging.

Giraffe begins with parsing the textbook for figures and facts. This content is then sent to GPT-3 which summarizes the content for the level of the user. This means that our application can be used by middle schoolers and undergraduates regardless of the inputted textbook.

Next in the pipeline is slide generation. The simplified content is then passed to GPT-3 to generate summaries of the simplified content. This is then rendered onto the slides that are shown in the virtual reality environment along with the appropriate figures.

Lastly, the simplified speech of the textbook is passed to the facial model which takes in the speech and animates a 3d model into speaking. This speaking head is the lecturer and will help make it interactive for people studying.

All of these elements are then brought together into a virtual reality lecture hall where they can feel like the lecturer is teaching them the book in the most engaging way possible.

# What is unique about Giraffe?

The only alternatives to our product are online videos and textbook summaries. 

Online videos struggle from not having to be manually created by content creators for different subjects. This content is not automated and is highly dependent on people creating videos and what they want to create content about. Our product provides an automated mechanism for creating highly interactive content.

On the other hand, textbook summaries to fully capture the same content in an interactive way, falling for the same problem is verbose textbooks, just slightly shorter.

Our video combines the full capacity of the textbook in a digestible format that fits the user. No other product can provide this level of customization in a digestible way for users.

# Challenges we ran into

We found it really difficult to see the first party support we were hoping for cross platform VR solutions. Because of this, we had to explore many different frameworks and libraries and ultimately found Three. Although it was a challenge to identify a framework, Three has been an invaluable asset in creating a virtual reality to host our lectures. Another immense challenge was the animated lecturer piece of our pipeline, having someone teach you the material is more much beneficial than a disembodied monotoned figure. But, having a speech to facial renderer compile seemed almost impossible because almost every model we would implement would have too many conflicts. However, after hours of debugging, we ended up finding a model that worked, making the animated lecturer a (virtual) reality. And another huge challenge was idea generation, coming up with this huge pipeline, its minor components, and overarching goals was difficult. We needed to think of something to make our hackathon worth hacking for. Luckily, we did, we genuinely found something we enjoyed building, and came to an idea that will help a lot of people.

# Accomplishments we are proud of

Usability is a huge component of our project that we’re really proud of. We know for an application as robust as this, having a good and easy experience for the user is essential, and we believe that our beautiful design allows each user to be able to have that. And, we’re also extremely proud of our architecture, the pipeline needed to make every single component happen is intense, behind the scenes there is an advanced level of Natural Language Processing and Deep Learning occurring, as well as a huge load on the backend. But more than anything, we’re really proud of the idea that we came up with and ended up pursuing. Coming into this project, we wanted to not only make something cool and use innovative technologies, but make something meaningful that we believe could actually help others, and we hope we achieved that goal. Making a seamless architecture integrating with many different features and allowing users to have an easy experience is amazing, but above anything else, we pride ourselves for the reason we decided to pursue this project.

# Screenshots
![Screen Shot 2022-10-02 at 9.15.43 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fce2a39b-4930-4d66-87c6-472e96f998ce/Screen_Shot_2022-10-02_at_9.15.43_AM.png)
Above is the hompage of the website where users can understand the product and begin summarizing their first textbook.

![Screen Shot 2022-10-02 at 9.15.58 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c49b4b97-da35-47f2-9f93-5f1c3db0c9b7/Screen_Shot_2022-10-02_at_9.15.58_AM.png)
Above is the confirmation page where users can ensure they want to continue with the VR textbook generation process. In the next step, we upload the PDF of the textbook to our backend cloud which parses it for images and paragraph based content to be fed into the machine learning model.

![Screen Shot 2022-10-02 at 9.16.04 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8413e460-ccc2-4619-89f0-30b0f2b585eb/Screen_Shot_2022-10-02_at_9.16.04_AM.png)
In this screenshot, you can see the loading indiciator for the three major steps of the pipeline: textbook loading, slide generation, and lecture animation. These tasks are very computationaly intensive, even with concurrency and parallelism in mind.

# Sponsor Challenges
Throughout this competition, we challenged ourselves to incorprate as many sponsor challenges as possible in order to really push our selves to learn more. The following are discussion of how we met the challenges and what we learned throughout the process.

## Meta
Even before coming hearing Meta was a sponsor, our team wanted to work on an AR/VR project so we can develop our skills in Metaverse technologies. We see the next generation of entertainment coming from the Metaverse. We recognized VR's ability to grab your full attention as a tool for studying, where we can make the mundane task of reading through a textbook as engaging as a college lecture. On the technical side, we made use Three.js, a library for creating VR applications in the browser. Accessibility was a huge point for our choice of technology stack and serving our application through the web ensures that the only thing required for users to be able to learn is an internet connection.

## Arrowstreet Capital
The Arrowstreet Natural Language Processing challenge excited us as its a type of technology our team has not worked with much before. We saw the use of natural language models as an ideal tool in our goal to educate students better. We incorporated NLP into Giraffe with our contextual summarization model which can adapt to the user and summarize for the user based on their level. Most textbooks are verbose and confusing to understand, but Giraffe's NLP algorithm leveraging GTP-3 can be changed so the student is comfortable with the level of detail the model is presenting to them with.

## Five Rings
Our project is highly dependant on data pipelines and asyncronous modules who simply parse through a pdf to running advanced machine learning models mimicking facial movement and speech. With such a computationally intesive tasks, we needed to build our infrastructure in a scalable way where users aren't waiting too long for their VR environments to be ready for lecture. One of our key insights was recognizing that the key bottleneck in our system would be generating slides and animating the human model which both depend on the simplifying summarization of the textbook. Based on this insight, we were able to organize our pipeline so we initially scrape the PDF and simplify the data and then send the information to two servers who work on slide generation and animation respectively. The client then waits for both modules to complete and then moves into the VR environment were it leverages that computation to create an immersive environment. This key insight outlining how we could create a system with concurrency in mind has led to our significantly reduced computation time. 

## Y-Combinator
As technologists who look for impact in the products we built, we entered the Y Combinator challenge to learn more about how the top startup accelerator in the world thinks about business and technology. Throughout the process, we used the questions in the Team Entry Google Form to guide our decision making regarding user interface, experience, and impact. Altogether, the Y-Combinator challenge allowed us not only to make a project, but one that has impact and merits an actual product.
