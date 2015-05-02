<title>Gamification - literature review<\title>

# Introduction

The literature on Gamification can be divided into three categories: theory, guides, and case studys. “Guides” are sources that range from general recommendations based on theory, to recommendations of specific mechanics.  The former are related to “theory” papers, and the latter to “case studies”. This review divides the literature that way into two groups: the first is sources with theory and theory-based broad recommendations; the second is sources with more practical recommendations, and case studies.

I look first at the theory side of gamification, focusing on the definition of gamification, and discussion of goals and objectives of gamification.  I then review some sources borrowed from other fields on the subject of player/user motivation, which helps bridge the gap from theory to practice.  I then review the practical advice and case studies against the concepts in the theory sources.

# Definition

The first topic in review the theory-classed sources is the definition of “gamification”.  This is necessarily preceded by a brief review of the definition of a digital game.

## What is a digital game?

The process of gamification is nearly always being applied on a digital platform, so for the purposes of this review and guide, only digital games are included in the discussion.  

What distinguishes a digital game from non-game applications is that a digital game creates meaningful play.  Meaningful play comes in part from allowing users to make “choices that influence the outcomes of events” (Ferrara 2012). That interaction between choices and outcomes can be broken down further: the actions a user chooses must have immediate outcomes, for which the player can *discern* the outcome's causation and nature. And the outcomes of actions must *integrate* with the outcomes of other actions in that they all have effects on the larger context of the over-all game. (Salen and Zimmerman 2004)  

Games create meaningful play by having actions with *integrated*, *discernable* outcomes.  Another way to consider those relationships is to say that game actions provide immediate *feedback*, and the combined feedbacks determine the player's *progress* toward a goal.  The terms “feedback” and “progress” show up often in the literature about gamification, presumably because they map directly to the core characteristics of what distinguishes a game from both undirected play and other non-games.

## What is gamification?

Gamification is taking something that isn't a game and making it somehow more game-like.  The reason for doing so is “to motivate desired behaviors” and to increase “engagement” (Deterding 2012).  A commonly cited definition for gamification is:

> “‘Gamification’ is the use of game design elements in non-game contexts.” (Deterding *et al.* 2011)

But that would seem to be more of an way of identifying when gamification has happened, since it really only considers the results, and not the process or the goal.  A similar sort of exclusive focus on the resulting mechanics has led to a commonly quoted gamification criticism:

> “You’ll be able to tell when something’s been gamified because it will have points and badges. And this is the nub of the problem… gamification isn’t gamification at all. What we’re currently terming gamification is in fact the process of taking the thing that is least essential to games and representing it as the core of the experience. Points and badges [are] great tools for communicating progress and acknowledging effort, but neither points nor badges in any way constitute a game. Games just use them… to help people visualise things they might otherwise lose track of. They are the least important bit of a game, the bit that has the least to do with all of the rich cognitive, emotional and social drivers which gamifiers are intending to connect with.” (Robertson, Margaret. 2010)

As Elizabeth Lawley writes, for the process of gamification “to be successful, it must include game design, not just game components. Games are not a replacement for thoughtful experience and interaction design; they are an alternate lens for framing that process” (Deterding 2012).

So, while elements of game design are indicative of an attempt at gamification, successful gamification will foster “cognitive, emotional and social” motivations and create a game-like experience.  Huotari and Hamari have proposed that gamification should be defined in terms of that experience, not the mechanics that are used to create it:

> “Past definitions rely on the notion that gamification is based on the use of game elements. However, there doesn’t seem to exist a clearly defined set of game elements which would be strictly unique to games, neither [do] they automatically create gameful experiences. We can find similar elements from a variety of non-game contexts as well. …We argue that the definition of gamification… cannot be based on a set of methods or mechanics, but instead it has to be understood more broadly as a process in which the gamifier is attempting to increase the likelihood for the gameful experiences to emerge by imbuing the service with affordances for that purpose (be it badges or more implicit cues).” (Huotari and Hamari 2012)

A useful definition of gamification, it would seem, should include not only the resulting elements, but also the process by which those elements were chosen, and the goals for which those elements were chosen.  Such a definition doesn't seem to exist in the literature.

Though there is no a consensus on a complete definition of gamification, there is enough agreement on what gamification is&mdash;or perhaps what it should be&mdash;for there to be coverage in the literature of other issues such as the goals and objectives of gamification projects, which is the first topic in the next section of this review.

# Goals and motivations

The general frameworks given in the literature for how to go through a gamification project largely mirror one of the approaches used in either user experience (UX) design or game design. Which is not surprising, since gamification would seem to be the bridge between the two fields.

