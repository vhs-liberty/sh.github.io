---
title: "The Extent Visualized"
section: "CTS 2010"
layout: page
---
## The second part to the [data project]({% link _digital-humanities/Magnetron-survey.md %}) that is a data vizualization and story.
By Amir Benkelai

## Reflection

Following the blueprinting and analysis from my [previous post]({% link _digital-humanities/Magnetron-survey.md %}), I went ahead and visualized some of the data in a [conceptual style](https://www.britannica.com/art/conceptual-art) to yield the same answer I reached. Due to the low sample size, I was not able to get any sort of “basic” statistical item to work through Flourish and, since that failed, did not see the need to try it on Excel. I thought of maybe [cleaning up my data with python as first suggested]({% link _digital-humanities/Magnetron-survey.md %}) but then I had a lightbulb moment. [I went back to my previous post and realized I could use that framework for my visualization]({% link _digital-humanities/Magnetron-survey.md %}). Then, I gathered the data from those 3 key questions I explored but ran into another issue: how do I make the visualization in Minecraft? After a lot of creative thinking and not much writing down, plus a discussion with my classmates, a data visualization that would likely make a traditional data scientist gag was born.

The core idea was simple: build a big enough microwave oven to house the 3 key questions on each wall. However, during the building process, it turned out the radiation question may not make sense without one of its supporting questions: Do you feel safe around a microwave oven? The reason behind this is that the radiation query cannot properly work without also knowing if someone feels safe or not because in physics terms microwaves are a type of radiation. [See the previous post for details] (({% link _digital-humanities/Magnetron-survey.md %})). From there, it kept growing; microwave oven was done but the layout looked like a gallery exhibit (in a conceptual likeness), so, logically, encase it in a museum building aptly named “The Data Museum”. This itself was designed in a brutalist style because its raw elements and sharpness do well to symbolize the strangeness of visualizing data this way. And then an exhibit explanation followed to help build up the contextual asset of the story. In the end, I was surprised to discover how well the oven and concrete texture turned out, since I usually do not consider myself that great of a builder. I also learnt a few things from this creative endeavour.

One of these is the power in showing numbers, that is, giving a way to see the quantity instead of just the quantity’s digit. For example, 14 sheep for 14 respondents or 3 cooked muttons for 3 respondents. Not incredibly hard to visualize numbers but having that component can still be handy. Reflecting upon it, I realise I made the equivalent of a three dimensional bar chart for much of the data since I did choose Minecraft in place of Excel or Flourish. This made me wonder if there can be a difference in data perception simply by having it designed through a three dimensional form; cuboids in place of rectangles, &c. However, in pursuing this, I do realize that this piece asks from the viewer to do a lot of heavy lifting. The answers must be brought together by starting from left and going right, the one hint given by the contextualizing item at the beginning. The choices were also difficult to narrow down as each block represents the answer or question. For example, sheep are food, heating refers to heating food, thus sheep for heating and cooked sheep (mutton) for cooking (watch the 1st minute of the video if confused). Some abstract ones, for certain, were the safety and maintenance questions. The block chosen for safety’s graphing, the copper slab and oxidized copper slab, is a simple reference to electricity, the driver of the appliance. For maintenance, the closest I could think of is a pickaxe, since it is [the representative Minecraft tool for such tasks](https://minecraft.fandom.com/wiki/Pickaxe), and the redstone block because redstone is the closest thing to actual circuitry. This turns the visualization into a piece that requires not just understanding what research is being conducted but also understanding each Minecraft object chosen to make sense of the artistic reasoning behind it.

The final notable asset here then is the plate at the center of the microwave oven. I had turned the plate into a lounging area because it looked awkward when left empty. The books I placed on the table are meant to be [the few existing sources on microwave oven history]({% link _digital-humanities/Magnetron-map-dev.md %}). Speaking of, in terms of microwave oven data gathering, all I can really find is this one [Arkansas survey conducted back in 1970](https://ajph.aphapublications.org/doi/pdf/10.2105/AJPH.63.3.193). It does cover the aspects of microwave oven safety from a more technical standpoint whilst referencing public perception in its analysis.

<br>

<!--The code below helps stylise the grid for the images-->

<style>
div.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
}
div.gallery-item {
  margin: 5px;
  border: 2px solid #000;
  width: 350px;
}
div.gallery-item img {
  width: 100%;
  height: auto;
}
</style>

<!--The code below draws the images into the grid stylised above. Not the best way to do it, but the simplest I could find that did not give me another headache.-->

<div class="gallery">

<div class="gallery-item">
    <img src="/images/mc_dv/1.png" alt="Minecraft building front reading 'data museum' with banners." width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/2.png" alt="Inside the museum, where there are teal pillars, is a giant black microwave with white blocks for buttons. There is a lectern to the right with a sign reading 'READ ME'." width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/3.png" alt="View of the inside of the microwave. Sheep, zombie heads, signs, and light are visible." width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/4.png" alt="A book reading 'Benkelai has been investigating the significances of the magnetron. As part of this research, he surveyed his class to figure out the extent to which his class thinks of microwave oven as harmful.'" width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/5.png" alt="A book reading 'In doing so, he has found out that his class, by a large extent, do not think so. This result was achieved by comparing the understandings of the magnetron, aided by this visualization piece.'" width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/6.png" alt="A book reading 'Here depicted, then, is the visualization of his data that helped answer his research
    I question. As you go in, start from the left, slowly turning to the right side. Once complete, you can learn mone from curated sources at the lounging area.'" width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/7.png" alt="A book reading 'We hope you enjoy this month's piece. Thanks,The Data Museum.'" width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/8.png" alt="A sign reading 'What do you use the microwave oven for?' with colored sheep showing the answers for 'Heating,' 'Cooking,' and 'Scientific Experiment.'" width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/9.png" alt="A sign reading 'Do you think microwave ovens operate by radiation?' with zombie heads to show the number of yes, above which is a sign reading 'Yes (10),' and near are Minecraft Steve heads showing the number of no, above which is a sign reading 'No (4).'" width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/10.png" alt="A sign reading 'Do you feel safe around microwave ovens?' with copper colored slabs showing the number of yes, above which is a sign reading 'Yes (7),' and near are cyan colored slabs showing the number of no, above which is a sign reading 'No (3).'" width="600" height="400">
</div>

<div class="gallery-item">
    <img src="/images/mc_dv/11.png" alt="A sign reading 'Are you knowledgeable of microwave maintainance?' with red blocks showing the number of yes, above which is a sign reading 'Yes (2),' and near are framed pickaxes showing the number of no, above which is a sign reading 'No (12).'" width="600" height="400">
</div>

</div>

<br>

<!--The code below is to frame the Google Drive video.-->

<iframe
  src="https://drive.google.com/file/d/1Y2M_zIEUIWl4PkGn0dvnrX59fT-9lPLM/preview"
  style="width:100%; max-width:800px; aspect-ratio:16/9; border:0;;"
  allowfullscreen>
</iframe>

## **World Download**

[Download the world by clicking here](https://drive.google.com/file/d/1iGQqdxo9sNYeYdrlSWW6GfApPBGAb362/view?usp=sharing).

[For instructions on world importing/downloading in Minecraft, see here](https://www.wikihow.com/Insert-a-World-Into-Minecraft). *(Scroll to the Q&A section at the bottom for Mac)*