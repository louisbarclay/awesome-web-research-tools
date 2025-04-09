# Awesome Web Research Tools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome tools, frameworks, and resources for web research data collection, including tools that support observational methods, experimental interventions on the web, and simulations of the web for experiments.

**Why does this list exist?**

To quote [this paper](https://osf.io/preprints/psyarxiv/wvfjq_v1):

> Researchers are constantly reinventing the wheel, building methodological frameworks and technical tools that have already been built in the same or at least similar ways

## Contents

- [Tools](#tools)
  - [Observational Tools](#observational-tools)
  - [Experimental Interventions on the Web](#experimental-interventions-on-the-web)
  - [Experimental Interventions on Simulated Websites](#experimental-interventions-on-simulated-websites)
  - [Other Tools](#other-tools)
- [Organizations](#organizations)
- [Related Resources](#related-resources)
  - [Publications & Journals](#publications--journals)
  - [Relevant Awesome Lists](#relevant-awesome-lists)
- [Contributing](#contributing)
- [Inbox](#inbox)

## Tools

### Observational Tools

*Note: many possible sub-sections or sorting methods - e.g. open source vs. commercial; actively maintained/date of last commit. Are APIs tools?*

- [AlgoTransparency](https://www.algotransparency.org/) - Data on algorithmic recommendations from YouTube and more (no longer maintained)
- [Blacklight](https://themarkup.org/blacklight) - Real-time website privacy inspector [GitHub](https://github.com/the-markup/blacklight-collector)
- [EnviroReport](https://www.chicago-cachet.org/enviroreport/) - Data donation for crowdsourcing environmental incidents (free but closed source)
- [HabitLab](https://habitlab.github.io/) - Browser extension with interventions for online habits ([GitHub](https://github.com/habitlab/habitlab)) (no longer maintained)
- [Internet Archive](https://archive.org) - Digital library of Internet sites and other cultural artifacts
- [Junkipedia](https://www.junkipedia.org/) - Tool for organizing and tracking social media content (requires access request)
- [Kiran Garimella/Rutgers University Data Donation tools](https://data-donation.vercel.app/) - Collection of assorted data donation tools for research purposes, including [WhatsApp donation tool](https://whatsapp.whats-viral.me/) and [Diaspora Watch](https://www.diaspora-watch.us/home/?next=/)
- [Lumen Database](https://lumendatabase.org/) - Collects and analyzes legal complaints about online content
- [Meedan Check](https://meedan.com/check) - Collaborative verification platform
- [Meta Content Library](https://www.facebook.com/ads/library/) - Official transparency tool for content on Meta platforms
- [Mozilla Rally](https://github.com/mozilla-rally) - Data donation platform ([GitHub](https://github.com/mozilla-rally)) (no longer maintained)
- [NodeXL](https://nodexl.com/) - Network analysis and visualization software
- [Perspective API](https://perspectiveapi.com/) - Content classification to monitor health of online conversations ([GitHub](https://github.com/conversationai/perspectiveapi))
- [RecAlign](https://www.recalign.com/) - Platform for studying recommendation systems ([Github](https://github.com/recalign/RecAlign))
- Social listening tools e.g. [Brandwatch](https://brandwatch.com/) for monitoring social media (expensive)
- [TikTok Research API](https://developers.tiktok.com/products/research-api/) - Official research API (restrictive terms and conditions)
- [Understanding.Social](https://understanding.social/) - Browser extension that captures Facebook content to recreate news feeds for experiments (by [Who Targets Me](https://whotargets.me/en/))
- [WebHistorian](https://webhistorian.github.io/) - Web history visualization tool ([GitHub](https://github.com/WebHistorian)) (Educational version available on the [Chrome store](https://chromewebstore.google.com/detail/web-historian-education-e/chpcblajbmmlbhecpnnadmjmlbhkloji?hl=en&pli=1), moving to BRIC organization)
- [WhatsApp Watch](https://www.digitalwitnesslab.org/whatsapp-watch) - Monitoring tool for WhatsApp content
- [Who Targets Me](https://whotargets.me/en/) - Browser extension tracking political advertising ([GitHub](https://github.com/WhoTargetsMe/Who-Targets-Me))
- [Who Targets Me GitHub](https://github.com/WhoTargetsMe/Who-Targets-Me) - Source code for the Who Targets Me extension. ([GitHub](https://github.com/WhoTargetsMe/Who-Targets-Me))
- [X API](https://developer.twitter.com/en/docs/twitter-api) - API for accessing X (formerly Twitter) data (expensive)
- [Django URL Shortener](https://github.com/audacious-software/Django-URL-Shortener) - Django app for creating a self-hosted URL shortening service with click tracking ([GitHub](https://github.com/audacious-software/Django-URL-Shortener))

### Experimental Interventions on the Web
- [FeedMonitor](https://github.com/StanfordHCI/FeedMonitor) - Tool for monitoring and manipulating social media feeds ([GitHub](https://github.com/StanfordHCI/FeedMonitor))
- [CivilServant](https://github.com/citizensandtech/CivilServant) - Platform for running A/B tests in online communities ([GitHub](https://github.com/citizensandtech/CivilServant))
- [Mozilla YouTube RegretsReporter](https://foundation.mozilla.org/youtube/regretsreporter/) - Browser extension for YouTube algorithm research ([GitHub](https://github.com/mozilla-extensions/regrets-reporter)) (no longer maintained)
- [RecAlign](https://www.recalign.com/) - Browser extension that changes recommendations on social media with LLMs ([Github](https://github.com/recalign/RecAlign))
- [Webmunk](https://www.webmunk.org/) - Browser extension for both data gathering and intervention studies ([GitHub](https://github.com/Webmunk-Project))
- [Prosocial Ranking Challenge browser extension](https://humancompatible.ai/news/2024/01/18/the-prosocial-ranking-challenge-60000-in-prizes-for-better-social-media-algorithms/) - Browser extension for algorithm research (not public)

### Experimental Interventions on Simulated Websites
- [The Truman Platform](https://github.com/cornellsml/truman_2023) - Social media simulation platform ([GitHub](https://github.com/cornellsml/truman_2023))
- [YourFeed](https://www.media.mit.edu/projects/yourfeed/overview/) - Simulated news feed environment for lab experiments (no longer maintained)
- [Social Media TestDrive](https://socialmediatestdrive.org/) - Social media simulation for educational purposes
- [PAIR code](https://github.com/pair-code) - Set of tools for testing human-AI interactions from Google's People+AI Research (PAIR) Initiative

### Other Tools

- Fresco - Network interviews in the web browser ([GitHub](https://github.com/complexdatacollective/Fresco))
- Automated Conversation Kit - Open source platform for creating automated conversations
  - [Django Dialog Engine](https://github.com/audacious-software/Django-Dialog-Engine) - Automated dialog / chatbot engine for Django. ([GitHub](https://github.com/audacious-software/Django-Dialog-Engine))
  - [Simple Messaging](https://github.com/audacious-software/Simple-Messaging-Django) - Collection of Django apps and libraries for constructing text-messaging interventions. ([GitHub](https://github.com/audacious-software/Simple-Messaging-Django))
    - [Django Dialog Engine support](https://github.com/audacious-software/Simple-Messaging-Dialog-Engine-Support)
    - [Twilio support](https://github.com/audacious-software/Simple-Messaging-Django-Twilio)
    - [Azure support](https://github.com/audacious-software/Simple-Messaging-Django-Azure)
    - [Local loopback channel support](https://github.com/audacious-software/Simple-Messaging-Django-Loopback)
    - [Multi-channel support](https://github.com/audacious-software/Simple-Messaging-Switchboard)
- [HealthySMS](https://mental.jmir.org/2024/1/e49317) - Messaging-based health intervention platform (Commercial license through UC Berkeley)
- [Hive Mechanic](https://www.hivemechanic.org/) - Platform for creating place-based experiences and games ([GitHub](https://github.com/bdcheck))
- [Passive Data Kit](https://passivedatakit.org/) (PDK) - Framework for collecting passive data from multiple sources.
  - [Passive Data Kit Django](https://github.com/audacious-software/PassiveDataKit-Django) - Django app for building cloud data ingestion server. ([GitHub](https://github.com/audacious-software/PassiveDataKit-Django))
  - [Passive Data Kit Django: External Data](https://github.com/audacious-software/Passive-Data-Kit-External-Data) - PDK extension for collecting data donations ([GitHub](https://github.com/audacious-software/Passive-Data-Kit-External-Data))
  - [Passive Data Kit Django: iOS](https://github.com/audacious-software/PassiveDataKit-iOS) - Framework for collecting data from iOS devices ([GitHub](https://github.com/audacious-software/PassiveDataKit-iOS))
  - [Passive Data Kit Django: Android](https://github.com/audacious-software/PassiveDataKit-Android) - Library for collecting data from Android devices ([GitHub](https://github.com/audacious-software/PassiveDataKit-Android))
- [AWARE Framework](http://www.awareframework.com/) - Mobile sensing framework for data collection ([GitHub](https://github.com/denzilferreira/aware-client)) (no longer maintained)
- [Detoxify](https://github.com/unitaryai/detoxify) - Tool for toxicity detection in text. ([GitHub](https://github.com/unitaryai/detoxify))
- [Various tools by Kaspar Welbers](https://github.com/kasperwelbers) - Various computational text analysis tools ([GitHub](https://github.com/kasperwelbers))
- Phone Dashboard - Open source app for Android app usage gathering and behavioral interventions. (iOS version is in the middle of its first field study - will be posted soon.) ([GitHub](https://github.com/Phone-Dashboard/Phone-Dashboard-Android))
- [Purple Robot](https://pmc.ncbi.nlm.nih.gov/articles/PMC4129186/) - Sensing and intervention platform for Android. ([GitHub](https://github.com/cbitstech/Purple-Robot)) (no longer maintained)

## Organizations

- [BRIC (Behavioral Research Innovation Center)](https://bric.digital/) - Organization helping researchers to find the right tools for web research (actively contributing to this list)
- [Check My Ads](https://checkmyads.org/) - Online ads watchdog
- [Data Transfer Initiative](https://dtinit.org/) - Initiative to enable data portability between platforms
- [Digital Communication Lab](https://digicomlab.github.io) - University of Amsterdam research group which develops tools for web research
- [Digital Methods Initiative](https://www.digitalmethods.net/Dmi/DmiAbout) - Research program dedicated to studying the web and building web research tools
- [Human Compatible AI](https://humancompatible.ai/) - Hosts the Prosocial Ranking Challenge browser extension (see above)
- [Human Screenome Project](https://screenomics.stanford.edu/) - Research project which developed tools to observe online behavior in-depth
- [IDEA Lab](https://idea-lab.uni-graz.at/en/) - Research lab focused on digital ethics and algorithms which develops its own tools
- [MIT Applied Cooperation Initiative](https://mitsloan.mit.edu/centers-initiatives/mit-applied-cooperation-initiative/welcome) - Research group which develops tools to study misinformation and social media
- [National Internet Observatory](https://nationalinternetobservatory.org/) - U.S. national data collection effort that creates tools to collect web browsing and mobile trace data from a large sample of participants who also complete surveys. Intention to open-source tools in the future.
- [NYU Ad Observatory](https://adobservatory.org/) - Platform for studying political ads (no longer active)
- [OneSec](https://one-sec.app/research/) - Commercial app which conducts research with user base
- [Prosocial Design Network](https://prosocialdesign.org/) - Review of prosocial interventions and community around prosocial design
- [University of Washington Information Science](https://ischool.uw.edu/) - Research group which develops web research tools
- [University of Zurich, Social Computing Group](https://www.ifi.uzh.ch/en/scg.html) - Research group which develops web research tools

## Related Resources

### Publications & Journals

- [Auditing Pipeline Research](https://www.pnas.org/doi/abs/10.1073/pnas.2213020120) - Audit of YouTube's algorithm
- [Journal of Computational Communication Research](https://journal.computationalcommunication.org/) - Academic journal on computational methods in communication research
- [Journal of Social Computing](https://www.sciopen.com/journal/join_journal/about_journal?id=1400738783960883202&issn=2688-5255) - Research on computational aspects of communication
- [Independently testing prosocial interventions: Methods and recommendations from 31 researchers](https://osf.io/preprints/psyarxiv/wvfjq_v1) - Paper reviewing approaches to web research, with a focus on interventions
- [Internet Interventions](https://www.sciencedirect.com/journal/internet-interventions) - Journal focused on mental and behavioral health interventions delivered through the internet
- [RecAlign (Paper)](https://arxiv.org/abs/2406.19571) - Research paper about re-ranking of recommendation systems
- [Social Media Accelerator (Paper)](https://osf.io/preprints/socarxiv/ucfbk_v1) - Proposal for a CERN-like environment for researching social media

### Relevant Awesome Lists

- [Awesome OSINT](https://github.com/jivoi/awesome-osint) - A curated list of resources for open source intelligence (OSINT)
- [Awesome Data Science](https://github.com/academic/awesome-datascience) - A curated list of resources for data science
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of awesome Awesome lists
- [Awesome Computational Social Science](https://github.com/gesiscss/awesome-computational-social-science) - Resources for computational social science
- [Awesome JavaScript](https://github.com/sorrycc/awesome-javascript) - Collection of awesome browser-side JavaScript libraries
- [Awesome Network Analysis](https://github.com/briatte/awesome-network-analysis) - Resources for network analysis
- [Awesome R](https://github.com/qinwf/awesome-R) - Collection of R packages and resources

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or an Issue.

## License

This list is under the [Creative Commons Zero v1.0 Universal](LICENSE) license.