>“User experience design and video game design are something like siblings who were raised in separate homes. It’s easy to understand both as forms of human-computer interaction and as centrally concerned with the design of experience. But UX design creates experiences that help people meet their real-world needs, whereas game design is about the experience for the sake of the experience.” (Ferrara 2012)

This section focuses on the issue of defining project objects, and the following section will cover user motivations.  These two seem to be the areas where the process of gamification diverges most from both of its parent fields, UX and game design. 

## Goals

Both Raftopoulos (2014) and Ferrara (2012) explicitly advise to start a gamification project by determining the goals for the system. But what those goals are&mdash;or at least what they should be&mdash;is not an obvious question. To begin with, how can you properly balance the goals of the organization and the goals of the users?

Often, the goals of the organization obscure the goals of the user, such as in the gamification of a university course, when “Our goal with gamification was to improve lecture attendance, content understanding, problem solving skills and general engagement. [These were] measured using course marks, lecturer evaluations, lecture attendance, and a questionnaire” (O’Donovan *et al.* 2013).  While improved marks are evidence that the users of the system, the students, benefitted from it, the inclusion of “lecturer evaluations” as an indicator of success implies that overall the goals were organization-centric.

Or the goals of the organization may simply ignore the goals of the user. “The language used by vendors selling gamification solutions imply that it is something performed on employees by management” in order to improve employee performance (Raftopoulos 2014), as opposed to something that assists, or benefits employees.  More so “gamification too often invokes organization-centered design, treating users as zombies: senseless mechanisms urged onwards by a desire for extrinsic rewards. Gamification still often fails to acknowledge the user’s context and innate psychological needs” (Conway 2014).

While the analogy to mindless zombies might be hyperbole, at least one example of gamification did treat its users as something like non-sentient beings. In order to gather data on the deployment of Near-Field Communication tags, researchers released what was ostensibly a game, but what it could also be argued was an application, with a heavy layer of gamification that obscured its objective and the core process. The researchers themselves described their project as using “gamification”, and reported that “most users are unaware of the game's purpose as a research project”.  In describing the process of deploying their application, they wrote that they “chose a neutral name for our game that did not disclose its nature as a research project, but did rather seem like a game of an independent development studio” (Kranz 2013).  The intentional obfuscation of the true purpose of an application is, if nothing else, putting the goals of the organization well ahead of those of the user.

Conversely, the goals of the user might be made superior to those of the organization. Some have recommended that “…meaningful gamification puts the needs and goals of the users over the needs of the organization”.  And while we are assured that “if users have a positive and meaningful game-based experience that is well-connected to the underlying non-game setting, then the organization will benefit in the long term” (Nicholson 2012), much like with the student's goals in the example above, merely ensuring that the organization benefits is not the same as ensuring that the organizational goals are serviced.

This confusion and conflict between user and organization goals is a consequence of trying to define goals for a gamified application as opposed to a game application.

Designers of games don't necessarily have an easy task in defining project goals, but it is at least a straight-forward one, since “the fundamental role of the game designer is to be the ‘advocate of the player’ and the designer must look at the game world that is being created through the eyes of the player and focus completely on the player experience without being distracted by the other concerns of production”. In contrast, “a gamification designer is often the advocate of management… and the role of the player or worker is fundamentally subordinate in the game that is being developed. The engagement and experience of the player in a gamified enterprise application is typically a means to an end…, rather than the end in itself…” (Raftopoulos 2014).

One way proposed to overcome the confusion and possible conflict between the goals of users and the goals of the organization in of a gamification project is to include users in the process of defining the project goals, and also by framing those objectives within a larger definition of project values&mdash;which users also participate in defining (Raftopoulos 2014).

Another possible difficulty in defining the goals of a gamification project occurs in case where the intended users of the system have a wide variety of goals. A proposed approach to resolving the problem of needing to accomodate a broad spectrum of user goals is to adapt the Universal Design for Learning from education, which is used to create courses that are appropriate for a wide range of students.  The basic approach is to break down the overall process into steps, and then to provide a variety of approaches for each step.  At each step, users can find the approach that works best for them.  In other words, there is no single path of progress through the system, and users can switch between paths along the way.  Developing these multiple pathways can increase design difficulty, but “opening up the design of the gamification to users of the system can help designers overcome that challenge” (Nicholson 2012).

So, again, a good way to ensure an appropriate inclusion of user goals in the project's goals is to include users in the process, or to deploy a system that allows users to customize and expand the system. 

----

## Motivations

