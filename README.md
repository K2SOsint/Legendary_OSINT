# 🛰 Legendary OSINT

A curated list of **OSINT** tools & resources.  
Sources include newsletters, Telegram groups, curated startpages, GitHub repos, and other public collections.  
Most tools are third-party — always vet and use responsibly.  

Inspired by [Legendary_Crypto](https://github.com/K2SOsint/Legendary_Crypto).  

---

## 📖 Table of Contents
- [👤 People Search & Social Media](#-people-search--social-media)
- [✈️ Aviation Movements & Flight Tracking](#️-aviation-movements--flight-tracking)
- [🌍 Domains, IPs & Infrastructure](#-domains-ips--infrastructure)
- [🎣 Phishing & Email Investigation](#-phishing--email-investigation)
- [🦠 Malware Analysis & CTI](#-malware-analysis--cti)
- [🕳 Dark Web & Leaks](#-dark-web--leaks)
- [🔍 Search Engines](#-search-engines)
- [🗄 Website Archiving & Caching](#-website-archiving--caching)
- [🛰 Geospatial & Mapping OSINT](#-geospatial--mapping-osint)
- [📰 News & Media Monitoring](#-news--media-monitoring)
- [📷 Image & Reverse Search](#-image--reverse-search)
- [🎥 Video OSINT](#-video-osint)
- [💼 Business & Company Intelligence](#-business--company-intelligence)
- [⚖️ Government & Legal Records](#-government--legal-records)
- [📚 Academic & Research Databases](#-academic--research-databases)
- [🤖 Automation & Recon Frameworks](#-automation--recon-frameworks)
- [📡 Intelligence Feeds](#-intelligence-feeds)
- [🧑‍🤝‍🧑 OSINT for Good (NGOs & Initiatives)](#-osint-for-good-ngos--initiatives)
- [📚 Learning Resources](#-learning-resources)
- [⚖️ License](#️-license)

## 👤 People Search & Social Media

### Cross-Platform
- [Sherlock](https://github.com/sherlock-project/sherlock) — Username search across 350+ sites  
- [WhatsMyName](https://whatsmyname.app/) — Fast username enumeration  
- [Maigret](https://github.com/soxoj/maigret) — Collect profiles by username across 2000+ sites  
- [Holehe](https://github.com/megadose/holehe) — Check if email is registered on platforms  
- [Blackbird](https://github.com/p1ngul1n0/blackbird) — Alternative username search engine  
- [Namechk](https://namechk.com/) — Username/domain availability  
- [Socialscan](https://github.com/iojw/socialscan) — Check username/email across services  
- [UserSearch](https://usersearch.org/) — Find usernames across forums, social, communities  
- [IDcrawl](https://www.idcrawl.com/) — Meta search for people across multiple social networks  
- [PeekYou](https://www.peekyou.com/) — Publicly available people search  
- [Pipl](https://pipl.com/) — Commercial people search & enrichment  

---

### Twitter / X
- [Twint](https://github.com/twintproject/twint) — Scrape Twitter without API keys  
- [snscrape](https://github.com/JustAnotherArchivist/snscrape) — Scrape tweets, profiles, hashtags  
- [TweetBeaver](https://tweetbeaver.com/) — Lookup tools for profiles, likes, followers  
- [Foller.me](https://foller.me/) — Analyze Twitter account topics & activity  
- [BirdHunt](https://birdhunt.co/) — Historical tweet search  
- [Twitonomy](https://www.twitonomy.com/) — Analytics on tweets, mentions, followers, lists  
- [Bot Sentinel](https://botsentinel.com/) — Detect and analyze bot-like or inauthentic accounts  
- [Wayback Tweets](https://waybacktweets.streamlit.app/) — Retrieve deleted or archived tweets  
- [Nitter](https://nitter.net/) — Alternative Twitter front-end, useful for OSINT scraping  
  

---

### Instagram
- [Instaloader](https://github.com/instaloader/instaloader) — Download posts, stories, metadata  
- [OSINTgram](https://github.com/Datalux/Osintgram) — Command-line Instagram OSINT  
- [InstaLooter](https://github.com/althonos/InstaLooter) — Download profile content  
- [Picuki](https://www.picuki.com/) — Instagram web viewer/downloader  
- [StoriesDown](https://storiesdown.com/) — Download Instagram stories anonymously  
- [InstaDP](https://www.instadp.io/) — View and download profile pictures  

---

### LinkedIn
- [LinkedInt](https://github.com/vysecurity/LinkedInt) — Gather employees from LinkedIn  
- [RocketReach](https://rocketreach.co/) — Email/profile enrichment (freemium)  
- [SignalHire](https://www.signalhire.com/) — LinkedIn email extraction (freemium)  
- [Hunter.io](https://hunter.io/) — Corporate email discovery  
- [PhantomBuster](https://phantombuster.com/) — Automate LinkedIn scraping (freemium)  
- [SalesQL](https://salesql.com/) — LinkedIn lead & contact extraction  

---

### TikTok
- [TikTok-OSINT](https://github.com/isaacjullien/TikTok-OSINT) — Extract TikTok profile data  
- [TikTok-Scraper](https://github.com/drawrowfly/tiktok-scraper) — Download videos, scrape metadata  
- [Urlebird](https://urlebird.com/) — View TikTok profiles without login  
- [Exolyt](https://exolyt.com/) — TikTok analytics & monitoring (freemium)  

---

### Reddit
- [Pushshift Reddit Search](https://redditsearch.io/) — Historical Reddit data  
- [Reddit Insight](https://redditinsight.com/) — Analyze profiles & posting activity  
- [ReSavr](https://www.resavr.com/) — Recover deleted comments  
- [Camas Reddit Investigator](https://camas.github.io/reddit-search/) — Search Reddit posts & comments  

---

### YouTube
- [YTCommentSearch](https://polsy.org.uk/stuff/ytrestrict.cgi) — Search video comments  
- [Noxinfluencer](https://www.noxinfluencer.com/) — YouTube channel analytics  
- [Channel Crawler](https://channelcrawler.com/) — Find channels by keyword/topic  
- [Social Blade](https://socialblade.com/) — Stats on YouTube/Twitch/Twitter accounts  

---

### Telegram
- [Telegago](https://github.com/Telegago/Telegago) — Group/channel OSINT  
- [TgScan](https://tgscan.xyz/) — Search public groups/channels  
- [Telepathy](https://github.com/tejado/telegram-osint) — Extract account info via API  
- [FindThatGroup](https://findthatgroup.com/) — Public group/channel directory  
- [Combot](https://combot.org/telegram/top/groups) — Top Telegram groups/channels  
- [TLGrip](https://github.com/Ph055a/TLGrip) — Telegram scraper for groups/chats  

---

### Discord
- [Disboard](https://disboard.org/) — Server directory  
- [Discord Lookup](https://discord.id/) — Lookup user IDs  
- [Snowsta](https://snowsta.com/) — Discord snowflake ID OSINT  
- [Guild.xyz](https://guild.xyz/) — Explore Discord guilds & communities  

---

### Facebook
- [StalkFace](https://stalkface.com/) — Extract hidden profile info  
- [Lookup-ID](https://lookup-id.com/) — Get Facebook IDs from URLs  
- [GraphTips](https://github.com/Malandrin/GraphTips) — Facebook graph search revival  
- [Social Search Facebook](https://www.social-searcher.com/facebook-search/) — Search within Facebook  

---

### Other Platforms
- [Flickr API](https://www.flickr.com/services/api/) — Photo metadata  
- [VK OSINT](https://vk.watch/) — Russian social network search  
- [Mastodon Instances](https://instances.social/) — Fediverse OSINT  
- [Gab Trends](https://trends.gab.com/) — Gab content tracker  
- [Clubhouse Tools](https://clubsearch.io/) — Clubhouse room & club search (limited)

## ✈️ Aviation Movements & Flight Tracking

### Live Tracking
- [ADS-B Exchange](https://www.adsbexchange.com/) — Largest unfiltered flight data coop  
- [Radar.freedar.uk](https://radar.freedar.uk/VirtualRadar/desktop.html) — Virtual radar desktop view  
- [Flightradar24](https://www.flightradar24.com/) — Real-time flight tracking  
- [FlightAware](https://uk.flightaware.com/live/) — Live flight data and analytics  
- [LiveATC](https://www.liveatc.net/) — Listen to live air traffic control  

### Historical Flight Data
- [ADS-B Exchange Historical](https://flight-data.adsbexchange.com/) — Archived flight data  
- [GVA Dictator Alert](https://github.com/lefranz/geneva-dictators) — Track dictator aircraft movements in Geneva  
- [Planespotters](https://www.planespotters.net/) — Civil aviation spotting and aircraft registry  
- [Airfighters](http://www.airfighters.com/) — Military aircraft database with photos  
- [LocalizaTodo](http://www.localizatodo.com/html5/) — Real-time vessel and aircraft tracking  
- [FlightConnections](https://www.flightconnections.com/) — Interactive airline route maps  
- [NATO/US Military Tracker](http://www.planeflighttracker.com/2014/04/united-states-military-aircraft-in.html) — Military aircraft tracker  

### Aircraft Databases
- [OpenSky Aircraft DB](https://opensky-network.org/aircraft-database/) — Registered aircraft database  
- [JetPhotos](https://www.jetphotos.com/) — Aircraft spotter photos and database  
- [OpenSky Explorer](https://opensky-network.org/network/explorer) — Live ADS-B based flight explorer  

## 🌍 Domains, IPs & Infrastructure

### Registries and Whois
- [Whois](https://who.is) — Basic Whois lookup  
- [ICANN Whois](http://whois.icann.org/en) — Official ICANN Whois  
- [ARIN](http://arin.net) — North America IP registry  
- [RIPE](http://ripe.net/) — Europe, Russia, Middle East IP registry  
- [APNIC](http://apnic.net) — Asia-Pacific IP registry  
- [LACNIC](http://lacnic.net) — Latin America and Caribbean IP registry  
- [AFRINIC](http://afrinic.net) — Africa IP registry  
- [Apnic WhoWas](https://www.apnic.net/static/whowas-ui/) — Historical Asia-Pacific domains  
- [SIDN](http://sidn.nl) — Netherlands domain registry  
- [Eurid](https://eurid.eu/en/) — .EU domain registry  

### Domain Intelligence
- [DomainTools](https://domaintools.com) — Domain research platform  
- [DomainIQ](https://www.domainiq.com/) — Domain intelligence and history  
- [Completedns](https://completedns.com/dns-history/) — DNS history database  
- [WhoisRequest](http://whoisrequest.com/history/) — Domain ownership history lookup  
- [DomainBigData](http://domainbigdata.com) — Domain ownership and historical data  
- [SecurityTrails](https://securitytrails.com/) — DNS and infrastructure data  
- [Robtex](http://robtex.com/) — Infrastructure graph explorer  

### Certificates and DNS
- [CertDB](http://certdb.com) — Historical SSL certificates  
- [crt.sh](https://crt.sh/) — Certificate Transparency logs  
- [PassiveDNS (Mnemonic)](https://passivedns.mnemonic.no/) — Historical DNS resolution  
- [DNSDumpster](https://dnsdumpster.com/) — DNS mapping and reconnaissance  
- [DNSlytics](https://dnslytics.com) — DNS, IP, and ASN intelligence  
- [ViewDNS](http://viewdns.info) — Multi-tool for DNS and Whois lookups  

### Technology Fingerprinting
- [BuiltWith](https://builtwith.com/) — Website technology profiler  
- [Wappalyzer](https://www.wappalyzer.com/) — Detect CMS, frameworks, and technologies  
- [Netcraft](https://toolbar.netcraft.com/site_report?url=) — Site reports and hosting analysis  
- [SpyOnWeb](http://spyonweb.com) — Shared analytics and advertising IDs  
- [VisualSiteMapper](http://www.visualsitemapper.com) — Website relation mapping  

### IP Tools
- [IPVoid](http://www.ipvoid.com/) — IP lookup and blacklist checks  
- [GeoIP Tool](https://geoiptool.com/) — Approximate IP geolocation  
- [CentralOps](http://centralops.net) — Network lookup toolkit  
- [Network-Tools](http://network-tools.com) — Classic network OSINT (legacy)  
- [I Know What You Download](https://iknowwhatyoudownload.com/en/peer/) — Torrent history by IP  

### Domain Age and History
- [CarbonDate](http://carbondate.cs.odu.edu/) — Estimate when a domain was created  
- [Webotheek.nl](https://webotheek.nl/) — Dutch .nl domain research  
- [Timer4Web](http://timer4web.com) — Detect changes and analytics IDs (partial free, paid features)  
- [Whois EasyCounter](https://whois.easycounter.com/) — Historical Whois and ownership details  
- [WhyNoHTTPS](https://whynohttps.com/) — Database of sites without HTTPS  

## 🎣 Phishing & Email Investigation

### Email Breach and Reputation
- [Have I Been Pwned](https://haveibeenpwned.com/) — Search if an email appears in known data breaches  
- [DeHashed](https://dehashed.com/) — Breach and credential search  
- [EmailRep.io](https://emailrep.io/) — Email reputation and risk scoring  
- [Hunter.io](https://hunter.io/) — Discover corporate email patterns and addresses  

### Email Analysis
- [MX Toolbox](https://mxtoolbox.com/EmailHeaders.aspx) — Email header analyzer and MX tools  
- [mailtester.com](http://mailtester.com/) — Check if an email address is valid and deliverable  
- [VerifyEmail](https://tools.verifyemailaddress.io/) — Verify the validity of an email address  

### URL and Phishing Kit Analysis
- [urlscan.io](https://urlscan.io/) — Sandbox and visualize web requests from a URL  
- [URLquery](http://urlquery.net) — Analyze suspicious URLs and detect malicious behavior  
- [PhishTank](https://phishtank.org/) — Community-driven phishing URL database  
- [OpenPhish](https://openphish.com/) — Automated phishing feed  
- [StalkPhish](https://github.com/t4d/StalkPhish) — Identify phishing kits and reused infrastructures  

### IOC and Threat Intelligence Integration
- [Maltiverse](https://maltiverse.com/search) — IOC enrichment and threat intelligence search  
- [ThreatMiner](https://www.threatminer.org/) — IOC and malware sample data mining  
- [ThreatCrowd](https://threatcrowd.org/) — Investigate domains, IPs, and emails via visual graphs

## 🦠 Malware Analysis & CTI

### Multi-engine Scanners
- [VirusTotal](https://www.virustotal.com/) — Analyze files and URLs with multiple AV engines  
- [Hybrid Analysis](https://www.hybrid-analysis.com/) — Free malware analysis service with sandboxing  
- [Joe Sandbox](https://www.joesandbox.com/) — Advanced malware analysis sandbox (limited free tier)  
- [MetaDefender Cloud](https://metadefender.opswat.com/) — File, URL, and hash analysis  

### Sandboxes and Detonation
- [ANY.RUN](https://any.run/) — Interactive sandbox for dynamic malware analysis  
- [Cuckoo Sandbox](https://cuckoosandbox.org/) — Open-source automated malware analysis system  
- [Detux](https://github.com/detux-org/detux) — Linux sandbox for dynamic malware analysis  

### Malware Classification and Enrichment
- [Intezer Analyze](https://analyze.intezer.com/) — Classify malware by code reuse and genealogy  
- [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/) — Open encyclopedia of malware families  
- [YARA](https://virustotal.github.io/yara/) — Tool for identifying and classifying malware samples  
- [CAPA](https://github.com/mandiant/capa) — Identify capabilities in binaries  

### OSINT and Threat Intelligence Platforms
- [MISP](https://www.misp-project.org/) — Open-source threat intelligence platform  
- [OpenCTI](https://www.opencti.io/en/) — Cyber threat intelligence knowledge graph  
- [CRITIFENCE CTI](https://www.critifence.com/) — Threat intelligence for critical infrastructure (commercial)  
- [Abuse.ch](https://abuse.ch/) — Threat intel projects like ThreatFox, URLhaus, Feodo Tracker, MalwareBazaar  
- [AlienVault OTX](https://otx.alienvault.com/) — Open threat exchange community platform  
- [CIRCL OSINT Feeds](https://www.circl.lu/services/osint/) — Public OSINT-based threat feeds  

### Network and Attack Surface Intelligence
- [GreyNoise](https://www.greynoise.io/) — Context for internet scanning and noisy IPs  
- [Shodan](https://www.shodan.io/) — Internet-wide scanner for open ports and services  
- [Censys](https://censys.io/) — Search engine for internet-connected devices and certificates  

### Malware Analysis Toolkits
- [REMnux](https://remnux.org/) — Linux distro for reverse engineering and malware analysis  
- [Flare VM](https://github.com/mandiant/flare-vm) — Windows malware analysis toolkit  
- [Karton](https://github.com/CERT-Polska/karton) — Malware analysis orchestration framework  
  
## 🕳 Dark Web & Leaks

### Dark Web Search Engines
- [DarkSearch](https://darksearch.io) — Search engine for Tor hidden services  
- [Ahmia](https://ahmia.fi) — Search and index of onion sites  
- [OnionLand Search](https://onionlandsearchengine.com/) — Alternative dark web search engine  

### Leak and Breach Databases
- [IntelligenceX](https://intelx.io) — Search engine for leaked data, darknet, and paste sites  
- [OCCRP Aleph](https://data.occrp.org) — Public records and leak database  
- [Scylla.sh](https://scylla.sh/) — Breach and leak search platform  
- [Leak-Lookup](https://leak-lookup.com/) — Email and credential leak search (freemium)  

### Dark Web Investigation Support
- [IACA Dark Web Tools](https://iaca-darkweb-tools.com) — Toolkit for darknet investigations  
- [Tor Metrics](https://metrics.torproject.org/) — Statistics and insights into Tor usage  
- [Darknet Live](https://darknetlive.com/) — News and updates on darknet markets and activity  

### Open Directories and FTP
- [Napalm FTP Indexer](https://www.searchftps.net) — Search open FTP servers  
- [Index of Directories Search](https://www.index-of.co.uk/) — Public open directory listings  
- [Filemare](https://filemare.com/) — Search engine for open file directories  

### Web Archives and Historic Data
- [Archive.org](https://archive.org) — Internet Archive and Wayback Machine  
- [Google CSE Utopia](https://start.me/p/EL84Km/cse-utopia) — Curated collection of custom search engines

## 🔍 Search Engines

### General Search Engines
- [Google](https://www.google.com) — The most widely used web search engine  
- [Bing](https://www.bing.com) — Microsoft’s search engine  
- [DuckDuckGo](https://duckduckgo.com) — Privacy-focused search engine  
- [Startpage](https://www.startpage.com) — Google results with enhanced privacy  
- [Yahoo Search](https://search.yahoo.com) — Web search with integrated news and content  
- [Yandex](https://yandex.com) — Russian search engine with strong image search  
- [Baidu](https://www.baidu.com/) — Leading Chinese search engine  
- [Swisscows](https://swisscows.com) — Family-friendly, privacy-based search  
- [Qwant](https://www.qwant.com) — European privacy-focused engine  
- [Brave Search](https://search.brave.com) — Independent index, privacy-first  
- [Mojeek](https://www.mojeek.com) — Independent UK crawler-based search  
- [MetaGer](https://metager.org/) — German metasearch engine with anonymization  
- [Ecosia](https://www.ecosia.org) — Eco-friendly search engine that funds tree planting  
- [Marginalia](https://marginalia-search.com/) — Alternative search engine for the “small web”  

### Academic and Research Search
- [Google Scholar](https://scholar.google.com.au/) — Search scholarly literature and academic papers  
- [Litmaps](https://app.litmaps.com/) — Visual literature discovery and citation network  
- [Semantic Scholar](https://www.semanticscholar.org/) — AI-powered academic search  
- [BASE](https://www.base-search.net/) — Bielefeld Academic Search Engine for scholarly resources  
- [CORE](https://core.ac.uk/) — Access millions of open access research papers  
- [WorldCat](https://www.worldcat.org/) — Global library catalog  

### Advanced Search and Dorking
- [Google Hacking Database (GHDB)](https://www.exploit-db.com/google-hacking-database) — Community-curated Google dorks  
- [Pentest-Tools Google Hacking](https://pentest-tools.com/information-gathering/google-hacking) — Automate Google dorking  
- [Boolean Strings](https://booleanstrings.com/) — Advanced boolean queries for OSINT  
- [Google Advanced Search](https://www.google.com/advanced_search) — Google advanced search form  
- [Google Search Operators](https://support.google.com/websearch/answer/35890) — Official operator reference  
- [Yandex Advanced Operators](https://yandex.com/support/search/en/search-results/settings) — Yandex operator reference  
- [Bing Search Operators](https://support.microsoft.com/en-au/topic/advanced-search-keywords-ea595928-5d63-4a0b-9c6b-0b769865e78a) — Bing operator reference  
- [DuckDuckGo Syntax](https://duckduckgo.com/duckduckgo-help-pages/results/syntax/) — Search syntax and operators  
- [Baidu Advanced Search](https://www.baidu.com/gaoji/advanced.html) — Baidu operator guide  

### Specialized Search Engines
- [Social Mention](http://socialmention.com) — Real-time social media search  
- [Social Searcher](https://www.social-searcher.com/) — Monitor mentions across social media  
- [Google Social Search](https://www.social-searcher.com/google-social-search) — Google-powered social media search  
- [Carrot2](https://search.carrot2.org/) — Clustered search results visualization  
- [DocJax](https://docjax.com) — Document search engine  
- [PublicWWW](https://publicwww.com) — Search source code and analytics IDs  
- [osint.sh](https://osint.sh/buckets) — Search exposed cloud buckets  
- [GrayHatWarfare](https://buckets.grayhatwarfare.com) — Public S3 bucket search  
- [I Search From](http://isearchfrom.com) — Google search simulator for location/device  
- [MAC.lc](https://mac.lc) — MAC address lookup
- [Marginalia](https://marginalia-search.com/) — Alternative search engine focusing on smaller sites  
- [Media Search Tool](https://www.no-nonsense-intel.com/adverse-media-search-tool) — Adverse media OSINT search tool  
- [Shodan](https://www.shodan.io) — Search for internet-connected devices  
- [Censys](https://censys.io) — Search infrastructure and SSL certificates  
- [FOFA](https://fofa.so) — Internet-wide search engine  
- [ZoomEye](https://www.zoomeye.org) — IoT and cyberspace search  
- [Thingful](https://www.thingful.net) — Search engine for IoT devices  
- [LeakIX](https://leakix.net) — Search exposed services and databases  

## 🗄 Website Archiving & Caching

### Web Archives
- [Wayback Machine](https://archive.org/web/) — The largest web archive for historic snapshots  
- [Archive.today](https://archive.today/) — On-demand webpage snapshots, bypasses paywalls  
- [Ghostarchive](https://ghostarchive.org/) — Archive YouTube and social media posts  
- [Memento Time Travel](http://timetravel.mementoweb.org/) — Aggregate snapshots from multiple archives  
- [Perma.cc](https://perma.cc/) — Permanent archiving for academic and legal citations  
- [WebCite](http://www.webcitation.org/) — Citeable web archiving service (legacy, limited availability)  

### Cached Pages and Mirrors
- [CachedView](http://cachedview.com/) — View cached versions from Google and Wayback  
- [CoralCDN Web Cache](http://www.coralcdn.org/) — Access cached copies of popular websites  
- [Google Cache](https://www.google.com/) — View cached versions of web pages (via “cache:” operator)  
- [Bing Cache](https://www.bing.com/) — Cached pages accessible via search results  

### Social Media and Multimedia Archiving
- [SavePageNow (Wayback)](https://web.archive.org/save) — Force snapshot into Wayback Machine  
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — Download and archive YouTube videos  
- [archivebox](https://github.com/ArchiveBox/ArchiveBox) — Self-hosted webpage archiving solution  
- [SingleFile](https://github.com/gildas-lormeau/SingleFile) — Browser extension to save complete pages as a single HTML

## 🛰 Geospatial & Mapping OSINT

### Satellite Imagery
- [Google Earth](https://earth.google.com/) — Global 3D imagery and satellite data  
- [Google Earth Pro](https://www.google.com/earth/versions/) — Desktop version with advanced tools  
- [Sentinel Hub](https://www.sentinel-hub.com/) — Access free Sentinel satellite imagery  
- [NASA Worldview](https://worldview.earthdata.nasa.gov/) — Daily global satellite data  
- [USGS EarthExplorer](https://earthexplorer.usgs.gov/) — Access historical satellite imagery  
- [ESA Copernicus Open Access](https://scihub.copernicus.eu/) — Sentinel mission data access  
- [NOAA Satellite Data](https://www.nesdis.noaa.gov/) — US environmental satellite imagery  

### Mapping and Street-level
- [Google Maps](https://maps.google.com/) — Standard mapping and geolocation platform  
- [Google Street View](https://www.google.com/streetview/) — Ground-level panoramas worldwide  
- [Mapillary](https://www.mapillary.com/) — Crowdsourced street-level imagery  
- [OpenStreetMap](https://www.openstreetmap.org/) — Community-driven world map  
- [Bing Maps](https://www.bing.com/maps) — Microsoft’s mapping solution  
- [HERE WeGo](https://wego.here.com/) — Mapping and routing platform  
- [Wikimapia](http://wikimapia.org/) — Collaborative map with user-added info  

### Satellite and Aerial Tracking
- [Space-Track.org](https://www.space-track.org/) — US Space Command satellite data  
- [N2YO](https://www.n2yo.com/) — Real-time satellite tracking  
- [Heavens Above](https://heavens-above.com/) — Satellite, ISS, and astronomy tracking  
- [SatNOGS](https://satnogs.org/) — Open-source satellite ground station network  
- [Celestrak](https://celestrak.org/) — Orbital data for satellites and debris  
- [In-The-Sky](https://in-the-sky.org/satmap_worldmap.php) — Interactive satellite maps  

### Geospatial Analysis Tools
- [SunCalc](https://suncalc.org/) — Calculate sun position and shadows for a given time  
- [PeakFinder](https://www.peakfinder.org/) — Identify mountains and terrain from coordinates  
- [GeoNames](https://www.geonames.org/) — Geographical names database  
- [QGIS](https://qgis.org/) — Open-source desktop GIS application  
- [ArcGIS Online](https://www.arcgis.com/) — Cloud-based mapping and spatial analysis  
- [Gephi](https://gephi.org/) — Visualization and spatial network analysis (general OSINT use)  

## 📰 News & Media Monitoring

### News Aggregators
- [Google News](https://news.google.com/) — Aggregated news across global sources  
- [Yahoo News](https://news.yahoo.com/) — Mainstream news aggregation and coverage  
- [Euronews](https://www.euronews.com/) — European and international news service  
- [AllSides](https://www.allsides.com/unbiased-balanced-news) — News aggregation with political bias rating  
- [NewsNow](https://www.newsnow.co.uk/) — Breaking news aggregation by region and topic  

### Media Search Engines
- [GDELT Project](https://www.gdeltproject.org/) — Global database of events, language, and tone in news media  
- [Media Cloud](https://mediacloud.org/) — Research tool for analyzing online news  
- [Event Registry](https://eventregistry.org/) — AI-driven news aggregation and analysis  
- [AYLIEN News API](https://aylien.com/news-api/) — News search and analysis API (freemium)  
- [Bloomberg](https://www.bloomberg.com/) — Business and global news (commercial)  
- [Reuters](https://www.reuters.com/) — International newswire service  

### Adverse and Risk-focused Media
- [Adverse Media Search](https://www.no-nonsense-intel.com/adverse-media-search-tool) — Search for adverse media reports on entities  
- [Dow Jones Risk & Compliance](https://professional.dowjones.com/risk-compliance/) — Adverse media and watchlists (commercial)  
- [LexisNexis Newsdesk](https://www.lexisnexis.com/en-us/professional/solutions/newsdesk.page) — Professional news and risk intelligence platform  

### Broadcast and Live Monitoring
- [LiveNewsNow](https://www.livenewsnow.com/) — Live streaming of news channels  
- [EarthCam](https://www.earthcam.com/) — Live webcams from around the world  
- [NewsLookUp](https://newslookup.com/) — News search engine with live feeds and archive  

### Social Media & Trend Tracking
- [CrowdTangle](https://www.crowdtangle.com/) — Facebook and Instagram content monitoring (restricted access)  
- [BuzzSumo](https://buzzsumo.com/) — Content monitoring and social trend analysis (freemium)  
- [Talkwalker Alerts](https://www.talkwalker.com/alerts) — Google Alerts alternative for media and web mentions  
- [Mention](https://mention.com/en/) — Monitor mentions across news and social media (freemium)

## 📷 Image & Reverse Search

### Reverse Image Search Engines
- [Google Images](https://images.google.com/) — Reverse image search and visual similarity  
- [Yandex Images](https://yandex.com/images/) — Powerful reverse search, especially for faces and objects  
- [TinEye](https://tineye.com/) — Reverse image search with focus on older content  
- [Bing Visual Search](https://www.bing.com/visualsearch) — Reverse image search from Microsoft  
- [Karma Decay](https://karmadecay.com/) — Reverse search for Reddit images  

### Metadata Extraction
- [ExifTool](https://exiftool.org/) — Extract EXIF and metadata from images  
- [Jeffrey’s Exif Viewer](http://exif.regex.info/exif.cgi) — Online EXIF metadata viewer  
- [Exif.regex](https://exif.regex.info/) — Alternative online EXIF viewer  

### Image Forensics
- [Forensically](https://29a.ch/photo-forensics/) — Online forensic suite for images  
- [FotoForensics](http://fotoforensics.com/) — Error Level Analysis and image authenticity tools  
- [Image Edited?](https://imageedited.com/) — Quick analysis of digital image edits  
- [IZITRU](http://www.izitru.com/) — Authenticate photo originality (legacy, limited availability)  

### Facial Recognition and Search
- [PimEyes](https://pimeyes.com/) — Face search engine (commercial)  
- [Betaface](http://www.betaface.com/demo.html) — Face recognition demo  
- [FindClone](https://findclone.ru/) — Russian facial recognition search engine

## 🎥 Video OSINT

### Video Verification
- [InVID/WeVerify](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) — Browser plugin for video verification and analysis  
- [YouTube DataViewer](https://citizenevidence.amnestyusa.org/) — Extract video metadata and upload time  
- [Amnesty YouTube Metadata Tool](https://citizenevidence.amnestyusa.org/) — Archive and metadata extraction  

### Video Download and Archiving
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — Download and archive YouTube and other videos  
- [4K Video Downloader](https://www.4kdownload.com/products/product-videodownloader) — Cross-platform video downloader (freemium)  
- [SaveFrom.net](https://en.savefrom.net/) — Quick video download service  

### Streaming and Broadcast Analysis
- [TwitchTracker](https://twitchtracker.com/) — Analytics and tracking for Twitch channels  
- [Streamscharts](https://streamscharts.com/) — Track statistics of live streams  
- [Facebook Video Insights](https://www.facebook.com/business/help/788388387972460) — Analytics for Facebook video content  

### Deepfake and Manipulated Media Detection
- [Deepware Scanner](https://deepware.ai/) — Tool to detect deepfakes in videos  
- [Sensity AI](https://sensity.ai/) — Commercial solution for deepfake and visual threat detection  

## 💼 Business & Company Intelligence

### Company Databases
- [OpenCorporates](https://opencorporates.com/) — Global database of company registrations  
- [Crunchbase](https://www.crunchbase.com/) — Business and startup intelligence (freemium)  
- [PitchBook](https://pitchbook.com/) — Private equity and venture capital database (commercial)  
- [CB Insights](https://www.cbinsights.com/) — Market intelligence and company data (commercial)  
- [PrivCo](https://www.privco.com/) — Private company financial intelligence (commercial)  

### Registries and Filings
- [SEC EDGAR](https://www.sec.gov/edgar.shtml) — US public company filings  
- [Companies House](https://www.gov.uk/government/organisations/companies-house) — UK company registry  
- [Canadian Corporations](https://www.ic.gc.ca/eic/site/cd-dgc.nsf/eng/home) — Canadian business registry  
- [Australian Business Register](https://abr.business.gov.au/) — Australian business records  
- [European Business Register](https://www.ebr.org/) — European cross-border company data  

### Business Intelligence Platforms
- [Orbis (Bureau van Dijk)](https://www.bvdinfo.com/en-gb/our-products/data/international/orbis) — Extensive global company data (commercial)  
- [D&B Hoovers](https://www.dnb.com/) — Company intelligence and sales intelligence (commercial)  
- [Kompass](https://www.kompass.com/) — Global B2B company directory  
- [Glassdoor](https://www.glassdoor.com/) — Employee reviews and salary information  
- [Craft.co](https://craft.co/) — Company profiles and org intelligence  

### Corporate Risk and Compliance
- [OpenSanctions](https://www.opensanctions.org/) — Database of sanctions lists and persons of interest  
- [World-Check (Refinitiv)](https://www.refinitiv.com/en/products/world-check-kyc-screening) — Commercial risk intelligence database  
- [Sayari](https://sayari.com/) — Global business risk intelligence platform (commercial)  
- [SEON](https://seon.io/) — Fraud prevention and business risk detection (commercial/freemium)  

## ⚖️ Government & Legal Records

### Court and Legal Databases
- [PACER](https://pacer.uscourts.gov/) — US federal court records (paid access)  
- [CourtListener](https://www.courtlistener.com/) — Free access to US legal opinions and filings  
- [Justia](https://www.justia.com/) — US law and case database  
- [BAILII](https://www.bailii.org/) — British and Irish legal information institute  
- [EUR-Lex](https://eur-lex.europa.eu/) — Access to European Union law  
- [CanLII](https://www.canlii.org/) — Canadian case law and statutes  
- [AustLII](http://www.austlii.edu.au/) — Australian legal database  

### Government Records and Open Data
- [Data.gov](https://www.data.gov/) — US government open data portal  
- [EU Open Data Portal](https://data.europa.eu/en) — European Union open datasets  
- [UK Data Service](https://ukdataservice.ac.uk/) — UK government open data  
- [World Bank Data](https://data.worldbank.org/) — Global development and economic datasets  
- [IMF Data](https://www.imf.org/en/Data) — International Monetary Fund data portal  

### Official Registers
- [UN Sanctions List](https://scsanctions.un.org/) — Consolidated United Nations sanctions  
- [Interpol Red Notices](https://www.interpol.int/en/How-we-work/Notices/View-Red-Notices) — Wanted persons database  
- [OFAC Sanctions List](https://sanctionssearch.ofac.treas.gov/) — US Treasury sanctions search  
- [FBI Most Wanted](https://www.fbi.gov/wanted) — FBI wanted fugitives list  
- [EU Sanctions Map](https://www.sanctionsmap.eu/) — Sanctions measures of the EU

## 📚 Academic & Research Databases

### General Academic Search
- [Google Scholar](https://scholar.google.com/) — Academic literature search  
- [Semantic Scholar](https://www.semanticscholar.org/) — AI-powered academic research engine  
- [BASE](https://www.base-search.net/) — Bielefeld Academic Search Engine for scholarly documents  
- [CORE](https://core.ac.uk/) — Global aggregator of open access research papers  
- [WorldCat](https://www.worldcat.org/) — Global library catalog  

### Scientific & Technical
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/) — Biomedical and life sciences literature  
- [arXiv](https://arxiv.org/) — Open-access preprints in science, math, and computer science  
- [IEEE Xplore](https://ieeexplore.ieee.org/) — Technical literature in engineering and computer science  
- [ScienceDirect](https://www.sciencedirect.com/) — Scientific publications and journals (commercial)  
- [SpringerLink](https://link.springer.com/) — Academic books and journals (commercial/freemium)  

### Research Tools
- [Litmaps](https://app.litmaps.com/) — Visualize citation networks  
- [ResearchGate](https://www.researchgate.net/) — Academic social network and research sharing  
- [Academia.edu](https://www.academia.edu/) — Platform for academic paper sharing  
- [OpenAIRE](https://www.openaire.eu/) — Open access research aggregator  
- [Directory of Open Access Journals (DOAJ)](https://doaj.org/) — Index of peer-reviewed open-access journals  
  
## 🤖 Automation & Recon Frameworks

### Recon Frameworks
- [SpiderFoot](https://www.spiderfoot.net/) — Automated reconnaissance with 200+ modules  
- [Recon-ng](https://github.com/lanmaster53/recon-ng) — Open-source recon framework  
- [Maltego](https://www.maltego.com/) — Link analysis and visualization platform  
- [OSRFramework](https://github.com/i3visio/osrframework) — Username, email, and phone recon  
- [theHarvester](https://github.com/laramies/theHarvester) — Harvest emails, hosts, subdomains  
- [datasploit](https://github.com/DataSploit/datasploit) — OSINT automation toolset  

### Browser Extensions and Utilities
- [Mitaka](https://github.com/ninoseki/mitaka) — IOC investigation from the browser  
- [Shodan Plugin](https://chrome.google.com/webstore/detail/shodan/jjalcfnidlmpjhdfepjhjbhnhkbgleap) — Shodan search extension  
- [Wappalyzer Extension](https://www.wappalyzer.com/apps) — Detect web technologies directly in browser  

### Metadata and Document Analysis
- [Metagoofil](https://www.edge-security.com/metagoofil.php) — Metadata extraction from public documents  
- [FOCA](https://github.com/ElevenPaths/FOCA) — Document metadata collection and analysis  
- [Bulk Extractor](https://github.com/simsong/bulk_extractor) — Forensic tool for extracting digital artifacts  

### Self-hosted and Modular Platforms
- [Cortex](https://github.com/TheHive-Project/Cortex) — Observable analysis and enrichment framework  
- [OpenCTI](https://www.opencti.io/en/) — Threat intelligence platform with enrichment modules  
- [IntelOwl](https://github.com/intelowlproject/IntelOwl) — API-driven threat intel and OSINT automation  
- [Kali Linux](https://www.kali.org/) — Linux distribution with OSINT and recon tools included

## 📡 Intelligence Feeds

### Community Threat Feeds
- [ThreatFox](https://threatfox.abuse.ch/) — Community-driven IOC feed  
- [URLhaus](https://urlhaus.abuse.ch/) — Malicious URL tracker  
- [Feodo Tracker](https://feodotracker.abuse.ch/) — Banking trojan command and control trackers  
- [MalwareBazaar](https://bazaar.abuse.ch/) — Malware sample and hash sharing platform  
- [AlienVault OTX](https://otx.alienvault.com/) — Open threat exchange community  

### Commercial and Specialized Feeds
- [Spamhaus](https://www.spamhaus.org/) — Blocklists for IPs, domains, and spam sources  
- [AbuseIPDB](https://www.abuseipdb.com/) — Community-reported IP abuse database  
- [CIRCL OSINT Feeds](https://www.circl.lu/services/osint/) — Public OSINT-based threat feeds from Luxembourg  
- [Abuse.ch SSLBL](https://sslbl.abuse.ch/) — SSL certificate blocklist for malicious infrastructure  
- [PhishTank](https://phishtank.org/) — Community phishing URL repository (overlaps phishing but also feed source)  
- [OpenPhish](https://openphish.com/) — Automated phishing intelligence feed  

### Attack Surface and Internet Scanning
- [GreyNoise](https://www.greynoise.io/) — Contextual intelligence for internet scanners  
- [Shodan Alerts](https://www.shodan.io/alerts) — Monitor exposure of internet-connected assets  
- [Censys Search and Data](https://censys.io/) — Enriched dataset of hosts and certificates

## 🧑‍🤝‍🧑 OSINT for Good (NGOs & Initiatives)

### Child Protection and Exploitation Prevention
- [NCMEC](https://www.missingkids.org/) — US National Center for Missing and Exploited Children  
- [Europol Trace an Object](https://www.europol.europa.eu/stopchildabuse) — Crowdsource identification of child abuse materials  
- [NCPTF](https://www.ncptf.org/) — National Child Protection Task Force  
- [FBI ECAP](https://www.fbi.gov/wanted/ecap) — FBI Endangered Child Alert Program  
- [Trace Labs](https://www.tracelabs.org/) — Crowdsourced OSINT for missing persons  

### Anti-Trafficking and Human Rights
- [Innocent Lives Foundation](https://www.innocentlivesfoundation.org/) — Identify perpetrators of child exploitation  
- [StopTheTraffik](https://www.stopthetraffik.org/) — Global initiative to disrupt human trafficking  
- [ATII](https://followmoneyfightslavery.org/) — Anti-Human Trafficking Intelligence Initiative  
- [BADASS Army](https://badassarmy.org/) — Fight against non-consensual image sharing  
- [Amnesty Citizen Evidence Lab](https://citizenevidence.org/) — Tools and resources for human rights verification  

### Crisis Mapping and Volunteer Intel
- [Humanity Road](https://www.humanityroad.org/) — Crisis response and disaster mapping  
- [CrisisMapping Network](http://crisismapping.ning.com/) — Community for humanitarian crisis mapping  
- [InformNapalm](https://informnapalm.org/en/) — Volunteer intelligence about conflicts and disinformation  
- [Locate International](https://locate.international/) — Cold case review and investigation through OSINT  

## 📚 Learning Resources

### Guides and Books
- [Open Source Intelligence Techniques (Michael Bazzell)](https://inteltechniques.com/) — Comprehensive OSINT book and toolkit  
- [Bellingcat OSINT Guides](https://www.bellingcat.com/resources/) — Investigative journalism and OSINT techniques  
- [OSINT Techniques (Sector035’s Curated Lists)](https://sector035.nl/) — Weekly curated OSINT links and guides  
- [Handbook of Collective Intelligence](https://collective-intelligence.github.io/) — Research and methodology (academic)  

### Training and Communities
- [OSINT Dojo](https://www.osintdojo.com/) — Free structured learning path for OSINT  
- [OSINT Curious](https://www.osintcurio.us/) — Blog, podcast, and tutorials (archived but valuable)  
- [Trace Labs OSINT VM & CTFs](https://www.tracelabs.org/) — Virtual machines and OSINT competitions  
- [Quiztime](https://twitter.com/quiztime) — Daily OSINT challenges on Twitter/X  
- [Bellingcat Workshops](https://www.bellingcat.com/workshops/) — Paid training on open source investigations  

### Blogs and Podcasts
- [SecJuice](https://www.secjuice.com/) — Articles on OSINT, infosec, and cyber investigations  
- [NoHat](https://www.nohat.cc/) — OSINT and cybersecurity research blog  
- [SANS OSINT Blog](https://www.sans.org/blog/osint/) — Professional OSINT articles  
- [CyberWire Daily](https://thecyberwire.com/podcasts/daily-podcast) — Cybersecurity news and OSINT-adjacent podcast  

## ⚖️ License

**CC0-1.0 Universal (Public Domain Dedication)**  
No rights reserved. Use, modify, or share freely. Attribution appreciated.  

