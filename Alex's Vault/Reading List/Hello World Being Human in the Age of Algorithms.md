# Key Points

- Understanding the relationship between humans and machines is essential for understanding algorithms.
- Critical questions to ask individually and as a society:
    - Do we understand specific algorithms? How they work what their limits are? What are the pros and cons?
    - Does the specific algorithm result in a net benefit to society?
    - When should we trust machines over human judgement?
    - What kind of world do we want to live in?

**Chapter 1: Power**

- Example: Deep Blue vs. Kasparov chess match in 1997.
    - IBM designed Deep Blue to appear more “uncertain” than it was: “the machine would occasionally hold off from declaring its move once a calculation had finished, sometime for several minutes.” This unnerved Kasparov, forced him to second-guess himself (and the computer’s capabilities) and ultimately, altered his chess strategy in the match for the worse.
    - “The power of an algorithm isn’t limited to what is contained within its lines of code.”
    - “Understanding our own flaws and weaknesses—as well as those of the machine—is the key to remaining in control.”
- **Algorithms defined**:
    - Dictionary definition: “A step-by-step procedure for solving a problem or accomplishing some end especially by a computer.”
    - “A series of logical instructions that show, from start to finish, how to accomplish a task.”
    - Practically speaking the term connotes a mathematical or logical construct that uses math operations, arithmetic, algebra, calculus, logic and probability and manifests in the form of computer code.
- Four algorithmic task-categories:
    - **Prioritization**:
        - Making an ordered list.
        - Example: Google returns a ranked list of search results sorted by relevance.
        - Example: GPS/Maps apps identify the fast route to a destination.
        - Example: Deep Blue prioritized the next best move from a huge set of possible moves.
    - **Classification**:
        - Picking a category.
        - Example: Internet advertising identifies/targets groups of users receptive to their marketing messages (based on common characteristics).
        - Example: Automated moderation tools that remove inappropriate content (e.g. spam filters).
    - **Association**:
        - Finding links and relationships between things.
        - Example: OKCupid and dating algorithms look for links between people [me: How is classification distinct from association? Is it that you have two human parties being matched?]
    - **Filtering**:
        - Isolating what’s important. Separating the signal from the noise.
        - Example: Speech recognition algorithms like Siri, Alexa and Cortana which filter out the voice from the background noise before processing what you are saying.
        - Example: Facebook and Twitter filter stories that relate to your known interest to help you stay engaged.
- Many algorithms use combinations of the above task-categories.
- Two methodological paradigms for algorithms:
    1. **Rules-based algorithms**: Directly designed by humans with explicit instructions and logic.
        - Easy to comprehend. Can read the program and understand the underlying process.
        - Only usable in cases where humans know how to write the instructions.
    2. **Machine-learning algorithms**: Doesn’t use precise set of instructions. Instead, begins with an objective and leaves it to the algorithm to determine how to arrive at that outcome.
        - Black box: difficult for human observers to comprehend the logic behind the outcome.
        - Work well at problems where writing a list of instructions doesn’t work (for instance image recognition of objects).
- Regarding “AI” and machine learning: “[It’s] more useful to think of what we’ve been through as a revolution in computational statistics than a revolution in intelligence.”
- “The Search Engine Manipulation Effect” (2015 research study):
    - Experiment that sought to understand the impact of how search engines like Google influence our view of the world.
    - “When people are unaware they are being manipulated, they tend to believe they have adopted their new thinking voluntarily.” — Robert Epstein (psychologist and co-author).
    - People see algorithms as a “convenient source of authority.”
    - Results show a lack of user scrutiny and critical thinking towards the quality or veracity of algorithmic output.
- “The only way to objectively judge whether an algorithm is trustworthy is by getting to the bottom of how it works.”
- “Having a person with the power of veto in a position to review the suggestions of an algorithm before a decision is made is the only sensible way to avoid mistakes.”
    - Example: The story of Stanislov Petrov, the Soviet military officer who prevented nuclear annihilation when he used his intuition to mistrust an algorithm that told him a nuclear strike from the United States was imminent in 1983.
    - Counter-example: The 2015 UK Smiler rollercoaster crash in which two roller coaster operators overrode a computer algorithm that set off a warning system. The operators, confident that the ride was safe, ignored the warning system resulting in a catastrophic accident.
- **Algorithm aversion**: Phenomenon where humans are less tolerant of algorithmic errors than of their own (even when the humans are more prone to error).
    - We tend to over-trust algorithms UNTIL they exhibit errors or poor results.
    - Once an algorithm demonstrates fallibility, we overcompensate in the other direction and begin to dismiss the generally useful output.
    - [Me: Human behavior of overcompensating too much in one direction or the other based on small data-sets and a difficulty comprehending probabilistic outcomes AND from separating sound processes systems from the results.]

