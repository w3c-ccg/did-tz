# did-tz
We would like to open up the design process for did:tz to a more open and consultative/deliberative conversation in the open to better serve the Tezos community.

## Include Link to Abstract or Draft 

Draft spec [here](https://did-tezos-draft.spruceid.com/) (ReSpec)

## List Owners

Wayne Chang, Spruce, @wyc
Francois Guerin, Gravity.earth, @Francois-Guerin-Gravity

## Work Item Questions

### Explain what you are trying to do using no jargon or acronyms.

We would like to open up the design process for did:tz to a more open and consultative/deliberative conversation in the open to better serve the Tezos community.

did:tz is a multi-modal DID method design with many offchain, on-chain, and side-chain/L2 use cases in mind.  A valid Tezos address (controlled by a private key from any of 3 supported curves) can control an "implicit" DID document (generatively created from the address like a did:key), an "onchain" DID document (published via smart contract on any Tezos ledger), or have "patches" applied to it that are published and governed by a closed network or authority (including, for example, a sidetree network).  In particular, this third option has not been specified in any detail, and we would be particularly curious to hear from implementers of such systems before further specifying it.

2. How is it done today, and what are the limits of the current practice?

There are already users of the first two kinds of did:tz mentioned above, and work has begun on at least one system that would utilize the third. For this reason, design and specification are timely.

3. What is new in your approach and why do you think it will be successful?

We think that a method that specifies the three "layers" of resolution in common and outlines upgrade paths for moving from the simpler to the more complex forms of DID without rotation or additional set-up will, in time, simplify and strengthen the options available to relying systems.

4. How are you involving participants from multiple skill sets and global locations in this work item? (Skill sets: technical, design, product, marketing, anthropological, and UX. Global locations: the Americas, APAC, Europe, Middle East.)

We are hoping that by opening up our DID method design process to be more open, we will hear from business and technical voices far and wide, particularly since the Tezos ecosystem is fairly international and open-source in nature. If many weeks pass without input, we may do active outreach via the Tezos community and DIF.

5. What actions are you taking to make this work item accessible to a non-technical audience?

We have tried to craft a did method specification draft that is accessible and welcome PRs if it can be made more accessible.
