# Chapter 2: The platformisation of social media

## Outline

* Enclosure as part of platform dynamics (walled gardens, filter bubbles, etc.)
* From early social media through a tipping point of platformisation to 
* Key moments:
    + when IRCv3 protocol standardisation failed
    + Microsoft and Skype closing public chats
 * Explanatory factors:
    + Dissappearance of public infrastructures [@Plantin:Lagoze:Edwards:Sandvig2018a]
    + Moderation
    + Corporatisation
        - privatisation (not really public spaces because they belong to a private organisation)
        - the owner of the space is liable for anything that happens (moderation again)
        - is this why they moved from place-centred to people-centred social media?
        - dissappearance of multi-platform client
    + APIs, technical means and strategies of enclosure [@Helmond2015a; @Helmond+etal2019a]

## From @LatzkoToth2014a (adapted and expanded draft version)

## The unreachable standard
In april 1997, a "bird-of-a-feather" on "Internet Relay Chat Update" was held in Memphis, Tennessee, in the context of the 38th 
Internet Engineering Task Force (IETF) Meeting. The main point at the agenda was that there was "no draft on the standards track addressing
chat" at the time, as noted by the meeting chair, John Noerenberg, a Qualcomm representative [**NOTE:** Minutes of the IRCUP (Internet Relay Chat UPdate) BOF, April 9, 1997,38th IETF Meeting, Memphis, Tennessee. Notes taken by Ian King from Microsoft. Retrieved from the IETF ftp server]. The meeting ended on the decision to create an IRC Update Working Group (IRCUP) which would take the form of a mailing list gathering various actors interested in IRC standardization. One of the objectives of the process was to develop a perfectly scalable system, suitable both for private mini-networks (at the scale of an organization) and for vast public networks able to accomodate up to “one million users on 100,000 channels,”[**NOTE:** Minutes cited before] which was deemed to be a considerable number at the time. 