**Chapter 2: Data**

- Data collection is used by businesses to understand consumer behavior and generate insights that can result increased profitability and competitive advantage.
- Data collection is ubiquitous. Notable examples:
    - 1993 Tesco: Loyalty card that first tracked purchase amounts and later actual items purchased. Tesco improved targeted offers to customers based on this data.
    - 2002 Target: Algorithm that identified expectant mothers based on purchasing behaviors.
- **Data brokers**: Companies that purchase and collect personal information and then resell it for profit.
    - Notable data brokers: Palantir, Acxiom, Corelogic, Datalogix, eBureau.
    - Types of information collected: Online shopping data, newsletter signups, website registrations, warranties submitted, home purchasing info, voter registration, browser history and more.
    - Single file is generated for each individual that aggregates and cross-references all of this personal data.
    - File includes: “Your name, your date of birth, your religious affiliation, your vacation habits, your credit-card usage, your net worth, your weight, your height, your political affiliation, your gambling habits, your disabilities, the medication you use, whether you’ve had an abortion, whether your parents are divorced, whether you’re easily addictable, whether you are a rape victim, your opinions on gun control, your projected sexual orientation, your real sexual orientation, and your gullibility.”
- Rich personal data allows for hyper-efficient matching algorithms.
    - Payday lenders can target people with bad credit scores.
    - Online betting can be targeted at people who frequent gambling sites.
- “Business models are based on the idea of micro-targeting. They are gigantic engines for delivering adverts.”
- “Algorithms are trading on information you didn’t know they had and never willingly offered. They have made your most personal, private secrets into a commodity.”
- The Facebook Cambridge Analytica scandal highlights a situation in which private and sensitive personal information was gathered and then used to manipulate those same individuals.
    - Cambridge Analytica used personality profiles and delivered charged political messages and fake news stories at particularly susceptible audiences.
    - Remember the finding from the 2015 Epstein study in Chapter 1: People are susceptible to manipulation from algorithms that are deemed authoritative.
- China’s “Sesame Credit” as a future case for an omnipresent, government sponsored data broker.
- To date there is little government regulation around data collection. Some notable exceptions:
    - European Union’s GDPR (General Data Protection Regulation). Prevents storage of data without explicit purpose and requires consumer consent for use of data.
- “Whenever we use an algorithm—especially a free one—we need to ask ourselves about the hidden incentives. Why is this app giving me all this stuff for free? What is this algorithm really doing? Is this a trade I’m comfortable with? Would I be better off without it?”

**Chapter 3: Justice**

- Judicial system is not an exact science. Judges cannot guarantee precision.
    - This fact is evidenced by the prominence of concepts like “reasonable doubt” and “substantial grounds.”
    - Appeals are an important part of the process.
- Result is a system with some significant discrepancies in the treatment of similar cases and defendants.
- Research studies over the past 50 years demonstrate how much disparity there is:
    - 1977 study: 47 judges shown an identical case and asked to render a decision. Verdicts ranged from setting defendant free to being sent to jail.
    - 2001 study: 81 judges asked to award bail to a variety of imaginary defendants. Some of the cases were identical but the names of the defendants were changed. Most judges failed to make the same decision on the same case when seeing it for a second time.
- “Whenever judges have the freedom to assess cases for themselves, there will be massive inconsistencies. Allowing judges room for discretion means allowing there to be an element of luck in the system.”
- Burgess prediction tool (1928):
    - Algorithm uses 21 factors deemed significant in determining whether someone would violate parole.
    - Inmates are scored for each question (1 or 0) and can score up to 21 points. High scores between 16-21 are deemed low risk for recidivism.
    - Algorithm performed well: 98% of low risk group didn’t break parole. Only 33% of high risk group made it through parole.
- Systemic trade-off between consistency and fairness.
- **Decision tree**: A flowchart that takes a set of circumstances and assesses, step by step, what to do or what will happen.

- **Ensemble method**: The combining of several decision trees to generate better predictive performance over the use of a single tree.
- **Random forrest**: A large group of decision trees that, in concert, can be utilized to reach a consensus decision in order to account for a wide array of circumstances and factors that a single (simpler) decision tree cannot.
- Two types of algorithmic errors:
    - **False negatives**: Failure to identify the person or thing the algorithm is looking for. Example: A criminal identification algorithm letting Darth Vader go free.
    - **False positives**: Incorrectly identifying a person or thing. Example: The same criminal identification algorithm incarcerates Luke Skywalker (who is innocent).
