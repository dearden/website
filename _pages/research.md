---
title: "Research"
permalink: /research/
date: 2019-12-30T00:00:00+00:00
sidebar:
  title: "Navigation"
  nav: "research"
---

I am a PhD researcher at Lancaster University, in the third year of my studies.
My primary research interest is the effect of belief on the language of false information.
On this page I will give a brief overview of my research.

A list of my publications to date can be found [here](http://www.research.lancs.ac.uk/portal/en/people/edward-dearden(6a07b9df-a13f-483c-9ad7-bc5eb66cf6d7)/publications.html).

## Quick Overview of the Area

Natural Language Processing (NLP), is a field of Computer Science where computers are used to examine language.
By analysing text with technology such as Machine Learning, we can learn more about the way people use words and apply what we learn to real world problems.
NLP can be used in a range of applications, from autocomplete on your phone, to catching criminals on the dark web.

{% capture fig_img %}
![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/research/fake-news.jpg)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>(Image by <a href="https://pixabay.com/users/memyselfaneye-331664/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=4881488">memyselfaneye</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=4881488">Pixabay</a>)</figcaption>
</figure>

Over the past few years "Fake News" has been highlighted as a key problem of the internet age.
To tackle this issue, researchers around the world are looking for ways to solve this problem.
Many of these potential solutions involve using NLP methods to identify claims to fact check, or to predict based on language whether or not a news article is genuine.

## My Research

In my research, I am interested in the way that the beliefs of the people spreading false information affects the language.
For example, if the author of a "fake" news article believes the lie, is their article more similar to a "real" news article than an article that has been deceptively written.
This is an important problem because many examples of disinformation are shared by people who believe them, even if they are spread by people who don't.
Working to understand the affect of belief on language may contribute to the wider problem of false information.

## April Fools Hoaxes

The first section of my PhD involved looking at the use of language in April Fools' hoax news articles compared to genuine news.
April Fools' articles are a useful source of false information for several reasons.
They don't require fact checking, they are knowingly untrue, and we have a large pool of examples going back years from a diverse range of websites, authors, and genres.

{% capture fig_img %}
![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/research/fool.jpg)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>(Image by <a href="https://pixabay.com/users/tom1068-3109971/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2072475">Tom Woodgate</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2072475">Pixabay</a>)</figcaption>
</figure>

We trained a machine learning classifier on a dataset of real and hoax stories and taught it to distinguish between the two.
The classifier learnt to classify articles using a range of features inspired by previous work in deception detection and fake news detection.
Examples of the kinds of features we used were things like proper nouns, and references to the date.
The classifier achieved an accuracy of 75% which, while not incredibly accurate, suggests differences in language between genuine news articles and hoaxes.
Features relating to structural complexity and level of detail were found to be most important in identifying April Fools' hoaxes.

Next we decided to evaluate our classifier on "Fake News" articles.
A slightly lower, but not dissimilar, accuracy was achieved on a set of fake articles gathered by Buzzfeed.
This suggested that similar features were important for both tasks.
We also trained a classifier on April Fools hoaxes and then used it to predict fake news articles.
The classifier, which had never seen Fake News before, achieved an accuracy of 65%, not an awful lot worse than the main classifier.
This result suggests that the same kinds of feature are useful in both tasks, and also that some of these features manifest the same way in both Fake News and April Fools.

## Language Change in Online Conspiracy Groups

Following on from my work with April Fools' hoaxes, I am interested in the way that language spreads in online conspiracy communities.
Over the past few years, various conspiracy theories have become increasingly prominent online.
These increasingly pervasive falsehoods potentially pose a risk to our society.
For example, in the USA the prominent "Anti-Vax" movement encourages parents not to vaccinate their children, citing disproven scientific evidence that shows Vaccines to cause health problems.

{% capture fig_img %}
![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/research/anti-vax.jpg)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>(Credit: Wellcome Library, London. Wellcome Images.</figcaption>
</figure>

I am interested in how members of these conspiracy communities use language.
Particularly, I want to look at the differences in language between trolls, who say things they don't believe for attention, and genuine members.
This ongoing project fits into my work in the effects of belief on language.

## Parliamentary Language Change

{% capture fig_img %}
![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/research/parliament.jpg)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>(Image by <a href="https://pixabay.com/users/derwiki-562673/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=530055">Adam Derewecki</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=530055">Pixabay</a>)</figcaption>
</figure>

Another area I am interested in looking at the affects of belief on language is in parliamentary debates.
I am currently looking at the changes in language of MPs who changed stance on the issue of brexit over the past few years.
From this work, I am hoping to develop methods for tracking changing beliefs using language.
These techniques can then be applied to conspiracy communities.
I am interested to see if we could track the language change of members as they join conspiracy communities to see if their language is changed.