The promise of gamification is motivation&mdash;people will *want* to use the gamified application (Deterding 2012).

The gamification literature has sparse coverage of motivation theory, so for this review I will borrow from other fields.  There are three parts to this section, the first considers motivations as understood through the games that people are motivated to play; the second covers motivations as they relate to workplace performance; and the third covers the underlying desires that drive all human behavior, and the  motivations that tie the desires to the behaviors.

----

### Motivations &ndash; game focus

There is a list of motivations in “Playful Design &ndash; Creating game experiences in everyday interfaces” (Ferrara 2012) that is from the perspective of a game designer.  It attempts to answer the question of why people are motivated to play the games they play.

* *Autonomy* &ndash; People are motivated to play games in which they have freedom of action. Players' enjoyment of a game “is very strongly related” to “the degree of autonomy” that it gives them.
* *Immersion* &ndash; Games that give players a “deep experience of immersion” create the possibility for achieving “flow” (Csikszentmihalyi 1991). The resulting “feelings of contentment and well-being, even euphoria” motivate players to play the game.
* *Competence* &ndash People want to feel that they are competent at some chosen activity; they desire to improve their skills and abilities, and the rising difficulty so some games gives players the opportunity to do this.
* *Catharsis* &ndash; Players can experience a sense of cathartic relief by expressing within a game their aggressive reactions to tensions in their lives.  They are motivated to play the game to feel that catharsis.
* *Accomplishment* &ndash; Overcoming the challenges in a game to achieve a goal can give players a sense of accomplishment.  People who can't satiate their desire for accomplishment in the non-game world will be motivated to accomplish tasks in games.
* *Social Image* &ndash; A game can provide a platform in which players can show off their skills and achievements.  Unlike being motivated by *competence*, when motivated by *social image* players acquire skills in order to improve (or maintain) their social rank.
* *Social Interaction* &ndash; People all desire some amount of social interaction; for people who are not socializing as much as they want, a game can be a pretext to engage in social interaction.
* *Creativity* &ndash; A desire to express themselves and their imaginations through acts of creation can motivate players to play games that provide opportunities to do so.

Unfortunately, looking at motivation through the lens of game design largely gives you an understanding of how those motivations interact with in-game activities.  But for gamification, what is needed is an understanding of the how motivations are related to those “aspects of the underlying non-game activity that are being transformed with game design elements” (Nicholson 2012).

To do that we'll next consider self-determination theory.

---- 

### Motivations &ndash; workplace focus

Self-determination theory is a work motivation theory that focuses “on the relative strength of autonomous versus controlled motivation” (Gagné and Deci 2005). Much as with game-focused motivation and the desire to play a game, the strength of *autonomy* in motivations has a ‘very strong’ influence on work performance.

The motivations with the highest autonomy are intrinsic motivations, which under self-determination theory are motivations that stem solely from an inherent, internal interest (Gagné and Deci 2005) or enjoyment (Ryan and Deci 2000) in an activity.

Extrinsic motivations are those that depend on a contingency between an action and some external consequence, and within self-determination theory they are placed on “a self-determination continuum” (Gagné and Deci 2005) depending on the level of autonomy they comprise.  The extrinsic motivations with the most autonomy are integrated extrinsic motivations, and the least self-determined are external extrinsic motivations.

Since internalized extrinsic motivations are highly autonomous, they are largely indistinguishable in terms of workplace performance from intrinsic motivations.  There are two ways that those can be distinguished: A) integrated extrinsic motivations started out as external, but over time became integrated, and B) integrated extrinsic motivations are not required to be enjoyable or interesting.

However, the latter distinction is problematic.  Ferrara describes the phenomenon of players “grinding” through parts of a game: 

> “[Being motivated by fun] doesn’t account for the nearly masochistic things people
are willing to do when playing a game. Many of the most popular role-playing games, for example, require players to fight the same enemies over and over again (and then again and again) to get the experience and loot they need to advance in the game. Players may spend dozens of hours in thousands f battles. So many games involve these kinds of endless repetitive actions that the gaming community has given it a name: grinding. This term is related to how we describe work we really don’t enjoy&mdash;as ‘a grind.’ So why do people pay good money to subject themselves to something that’s as unpleasant as the work an employer would pay them to do? This is a really big problem if your only explanation for why people play games is to have fun.” (Ferrara 2012) 

Those players are volunteering to play the game; they are not motivated by some external consequence.  Therefore their motivation is not an extrinsic one.  But if it's not an extrinsic motivation, then presumably it's an intrinsic motivation, yet “grinding” through a game is neither interesting or pleasurable.

