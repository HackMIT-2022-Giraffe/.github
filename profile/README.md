## Hi there 👋
![image](https://user-images.githubusercontent.com/23004551/193457353-4ef695d9-9642-4f6a-a5bf-bc094a45f590.png)

We are team Capybara and we are passionate about teaching people just like us. As life long learners, we know how it important it is for people of all ages to be enganged science, history, technology and more. In addition, we are all passionate about the rise of the Metaverse and impact on the entertainment space as a whole. We tried to combine these two goals, with a passion for performant systems and natural langauge processing, to help students become more engaged with learning.

# What is Giraffe?

Giraffe is a virtual reality environment to make your textbook readings more engaging. Often, our professors are not able to cover all the important points they test for on exams. Because of this, it’s our duty as students to complete textbook readings and know the content like the back of our hand. Although we know it’s important for our grade, if you’re like us, you get lost in the mountain of words and find the lecture format to be far more engaging.

Giraffe begins with parsing the textbook for figures and facts. This content is then sent to GTP-3 which summarizes the content for the level of the user. This means that our application can be used by middle schoolers and undergraduates regardless of the actual textbook given.

Next in the pipeline is slide generation. The simplified content is then passed to GTP-3 to generate summaries of the simplified content. This is then rendered onto the slides that are shown in the virtual reality environment along with the appropriate figures.

Lastly, the simplified speech of the textbook is passed to the facial model which takes in the speech and animates a 3d model into speaking. This speaking head is the lecturer and will help make it interactive for people studying.

# What is unique about Giraffe?

The only alternatives to our product are online videos and textbook summaries. 

Online videos struggle from not having to be manually created by content creators for different subjects. This content is not automated and is highly dependent on people creating videos and what they want to create content about. Our product provides an automated mechanism for creating highly interactive content.

On the other hand, textbook summaries to fully capture the same content in an interactive way, falling for the same problem is verbose textbooks, just slightly shorter.

Our video combines the full capacity of the textbook in a digestible format that fits the user. No other product can provide this level of customization in a digestible way for users.

# Challenges we ran into

We found it really difficult to see the first party support we were hoping for cross platform VR solutions. Because of this, we had to explore many different frameworks and libraries and ultimately found Three. Although it was a challenge to identify a framework, Three has been an invaluable asset in creating a virtual reality to host our lectures.

# Screenshots
![Screen Shot 2022-10-02 at 9.15.43 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fce2a39b-4930-4d66-87c6-472e96f998ce/Screen_Shot_2022-10-02_at_9.15.43_AM.png)
Above is the hompage of the website where users can understand the product and begin summarizing their first textbook.

![Screen Shot 2022-10-02 at 9.15.58 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c49b4b97-da35-47f2-9f93-5f1c3db0c9b7/Screen_Shot_2022-10-02_at_9.15.58_AM.png)
Above is the confirmation page where users can ensure they want to continue with the VR textbook generation process. In the next step, we upload the PDF of the textbook to our backend cloud which parses it for images and paragraph based content to be fed into the machine learning model.

![Screen Shot 2022-10-02 at 9.16.04 AM.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8413e460-ccc2-4619-89f0-30b0f2b585eb/Screen_Shot_2022-10-02_at_9.16.04_AM.png)
In this screenshot, you can see the loading indiciator for the three major steps of the pipeline: textbook loading, slide generation, and lecture animation. These tasks are very computationaly intensive, even with concurrency and parallelism in mind.
