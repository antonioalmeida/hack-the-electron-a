# Hack The Electron A

Team Pyto's entry at EDP's [Hack the Electron A](https://taikai.network/edpdistribuicao/challenges/hacktheelectron-a) challenge.

## tl ; dr
- [Challenge](https://taikai.network/edpdistribuicao/challenges/hacktheelectron-a)
- [Our Submission](https://taikai.network/edpdistribuicao/challenges/hacktheelectron-a/projects/cjwdktnzs2eo00930yj1irauo) (it's private, but it's cloned [below](#️-zapzap))
- *we passed to the finals*
- [Our finals pitch](https://docs.google.com/presentation/d/1nGbbnWcQl8Q-Gz-yiQBqLTW_ecX0PUhEq6i-hfuOdhc/edit?usp=sharing)



<h1 align="center">⚡️ ZapZap</h1>
<p align="center">
  We give the <b>power</b> to the people and make sure they <b>compete for reducing energy consumption</b> on a <b>macro</b> level.
</p>
  
## Idea
ZapZap is a multi-platform mobile app that works as a personal dashboard and has the following functionality:

- Get **real-time values** of power consumption, its history and **predict** final monthly price and tariffs
- Simulate the addition of **Photovoltaics** (PV) in the household
- Teach consumers how **Electric Vehicles** (EV) can change their life in a micro and macro scale
- Use **Behavioural Science** to make neighbours compete and reduce energy consumption
- **Detect irregularities** in energy spending and give owners piece of mind

## How does it work?

### 📈 Real-time monitoring and predictions

Give the user a visual dashboard that contains information on current energy consumption and includes the ability to travel back in time and visit different months and days, it is also possible to add notes for each day such as "Marcelo's birthday".

With this dashboard users can better understand **how** they are spending energy and understand how their consumption evolves overtime.

A prediction tab is also available for users to get estimates on their **monthly bill** and understand what is the best **contracted power** for them.

### ☀️ PV Simulation

For those customers that have the physical space for installing PV, we provide a simulator dashboard that takes into account:

- Available area
- Typical PV production for that city over the different months
- Energy selling conditions (estimated amount of surplus in the DSO grid)

And we calculate:

- Return Of Investment prediction
- Estimated profit per month
- Impact on current tariff

![average-production](https://i.imgur.com/Qt8B0uu.jpg)

### 🔋 EV for Sustainibility

As for EVs a new approach is proposed. If we take a closer look at the plot below, we see the existence of two energy consumption peeks at **lunch** and **dinner** times.

With the use of EVs a new trend could be stimulated, one that would benefit both individuals as well as suppliers.

- If consumers **charge** their EV during the **night** -> we expect an increase of power consumption during off-peak times (1am to 6am)
- If they then use the **EVs as batteries** during peak and super-peak times -> we expect a decrease of consumption during those times

This will, therefore be better for:

- EV owners who pay less for the same amount of energy
- Other consumers as the impact of peak prices is reduced
- Energy suppliers as the grid requirements become less demanding as a more homogeneous curve is achieved

![daily-average-consumption](https://i.imgur.com/Luozk8Q.png)

### Behavioural Science and Nudges

This [TED Talk](https://www.ted.com/talks/alex_laskey_how_behavioral_science_can_lower_your_energy_bill?language=en) reveals a study on human energy consumption that is as simple as it is powerful:

> Show people what their neighbour's energy consumption is like and let them do the rest

By including, in the monthly energy bill, the energy consumption of neighbours a company called Opower unleashed the competitive traits in people and was able to save consumers more than **250 million dollars**.

*ZapZap* includes a **monthly leaderboard** in which each consumer can see what their neighbours are spending thus bringing **gamification** into the energy market.

Further steps can be taken towards this goal such as the creation of **other leaderboards** such as:

- Amount of **power produced by PVs** -> Giving incentive for investing in PVs and also to take care of them.
- **Impact of EV** on the overall peak -> Fostering the use mentioned in the previous section.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=4cJ08wOqloc
" target="_blank"><img src="https://i.imgur.com/3n91iu3.jpg" 
alt="how behavioral science can lower your energy bill" width="500" border="10" /></a>

### Detect Irregularities

Looking at individual consumption history we can detect irregular periods of time:

- **Short** periods of **little** consumption -> days out
- **Long** periods of **little** consumption -> typically holidays away from home
- **Short** periods of **high** consumption -> many explanations but most are predictable by humans (warmer or colder days, parties, ...)
What can we do for users with this information? Simple, we can detect these irregularities and warn them.

- If a consumer is on vacation away from home and a power surge appears that may be due to a burglar or someone stealing their power.
- If parents are away for a few days and a surge is detected then maybe their teenage sons are trowing a party
- Whichever the reason, **we give consumers** the **comfort** of knowing that they will be notified when unexpected events are registered

![full-consumption-history](https://i.imgur.com/kfa9kst.png)

### 💡Progress
Thus far we have completed a thorough analysis on the datasets that served as background and inspiration for the design of the ZapZap mobile application. We have also automated the cleanup and extension process for raw datasets into complete ones that have all the tariff, holiday, season time, and more. All of this is accessible through this repository's Jupyter notebooks.

 ## Authors

- [André Cruz](@ndrefcruz)
- [António Almeida](@antonioalmeida)
- [Miguel Ramalho](@msramalho)
- [Thiago Munhoz](@MunhozThiago)
- [Xavier Fontes](@xfontes42)

<p align="center">
  <i>Brought to you by</i><br>
  <img src="https://i.imgur.com/BztzEUP.png" alt="pyto"/>
</p>