While self-determination theory is useful for its method of using autonomy as an indicator of the relative strength of a motivation, its distinction between integrated extrinsic motivations and intrinsic motivations that is based on interest and enjoyment likely isn't.  Indeed, a cornerstone of Reiss' Theory of 16 Basic Desires (Reiss 2004), which is covered in the next section, is the rejection of the requirement for intrinsic motivations to be pleasurable.


----

### Motivations &ndash; generalized

As mentioned in the description of the utility of self-determination theory, it has been proposed that “[Intrinsic Motivation] theorists may have erred in embracing hedonism, the philosophy that pleasure motivates behavior,” and that “we may question whether [Intrinsic Motivation] theorists have exaggerated the extent to which certain activities really are pleasurable” (Reiss 2004).

A specific example is the intrinsic motivation for knowledge, and the purported intellectual pleasure that drives it. And yet “many scientists have written about the agony of the creative inquiry process and the emotional ups and downs of research” (Reiss 2004).

Instead of pleasure or interest or enjoyment, the distinction between extrinsic and intrinsic motivations is made based on the location of the consequence or outcome of the behavior.  Intrinsic motivations are linked to internal outcomes, and extrinsic motivations are linked to external outcomes.

(Conway seems to be a mid-point between self-determination theory and Reiss's 16 motives: “Intrinsic motivation is intimately tied to the locus of control, part of one’s sense of autonomy. As we have discussed, external rewards can cause a shift in an individual’s sense of the locus of control, as moving away from the person towards the source of the reward” (Conway 2014). Like Reiss, he seems to link a motivation's type to it being either internal or external; but like Gagné and Deci (2005) he talks not of ‘outcomes’, but rather of ‘control’.)

The internal outcomes for Reiss' 16 intrinsic motivations are a matching 16 intrinsic desires.  (See Table 1.)

#### Table 1

| Motive name       | Motive                                    | Intrinsic feeling             |
|-------------------|-------------------------------------------|-------------------------------|
| Power             | Desire to influence (including leadership; related to mastery) | Efficacy |
| Curiosity         | Desire for knowledge                      | Wonder    |
| Independence      | Desire to be autonomous                   | Freedom   |
| Status            | Desire for social standing (including desire for attention) | Self-importance |
| Social contact    | Desire for peer companionship (desire to play) | Fun  |
| Vengeance         | Desire to get even (including desire to compete, to win)    | Vindication |
| Honor             | Desire to obey a traditional moral code   | Loyalty   |
| Idealism          | Desire to improve society (including altruism, justice)     | Compassion |
| Physical exercise | Desire to exercise muscles                | Vitality  |
| Romance           | Desire for sex (including courting)       | Lust      |
| Family            | Desire to raise own children              | Love      |
| Order             | Desire to organize (including desire for ritual)            | Stability |
| Eating            | Desire to eat                             | Satiation (avoidance of hunger) |
| Acceptance        | Desire for approval                       | Self-confidence   |
| Tranquility       | Desire to avoid anxiety, fear             | Safe, relaxed     |
| Saving            | Desire to collect, value of frugality     | Ownership         |




* Conway, Steven. 2014. “Zombification?: Gamification, Motivation, and the User.” *Journal of Gaming & Virtual Worlds* 6 (2): 129–41. doi:10.1386/jgvw.6.2.129_1.

* Reiss, Steven. 2004. “Multifaceted Nature of Intrinsic Motivation: The Theory of 16 Basic Desires.” *Review of General Psychology* 8 (3): 179–93. doi:10.1037/1089-2680.8.3.179.

# Game design elements

The purpose of gamification is to improve an non-game application by using game design, and game design elements.  What are game design elements? Deterding *et al.* propose that they are “elements that are characteristic to games – elements that are found in most (but not necessarily all) games, readily associated with games, and found to play a significant role in gameplay” (Deterding *et al.* 2011).

Those elements should also be the result of a game design-like process, so that they are implemented in ways similar to the way they are in games. E.g., an application can have “levels” as part of how it structures content or access without having game-like “levels”, which are tied to progression through the game.  If there is a connection between “levels” and progression toward a goal, then that would be an example of a game design element.

## Goals, motivations, and games design elements

A gamification project has goals.  Users are directed toward those goals by motivations.  Those motivations are strengthened by appropriate game design elements.

Ferrara (2012) gives examples of combinations of appropriate game design elements (in games) and game-informed motivations. 