- COMPAS is a proprietary risk-assessment algorithm.
    - 2016 ProPublica investigation found:
        - The algorithm’s false positives were disproportionately black.
        - The algorithm’s false negatives were disproportionately white.
    - Is it possible to develop an “unbiased” algorithm?
    - Algorithms like COMPAS are probabilistic:
        - Outcomes will be biased because reality is biased.
        - Example: More men commit homicides so more men will be falsely accused of having the potential to murder.
        - See figure below which shows ratio of female (top) to males (bottom) flagged by an algorithm as potential murderers. The ratio is 25% female and 75% male. If the algorithm is 96% accurate there will be 4 false positives (which are disproportionately male).

- Should an algorithm reflect current reality or should it encourage an alternative--e.g. more fair--reality?
- Example: Google image search results for “math professor” could return photos of white men (current reality) or prioritize images of female non-white professors (reality we aspire to).
- System 1 vs. System 2 thinking:
    - **System 1**: Automatic, instinctive, but prone to mistakes.
    - **System 2**: Slow, analytic, considered, but often lazy.
    - “Our minds aren’t built for robust, rational assessment of big, complicated problems.”
- Cognitive biases impact the decision-making of judges:
    - **Anchoring effect**: The cognitive difficulty of setting numerical values on things. We are better at making comparisons with preexisting values. This tendency can be exploited. Example: If prosecution demands higher damages, a judge is more likely to award higher damages (due to anchoring?).
    - **Weber’s Law**: “The smallest change in a stimulus that can be perceived is proportional to the initial stimulus.” This idea can impact sentence lengths judges choose.
    - More bias examples:
        - Judges with daughters deliver more favorable decisions to women.
        - Judges are less likely to award bail of the local sports team has lost recently.
        - Time of day may impact whether or not a favorable decision is made.
- “The choice isn’t between a flawed algorithm and some imaginary perfect system. The only fair comparison to make is between the algorithm and what we’d be left with in its absence.”
- A well-designed and transparent algorithm can minimize systematic bias and random error (though it still will not be 100% perfect).
- Hybrid approach that balances and combines algorithmic thinking with human judgement may be the optimal solution.

**Chapter 4: Medicine**

- Modern medicine is built upon the finding of patterns in data.
- Algorithms are very good at pattern recognition, classification and prediction.
- Limitations of current human pathologists:
    - Cases at the extreme are easy to identify. Pathologist diagnostic accuracy is > 96% in these cases.
    - Ambiguous cases (between normal and obviously malignant) pose the biggest diagnostic challenges.
    - “One 2015 study took 72 biopsies of breast tissue, all of which were deemed to contain cells with benign abnormalities (a category towards the middle of the spectrum) and asked 115 pathologists for their opinion…the pathologists only came to the same diagnosis 48 per cent of the time.”
- Image recognition algorithms can be used to help improve accuracy and speed of pathology diagnoses.
- **Neural networks**:
    - “An enormous mathematical structure that features a great many knobs and dials. You feed your picture in at one end, it flows through the structure, and out at the other end comes a guess as to what that image contains. A probability for each category: Dog; Not dog.”
    - “At the beginning, your neural network is a complete pile of junk. It starts with no knowledge – no idea of what is or isn’t a dog. All the dials and knobs are set to random. As a result, the answers it provides are all over the place – it couldn’t accurately recognize an image if its power source depended on it. But with every picture you feed into it, you tweak those knobs and dials. Slowly, you train it.”
    - Once a neural network is properly trained and tuned, it can classify previously unseen images as either “dog” or “not dog” based on prior training.
    - The neural network is a **black box** in that all the “knobs and dials” are not well understood by the human observer.
        - Example: An algorithm that differentiates between huskies and wolves doesn’t make a determination on the animal itself, but rather looks for the presence of snow.
- The sensitivity vs. specificity tradeoff:
    - These are statistical measures of performance in a binary classification test.
    - Ideally you want as few false positives and as few false negatives as possible.
    - **Sensitivity** is the statistical measure of correctly identifying true positives. Example: A test for cancer with 100% sensitivity will identify everyone who has cancer. The downside is that it will also result in false positives (people identified as having cancer who do not have cancer).
    - **Specificity** is the statistical measure of correctly identifying true negatives. Example: A test for cancer with 100% specificity will never identify someone as having cancer who does not. The downside is that some people with cancer will be missed.
    - Very few tests excel at both sensitivity and specificity. There is usually a tradeoff between the two. Example: An algorithm prioritizing sensitivity will mean lower specificity.
    - “Human pathologists don’t tend to have problems with specificity. They almost never mistakenly identify cells as cancerous when they’re not. But people do struggle a little with sensitivity. It’s easy for us to miss tiny tumours…”
