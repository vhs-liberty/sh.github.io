---
title: "To What Extent do CTS*2010 Students Think Microwave Ovens are Harmful?"
section: "CTS 2010"
layout: page
---
## The first part to a data project that is a reflection on survey creation and plans for next-steps.

By Amir Benkelai

Taking a bird’s eye view of my technology; I chose to work on the research question “To what extent do CTS*2010 students think microwave ovens are harmful?” because I can loosely bring it back full circle to the magnetron. That is, the magnetron is the very technology that produces the microwaves, whilst the remaining technologies exist for operational and guiding purposes [(briefly speaking)](https://www.homenish.com/parts-of-a-microwave/). So, by asking about microwave oven habits and familiarity, I can answer this question from the perspective of misunderstanding the function of a magnetron. This is also because I can frame my data visualization around how magnetrons generate microwaves and that those microwaves are the core function of the oven (Zante). Before diving into the analysis, please note that this post will use oven and microwave oven interchangeably and may use “radarange” to refer to microwave oven. Hence, to begin, out of the core questions, the following three will be most important to explore:
<br>
<li> What do you use a microwave oven for? (Select all that apply) </li>
<li> Do you think microwave ovens operate by radiation? </li>
<li> Are you knowledgeable of microwave oven maintenance? (Keeping the container clean, replacing parts, etc.) </li>
<br>
The first question is to help gather data on radarange habits because how it is used can give an idea of if someone trusts the technology or not. For example, someone who always heats their food on the stove when they have a radarange likely may do so either because it does not do a good enough job or they do not trust it to be safe (Zante). To determine if it is a safety concern is where the next question comes in, where it is assumed that people will respond based on whether they subscribe to the idea that [“radiation = danger”](https://www.codastory.com/disinformation/radiation-fears-dangerous/). As this may not be the case all the time, there are follow-up questions for those who do answer “yes”:
<figure>
    <img src="/images/q_1.png" alt="Screenshot of a questionnaire condition reading 'If Do you think microwave ovens operate by radiation? Yes Is Selected' after which the conditioned question reads 'Do you feel safe around a microwave oven?' with two answers, yes, or no.">
    <img src="/images/q_2.png" alt="Screenshot of a questionnaire condition reading 'If Do you feel safe around a microwave oven? No Is Selected' after which the conditioned question reads 'How often do you use the microwave oven?' with a slider from 1 to 5.">  
    <figcaption>Figure 1: Follow-up questions if "Do you think microwave ovens operate by radiation?" is answered with "yes".</figcaption>
</figure>

If they answer here with “yes” again, then they are unlikely to agree that “radiation = danger”, and if no, then they may be more likely to do so, which can be determined with the scale. Of course, it is not possible in any manner to properly determine this, and thus this is an assumption that will be considered during analysis. As well, those who answer “yes” in both cases do potentially view radaranges as harmful, which may be somewhat compared to their answer on the previous question. So, for example, 3 people responded that they do not feel safe around a microwave oven, out of 14 who answered yes to the radiation question. One person’s response has a 0 on the scale and thus may be interpreted as that they use the microwave oven once in a blue moon for heating purposes. This, then, likely means they do not have a radarange at home and may utilize the device when out of home. As a result, they may not have one at home because they do not trust it, prefer traditional stove, and/or cannot afford it.

As for why these three were chosen out of the whole for this analysis, that is because they are a backbone framework. That is, their results can be both analyzed and interpreted to gain an idea of if someone thinks a microwave oven is safe. The remainder of questions is to support either claim, like pillars of the framework. Using this model, the survey has received a total of 19 responses, though some of these may be botted and need removing. Out of the 19, 14 said they use it for heating food, 3 for cooking, and 1 for scientific experimentation (surprising). Out of these, majority think these ovens operate by radiation, with only one person likely not feeling safe near a radarange (as explored up above). And last, majority is not knowledgeable of microwave oven maintenance, which all together just answers the question as: the class of CTS*2010 students does not think microwave ovens are harmful by a considerable extent. As for how, that is where those supporting questions come in.

To understand this, the following can help:

<figure>
    <img src="/images/q_3.png" alt="A question from a questionnaire reading 'Please select which of the following, if any, sound familiar to you,' with a list of options, and a percentage of how many respondents were familiar with each option. Circuit Controls, 29%, Door Seal, 36%, Magnetron 29%, Transformer 43%, Wave Guide 7%, and Microwaves, 86%. ">
    <figcaption>Figure 2: Technical Familiarity - A supporting question to help with the claim made.</figcaption>
</figure>

Seems like a lot of the class is knowledgeable on some technical terminology, which was definitely a surprise for me. Specifically, there seems to be 12 people who are familiar with microwaves, which were defined at the beginning of the survey:

<figure>
    <img src="/images/q_3.png" alt="Screenshot of text reading 'This is a survey on microwave oven use. Here, microwave ovens as appliances will be referred to as microwave ovens, whilst microwaves as light waves will be referred to as such.'">
    <figcaption>Figure 3: Definition of "microwave oven" and "microwaves" at start of survey.</figcaption>
</figure>

Clearly, these 12 respondents may know about light waves and thus know part of the radarange's functions. As has been illustrated, the methodology of analysis will be interpretative and focus on this backbone/pillar model I have hereby constructed. However, what about cleaning? Clearly, some things may need to be ommitted, and Qualtrics happens to offer CSV files. I will utilize the Pandas python library to create a cleaner data set from where a written interpretation will be generated by hand and then used for the visualization.

As for *how* to visualize this and build a story, well, first point of order is to of course choose an arbitrary magnetron and give it a name: Maggy. Maggy, over here, is sad and feels misunderstood. I wanted to help show them that, no, they are in fact understood. To do so, this survey was created. Okay, slightly cheeky character building aside, the idea is to have a character called Maggy who uncovers that they are in fact not misunderstood by the class of CTS*2010. For the sake of storytelling, let us say they happen to be a student in that class. The next question, then, is where does the data come in? And what medium: short story, poem, video game, film?

For medium, it is between short story or video game. Ideally, if I find time, I might try to use the PyGame python library designed to help create simple 2D games (I have played with it before but never got around to finishing my project). The function for this is plain: information has to be collected and compiled by the player in order to win. Once compiled properly, the player wins, and gains the information. The other idea, short story, is going to be a narrative from Maggy themselves centred around a kind of “self-discovery” journey.

**Works Cited**

Zante, Helen J. Van. *The Microwave Oven*. Houghton Mifflin Company, 1973.