**Autonomy** &ndash; Games can give players an increased sense of freedom by giving them multiple objects from which to choose, and a variety of ways to meet those objectives.  By not imposing time restraints, and not forcing players through parts of a game that don't interest them, games can let players enjoy their autonomy.

**Competence** &ndash; Players motivated by confidence need the challenge to their skills to constantly increase&ndash;if the game becomes too easy, they'll lose interest.  However, it's impossible to create a sequence of increases in difficulty that appeal to all players.  So, a common approach is to make the standard sequence increase in difficulty at a rate that only the best players can keep pace with, then offer options to help other players advance.  

Players can be helped by giving them the option to choose a lower level of difficulty.  Or, there can be ways for players to earn items or features that will assist them.  Also, coaching players or having “practice” areas with little risks can help players build the skills they need to be good enough at playing the game to enjoy it.

**Social Image** &ndash; Players motivated by wanting to maintain or improve their social image will want a game to provide ways to compare achievements between players.  They will enjoy having ways to display their achievements, such as items acquired in the game, or badges earned, and will expect to be able to view others achievements.

**Creativity** &ndash; In a game appealing to the player's desire to be creative, the player will not be tied to any particular objective.  An easy-to-use interface will allow the player to create a wide variety of things, which are readily identified as distinct from other player's creations.  And the game will provide a way for the player to showcase her creations.

Everywhere in the literature, the one game design element that seemingly is always included if any specific game design elements are discussed is ‘points!’.  That is why it merits its own section, which follows.
## Points!

While there are a wide variety of game design elements that might be used to strengthen user motivations, the most popular by far is ‘points!’. Sometimes rebadged as ‘coins’, or ‘karma’, descriptions of various implementations of the intrinsically valueless counters takeup 10 pages in “Gamification by Design: Implementing Game Mechanics in Web and Mobile Apps” (Zichermann 2011).  In “Play at Work: How Games Inspire Breakthrough Thinking”, having a points! element is enough for an application or promotion to be included as an example of “gamification” in our everyday lives.

This identification of points! as synonymous with of gamification is completely specious: “What we’re currently terming gamification is in fact the process of taking the thing that is least essential to games and representing it as the core of the experience” (Robertson 2010).

The irony is that points! often play an important role in gamification.  But they are not rewards.  They do not motivate users.  When used properly, points! are an effective mechanic to provide feedback, and they can also work as indicators of progress.

Which means that they can be used for both of the requisite characteristics of meaningful play; actions with discernable outcomes, and outcomes that integrate into the overall game experience (Salen and Zimmerman 2004).  Points! can make the outcomes of actions discernable.  And they can be combined from independent outcomes and have an impact on overall gameplay.

What does it mean for points! to be properly implemented?  From a work motivation perspective, “feedback needs to be specific and relevant if it is to motivate and direct” (Siegall 1988).  So, when used as feedback points! must be tied to a specific user action, and they must be tied to the *right* user action.  

Points! as feedback must also be obviously tied to the triggering action. Otherwise, they can have a negative effect on motivation: “When reward is presented independently of performance, people may learn they cannot influence reward presentation, resulting in reduced motivation” (Eisenberger and Cameron 1996).

----

## A whirlwind literature review

Having gathered the theory side of the gamification literature, and added in some motivation theory from other fields, I can use those to evaluate the practical gamification literature. Specifically, I  critically consider two broad issues: one is whether the goals of the project and/or gamified application are those of the organization or of the user; the other is the correlation between goals, motivations, and the game design elements used.

In general, I focus on examples of failures to account for user goals, or failures to align goals, motivations and game design elements.

### Practical advice on gamification


#### “Gamifying Support”

* Sampanes, Anthony Chad. 2013. “Gamifying Support.” In *Human-Computer Interaction. Applications and Services*, edited by Masaaki Kurosu, 284–91. Lecture Notes in Computer Science 8005. Springer Berlin Heidelberg. doi:10.1007/978-3-642-39262-7_32.

The author of “Gamifying Support” gets off to a good start, by stating that “Points serve as feedback and track progression”, and by recommending that points are tied to “the behaviors your company wants to reinforce”.

However, when describing how points can applied to customer support engineers, while they are  referred to as being part of a “feedback loop” they are no longer feedback.  Instead, they have become a work-performance metric: “How customers respond to survey’s about the quality of their interaction… could provide another source of points for the engineer.… The feedback loop for them seeing the points accumulated from “tough” calls and how this is tracked and shared with the organization can help keep the engineer focused on the solution while working to keep their composure in stressful times. Other metrics, based on analytics within a call or support center can also drive points, badges, and esteem….”