Among the participants in the IRCUP working group were some key actors of the development of major IRC networks, including Microsoft. One of its spokespersons, Thomas Pfenning, had previously submitted a working paper proposing a series of protocol extensions under the name “IRCX” [**NOTE:** The most recent version is : D. Abraham, “Extensions to the Internet Relay Chat Protocol (IRCX)”, Internet Draft, Microsoft Corporation, June 1998]. 
The IRCUP mailing list was active from January to July 1998, but its members failed to agree even on a common agenda, and it was eventually dissolved . Microsoft reiterated its proposal in april 2004[**NOTE:**See “Exchange Chat Features/IRCX”, Microsoft Corporation, 2004/04/19. Retrieved from https://docs.microsoft.com/en-us/previous-versions//cc767140(v=technet.10)?redirectedfrom=MSDN]; its goal, it said, was to overvome the 'ill-fated' IRC standardization effort, and unify the archipelago of chat devices and IRC server code variants around a robust standard, offering a refined gradation of sociotechnical roles and adding several features to the protocol . Furthermore, Microsoft wanted to make IRCX the chat protocol of its “Microsoft Exchange Server” platform, which up-to-then used a proprietary protocol, Microsoft Internet Chat (MIC). Having failed to convince IETF and the community of IRC developers, Microsoft abandoned the project and focussed on a proprietary protocol, the “Messenger” protocol, which would underlie its instant messaging system, MSN Messenger, launched in 1999. 

In a message dated February 1, 1998, Peter de Vries, one of the members of IRCUP, sums up the difficulties experienced in trying to agree on a standard for IRC:

> The “dream” of IRC3 means different things to different people.  Everyone would agree that IRC3 must “improve on the original concept and expand it into logical new areas to meet modern needs”.  But .. the agreement stops there.  Sure, there are some issues that everyone agrees needs fixing (ie: scalability).  But there are other concepts in IRC2 that some people think are “bugs” while other people think they are “features” [...]. Even ideologically [...] there is disagreement. [...] Some people believe that certain extensions would are “logical extensions of the paradigm”.. that they would have existed already “if cpu or development time had allowed” or “if the problem existed then”. Others take a look at the same concept and don’t see it jiving with their “vision” of IRC at all. I think the “difference in vision” problem is a big one.  IRC3 is a big problem – many possible directions.. many possible (& divergent) solutions. This is no normal WG [working group]. [...] We are still at the explosive “determine the paradigm” section [...].    

## Platformisation

The platformisation process did not happen overnight. There were gradual steps taken by the various commercial actors that would become the giants of the web as we know them today--the "GAFAM". This phase, that could roughly been situated in the first decade of the millenium, can be called the *proto-platformisation* of the Internet in general, and of social media in particular. The first step is privatisation of the communicational space. The second one is its technical enclosure through the restriction of its iteroperability with third party clients. The third step is its commercialisation and its "corporatisation". Soon after will come the adoption of the platform model, from the examples of newcomers like Facebook and Twitter.       

### First step: the privatisation of chat

In october 2006, Microsoft shut down its MSN Chat service, closing thousands of chatrooms to the dismay of their users. The official reason put forward by Microsoft was the lack of profitability. The move started three years before, in september 2003, when Microsoft closed its chatrooms in Europe and Asia, officially to protect youth from sexual agressors. Chatrooms stayed open in countries where their access was subscription-based, like in United States and Canada, "where MSN ha[d] billing relationships that enable[d] it to track abusers if necessary" [**NOTE:**Microsoft, “Protecting children online”, 2005/10/05.] Interstingly, Skype also put its "public chats" to an end with the introduction of Skype 4.0, in 2009. As a tech blogger (@Courtney2009a) observed at the time:

> Skype for Windows Product Manager Mike Bartlett claimed yesterday, during an interview, that Skype was reviewing how to embark on “public conversations” in today’s messaging world where services such as Twitter and Friend Feed also provide ongoing dialogues. However, Skype Public Chat has its own “space” in terms of user community; it needs to be brought back as soon as possible.
> 
It was never brought back, in line with a trend that followed all the major proprietary chat device providers. 

After the dot-com boom, market concentration set in within the online services sector, establishing social networks as the most lucrative business model. On the one hand, social media proﬁts are turned through datamining and proﬁling of users, which enhances targeted advertising to the same audience (Fuchs 2012). On the other hand, social media monopolies establish themselves as obligatory passage points for data trafﬁc to and service provision by other actors, a leverage they can exploit for capital accumulation and market positioning. This process has been described as the “platformization” of Internet services (Gillespie 2010). Rather  than a service in its own right, instant messaging is seen today as a core component of social networking. While presence and contact management distinguished IM from other participation frameworks, the rise of social networking led to a hybrid- ization with chat devices where they can scarcely be discussed as a distinct form of mediation, and therefore, sociality.
The XMPP (Extensible Messaging and Presence Protocol) family of standards was proposed by open-source advocates in 1999. The open protocol aimed to make proprietary Instant Messengers compatible through a common language, addressing the problem of market fragmentation where messages cannot cross corporate silos; to allow anybody to provide compatible IM services, decreasing the grip of social media monopolies on users; and to support the seamless integration of messaging into the widest possible range of technologies, encouraging hybridization. Propri- etary IM operators progressively added various levels of XMPP support (Skype 2003; Google Talk 2005; Facebook Chat 2008; AOL 2008). Ironically, XMPP itself soon fell victim to fragmentation due to its many extensions. Its popularity fell from ten million users in 2003 – when it reportedly surpassed ICQ users – to a level where its relevance itself is debated (XMPP Standards Foundation 2003; Quora 2015). Monopolies progressively dropped XMPP compatibility, yet incompatible implementations still form the core of many popular services such as WhatsApp, PlayStation, or Facebook. A similar contemporary attempt is the Matrix protocol which pitched platformization as its ultimate goal  from  the  very  beginning,  even though it is still unclear whether users really need IM interoperability (Weinberger 2014).
Ultimately, today users encounter chat integrated into social media platforms (such as Twitter, Skype and Facebook) or IM on mobile platforms (such as WhatsApp, Telegram, and Signal). While these are generally built with person-to- person communication in mind, over time group chat features have been added to their functions, which is exploited by users to form topical communities. Therefore, some IRC-like dynamics emerge against the script of these devices.



## From @Maxigas2017c

Eventually, *surveillance* came to be the key means for both maintaining social peace and deepening exploitation on social media platforms. [^3]  Everyday, informal, even intimate gestures are captured and stored, sorted and mined for the purposes of both targeted advertising and targeted repression 
> [name=Alix-]
We will need to refrain from using a too obvious ideological tone in the analytical sections. I suggest using “targeted policing” (but we need to provide an example). Additionally, I think what follows should take place either at the end of the chapter, in a more reflective section (rather than analytical, as the chapter should start with), or in the beginning of the next chapter, as a fundamental argument for "pressing the ESC key".

Such revenue is indispensable to the capital accumulation mechanisms of a growing section of capital, while the intelligence gained by authorities who share access to the information flows is essential to the maintenance of social order in both dictatorships *and* democracies.  For instance, surveillance – technically based on the analysis of log files – accounted for 89% of Google’s profit in 2014 [@Griffith2015a]. [^4]  All this hinges on successful *platformisation*: the ability of a vendor to install themselves as an obligatory passage point for generally mundane and often minuscule social interactions [@Gillespie2010a].  The kind of digital milieus where average Internet users chit-chat nowadays have been variously described by scholars as *enclosures*, *walled gardens* and *social media monopolies* [@LovinkRasch2013a].

The anxiety experienced by users stems from the fact that a supposedly informal space of social interaction is mediated by capital and overseen by the state, through mechanisms that seem obscure, arbitrary and partial from below.  One can remember that the two defining characteristics of a healthy *civil society* that can support technological sovereignty are its independence from capital and separation from the state [@Hache2014d].  It is *privacy* in a structural and collective sense that can be reclaimed through technological sovereignty initiatives, but only through the continuous struggle of users for taking the technological mediation of their social life into their own hands.
> [name=Alix-]The sentence above is exactly the kind of stuff that should be found in the final chapter, where we articulate a "prescriptive proposal" for social media commons.

Notably, neither chat [@LatzkoToth2010a] nor personal computing [@Levy1984a] were “inventions” in the sense that a good idea was implemented and socialised through commodity circulation.  Both found a foothold in the market only after a relatively long period where fringe elements fought for them, often breaking existing laws, regulations and social norms.  Society then slowly tamed these technologies – and now they are used to pacify society itself.

## References

Courtney Jim. 2009. Skype for Windows 4.0 Goes Gold; Improved UI, Audio and Video Performance. Voice on the Web, http://voiceontheweb.biz/skype-world/skype-markets-skype-world/skype-for-personal/skype-40-goes-gold/, last accessed 2020/01/30.

Helmond, Anne. 2015. "The Platformization of the Web: Making Web Data
Platform Ready." *Social Media + Society*.

Helmond, Anne, David B. Nieborg, and Fernando N. van der Vlist. 2019.
"Facebook's Evolution: Development of a Platform-as-Infrastructure."
*Internet Histories* 3 (2): 123--146.
doi:10.1080/24701475.2019.1593667

Maxigas. 2017. "Keeping Technological Sovereignty: The Case of Internet
Relay Chat." In *Technological Sovereignty 2*, ed by. Alex Haché. Vol.
2. Dossier Ritimo. Paris: Ritimo.

Plantin, Jean-Chrisophe, Carl Lagoze, Paul N. Edwards, and Christian
Sandvig. 2018. "Infrastructure Studies Meet Platform Studies in the Age
of Google and Facebook." *New Media & Society* 20 (1): 293--310.
doi:10.1177/1461444816661553

