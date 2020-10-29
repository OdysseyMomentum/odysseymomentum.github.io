## How does this work?

During Odyssey Momentum Software Improvement Group (SIG) Code JEDI’s will support teams to write future-proof code by means of tooling and advice.

## Better Code Hub (BCH)

Teams will be invited to a GitHub team where they can push their code continuously. The repo can be a private or public. For every commit Better Code Hub (BCH) will automatically check the code quality. Installation of BCH is zero-setup. The code quality score is displayed on a 10 point scale. 

Together with the challenge leads SIG will qualify teams for a grill session, which means a short interview by a SIG Code JEDI. 


## SIG Grill Session

During this 10 minute grill session, a SIG code JEDI will interview the team on the issue they are addressing with their solution, and how it was implemented. The grill session will act as a sanity check and touches on various software quality aspects, like maintainability, security and scalability. Additionally, the team will be challenged on their implementation approach and decision making process.

Last year, all teams that had passed the grill session received a golden balloon, this year your team will receive virtually an avatar with a golden balloon. 

The results from the grill session will be visible on the teams MIRO-board, this will help to demonstrate the maturity of the prototype to the judges.

## Sigrid

BCH is linked to Sigrid, SIG’s software assurance platform. Challenge leads & challenge owners see in Sigrid how teams are performing. 
Via a livestream SIG will be interviewed by Odyssey and will show & explain what we see in Sigrid.

## Ok, what are those 10 guidelines?

1. Your code will be evaluated against 10 guidelines for building future-proof code. The guidelines are described in full in [“Building Maintainable Software”](https://www.softwareimprovementgroup.com/resources/ebook-building-maintainable-software/)

2. Find a concise reference card of the guidelines [here](https://cdn-images-1.medium.com/max/1200/1*TS-ZTeI7sQS7dy_AlMqSXQ.png).

3. You can check your code against the guidelines using Better Code Hub, a GitHub integration provided by [Software Improvement Group](https://www.sig.eu). Better Code Hub integrates with the GitHub CI and runs at Pull Requests and Pushes.

4. 17 modern programming languages are [supported](https://bettercodehub.com/docs/configuration-manual) with a maximum codebase size 200 KLoc.


## GitHub teams and private repos

- All the teams were created on forehand and email invites were send to the teamleads. 
- Please check these invite emails from GitHub.
- Your team is added here [OdysseyMomentum Organization](https://github.com/odysseymomentum)
- Your repo can be private or public

## More private repos

- You can add more repos to your team yourself.
- You first need to create the repository within the org (using the + next to your profile icon) 
- then add the repo to your team -> repositories -> add -> and add the created respository

## GitHub oAuth to login to Better Code Hub and run analysis

1. Go to [Bettercodehub.com](https://bettercodehub.com), login with your Github oAuth and accept the 3 scopes. 

2. Press play and get instant feedback on the guidelines and pick refactor candidates.

3. Click on the Pull request icon to make Better Code Hub run on every Push and Pull Request.


## How to get support

1. Before the event, through [email](mailto:bettercodehub@sig.eu).

2. During the event by talking to SIG JEDI 

3. After the event, through [email](mailto:bettercodehub@sig.eu).



## How to qualify for a ‘grill session’ by SIG? 

1. If you score high on software quality your chances of being selected by the challenge lead increases significantly.

2. The challenge lead will let you know when your team is selected. 

3. If you’re selected: visit the SIG meeting space to select your timeslot for the grill session.

4. If you pass you get an avatar with a golden balloon, the results will be shared with the organizers and added to the teams MIRO-board.



## Odyssey Hackathon Scoreboard

All the badges of the repos are collected [here](https://odysseyhack.github.io/scoreboard)
Not on the scoreboard? Let the Better Code Hub team know on Mobilize or send a PR.


## How to exclude library files from analysis / change your configuration

1. Get your current configuration file from your project settings. (Gear icon on bettercodehub.com)

2. Place that config in _.bettercodehub.yml_ in your repository root

3. Add a section called exclude, in there add the files/folders you want to exclude. Supported exclusion options can be found [at the bettercodehub documentation](https://bettercodehub.com/docs/configuration-manual)


## Why your Odyssey needs Future-Proof code

Read more [On why it needs high quality code ](https://medium.com/@jstvssr/why-blockchain-needs-future-proof-code-cb09b39175e1#.bqfmcig55)

Or about the [2017 Dutch Blockchain Hackathon in Groningen](https://dev.to/jstvssr/how-a-hackathon-appreciates-quality-code)


Let's build some great software!!

2020 SIG Jedi team

Bugra, Reinier, Mees, Rakesh, Rudy, Martin, [Jan](https://github.com/janlaan), [Michiel](https://github.com/michielcuijpers)