Also, the author's only explanation for why a customer support engineer would be motivated to “overcome harder challenges” and “attain higher levels” is that doing so would “brings novelty into their work environment (where there otherwise wasn’t)”.  In other words, the only motivation is the obvious ‘fun’ to be had.

In a final irony, the author explains one of the potential hazards of gamification: “Gamifying support could result in dehumanifying customers. Be careful that support engineers don’t get so caught up in the ‘game’ that they forget that customers are individuals whose feelings and thoughts must be considered throughout the process.”

Which is ironic because the game is dehumanifying the employees.  Indeed, the customer support engineer gamification as described in “Gamifying Support” easily embodies four of the seven “Value Destruction Risks” of gamification (Raftopoulos 2014).

1. *Coercive participation* &ndash; users that “are under pressure and obligation to perform and are aware that they are being scrutinized, measured and evaluated” are less likely to have a gameful experience
1. *The technological whip* &ndash; the gamified system is used by the organization for surveillance, monitoring and performance tracking.
1. *Homogenization of the workforce* &ndash; “self optimizing systems” encourage behavioral conformity, but do not shift attitudes; creativity and individuality are discouraged.
1. *Shallow and inauthentic* &ndash; the gamified system is less about fun than about distracting employees from organizational dysfunctions and the methods by which the organization is controlling them.

### Gamification case studies


#### “Gamifying Intelligent Environments”

* Liu, Yefeng, Todorka Alexandrova, and Tatsuo Nakajima. 2011. “Gamifying Intelligent Environments.” In *Proceedings of the 2011 International ACM Workshop on Ubiquitous Meta User Interfaces, 7–12. ACM*. doi:10.1145/2072652.2072655.

In the conclusion, the authors of “*Gamifying Intelligent Environments*” write, “Designer[s] should build the system as a fun application to interact (play) with. We believe that the expected game-like behaviors will only arise when user is truly having a fun experience…”.  The notion that ‘fun’ is the primary motivation for playing games is dismissed by game-focused motivation theories. 

The authors go on to say that, “a fun experience requires much more than simply adding basic game mechanics: well-designed avatars, content, flow, user interface and interaction model are all needful components for a successful gamification implementation”.  None of those requisite features inherently improve the autonomy of users, so according to self-determination theory, there is no reason to assume that they would increase user motivations.

The author's also fail to understand that gamified elements need to align with user motivations.  While they know that the users of one of their example gamified systems are motivated by an “environmentally friendly mind” and an “interests of saving energy”, they don't explain how their design supports those motivations.  How do elements like “virtual items [to] decorate their islands” and a mechanic that “successful [emissions rights] sellers can afford to decorate their island more” relate to users that are motivated by environmental concerns?  Applying Reiss' 16 motives, the designers seem to be providing users with an ‘idealism’ motive with a mechanic that feeds a ‘status’ motive.

#### “Gamification in Logistics and Supply Chain Education: Extending Active Learning”

* Wood, L. C., and T. Reiners. 2012. “Gamification in Logistics and Supply Chain Education: Extending Active Learning.” In *IADIS International Conference on Internet Technologies & Society 2012*. Perth, Australia: IADIS Press. http://aut.researchgateway.ac.nz/handle/10292/6202.

The authors of “*Gamification in Logistics and Supply Chain Education: Extending Active Learning*” only seem to go off the rails when explaining why “leaderboards and comparisons” would be an improvement.

>“Feedback needs be provided to students so that they can compare and contrast their own performance with that of their peers. It will become necessary to incorporate some form of the leaderboard or publication of results; even if these are not tied to particular students (we do not wish to breach privacy considerations). Such publications would allow an individual to understand where they are in comparison to their classmates; they may be able to determine that they are on the lower end of the class, motivating them to perform better in the future. …Staff can upload the results soon after assessments, ensuring students can perceive in near-to-real-time, how they are progressing in comparison to their classmates.”

Timely feedback is key to keeping users motivated.  But feedback should integrate into the overall progression through the system.  The proposed feedback doesn't do that&mdash;it only shows a user her relative rank in the class. So the leaderboard doesn't help create a gameful experience.

And to what motivation does it relate? Anonymous rankings don't promote a social image/status motive or any of the motives that non-anonymous leaderboards might.  Knowing her rank in class won't improve a user's sense of autonomy.  Worse, focusing on an external outcome such as a leaderboard, can shift her intrinsic motivations into extrinsic ones.

#### “A Case Study in the Gamification of a University-Level Games Development Course”

