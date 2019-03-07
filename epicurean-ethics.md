---
layout: subpage
title: Epicurean Ethics
image: css/epicurus.png
subpage: true
coursepage: false
---

## “Do not fear god, Do not worry about death; What is good is easy to get, and What is terrible is easy to endure.”
### -  Epicurus, *The Tetrapharmakos*

## Epicurean Positions on Selected Topics

### Diversity
There is a big issue with lack of diversity in the technology sector. This term diversity encompasses many groups of people and goes beyond the stereotypical gender divide. While it is definitely true that there are still a majority of men in the technology sector other minorities are also underrepresented. For example, immigrants and people of different ethnicities and races are minorities in this area. This has become an issue because the lack of diversity in tech has made it a hostile and unwelcoming environment for minority groups. This issue is important to Epicureanism because certain groups of people are being caused pain by the lack of diversity. Not providing these groups with equal opportunity is unfair to them and Epicurean ethics would have a lot to say about this issue. In fact, under this ethical framework, ethicists would argue that it is important to recruit people of all genders, races, and backgrounds in order to reduce the amount of future pain for the minority groups. Epicurus’ main goal in his ethical framework is for people to reach ataraxia, or a state of no anxiety about the future, and by not allowing minority individuals to work in these jobs, they are being set up to fail in this endeavor. Additionally, Epicurus talks about how the only desires we should fulfill are those that are natural and necessary which he argues are things such as food, shelter, and drink. Therefore, under Epicureanism it would be argued that everybody should be given a chance to work at these jobs because if not given this chance they are less likely to be able to fulfill these natural and necessary desires. Finally, by allowing diverse personalities to join a team and a workplace pleasure would be maximized due to the added value in knowledge as well as other sources of pleasure. In conclusion, this is a really important issue in the tech world today and Epicurean ethicists would take a stance like many others and argue that more diversity in the workplace is desired.

### Online Censorship
Online censorship is a problem that determines when a community or ideology hosted in an online group and perpetuated in an echo chamber should be censored, or “deplatformed.”  An echo chamber is an environment, often online, in which users find their own opinions repeated back at them, reinforcing the belief system shared by the users.  In these groups, opinions, especially controversial or toxic ones, manage to circulate and spread and become normalized.  In recent culture, online social media has garnered criticism for providing platforms to develop echo chambers.  With many echo chambers reinforcing controversial, toxic, or hateful speech, a concept known has “deplatforming” has cropped up.  Deplatforming occurs when the host of the community drops the community and stops supporting a group due to their ideas or actions.  Online censorship is important to the Epicurean framework because Epicureanism ethics provides guidance to responsibly pursue personal happiness while not obstructing others’ similar pursuits.  The issue is important because it tries to balance the “pleasure” of free speech, both now and in any implications in future society, while still respecting the viewpoints of others.  Epicureanism would likely approve of deplatforming as long as it followed a just process and was not used as a tool for stifling speech.  Namely, it should only be used as a tool against toxic communities, not all echo chambers.  Epicurus would argue that justice, as an agreement not to harm others, supports laws and punishments to defend others from harm such that they can pursue their own happiness.  Deplatforming is one such punishment for those who advocate hateful or violent behavior against others.  Since the deplatformed group is engaging in behavior inhibiting the happiness of others, it is a just response.  Though it seems to set a precedent against free speech, Epicureans should not abuse deplatforming against communities they simply disliked, as compared to communities they have good reason to deplatform, because it would inhibit the victim’s happiness.  Another consideration of the Epicurean response is the role of eliminating unnecessary desires, because these cause future anxiety, which is decidedly un-Epicurean.  One could argue that consuming media that explicitly promotes outrage in its readers – content designed to fear monger and provoke an extreme call to action by attacking insecurities – should be ignored by Epicureans and should be censored.  There is a difference between learning about opinions that differ from one’s own to obtain a more complete worldview versus consuming quick opinions to incite a population.  Finally, since the Epicurean framework places a large emphasis on the pleasures gained in friendships and relationships, one should be concerned with the consequences of their actions on others.  A group that seeks attention by bashing another group is not concerned with Epicurean relationships, and as such should lose their voice in an Epicurean society.

### Computer Assisted Warfare
Computer-assisted warfare is something that is becoming increasingly prevalent with technological progress.  This can take many forms going all the way to fully autonomous warfare systems with the ability to make life or death decisions without human control. This is important within the Epicurean framework because this technology has the potential to impact many people’s lives. The ethical evaluation from an Epicurean point of view on this technology would depend on the purpose of the implemented technology. If the goal is to minimize casualties while accomplishing the same goal as warfare that is not computer-assisted, Epicurean ethics would be in favor of it. This is because the goal of this framework is to achieve ataraxia which is no anxiety about the future which ending a war that was causing anxiety quickly with minimal casualties would do. Additionally, minimal casualties would allow those people to achieve their necessary and natural desires. However, if the goal is more sinister and the computers are being used for the purpose of maximizing destruction or another similar goal, Epicurean ethics would not be in favor of their use. This goal would keep others from being able to fulfill their natural and necessary desires and would invalidate Epicurious’ emphasis on friendship. In the case of fully autonomous warfare, Epicurean ethics would have more of a problem here. This is because the ambiguity of liability in an autonomous system could cause much future anxiety if something were to go wrong. We could also step back from this issue and look at the ethics of war in general. Epicureans place a value on friendship and allowing others to reach their desires, so unless the war was to secure one groups necessary and natural desires (food, water, shelter), the war itself could be considered unethical under our framework. In this case, any use or non-use of computers would be unethical as the war itself is unethical.

## An Algorithm for Epicurean Thinking

In order to determine the ethicalness of an action through an Epicurean standpoint, we first need to identify the following inputs:

    - Would the action fulfill a desire, eliminate pain, or eliminate an unnecessary desire
    - Who is directly performing the action
    - Who will the action directly affect
    - Who could the action indirectly effect, or who could be affected in the future
    - The net negative or net positive effect of the action on those not making it

After identifying these things, we can follow whether or not the action is ethical with the following algorithm:

1. Is the action fulfilling a desire that would be considered unnecessary?

    - If no, move to step 2
    - If yes, then the action is probably not considered ethical.

2. Does the action affect anyone other than the individual performing the action?

    - If yes, move to step 3
    - If no, then consider the following:
        + If the action is eliminating a pain or an unnecessary desire, then it would be considered ethical.
        + If the action is fulfilling a necessary desire, then it would be considered ethical.

3. If you have reached this step, then the action would have a net positive effect on those performing the action. Consider the net negative or the net positive effect on those both directly and indirectly affected by the action:
    - If the net effect is positive, then the action would be considered ethical
    - If the net effect is negative, then the action would not be considered ethical.


## Posts

{% for post in site.categories.epicurus %}
  [{{ post.title }}]({{ site.baseurl | append: post.url }})<br>
{% endfor %}
