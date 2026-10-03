# Problem 00: AI Harm (10 points / 40 points)

Edit this file to solve problem 00. Problem 00 will not be auto-graded.

This question is most aligned to our first class, where we discussed motivations for this course along with the benefits and risks that modern AI methods are bringing to society.

## Problem 00 - Part A

Modern AI techniques stand to bring great benefits to society, but these benefits come with risks of causing harm to individuals, organizations, and societies. This is particularly true for deep learning algorithms, which are composed of several layers of linear and nonlinear processing. This makes deep learning algorithms exceptionally capable for detecting subtle patterns in data and making inferences therefrom, often achieving human-like or even super-human performance. However, the deep layers of linear and nonlinear processing which comprise deep learned algorithms also make it hard for those deploying them to ensure they behave as expected. Deep learning algorithms might learn the right results for the wrong reason, might appear to perform well initially and then degrade in performance when the input data drifts, and might have unintended biases towards producing particular results.

List five examples in recent years (2010 onward) where AI capabilities have causes harm to people, organizations, or society:

Example 1: In 2018, Amazon discontinued an AI recruiting tool after it was found to disadvantage women. The system had learned from historical hiring data that favored men, causing it to penalize resumes containing indicators associated with women. Very weird but not suprising honestly considering that most of these fintech companies and computer science in general is disproportially male dominated and focused. Trainning on dataset that perpetuates these practices is definetly ... interesting even if hindsight is 20/20
* Example 2: In 2016, Microsoft’s AI chatbot Tay began producing offensive and inappropriate statements after interacting with users on Twitter. Microsoft removed the chatbot shortly after its launch, demonstrating how AI systems can behave unexpectedly when exposed to harmful input.
* Example 3: In 2016, an investigation found racial disparities in the COMPAS criminal justice risk-assessment algorithm. The system was more likely to incorrectly classify Black defendants who did not reoffend as being at high risk of recidivism.
* Example 4: Facial-recognition systems have contributed to wrongful arrests. In 2020, Detroit resident Robert Williams was wrongfully arrested after police relied on a facial-recognition match that incorrectly identified him as a theft suspect.
* Example 5: In healthcare, researchers found that a widely used algorithm underestimated the healthcare needs of Black patients because it used healthcare spending as a proxy for medical need. This resulted in Black patients being assigned lower risk scores than similarly sick white patients. This is already been an issue before the introduction of AI systems , so this perputating that sterrotype is extremly alarming. One of things I am interested in AI is combating and dismantiling racial bias in algorithms. 

## Problem 00 - Part B

For one of the examples you chose, describe a best practice we have discussed so far that could have helped to prevent the negative outcomes. You do not need to know how to implement the best practice you reference in code here or guarantee that the best practice you would recommend would fix the problem completely.

Answer : For the COMPAS algorithm, having more diverse training data could have helped prevent the racial bias. The developers should have made sure the data represented different racial groups and then tested the model to see if it was making different predictions for different groups. This could have helped identify the problem before the algorithm was used.


## Problem 00 - Part C

While the risks associated with AI are exacerbated by the prevalence of powerful deep architectures which started to gain popularity in the 2010s for image processing and in the 2020s for natural language processing, the risks of AI are not specific to deep neural networks. There are many other capabilities that would be considered AI by the Russell and Norvig definition that are not neural networks, and have been in use long before neural networks became popular.

List a time where an AI capability caused harm to an individual, organization, or society **before the year 2000**.

Answer : In 1983, the U.S. military’s Patriot air defense system incorrectly identified an incoming missile during the Gulf War and failed to intercept it. The system had a software timing problem that caused it to make an incorrect decision, contributing to the deaths of 28 U.S. soldiers.

Why does it make sense to describe this example as being caused by AI? Reference the Russell and Norvig definition of AI (*"AI agents are those which receive percepts from the environment and take actions"*).

 It makes sense to describe this as AI because the Patriot system received information from its environment through radar and then used that information to make a decision about what action to take. In this case, the system incorrectly processed the information and failed to intercept the missile, which caused harm. The Patriot system can be considered AI because it received information about objects in the environment through radar and used that information to decide what action to take. This matches the Russell and Norvig definition of AI: “AI agents are those which receive percepts from the environment and take actions.” The system analyzed the information it received and made an automated decision, which is what makes it an AI agent.