- 1986 Nun Study
    - Found a connection between language skills as a young adult and dementia in old age.
    - “Subtle signals about our future health can hide in the tiniest, most unexpected fragments of data.”
    - Suggests the immense potential for medical algorithms combined with rich individual datasets.
- Important to note that a diagnosis alone is not sufficient for determine how a particular condition will develop. There is a cost to veering too far into the realm of over-diagnoses and over-treatment.
- “If you can take a picture of it and stick a label on it, you can create an algorithm to find it.”
- Another important consideration for healthcare algorithms: balance between privacy and public good.

**Chapter 5: Cars**

- Autonomous vehicles appears to be a simple problem (only outputs are speed and direction) but in truth it is extremely complicated due to broad range of environmental circumstances and unpredictable variables (obstacles, terrain, human interactions).
- “Smart cars” must take inputs from a variety of sensors:
    - Cameras:
        - Strengths: Visual data.
        - Weakness: Cannot “see” in 3D on its own. Not good at measurements.
    - GPS:
        - Strengths: Provides high-level location information.
        - Weakness: Prone to uncertainty, not precise.
    - LiDAR (Light Detection and Ranging):
        - Strengths: Measuring distances.
        - Weakness: Cannot detect texture or color. Not good at long distances.
    - Radar:
        - Strengths: Effective in all weather conditions, can detect obstacles at long distances. Can see through some materials.
        - Weakness: Not good a providing details (e.g. shape or structure of obstacles).
- The trick to building a driverless car is to combine the various vehicle sensors into a seamless algorithm.
    - One problem is determining how to prioritize and harness disparate data.
    - Example: Tumbleweeds stymied vehicles in the inaugural DARPA Grand Challenge (contest for autonomous vehicles).
        - LiDAR says there is an obstacle ahead.
        - Camera agrees with LiDAR that there is an object.
        - Radar, which passes through the flimsy object, says there’s nothing to worry about.
- “Every measurement taken by the car will have some margin of error: radar readings, the pitch, the roll, the rotations of the wheels, the inertia of the vehicle. Nothing is ever 100 per cent reliable. Plus, different conditions make things worse: rain affects LiDAR; glaring sunlight can affect the cameras; and long, bumpy drives wreak havoc with accelerometers.”
- **Bayes' theorem**:
    - A system for updating a belief in a hypothesis on the basis of evidence.
    - Theory accepts that you can never be completely certain about the truth but that you can make a “best guess” from the available information.
    - Sharon Bertsch McGrayne: “Bayes runs counter to the deeply held conviction that modern science requires objectivity and precision.”
    - “Bayes allows you to draw sensible conclusions from sketchy observations, from messy, incomplete and approximate data — even from ignorance.”
    - **Probabilistic inference**: The iterative process of using the latest data available (along with Bayes theorem) to infer a truth. In the case of an automobile it would be understanding the location of a vehicle in the real world relative to an array of static and dynamic obstacles surrounding it.
- **The trolley problem**:
    - A thought experiment in the field of ethics.
    - The problem: There is a runaway trolley barreling down the tracks. Ahead of the tracks are five people unaware of the trolley. The trolley is headed straight towards them. You are an observing the scene and standing next to a lever. If you pull the lever, the trolley will switch to another set of tracks. However there is one person on the side track. The dilemma:
        - Do nothing and allow the trolley to kill the five people.
        - Pull the lever, save the five people and kill the one person instead.
    - The trolley problem demonstrates one type of ethical dilemma facing algorithmic systems.
- “Driverless technology is categorized using six different levels:
    - Level 0: No automation.
    - Level 1: Foot off.
    - Level 2: Cruise control. Hands off.
    - Level 3: Eyes off.
    - Level 4: Geo-fenced autonomous vehicles. Brain off.
    - Level 5: Fully automated.
- “In 1983, the psychologist Lisanne Bainbridge wrote a seminal essay on the hidden dangers of relying too heavily on automated systems. Build a machine to improve human performance, she explained, and it will lead – ironically – to a reduction in human ability.”
    - Example: People don’t remember phone numbers anymore.
    - Example: People can’t navigate city streets without GPS.
- Author advocates for the hybrid approach: “let the skills of the machine complement the skills of the human.”
    - Toyota is building cars with two modes: “chauffeur mode” (an auto-driving mode) and “guardian mode” (a backup safety mode while a human drives).
