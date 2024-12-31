# Alexandria

Open source, all purpose FREE Research Magazine, backed up with Blockchain technology.

>[!IMPORTANT]
>## WHY?
>This project aims to lead the scientific comunity to a higher level of virtous cooperation cycle.
We acknowledge that today, the scientific publication market is monopolized by a few agents, scientist are under-compensated for their roles as authors and reviwers, and accessibility to papers is limited or even restricted. All these characteristic are related and fundamented by the current system. The proposed solution then is a radical revolutionary change.
>
>## HOW?
>To drive the system into a better democratic state, this project aims to accomplish the following goals:
>1. Ensure **free of charge and free access to all the papers in this platform**. In other words, being a Reader has no conditions.
>2. Ensure a Peer Review validation of the published work, backed by the Blockchain technology.
>3. Enable **Authors** to **recieve direct profit from their publications**.
>4. Enable **Reviwers** to **recieve direct compensation** for their job.
>5. Ensure the only condition to become an Author and or a Reviwer is a criteria based on accademic competency and merit.
>6. Ensure that the rates assotiated to publish are established by the market.
>7. All the logic and the code is Open Source.

## Dynamics

Below we explain how the system works from the three possible perspectives: Reader, Author, Reviewer.

### Reader

The simplest way to be involved in the community by consuming the articles. 
- We require the user to create an account to certify it is not a bot.
- The Reader can search for articles across the whole database without restriction and download (read) free of charge as many as it wants.
- There will be a daily download quota to prevent overload. 
- Multiple downloads of the same article will not count as new downloads to prevent biasing the article read-popularity.

### Author

If you want to publish your work in this platform, you will have to become an Author. In order to do so you will have to provide further information that validate your qualifications, and nationality such as ID, college title, etc.

The Author pays the fee to start the Peer Review process which in turn enables it to complete the following steps:
1. add other authors,
2. select the contact-author,
3. upload the draft v1 as pdf,
4. write title and resume,
5. add topic tags,
6. select the 3 candidate Reviewers.

At this point the smart contract has began and the authorship of the text is preserved for as long as the process is `in-progress`. The reviewers are sent the title and resume to accept or reject being part of the review. If the reviewers reject, the contact author will be requested to provide another candidate. The time window for all 3 reviwers to accept is 14 days (continous), if in this time any of the reviewers haven't accepted, the smart contract gets `canceled` (the pdf content get deleted and the authorship preservation revoked).
If all 3 reviewers have accepted, the contact author must provide the funds to pay the reviewers, which are frozen until the process reaches its end. The author has 2 business days to do this or the contract gets canceled.
Upon acceptance, the draft v1 text is sent for the reviewers. After the review period is over they will have to return / upload their comments and their veredict if the draft is approved or rejected. In case the draft is rejected the contact-author will be requested to upload a 2nd version with the changes. There will be 2 corrections considered, i.e. up to version 3. If the later gets rejected the contract gets `canceled` and the process finished. If the majority of the reviewers approved the draft then it gets `published` and the process finished. It must be highlighted that the corrections are not mandatory unless the draft is rejected, when the reviewers are ask to decide on the draft they judge the draft without the modifications they suggested. This means that approving the draft means approving it as is.

TODO: add diagrams

- what happens if corrections are contradictory? this will have to be solved outside of this platform but within the period given to upload the new version.

- can a company / organization be an author? yes, but all the members have to have their own account.

>[!IMPORTANT]
> As an Author you will hold the rights of authorship but you resigns the rights of distribution, which are explicitly made free of access and download from this platform.

### Reviewer

The role of the reviewer is to act as an expert unbiased validator of third party work contributing to the Peer Review process.
Because of the nature of this role, becoming one requiers higher levels of merits, proofs and validations than the Author role.
There are however two paths to become a reviewer, there is the *organic path* and the *burocratic path* [TODO: replace by links to their own pages]. The organic way is straight forward and can be thought as an upgrade from the Author role, essentially once an author has reached X publications of a `[science][branch]` in the platform they will be offer the opportunity to create their Reviewer profile. Under other circumstances such as migrating from academia, they will have to validate their expertise on the subject by providing evidence such as links to published articles on well regarded magazines, university statements, etc.

As a Reviewer you will have one or more topic groups (branches tag) that you are eligible to review. For example if your `science = MATH` and your `branch = TOPOLOGY` you will be elegible to review any article with those tags and `topic = *`.
As hinted before, reviews are paid by the contact-author, and is the Reviewer who sets the price of it. In the Reviewer profile you can set your fee, which holds and applies to the whole Peer Review process, i.e. if your fee is 20 U$D and the process takes 3 versions, you will be paid 20 U$D (in ETH/BTC/ etc) once the process is completed. If the process required only one review, same as above, the payment is gicen upon completion. The fee that will be set in the contract is the one recieved in the offer of acceptance. If the Reviewer changes the fee the modifications will only apply for future contracts.

With the profile created the Reviewer can be found by Authors throught different queries: by name, tags, affiliation, etc. They will also be part of the Random Asignment Pool (more on that later).
If an Author has selected you as a candidate, you will receive an Offer of Acceptance containing the following information:
- your reported fee as seen and accepted by the author,
- the work title,
- the draft summary,
- the version of the draft,
- the tags of the draft.

You will have 2 days to accept or decline the offer.

>[!IMPORTANT]
> The Reviewer has the following responsabilities:
> 1. Ensure the draft is not in another indexed database.
> 2. Ensure it is not a copy of another work.
> 3. Enforce the minimal common format.
> 4. Validate the quality of the draft content.


## Market

As implied by the user dynamics defined above, there is an emergent market from the synergy between authors and reviwers.
Unless the community votes otherwise, this platform will be ads-free and will survive only due to the Peer-Reviwes dynamic contributions.

The cost of starting the Peer-Review process is used to support the expenses associated with the BlockChain, the maintenance of the Server, the compensation to contributors to this code base and the dividen payments to the authors.
The fee shall be an accessible amount world-wide, stable with low fluctuations; we will provide a process to update the value afterwards, at first it will be 10U$D.
The fee is paid per article draft, regardless of the number of authors attached.