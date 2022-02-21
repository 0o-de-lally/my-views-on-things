

# Why Teams

People have been wondering: why do we need "delegation", and why should we pay more rewards to Carpe?

TL;DR: I think these begin to solve the sustainability of participation; recruiting.


# The Problem

The only purpose of organizations is recruiting people. Everything else gets sorted downstream of that. High-impact workers that come together and stay together eventually settle on a product, on management, on financing, etc. Smart high-impact workers don't even consider organizations that cannot sustainably recruit new high-impact people. This is the typical failure case of companies, institutions, and blockchains.

I think these propositions are axiomatic, and not meaningfully contested.

I submit that the economics problem of blockchain networks with "free mining" is that they simply don't work at recruiting once the network is past bootstrapping. They don't survive as a vibrant ecosystem. This only worked once: Bitcoin when it was a monopoly.

In free-mining games (if left unaltered) there's no hope of catching up to someone who was in Genesis. This makes smart people feel foolish, and so they don't participate.

Free-mining however is the only pattern that affords a degree of regulatory safety, a big reason 0L genesis members picked it.

At 0L we spend a lot of time fixing free-mining instead of creating technologies and applications. It's a tradeoff we made and the hope is that this sets us up for long term success. The majority of the work I have contributed to 0L is to counteract the dysfunction and disincentives that are inherent in free-mining, proof-of-work networks; Designing "The Game". Community Wallets is one example of such a design, and a powerful weapon against free-mining. 

Working on The Game doesn't always yield fruit. It has diminishing returns. It distracts resources from technology, applications, marketing, etc. And it requires maintenance, as The Game is interactive. It requires in-flight updates which are often contentious. 

The Teams proposal is one such change to the Game. And once approved it will still require more work, more iterating on The Game.

The process of debating Teams (and not making great progress at that) has put us at a crossroads:

* a) spend time to iterate on The Game so it perpetually includes new people, or 
* b) freeze the current stakes, the game is fine, let's push (somehow?) to get wider recognition and use.

To me it's obvious option B is a trap, it ultimately fails. And personally I won't spend time on something that is obviously going to fail.

The text below explains why I think we still need to spend time on Plan A, and why Teams is the best shot we have right now.


# Decision Matrix

There are two axes to inform our decision about Teams.



* Carpe end-user adoption
* Delegation


# End user adoption

The first fork in the road: the community needs to decide if Carpe is an important growth vector.

That is: is it fundamentally important to have end-users with a desktop GUI client installed, that can serve as not only a wallet, but a gateway or browser of Web3 apps? 

This is not an obvious "Yes". There may be other cheaper and more effective user-growth and engagement tactics.

Plus the carpe-as-a-rocket strategy is proving to be somewhat elusive. After a lot of energy spent on fixing the UX, Carpe is still growing very marginally. 

There are other indications that people have lost interest or faith in the carpe-as-growth strategy.



* We don't provide a forum for Carpe users; we never poll them for opinions on changes to the network. 
* We have inaction at a "Make Whole" upgrade to solve the math error with Carpe. 
* And the Teams proposal doesn't get much discussion.

Teams would be a decisive commitment to end-users. It would mean more meaningful sharing of subsidies and future transaction fees with them. The higher rewards are necessary, afterall we are changing the 0L security model so that it explicitly depends on Carpe users. The validator set ultimately will be chosen by the end-users.

There is risk in that. Carpe is a bet. If the network decides to double-down on this bet we need to be proactive and urgent about it. On the other hand,  if we have lost conviction we should drop it. 

TL;DR: Vote YES to be proactive on Carpe, or  NO to move on.


# Delegation

Delegation of consensus votes has important benefits such as decentralization, having the entities who write to the ledger (Validators) be picked dynamically.

That's a deep rabbithole, but for now I want to highlight the importance of Delegation for community building.

In practice, when it works it allows more people to join the game in different capacities, at different moments in time. It recruits. It allows new people to catch up to early players, to feel they have agency. If done right it allows smart high-impact people to attract new ones.

There are three scenarios possible for the 0L network today with respect to delegation:



