# 2021 ~Weekly~ 6 weeks PM/PO Sync for ~CMS Export Build~ Content Release

## 9-7-21

### Agenda

- How many nodes are published now? 
- What is the general timeline and roadmap for node publishing? 

### Notes

- Health care systems node updates
   - Stan: We have 27 health care systems left (24?). Expect the standard requirements for each of those to be 100-150 per system. 
   - Mike C: Let's update the estimated notes per health care system on the Google spreadsheet? 
   - Stan: Each system has a required number we push, and then when the VA content editors come in they do add more. When they finish it's around 200-250 nodes. 
   - Dave: PAOs are really just beginning to get involved in filling out the rest of the info. We're about 2-3 months away from getting a really good idea of what our baseline will be and what our growth pattern will be. 
   - Mike C: Right now we have the estimate in the spreadsheet as 300 min - 600 max. If that's way off base, let's update. 
   - Dave: Let's hold off on updating that for now. 
   - Mike C: Is there a place we can go to check the number of VAMC systems that are published? In the CMS? 
   - Adrian: Yes I've been updating that every week — VAMC published
- Vet centers node updates
   - Dave: There are unpublished nodes in the CMS now for district 5. Nodes per vet center = at least 10. Not a significant number. Second week in October we'll be doing a kickoff for district 1 which will mean an additional 80 vet centers. Hope to publish those around end of year.
   - Overall estimate for vet centers MVP nodes is in 1k-5k range
- Campaign landing pages, resources and support 
   - Mike C: still relatively small content wise? 
   - Beth: yes. Occasionally we create content that we decide not to publish. Does that count as a node or not? 
   - Mike C: the part that is a constraint is the content build, which only builds things that are published. 
- Overview from Mike C
   - Started the year around 4,000 nodes and now we're up to 20,000 - published! 
   - Will continue supporting up to 50,000 and are on track to stay within that limit for the foreseeable future 
   - 


## 6-15-21

### Standing agenda

- How many nodes are published now?
- How many nodes have we successfully tested?
- What is the general timeline and roadmap for node publishing and technical iterations to support node publishing between where we are now and that limit?
- What is the current time to publish?
- How do we expect in progress or upcoming work (node publishing and technical iterations) to impact time to publish?

