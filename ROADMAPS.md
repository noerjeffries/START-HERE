# Roadmaps


1. [Latest Development News](https://github.com/WorldBrain/START-HERE/blob/master/DEVELOPMENT_ROADMAP.md#latest-development-news)
2. [Next Milestones](https://github.com/WorldBrain/START-HERE/blob/master/DEVELOPMENT_ROADMAP.md#next-milestones)
2. [Feature Roadmap for Webmarks](https://github.com/WorldBrain/START-HERE/blob/master/DEVELOPMENT_ROADMAP.md#feature-roadmap-for-webmarks)
3. [WorldBrain's 10 Year Roadmap](https://github.com/WorldBrain/START-HERE/blob/master/DEVELOPMENT_ROADMAP.md#worldbrains-10-year-roadmap)

<br>

## Latest Development News

To stay updated about WorldBrain's progress, check out our 2-3 minute sprint report video and the extended blog post, we publish every 2nd Wednesday [on our blog](www.worldbrain.io/blog/).

We just published our first prototype with the channel "Related Content" , powered by [Laterals News API](https://lateral.io/publishing) and broadcasted into a [Hypothes.is group](https://hypothes.is/groups/KG9bL1Bm/related-articles).

Currently we are working on the feature to be able to keywords search through the content of outlets **science community** trusts. (i.e. blogs, news, facebook groups/pages, scholarly and governmental databases) 

**[>> Want to have a specific source indexed?](www.worldbrain.io/install_bookmarklet/)** 

<br>


## Next Milestones

#### [Search Engine Prototype](https://github.com/WorldBrain/Webmarks/milestones/Search%20Prototype) (Due by July 17, 2016)

A simple google-like landingpage to enter search queries and get search result from a list of sources trusted by the scientific community. 

#### [Planning Freeze for MVP Features and Architecture](https://github.com/WorldBrain/Webmarks/milestones/Planning%20Freeze%20for%20MVP) (Due by July 23, 2016)
We want to have evaluated our options to build the prototype and planned the necessary features, so we can start the development on our **Minimum Viable Product**(MVP)

#### [Release Minimum Viable Product](https://github.com/WorldBrain/Webmarks/milestones/Minimum%20Viable%20Product) (Due date to be planned)
The release of the product that encapsules the set of features necessary, so we can call Webmarks a product.

<br>

## Feature Roadmap for Webmarks

#### Short Term (~3-6 months)

 - A search engine in the form of browser-sidebar, that lets users perform keyword searches through a list of outlets flagged by our scientific community as trustworthy.
 - A recommendation engine to get related content to the immediate article, also only from these trusted sources, displayed in the sidebar.

#### Medium Term (~6-12 months)

 - Additional meta browsing channels to put the immediate content into other contexts. For example by displaying Altmetric data in the sidebar or highlighting Wikipedia entries in the text. 
 - Personalisation of the choice of sources to get relevant content from and to search through.

#### Long Term (~1-1,5 years)

 - Opening up the meta browsing platform to developers and organisations to add new channels and distribute them to users.
 - (Maybe) Personal bookmarking, annotating, sharing and discussing of web content.

A search engine in the form of browser-sidebar, that lets users perform keyword searches through a list of outlets flagged by the user and/or our scientific community as trustworthy.
A recommendation engine to get related content to the immediate article, also only from these trusted sources, displayed in the sidebar.
There are endless opportunities to do this and we surely won’t cover all of them. That is why we open up this platform to developers and organisations to add new channels and distribute them to users.

<br>
<br>
## WorldBrain's 10 Year Roadmap

We want to live in a a world, where the belief systems of our society are based on verifiable facts instead of rumours and misinformation, where we have less fear based, more rational public dialogues.

In 10 years, we want to be able to provide the general public with a browser plugin that shows the accuracy and trustworthiness of web content, based on how well it represents scientifically verifiable facts. 
We follow an ambitious long-term goal, yet we are able to deliver immediate value to users and contribute to scientific literacy in the public at each step of our path.


### STAGE 1: WorldBrain's Webmarks (year 0-3)
Historical approaches to crowdsourced fact-checking, like factlink.com or grasswire.com, didn’t reach a critical mass of contributors, because there was no personal value for users to contribute.

This is why, in a first step, we build Webmarks; an open-source SaaS tool for science communicator like scientists, science writer and the skeptical communities to find quality scientific web content faster.
The strategic purpose of Webmarks is to build a large community of scientifically literate individuals and be an integral part of their day-to-day online web research.
By analysing our user’s workflows, users already contribute at this stage with important metadata about the quality of different websites and their content.  ([What data will we gather from users?](http://www.worldbrain.io/open_and_social/))

#### The user’s problem:
For people doing web research, it is a very time consuming process to find quality scientific content related to the immediate (news)article or their overall web research goal. 

To get this information, users currently have to search through all of their trusted outlets (i.e. blogs, news, facebook groups/pages, scholarly and governmental databases) separately or use google, where they are unable to filter for their trusted sources. 

#### Webmarks’ key features:
 - A search engine in the form of browser-sidebar, that lets users perform keyword searches through a list of outlets flagged by the user and/or our scientific community as trustworthy.
 - A recommendation engine to get related content to the immediate article, also only from these trusted sources, displayed in the sidebar. 
 - Additional meta browsing channels to put the immediate content into other contexts. For example by displaying Altmetric data in the sidebar or highlighting Wikipedia entries in the text.
 There are endless opportunities to do this and we surely won’t cover all of them. That is why we open up this platform to developers and organisations to add new channels and distribute them to users.

To get a feeling for how it works, [watch our short demo video.](https://www.youtube.com/watch?v=mWLg1awM3BE)


### STAGE 2: Finding the most communicated arguments on the web. (year 3-5)

In our second step at a yet undefined point in the future, given the condition that Webmarks’ community is large enough, we want to use the circumstance that for a given scientific debate, there are mostly only a couple of dozen arguments that are highly communicated online, although expressed differently in many places. 

With the help of algorithms that are able to detect these popular arguments, we want to create a list of the most communicated scientific claims, as well as their specific locations on the internet. 

A possible approach to generate the necessary data to train those algorithms is to let our users, who know the debates and their arguments well, annotate and summarise popular scientific claims in web content.

One of the most critical challenges here will be to bring the algorithms to sufficient precision, since logical argument detection in natural language processing is not mature yet. In fact, the data sets we produce could have the potential to contribute to further developments in this field.



### STAGE 3: Verifying Arguments & Scaled Verification (year 4-ongoing)

Yet knowing these argumentative patterns allows us, in a third step, to write crowdsourced summaries ([Visit showcase for summary](http://arguments.worldbrain.io/?p=326)) with state-of-the-art scientific findings that qualify these arguments and link them back to the exact locations where we found the related claim.
With that we generate the necessary data to publish our browser plugin intended for the general public. 

In order to provide a value with it, we don’t have to fully verify every piece of content nor every article on a website. 
We just have to verify enough of them to convince people with a credible analysis of either the content or the source, not to read and share bad ones. Because if that happens, outlets will lose clicks, therefore revenue and finally a monetary incentive on qualitative online journalism is imposed, which in turn would support an organic shift towards better quality overall.
To ensure the credibility of our content and a balanced power distribution, we will follow a contribution-based peer-reviewing model like successfully applied by StackOverflow. 

<br>

License
-------
WorldBrain's Webmarks will be published under the [BSD 2-Clause license](https://github.com/WorldBrain/START-HERE/blob/master/LICENSE).
