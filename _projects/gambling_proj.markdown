---
layout: page
title: Gambling Disorder Model
description: Project on causal modeling for 'Near-Miss Effect' in Gambling Disorder
img: /assets/img/gambling_1.jpg
importance: 1
---

### TL;DR

* A class project while I was at ETH Z&uuml;rich on causal modeling of an effect in gambling disorder
* Near-miss effect happens when you miss the jackpot by a little, and feel tempted to replay the game
* Using MATLAB, we plotted out the neuronal activity and BOLD signal change to visualize effects in each brain area
* [Dr.Stephan](https://www.tnu.ethz.ch/en/team/faculty-and-scientific-staff/stephan#c333) gave us useful insights to reconsider the choice of some brain areas, along with the possibility of noisiness in the area, and to focus more on practicality of implementing the model to real world application

***

As gambling is a category of activities that involves putting in money on an event with an uncertain outcome, with the primary intent of winning money or material goods, one would enjoy the activity responsibly as a recreational acitivity [1]. However, if one became obsessed with it, there can be problems caused by the activity, both incurred on them and potentially their family.

Pathological gamblers has these gambling problems such that they ignored the overall cumulative expected negative outcome of the game, and is enhanced by the biased processing of the chance, which in this case is the `'near-miss loss'` (NMs), feeling of being close to a win in electronic gambling machines such as slot machines [2,3]. As shown in figure 1, the slot machine reel outputs the first two consequential as being the same, and the last one being different, making an individual feel tempted, or reinforced, to play more.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/gambling_2.jpg' | relative_url }}" alt="" title="Near-Miss effect in slot machines"/>
    </div>
</div>
<div class="caption">
    Figure 1: Win and Near-Miss Loss Outcomes in Three-Reel Slot Machine
</div>

With this understanding, we have used dynamic causal modeling 

