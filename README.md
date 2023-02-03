# SootPut
SootPut is a solution for tracking and rewarding Climate+ action by individuals

Interface: A mobile friendly web application that prompts users to consider Climate+ opportunities in their day to day lives.

There are three contexts:
<li>Food:
Consumables that relate to health and waste

<li>Home: 
Infrastructure and Durable Goods

<li>World: 
The enviornment outside of the home

![High-Level](https://github.com/davepander/sootput/blob/main/img/SootPut%20App%20v.1.png)

As data is recorded by users, the inputs are processed by the SootPut backend algorithms to categorize and correlate each action with 
a Carbon impact score. Over time, users will be able to see their own progression relative to themselves and to regional and national averages.
<p>For instance, the average America household annually generates about 48 tons of Carbon impact. After inputting some basic information about diet, 
sq footage of home, and commute behavior, there will be a preliminary score compared to national averages.

As more data is captured, the users scores adjust relative to their personal baseline.

<br>
<B>Infrastructure</b>
<p>Public facing datasets will be stored in Tableland.
Datasets that relate to calculating the carbon impact of actions 
will be both on and off chain. </p>

<p><B>Tableland</b> will be used for Public data:</p>
<li>Computed values and scores across time for users.</li>
<li>Data Sources and their status, accuracy, validation histories</li>
<br>
<p>For Private data:</p>
<p>We are evaluating
<b>Ocean Protocol Compute-to-Data</b>  for 
User data relating to commercial purchases, any telemetric data from
transportation or commuting, environmental data relating to property, any
other PII will be encrypted and only available to the approved algorithms
</p>

As our algorithm code is based in python, we are also evaluating 
https://www.apeworx.io for interfacing with on and off chain algorithms.

For our front end interface, we are exploring https://www.bildr.com and their potential 
support for the tableland libraries.
<br>
<p>While individual Climate actions do not fall under current models for defining, registering, validating and
converting to Carbon Credits, we still plan to incentivize certain actions (that can be verified) with Carbon credit tokens.
These tokens will be purchased through Toucan and ideally correlated with actions in the SootPut platform.</p>
<br>
We are in discussions with organizations to create more verifiable actions that can be rewarded with Tokenize Carbon Credits.
One such example is tracking participation in trash-pick-up competitions. There are already prizes offered to winners in these instances, and SootPut plans to issue all participants
"credit" in their dynamic SootPut Climate NFT as well as appropriate Carbon credit token allocations.
https://docs.toucan.earth/toucan/bridge/tco2-toucan-carbon-tokens