* O’Donovan, Siobhan, James Gain, and Patrick Marais. 2013. “A Case Study in the Gamification of a University-Level Games Development Course.” In *Proceedings of the South African Institute for Computer Scientists and Information Technologists Conference, 242–51. SAICSIT ’13*. New York, NY, USA: ACM. doi:10.1145/2513456.2513469.

As referenced earlier, the authors of “*A Case Study in the Gamification of a University-Level Games Development Course*” give the organization's goals priority over those of the users, not including the latter at all: “Our goal with gamification was to improve lecture attendance,￼content understanding, problem solving skills and general￼engagement. The success of this intervention was measured using￼course marks, lecturer evaluations, lecture attendance, and a￼questionnaire….”

The authors confuse gamification with “pointsification” (Robertson 2010) with gamification:

>“Gamification… applies reward-based games design elements to tasks, such as visiting a website or using a product, in order to motivate the target market to engage in these tasks more often and deeply.”

And they confuse promoting intrinsic motivation with manipulation: “Gamification is applied to systems where specific user behaviour is desired. This requires that the game design techniques manipulate users’ behaviour with a high degree of certainty”.

They later explain that while they believe that good gamification manipulates behavior (instead of improving motivations) this should be hidden from users by creating a “illusion” of autonomy: “…if users feel that they are being manipulated, they may notice that their freedom within the product is an illusion”.

#### “Research in the Large: Challenges for Large-Scale Mobile Application Research &ndash; A Case Study about NFC Adoption Using Gamification via an App Store”

* Kranz, Matthias, Lukas Murmann, and Florian Michahelles. 2013. “Research in the Large: Challenges for Large-Scale Mobile Application Research- A Case Study about NFC Adoption Using Gamification via an App Store.” *International Journal of Mobile Human Computer Interaction* 5 (1): 45–61. doi:10.4018/jmhci.2013010103.

It could be argued that the project detailed in “Research in the Large: Challenges for Large-Scale Mobile Application Research- A Case Study about NFC Adoption Using Gamification via an App Store” is not an example of gamification, and that its application is like the “full-fledged games for non-entertainment purposes” that are considered to be ‘serious games’ (Deterding *et al.* 2011).  But as there is no sharp distinction between serious games and gamified applications, and since the authors describe there project as using gamification, it's included in this review.

As mentioned previously, this project is most notable for its goals.  More exactly, for actively hiding the project's goals, which were purely organization goals, from users of the data collection application disguised as a game. The authors report that “most users are unaware of the game's purpose as a research project”, and later describe their intentional obfuscation of the project's goals: “[we] chose a neutral name for our game that did not disclose its nature as a research project, but did rather seem like a game of an independent development studio”.

This would be ethically questionable if they described their application as a ‘serious game’; as gamification, it is both ethically questionable and an example of improperly defined goals.

----

## Conclusion

The definition of gamification is still not solidified.  An element-centric definition such as the one offered by Deterding *et al.* (2011) is most common, but there are also a number of experience-centric definitions, e.g., the definition given by Huotari and Hamari (2012).

The primary area of discourse in the practice of gamification seems to be project goals (cf. Deterding 2012, Ferrara 2012, Nicholson 2012, Conway 2014, Raftopoulos 2014).  Should gamification projects primarily focus on achieving organization goals; should they primarily focus on achieving user goals; or should they strike some balance between the two?  There are recommendations for ensuring the inclusion of user goals in gamification project goals (Nicholson 2012, Raftopoulos 2014) but no guidelines beyond simple inclusion.

Issues of motivation are often reduced to simplistic distinctions between intrinsic and extrinsic motivations, and to make things more difficult, motivations are confused with rewards.  Viewing motivations through a work-motivation lense, such as self-determination theory, is likely appropriate and useful for ranking the strength of motivations.  However, a more fine-grained view of motivation, such as provided by Reiss (2004), might provide a way to better map motivations to both goals, and to game design elements.

----

# References