### How many nodes are published now? 
- Jeff: 14,901 nodes and 218 active users
- [Google Spreadsheet for node publishing estimation](https://docs.google.com/spreadsheets/d/1pa0EgHuOXINvool4QHjV3lIDyYf-p9JRr8z1AuW4HFE/edit#gid=0)
- [Expected high/low vs real world](https://docs.google.com/spreadsheets/d/1pa0EgHuOXINvool4QHjV3lIDyYf-p9JRr8z1AuW4HFE/edit#gid=785739954)

### How many nodes have we successfully tested? 
- Megan: CMS and build pipeline can support 48k

### What is the general timeline/roadmap for node publishing? And for technical iterations to support node publishing between where we are now and that limit? 
- Jeff: Should we update the estimated node publish update? Actual publish seems to be a bit lower than what we estimated
- Stan & Dave: Not yet, but in August yes we will be able to update estimated node publish counts
- Megan: 48k capacity takes us at least to September, probably safely through end of year
- Mike: It looks like we've successfully squeezed a whole bunch more performance out of this existing infrastructure. We've got some headroom here in terms of pure capacity — can you publish nodes, will the system die if you try to publish nodes. So now is a good time to be doing some more thoughtful and proactive work. 
- If there are things (translation, CLP, etc) that are going to eat up a lot of nodes, bring it up to this group. The resources are still finite. 

## What is the current time to publish? 
- Around 10 min, give or take
- Scheduled releases hourly on weekdays (ish)

## How do we expect the time to publish to change? 
- As we reach 48k nodes, time to publish will increase towards an hour — but will not exceed 
- CMS Core App team would like to meet and coordinate with technical engineering staff of Public Websites and other teams so that we can work together on improvements and make sure everyone has capacity to support that

## 3-26-21

### Topics to discuss

* Content release schedule increase 
* Broken link validation
* Tracking conent build times (FE team) 

### Notes

* Content release schedule increase 
   * Oksana: next frequency promised was 8x/day, but that puts us outside of working outs. Question: what should we do with the next release? Switch to 6x/day? Content releases can be manually triggered at any time anyway
   * Megan: we can add an 8 AM deploy no problem (or other time after hours) but FE Tools will not be around to troubleshoot it
   * Broken link conversation is also related 
   * Mike: CMS support desk is online at 8 am - commitment is not that issues will be resolved by next release but that they will be responded to. 
   * CMS Tier 1 support can fix some broken links
* Broken link checking
   * We warn editors when they're trying to save a node if it has a broken link, but there are some situations where we aren't able to block people
* Content editor culture and notification system 
   * Need to set stage for detailed notification system for content editors 

### Action Items

* Megan set up meeting with CMS team to discuss deploy failure expectations and responsibilities 
* Comms notes
   * Still iterating on this
   * Time to respond to issues does not equal time to resolve issues 

## 3-12-21

### Topics to discuss

* Content Release - Next increase schedule & comms
* Full Site Deploy timing effects on:
   * Hourly deployment schedule
   * On-demand Content Release for Facility Operating status


### Notes


* Next content release frequency increase - 3/16 - 4x/day 
  * Need to define final times for 4x
     * Phase 2 - four times a day - 9AM, 11AM, 1:45PM, 4/5PM EST Mon-Fri **[Megan / Oksana to connect on exact timing on Monday 3/15]**
* FE tools team is looking at content build separation. Should be in Dev in a week or two. Anticipated launch to Prod  - April.
* On-demand Content Release for Facility Operating status
 * When editor updates Facility status - that triggers Content Release to VA.gov
 * If there was an incident that occurs at the facility during the Full Site rebuild, potentially life-saving situation could be held up by the full Site build.
 * We're dealing w/ emergency situation that would need to get out rapidly as a partof a Content Only build. Build for it, hopefully never us it.
 * We could in theory always cancel vets-website deploy in an emergency situation.
  * Content editors won't be able to communicate the urgency up to OCTO-DE every time it happens.
 * Option: editorial messaging, if you need to publish an alert between X and X, call Dave Conlon (?) 
  * Don't want to ocause anxiety in the field when this is a very edge case situation.
 * Separation of content build may solve the bottleneck between emergency messaging and full site deploy. Megan to check w/ the team on timing / options.


## 2-26-21

### Topics to Discuss
* Content release release timeline
* Continue scalability discussions from last week 

### Notes
* Content release release timeline 
   * VSP is ready to move to daily content release any time - this is good to go
   * Increased frequency beyond that should be messaged to content editors
      * Communication w/ content editors managed by CMS team - let's use this as messaging a win & testing our comms strategy with content editors 
   * Q: How do we communicate with content editors? Dlist? A: Yes
   * Dave: do we primarily need to message this to Pittsburgh? What about campaign landing pages? John: no concerns here, there aren't a host of other editors using the CMS on our end.
   * Expectation needs to be set with content editors that once you save, your content could go live 

* CMS team is continuing to build out tests and benchmarks to prove out the node count timeline more 
   * Oksana: we've gotten node counts re: VAMCs but not from Public Websites. Not sure if the latter would be significant enough to change the timeline estimates. 
   * John & Brian - clarified, we added the PW node estimates to the google sheet. Main concern/area to monitor would be Resources & Support 
   * John: Translation is something to keep an eye on 
   * Dave: What form translation will take is a really big Q 
   * Oksana: CMS Core App team should be extensively invovled in solutions around translation

* Should the frequency of these meetings change? 
   * Move to biweekly until end of quarter to stay in sync through quarterly planning
   * Expect to drop these meetings in Q2 and connect as needed moving forward

### Action Items 
* Megan & Oksana connect re: messaging to content editors 
   * What is VSP's conservative estimate for increasing frequency of auto-deploys? 
   * Does 3x/day mean 3x content only release, or 2x content only release? 
* VAMC & PW teams keep node count estimates up to date as they refine info (collab. w/ Oksana & Mike on these numbers)
* Megan cancel meeting series and update to biweekly
   

## 2-19-21

### Topics to Discuss 
* GraphQL vs CMS Export 

### Notes
* Mike: Ticket to document decision https://github.com/department-of-veterans-affairs/va.gov-team/issues/20165
   * Short version: CMS Export is fine, it's not necessarily going to reach parity where we need it to be in a way that's going to support the business needs. Scaling GraphQL is going to be a more effective way to deliver that functionality in the short to medium term. 
   * Looking at numbers from Facilities, VAMC, and node count targets, we believe that we can best meet that capacity using GraphQL approach due to improvements that have been made and benchmarking results that we've run and looking at known ways that we can scale 
      * There is still uncertainty around CMS Export and reaching parity with transformers 
   * That's the plan we're looking to move forward with to deliver this capability/capacity. Want to continue to coordinate regarding what those requirements are and flesh those out (node counts will be ranges, but we should continue to align as we learn more) 
* Dave: so we're sticking with GQL in the short term. What is the impact that decision has on shortening the publishing times?
   * Mike: This is all in service of scaling capacity and performance. The faster performance we have for any dataset of nodes, the faster that content can go out the door. I think what we're looking at is an initial hourly content only deploy, and FE tools has work that they're proceeding with to move forward with that. Simultaneously, CMS can work to fit more and more nodes into the given window. 
      * From there we can start to look at ... we have number of nodes & how fast it goes. How do we continue (in GQL & build pipeline) increasing node capacity _while also_ improving the speed? 
   * Other Dave Q: wiggle room. Part of the roadmap challenge is trying to determine capacity. We're going to be making bets about number of nodes, etc. Ex. tier 3 content we have _no idea_ how many nodes that will be. With anything we build in CMS it's not 1:1 page:node. So as we think about building new products, how much capacity wiggle room will we have? That will govern what we're actually able to deliver.
      * Mike: these numbers are estimates and ranges. Also, build times are estimates — real world is rarely the best or worst case scenario. We are starting with "worst case" so we can guarantee _at least_ that capacity. We are fleshing out benchmarking and fleshing out real world capacity. 
      * Ideally we want to get to a place where no one needs to count nodes. 
      * Dave: we don't know what we don't know. until we remove the node restriction, we're going to have to understand that risk and take it from there. 
* Dror: we are buying ourselves time by optimizing GQL. Realistically, I think the best long term solution is to do incremental builds. 
   * Intuitively, incremental builds are the end game. We need to buy ourselves 6 months or so -- and while we have that runway, we can work on incremental builds.
* Dave: so in the short term we're unblocked, but we still have a ceiling and we may run into issues with Tier 3 content or other. This buys us time but this is still a problem to be solved. Correct? 
   * Mike: Scaling will never be actually truly unlimited — we may have a cushion that is an order of magnitude. There will always be more scaling work, there will be additional approaches & implementations.
   * John: On Nick's approach, did we derive any value out of that experiment? 
      * Mike: Nick's multiple GraphQL was very valuable! 
* Michelle: Will publish time still be linear based on the number of nodes?
   * That's what the benchmarks showed so far, want to keep confirming though
* Dave: is the node count vs time a concrete trade off?
   * Mike: maybe? we can make that trade off to a degree
   * Dave: what if we need more nodes immediately.
   * Michelle: We're communicating the technical limitations of the system - that is why the benchmarking is so important, regarding what the system can reasonably accomodate given the current constraints 
   * Dror: we are far enough away that we have time to plan around this 
   * Dave: we are working on node estimates. but on the product side we need to back that up with actual data. we also need to work through what nodes can be sunset -- for example, events. 

### Action Items 
* Continue to refine node count estimates as more info is available from VAMC & other content editing teams (Oksana & Mike take point)
* CMS & VSP teams move forward work on optimizing GraphQL build times & hourly content release
* VFS teams stop working towards CMS Export <> GraphQL parity if they haven't already
* Continue conversation with this group next Friday 3/26

## 2-12-21

### Topics to Discuss
* Changes to broken link validation
   * Update from VSP on research
   * Out of scope for CMS Export release
* Status updates & timeline
   * What needs to happen by what deadline in order to stay on track for CMS Export release?
* What is a path forward for the unauth team (PW, Facilities) to be building new stuff on platform in GraphQL? 
   * GraphQL vs CMS Export 
   
### Notes 
* GraphQL vs CMS Export
   * This quarter GraphQL is being used in production on VA.gov until end of quarter
   * There are good results from GraphQL updates that improve scalability that will help scale to meet needs of Facilities & PW 
   * Current GraphQL changes get us from a ~4,000 node limit -> ~14,000 node limit (confirmed so far) 
   * CMS team continue to work on the node publishing timeline in collaboration with VFS teams - Oksana working with Stan, need to also connect with Public Websites
      * Vet Centers: 200 (nodes?) by end of quarter
   * CMS team has spent time this past week confirming that GraphQL can scale up to ~14,000 - will research how much higher this can go in coming weeks 
* CMS Export timeline 
   * Functional parity needs to be reached by end of Feb in order to meet the projected timeline of CMS Export by end of March
      * Facilities is on track to meet this timeline
      * Public Websites - will need to follow up with Brian next week
   * Would issues be build errors? FE issues that result in bad experience for FE?
      * Need to avoid build errors & isolate them to content only 
 * Broken link validation 
    * VSP: the level of effort of requested changes is not small
    * Mike: broken link risk as part of VAMC rollouts is fairly minimal; one-off broken links are more of an issue as the number of editors increase
       * Once we get to hourly content release, we can get fixes up & out the door faster. Improving broken link handling can occur after the move to hourly deploys.
    * Dave: Continue conversation offline. As we roll out VAMCs we roll out editors who are going to be going in and editing and making mistakes. We can come up with a short term solution or workaround. 
    * Decision: changes to broken link validation will happen post-MVP
   
### Action Items
* Oksana refine node timeline in collaboration with VFS teams - try to map this out to end of year (there will be a very large range in this based on strategy for Tier 3 content)
* Group: reconnect next week regarding scalability of GraphQL
* John, Mike, Dave, Stan, Oksana - discuss broken link validation next steps
* Brian & Michelle provide update on Public Websites timeline to reaching parity

## 2-5-21

### Topics to Discuss
* Status update from all teams
* Change management messaging with content editors

### Notes
* Status update 
   * CMS: working on exploring low hanging updates re: performance improvements to GraphQL. Next week early we will be reconnecting again with CMS internal team on broken link strategy. Will meet with VSP next week to talk about broken links more.
      * Will touch base with other OCTODE stakeholders on broken link strategy 
      * Connecting with VSP on CMS Export build improvements 
   * VSP:
      * Still cautiously optimistic on the latest written out timeline! The coming sprint is ambitious so some things will likely bleed over into the following sprint, but that should not put our velocity at risk significantly. 
      * Significantly learnings this week about scalability and where breaking points and bottlenecks are, so the level of uncertainty there is now very minimal. This is a big win.
   * VFS: 
      * Facilities: we have 3 issues that are ready to be picked up that resulted from the diff tool. Half of them are blocked by the arraysort ticket that are in progress. 
      * Public Websites: we have prioritized work on Campaign Landing Page. we did run the diff on that. Team started working on transformers fully today and will have more info next week. 
         * Potential risk area
   
   Dave: need to keep our finger on the pulse of — we're trying not to do too much drift or changes but we also don't want to freeze. Do we build a GraphQL query on that or do we hold on that? 
   Dror: bottom line is — in theory we're a month away, anything we can do to limit GraphQL is helpful. 
   Michelle: we actively deferred a couple changes this week expecting this release soon, so that is currently part of our decision making. 
   Oksana: as we launch CMS Export, we are keeping GraphQL in parallel 
   Dror/Megan: keep things in parallel until this is live in prod + a week for risk mitigation
   
* Change messaging for content editors
   * Publishing every hour is a big change! CMS has historically handled the messaging to content editors. Is that still the plan here? 
      * Dave: VAMCs and Pittsburgh are the ones being most vocal about this need. Communication should come from CMS if that works for other teams.
      * CMS team is willing to take on this communication. Need to stay coordinated on timing. 
* Broken link change 
   * Mike: originally talked about doing a threshold/limit of broken links. Dave suggested a pattern matching allow list. Update is that we are proposing to do both — there's an allow list for new content purposes, etc, and also having a threshold that's higher than 0 based around having more pages in the system, more active editors, more frequent deploys. 
   * Dave: product side is indifferent — this is more of a platform decision. Platform has a process in place regarding policy for broken links on VA.gov. If platform goes with a threshold approach that is fine, my product owner interest is primarily in the allowlist because that is what I know I will need.
   * Dror: Need to double check with Rachael but would largely ask product stakeholders for this decision.
   * VSP will review this proposal & provide level of effort next week 
   
Action Items: 
* Megan be sure that VSP is coordinating with CMS on deploy tickets and rollback plan
* Brian to provide an async update early/mid-next week about PW's discrepancies and rough level of effort to work through those

## 1-29-21

### Topics to Discuss
* Status update from all teams
* Continued build errors
   * What caused this week's issue? 
   * How can we better manage this moving forward?
* Handling of broken links in VA.gov build
* Change management messaging with content editors

### Notes

Handling of broken links
* Proposal: don't block builds due to broken links in content layer, with threshold 
   * Generate public CSV about broken links - must contain paths that generated broken links
   * CMS team will be notified in Slack and begin help desk triage based on CSV triage
   * V1 is hourly autodeploy during business hours - 8-8 M-F hourly
   * Consider: If the threshold is reached and the build breaks, can there be a manual override?
      * Ex. when something is being shared with content editors (dual state) and there's no impact to Veterans
   * Need to consider long term vs short term solution
      * Warning content editors when they have a broken link 
      * Long term solution is that CMS help desk doesn't triage this, notifications are sent to content editors 
   * Next steps: 
      * Identify threshold for broken links to break build — does there need to be any threshold? 
         * Less important is the number of broken links, more important is the location of broken links
      * Identify SLA for CMS team fixing broken links
      * **Continue conversation including all people needed**
      * VSP discuss level of effort for implementing this potential solution
   * Questions: 
      * How often is the broken link CSV sent? Hourly? Or daily? Answer: CSV should be published every hour, and Slack alerts will be managed by CMS team 
      
Status updates
* VSP
   * Discrepancies are in good shape
   * Continued concerns about build errors and scalability, working hard to resolve these uncertainties
* Facilities
   * 11 discrepancies identified with the JSON comparison tool, have been blocked by the broken build
* Public Websites
   * Working towards reaching parity — hoping by next week we've reached parity
   * 5 days was initial estimate 
* CMS
   * Broken build issue should be fixed!
   * Broken link updates above
   * Scalability research is ongoing - should have some info by next week
      

## 1-22-21

### Topics to Discuss
* Status update from VSP FE Tools
   * Build failures caused by Erie release (circular reference)
   * Comparison tool will be sent out today or Monday [issue](https://app.zenhub.com/workspaces/vsp---frontend-tools-5fc9325744944e0015ed1861/issues/department-of-veterans-affairs/va.gov-team/13762)
* Change management messaging with content editors
   * CMS team will take point — what do they need from other teams?
* Timing for hourly auto-deploy
   * Hourly 24/7, or within "business hours"?
* Circular reference errors in cms-export build [issue](https://app.zenhub.com/workspaces/vsp---frontend-tools-5fc9325744944e0015ed1861/issues/department-of-veterans-affairs/va.gov-team/13762)

### Notes

* Build errors with Erie release: circular reference errors.
   * System publishes are supposed to be "just" content releases, and are supposed to scale up to 1/day
* Build failure this morning. Broken links will cause a build failure. The dozens of new content editors will be producing broken links. 
   * Linking content and app builds together will continue to have a massive risk of links breaking the build
   * Example today: content editors are learning by doing, one person updated their "about us" page and moved it to published even though that wasn't yet ready 
* What types of build errors do we expect to see? How can we document that & plan for that risk? 
   * Mike should talk to Steve Wirt about links — [design doc](https://github.com/department-of-veterans-affairs/va.gov-team/blob/7785e85e3c68452857ec510ed5d2cb22bbd5f6cc/platform/engineering/design-docs/2020-09-27-broken-links.md)
   * What should happen with broken links? What does the business want to have occur? **Need to have convo about this
   * Breakout convo re: build errors
      * What errors are likely to come up with content publishing? With changes to the data? etc? 
* When can we continue to decrease the uncertainties? 
   * JSON comparison tool is ready & engineers should be able to use that to decrease unknowns over the next few days (yay!)
* What about a GraphQL freeze? If we implement a freeze on 3/1 for 2 weeks, how does that impact POs & teams? 
   * Facilities team is not making changes to GraphQL without also addressing those changes in CMS Export
   * Teams _either_ need to freeze, _or_ need to own the parallel changes to CMS Export. Facilities is doing this, need to confirm with Public Websites & CMS teams. 
* Timing of hourly auto-deploy — have folks discussed this? Is there an easy hour? 
   * CMS provides support 8-8 M-F 
   * Go with that, and reconnect for V1.1 