* No Delegation - The current validators (and distribution of coins) remains roughly the same in perpetuity.
* Delegation by Stake - implement a proof-of-stake model, and create delegation, much like Cosmos.
* Delegation by Tower - an 0L-native proposal to create delegation.


## Option 0 - No Delegation

I think this is a non-starter. All BFT networks have some sort of delegation scheme. It shakes things up, and as such it's uncomfortable for rent-seeking node operators. That's a good thing.

Current 0L validators are in an illusory comfortable position. It seems many have the expectation that if they drag their feet on Teams, the coin distribution and total supply get closer to stability, and their positions are more secure.

This is nearsighted. A network that freezes, is a network worth exponentially less than a network that is dynamic.

The failure case for 0L is: a Carpe new recruit joins, but after observing the firmly distributed stakes (by people contributing little work), they decide not to contribute. They don't even spend time looking around. They won't see the Community Wallet programs, which powerfully counteract the free-mining problem.

In short: a new recruit that sees rent-seeking will at best opt to be a rent-seeker. Worst case, if they are sufficiently resourced they leave and create a hard fork.

Voting "No" to delegation is a vote for rent-seeking, for feudalism.


## Option 1 - Proof of Stake

Though every known permissionless BFT chain has PoS delegation there are some serious tradeoffs to it.


* The dynamism favors capital, and entities  that can accumulate capital (e.g. exchanges).
* The delegations compete with each other for finite capital ("delegation wars"), not for new users.
* Issuance (inflation) schemes dilute end-users in favor of unproductive capital.

It's no wonder that these PoS schemes are especially attractive to venture-funded blockchains.

0L always has the option to do a vanilla PoS game. But I think it would lock us into the same-old-same-old patterns of blockchains.

I think we can do better given the types of stakeholders we currently have (and plan to attract).


## Option 2 - Delegated Towers

The principal innovation of 0L is creating a novel sybil-resistance technique which is acceptable for bootstrapping a BFT consensus network: Delay Towers.

This is an 0L invention. Not seen anywhere else. It has some really special properties.

However, inventing a "delegation" scheme with Towers has been a challenge. It's still a (fun) research puzzle. And will require some experimentation.