* Conway, Steven. 2014. “Zombification?: Gamification, Motivation, and the User.” *Journal of Gaming & Virtual Worlds* 6 (2): 129–41. doi:10.1386/jgvw.6.2.129&#x5f;1.
* Csikszentmihalyi, Mihaly. 1991. *Flow: The Psychology of Optimal Experience*. New York : Harper & Row.
* Deterding, Sebastian, Dan Dixon, Rilla Khaled, and Lennart Nacke. 2011. “From Game Design Elements to Gamefulness: Defining ‘Gamification.’” In *Proceedings of the 15th International Academic MindTrek Conference: Envisioning Future Media Environments, 9–15. MindTrek ’11*. New York, NY, USA: ACM. doi:10.1145/2181037.2181040.
* Deterding, Sebastian. 2012. “Gamification: Designing for Motivation.” *Interactions* 19 (4): 14–17. doi:10.1145/2212877.2212883.
* Eisenberger, Robert, and Judy Cameron. 1996. “Detrimental Effects of Reward: Reality or Myth?” *American Psychologist* 51 (11): 1153–66. doi:10.1037/0003-066X.51.11.1153.
* Ferrara, John. 2012. *Playful Design: Creating Game Experiences in Everyday Interfaces*. 1st ed. Brooklyn, New York: Rosenfeld Media.
* Gagné, Marylène, and Edward L. Deci. 2005. “Self-Determination Theory and Work Motivation.” *Journal of Organizational Behavior* 26 (4): 331–62. doi:10.1002/job.322.
* Huotari, Kai, and Juho Hamari. 2012. “Defining Gamification: A Service Marketing Perspective.” In *Proceeding of the 16th International Academic MindTrek Conference, 17–22. MindTrek ’12*. New York, NY, USA: ACM. doi:10.1145/2393132.2393137.
* Kranz, Matthias, Lukas Murmann, and Florian Michahelles. 2013. “Research in the Large: Challenges for Large-Scale Mobile Application Research- A Case Study about NFC Adoption Using Gamification via an App Store.” *International Journal of Mobile Human Computer Interaction* 5 (1): 45–61. doi:10.4018/jmhci.2013010103.
* Liu, Yefeng, Todorka Alexandrova, and Tatsuo Nakajima. 2011. “Gamifying Intelligent Environments.” In *Proceedings of the 2011 International ACM Workshop on Ubiquitous Meta User Interfaces, 7–12. ACM*. doi:10.1145/2072652.2072655.
* Nicholson, S. 2012. “A User-Centered Theoretical Framework for Meaningful Gamification.” In *GLS 8.0 Conference Proceedings*. Madison, WI, USA: ETC Press.
* O’Donovan, Siobhan, James Gain, and Patrick Marais. 2013. “A Case Study in the Gamification of a University-Level Games Development Course.” In *Proceedings of the South African Institute for Computer Scientists and Information Technologists Conference, 242–51. SAICSIT ’13*. New York, NY, USA: ACM. doi:10.1145/2513456.2513469.
* Penenberg, Adam L. 2013. *Play at Work : How Games Inspire Breakthrough Thinking*. New York: Portfolio/Penguin.
* Raftopoulos, Marigo. 2014. “Towards Gamification Transparency: A Conceptual Framework for the Development of Responsible Gamified Enterprise Systems.” *Journal of Gaming & Virtual Worlds* 6 (2): 159–78. doi:10.1386/jgvw.6.2.159_1. ._.
* Reiss, Steven. 2004. “Multifaceted Nature of Intrinsic Motivation: The Theory of 16 Basic Desires.” *Review of General Psychology* 8 (3): 179–93. doi:10.1037/1089-2680.8.3.179.
* Robertson, Margaret. 2010. “Can’t Play, Won’t Play.” *Hide&Seek*. October 6. http://www.hideandseek.net/2010/10/06/cant-play-wont-play. Accessed April 5, 2015.
* Ryan, Richard M., and Edward L. Deci. 2000. “Intrinsic and Extrinsic Motivations: Classic Definitions and New Directions.” *Contemporary Educational Psychology* 25 (1): 54–67.
* Salen, Katie, and Eric Zimmerman. 2004. *Rules of Play : Game Design Fundamentals*. Cambridge, Mass.: MIT Press.
* Sampanes, Anthony Chad. 2013. “Gamifying Support.” In *Human-Computer Interaction. Applications and Services*, edited by Masaaki Kurosu, 284–91. Lecture Notes in Computer Science 8005. Springer Berlin Heidelberg. doi:10.1007/978-3-642-39262-7_32.
* Siegall, Marc. 1988. “The Simplistic Five: An Integrative Framework for Teaching Motivation.” *Journal of Management Education* 12 (4): 141–43. doi:10.1177/105256298801200418.
* Wood, L. C., and T. Reiners. 2012. “Gamification in Logistics and Supply Chain Education: Extending Active Learning.” In *IADIS International Conference on Internet Technologies & Society 2012*. Perth, Australia: IADIS Press. http://aut.researchgateway.ac.nz/handle/10292/6202.
* Zichermann, Gabe. 2011. *Gamification by Design: Implementing Game Mechanics in Web and Mobile Apps*  1st ed. Sebastopol, California. O’Reilly Media.
