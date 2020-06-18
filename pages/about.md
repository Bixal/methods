---
title: About
layout: page
permalink: /about/
---

<div class="usa-alert usa-alert-info">
<div class="usa-alert-body">
<h3 class="usa-alert-heading">18F Content</h3>
<p class="usa-alert-text">
This page currently reflects the original 18F content. It will be updated with Bixal content.
</p>
</div>
</div>

# About

The Bixal Methods are a collection of tools that describe how our teams put human-centered design into practice. They are based on the 18F Methods, but have been adpated to reflect the language and practices we use at Bixal. Our goal is to help our teams and federal clients adopt human-centered design into their projects. These cards are focused on design in the context of digital services, but can be adapted to non-technical design projects as well.

## The basics of human-centered design
Human-centered design, also referred to as "user-centered design," is a methodology that incorporates feedback from the people for whom you are designing throughout the design process. The goal of human-centered design is to end up with a solution that is tailored to meet people's needs, with little wasted effort and reduced risk. To achieve this goal, project teams at Bixal talk with and observe real users to understand their needs, context, and challenges, come up with design concepts that might address these challenges, and then test them with real users. [Learn more about the benefits and techniques of human-centered design from IDEO](http://www.designkit.org/human-centered-design).

## Using the Bixal Methods
The Bixal Methods are broken up into 5 groupings. They roughly map to phases your team is likely to go through during a project, however, instead of thinking about them as a linear process, **we think it's more helpful to think about the methods as ways to answer questions you may have at different points in a project**. So instead of typical design phases you usually see, we've named the groupings according to needs you may have at any point in a project.

While some cards refer to other methods, you may use them independently. You do not need to use all the cards in a section or complete certain tasks before moving on to others. Take whatever cards are most useful to your team and incorporate more tools as you’re ready.

We’ve included additional guidance for using these methods in government research, specifically around the [Paperwork Reduction Act (PRA)](https://pra.digital.gov). We’re only able to include brief guidance on the PRA, and teams should double check with their client representatives for additional guidance. You should also read the cards in the fundamentals section for more background on conducting design research as a government contractors.

## Go behind the scenes
In keeping with the spirit of the original 18F project, this project is also completely open source. You are free to copy, share, or reuse this [as you wish](https://github.com/Bixal/methods/blob/master/LICENSE.md). We also welcome input from the public, whether it’s correcting a typo or suggesting a new method to include. You can see our [guidelines for contributing on GitHub](https://github.com/Bixal/methods/blob/master/CONTRIBUTING.md).

## Release notes

{% for release in site.data.releases %}
### {{ release.name }}
<p class="site-subheading">{{ release.published_at | date: "%B %d, %Y" }}</p>
{{ release.body | markdownify }}
{% endfor %}