[You should read the spec in detail](https://github.com/0o-de-lally/libra/blob/teams/ol/documentation/teams/about_teams.md). But in summary: Validators can keep building a single tower on their own, or recruit people to "team" together with their towers. The Collective Tower, now becomes the metric by which qualifying for validator set and consensus.

It's a pretty exciting new invention in sybil-resistance for blockchains.

But we shouldn't do it just because it's shiny.

It has important properties:

* No coins are needed to participate. No need to pay for anything.
* The protocol shares a greater part of the rewards to end users.
* The wider community of miners participates in selecting the validator set. They have agency.
* It favors the people who show up, use our tools and not the people with capital

Perhaps more importantly, Teams combines delegation with recruiting installation of Carpe, where PoS and No-Delegation, doesn't necessarily.


<table>
  <tr>
   <td>
   </td>
   <td>No Delegation
   </td>
   <td>PoS
   </td>
   <td>Tower
   </td>
  </tr>
  <tr>
   <td>End-users Needed
   </td>
   <td>N
   </td>
   <td>N
   </td>
   <td>Y
   </td>
  </tr>
</table>



# Alignment with Econ Principles

Otto wrote the guiding principles of the Economics for 0L: ["Futureproofing the Economics of Blockchains"](https://0l.network/2021/11/16/future-proofing-the-economics-of-blockchains-pts-1-2/). 

The Teams proposal is  compatible with the principles outlined.


## Don’t Eat Your Seed Corn

Community wallets are not affected by Teams. Assuming donations remain in place, the community wallets get funded at the same rate.


## Produce consumer surplus

Teams is neutral on creating surplus to end-users of applications. There's no increase in transaction fee cost from from implementing teams. 

While not strictly "consumer-surplus", Carpe users will at some point be users of applications, and/or sponsors of new developments and this will create value for other would-be application users.


## Maximize the correct resource

The resource 0L tries to optimize is labor. Aggregating productive workers to a Schelling Point. The name "Teams" was chosen specifically to connote the idea of work. If you read through the specification, Teams doesn't only serve for consensus purposes, but it serves as an identity for working together. Much of this work may initially be around social consensus formation, communication, and recruiting. But later it serves as a platform for crowdsourcing, and other DAO experimentation.


## Integrate with the world

Teams is neutral on the Integrate principle. The tokens and work generated are still only in service of the platform. Teams makes no claim about the types of applications or general utility of the blockchain.


# There are Winners and Losers

The winners are people who are visible contributors, and share a large amount of their rewards with end-users.

The losers are validators who expect to be passive. There may be different reasons why a validator may have had that expectation. And that is one of the predominant issues with "free mining" protocols based on some proof of work.

There's a special case where the algorithm makes human teams lose. 


# The Objection to Collective towers: Sybils

It's also possible that our algorithms don't initially disincentivize "synthetic teams" of people with large compute resources. That is, there's a risk the network devolves into a proof-of-work hardware race.

That's because combining tower work (into a "collective tower")  breaks one of the principal guarantees of Delay Towers: that gaining more weight in consensus cannot be parallelizable. Meaning, with teams you can use one or more machines.

This is a problem. It's especially a problem for the early stages of Teams, where more issuance of coins (e.g. the validator set shrinks) can be more easily scooped up by synthetic teams.

Different proposed solutions to the "ratchet" algorithm and/or including on-chain permission trees, I think can give us some more comfort that the roll-out of teams isn't exploited. There can also be a kill-switch for the rollout.

It's important to note that Phase 1 of teams is a soft launch for people to get familiar with the dynamics. Phase 2 would then implement the economics and consensus changes, and there are different ways of rolling it out.

But my position is that if we think Carpe is our growth strategy, and we work to get a 100% failsafe solution for "synthetic" Teams (which is impossible), we will miss the local and global opportunity.


# An Objection to Teams: Alienating Institutional Validators

Another objection I have heard is that institutions who are running validators are anxious about what that means for them. And that's reasonable. Institutions may observe "delegation wars" on other networks and think it's a fulltime job.

I think it's a mistake to think that Teams are necessarily competing against each other. One feature of the validator set is that all validators share the rewards equally. Once you are in the validator set, there's no advantage of being first. So in that sense the competition is between Teams that are engaged with the community, and ones that are not.

I think the bar for engagement is quite low. Being identified and participating in occasional meetings will be enough to separate you from the passive validators.

And for a non-profit organization who does not have a dedicated blockchain team, the administration of the team can itself be delegated. I for example would happily manage the operations and represent for one or more non-profits, and hustle to make them successful.

It's not obviously necessary to change consensus algorithms if there are institutions we care about, and we can ensure their success through offline coordination.

So long as there is a dedicated core group of profissional validator operators which can lend their time to administration of an institutional Team, I believe we can guarantee the success of non-profits in our community.

Let's just commit to making them successful, regardless of mechanism.


# Making Decisions

I want to be on record saying that I was a voice for including Delegation at 0L's Genesis. For a number of reasons the genesis group decided against it. That decision was about go-to-market timing, versus the research that was left to do on Tower delegation.

And upon launching the network, we started to get feedback from our institutional validators: "why aren't validators DAOs". And with that feedback I submitted a pull request Nov 24th 2021, for a delegation scheme: Teams.

So the decision has come up again with this upgrade proposal.

If the decision is to abandon Carpe as a growth strategy, we need to do that with finality. And we could be very successful with shutting it down, assuming we have a compelling strategy and vision. But indecision on this equals failure.

If the network votes "No" then we will need leadership from someone with a vision of how we grow without Carpe (and without delegation). I personally don't have any proposals for that, and the alternatives I've outlined above don't persuade me.

Voting "Yes" for the proposal doesn't mean implementing a fully-formed Teams without any mistakes. Phase 1 is for testing, but it also means committing to a vision that includes Carpe and rewards flowing to more than 100 people. A "Yes" vote doesn't mean getting it right the first time, but is a commitment to being proactive. 


# My View

Teams is exuberant. It's a new and plausible idea in a domain (delegation) that sees little innovation. It's also a different vision of Proof-of-Stake. If it works, it's going to be a lot of fun. Observe the success and dynamism of other networks with end-user miners (e.g. Chia, with 500K miners participating). 

This is something exciting to aspire toward.