- Important question that needs to be asked: “Once you’ve built a flawed algorithm that can calculate something, should you let it?”

**Chapter 6: Crime**

- People committing crime create reliable geographical patterns:
    - Most people operate locally.
    - Serious crimes tend to take place close to where the perpetrator lives.
- **Distance decay**: A criminological phenomenon that posts that the chance of finding a perpetrator’s residence drops as you move further and further away from the scene of a crime.
- **Buffer zone**: A geographical pattern in which serial offenders are unlikely to target victims who live too close.
- **Geoprofiling algorithm**:
    - Uses the two key patterns of distance decay and buffer zone.
    - Algorithm outputs a plausible range of locations where a perpetrator might live.
    - This output in turn helps police to prioritize their list of suspects and focus their limited resources on high-probability leads.
- CompStat data tracking tool:
    - Used to track crime data and identify urban hotspots.
    - Crimes no longer seen as isolated incidents.
    - Police forces can focus their attention on these areas that commit a disproportionate level of crime.
    - Boston study concluded that 66% of street robberies occurred on just 8% of the city streets.
    - Minneapolis study concluded that 50% of the emergency calls to the police came from just 3% of the city area.
- Flag and boost theories for hotspot forecasting:
    - **Flag**: These fixed factors that represent higher risk for certain crimes. For example: a highly trafficked thoroughfare vs. a quiet side street.
    - **Boost**: Current factors in your surrounding area. For instance, once a location is victimized, the chance of it or the surrounding properties being victimized increases significantly.
    - Criminologists found that earthquake patters and aftershocks have proven a useful model for understanding crime “aftershocks.”
- **PredPol** (aka Predictive Policing):
    - Predictive policing cannot target individual people only geography.
    - It can only predict **risk of future events** not the events themselves.
    - Furthermore the task of reducing crime based on the predictive modeling is a completely separate problem.
    - Many PredPol algorithms are proprietary “black box” solutions with no transparency as to algorithmic biases.
- **Feedback loops**:
    - By acting on a predictive algorithm you risk reinforcing the presence of whatever it is you are tracking.
    - Example: By using a “cops-on-the-dots” tactic where police patrols are sent to predicted hotspots, the presence of police in a specific location will observe and encounter crime simply by being there. In other words, the feedback loop creates a self-fulfilling prophecy.
- Facial recognition algorithms are becoming important for modern policing but come with a variety of problems.
    - Humans and computers are not 100% accurate at identifying people.
    - Resemblance and identity are not the same thing.
    - Apple’s Face ID system in not flawless: It can be fooled by twins, siblings and children.
- Algorithms in law enforcement require a trade-off between privacy and protection, fairness and safety.
    - Are false positives ever acceptable?

**Chapter 7: Art**

- **Social proof**: “Whenever we haven’t got enough information to make decisions for ourselves, we have a habit of copying the behaviour of those around us.”
    - Important factor in the popularity of some works of art.
    - Popularity can serve as a proxy for quality.
    - Quality and luck also have roles to play in the success of art.
- Algorithms have a difficult time predicting popularity:
    - Novelty is an important factor: “we’re put off by the banal, but also hate the radically unfamiliar.” Striking the right balance is difficult.
    - Algorithms can quantify the similarity of whatever has gone before.
    - Spotify and Netflix can recommend content that is “good enough to insure you against disappointment.”
- EMI (Experiments in Musical Intelligence):
    - Computer algorithm that generates music that humans have mistaken as composed by a human.
    - “However beautiful EMI’s music may sound, it is based on a pure recombination of existing work. It’s mimicking the patterns found in Bach’s music, rather than actually composing any music itself.”
- “True art can’t be created by accident. There are boundaries to the reach of algorithms. Limits to what can be quantified. Among all of the staggeringly impressive, mind-boggling things that data and statistics can tell me, how it feels to be human isn’t one of them.”

**Conclusion**

- Solving problems is not an end point. Algorithms create as many new problems as solve old ones.
    - Privacy considerations.
    - Bias and discrimination.
    - Accountability.
    - Transparency.
    - Fairness.
- “Thinking of algorithms as some kind of authority is exactly where we’re going wrong.”
- “Our reluctance to question the power of an algorithm has opened the door to people who wish to exploit us.”
- We must accept that perfection does not exist. Any system will exhibit some kind of bias.
- Author advocates for a hybrid approach in which algorithms complement human capabilities and human oversight and intuition is always closely linked to the decision-making process.
- “In the age of the algorithm, humans have never been more important.”