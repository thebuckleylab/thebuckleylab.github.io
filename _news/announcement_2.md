---
layout: post
title: Francesco Innocenti presents best paper for ICML Workshop on Localized Learning (LLW)
date: 2023-07-29 16:11:00-0400
inline: false
related_posts: false
---

Francesco Innocenti's submission for the <a href="https://sites.google.com/view/localized-learning-workshop">ICML 2023 Workshop on Localized Learning (LLW)</a> won 'best contributed paper'. He presented the paper <a href="https://arxiv.org/abs/2305.18188">'Understanding Predictive Coding as a Second-Order Trust-Region Method'</a>, written with Ryan Singh and Christopher Buckley, at the workshop in Hawai this week.

***

<div class="row mt-6">
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.html path="assets/img/pc_trust_region_toy.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A simple, elegant caption looks good between image rows, after each row, or doesn't have to be there at all.
</div>

The paper examines Predictive coding (PC) as a brain-inspired algorithm that has recently been suggested to provide advantages over backpropagation (BP) in biologically relevant scenarios. While theoretical work has mainly focused on showing how PC can approximate BP in various limits, the putative benefits of "natural" PC are less understood. The paper develop a theory of PC as an adaptive trust-region (TR) algorithm that uses second-order information. This work shows that the learning dynamics of PC can be interpreted as interpolating between BP's loss gradient direction and a TR direction found by the PC inference dynamics. 

>  Our theory suggests that PC should escape saddle points faster than BP, a prediction which we prove in a shallow linear model and support with experiments on deeper networks.y. We grow sometimes in one dimension, and not in another, unevenly. We grow partially. We are relative. We are mature in one realm, childish in another.
> —Francesco innocenti

This work lays a foundation for understanding PC in deep and wide networks.

The <a href="https://sites.google.com/view/localized-learning-workshop">ICML Localized Learning Workshop</a> aims to overcome the limitations of global end-to-end learning, delving into the fundamentals of localized learning, which is broadly defined as any training method that updates model parts through non-global objectives.

For more information, see this <a href="https://francescoinnocenti.github.io/posts/2023/08/10/PC-as-a-2nd-Order-Method/">blog post</a>. 