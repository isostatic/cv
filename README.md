# Paul Weaver

_An experienced BBC Broadcast Engineer with two decades of experience in multiple aspects of TV News_

[Email](mailto:paul@zpjw.net) / [Website](https://newweaver.com/) / [LinkedIn](https://www.linkedin.com/in/pauljamesweaver/) / [GitHub](https://github.com/isostatic/) / [CV](https://cv.newweaver.com)

## Experience

### Systems Engineer [BBC News](https://news.bbc.co.uk) 2016-2023

  - Full Stack Network Engineer
    - Responsible for design, build and operation of BBC's vendor-agnostic (Cisco, Juniper, Fortigate, Arista, Mikrotik) contribution network operating across hundreds of devices over dozens of sites nationally and internationally
    - Development and introduction of gitops powered automation in various parts of the network
    - Responsible for development of secure ways to access various remote production systems during Covid (OIDC integration into custom firewall controls, wireguard, remote desktop etc)
    - Development and operation of monitoring systems to provide visibility of network and broadcast infrastructure
  - Broadcast Operations
    - Designed and delivered connectivity for multiple major events (all 3 nominees for the RTS 2023 Line Event category were delivered by my team), including Covid-affected events, culminating in the funeral of Queen Elizabeth II where I was personally responsible for connectivity across 4 sites in Westminster
    - Designed and delivered IP contribution across various events from Sports to Concerts to Royal Funerals
    - Proven agility to respond to last minute requests and cope with unexpected events under unmovable deadlines
  - System Administration
    - Jointly responsible for various Xen Hypervisors and most of the VMs to provide the network and associated tools (DNS, proxy, monitoring etc) based mainly around Ubuntu
  - Software Development
    - BLT, a latency measurement system for measuring audio drift (Perl and C++)
    - [RTP transport stream monitoring system](https://github.com/isostatic/rtp_reader) (Python)
    - Wrappers around our IP management to improve with our A/B (PHP)
    - Network performance tool to investigate ZScaler issues in countries without local nodes (NodeJS)

### Project Manager [BBC News](https://news.bbc.co.uk) 2015-2016

  - Design and delivery of technical aspects of a [major new international bureau in Singapore](https://www.bbc.co.uk/mediacentre/worldnews/2015/new-asia-pacific-news-hq)
  - Project involved a constrained timetable with very limited time to pilot and launch (2 weeks from shut down of previous bureau to on air at new office)
  - Deployment of unproven (in the BBC) technologies including new CasparCG graphics

### Systems Development Engineer [BBC News](https://news.bbc.co.uk) 2006-2015

  - Third and fourth line support and development of the Jupiter/Quantel news production suite 
  - Conception, design and development of 'Davina', the web interface to BBC's "Jupiter" news production system
  - Design and development of the primary ['JFE' tool](https://www.tvbeurope.com/production-post/newsroom-systems-tv-journalism-on-jupiter) for delivering recorded packages from the field back to base (Java)
  - Design and development of the core BBC News monitoring system (Nagios)
  - Sysadmin work including standardisation of the BBC News internal Linux platform (Ubuntu)
  - Significant amounts of international work covering a variety of broadcasting technologies from cameras, to networks, to graphics, including development of network of international video contribution

### Trainee Broadcast Engineer [BBC News](https://news.bbc.co.uk) 2003-2006
  - BBC Engineering training at Wood Norton, combined with on-the-job training in a 24/7 technical support environment supporting BBC News production facilities in Television Centre

## Major Projects
### 2019 BCN Re-architecture
The BBC's contribution network had grown slowly since 2012, but in 2019 a colleague and I were giving limited funding to transform it into a reliable platform that could take an essential core part of the BBC's IP strategy which could be trusted to deliver the output for major events such as [the funeral of Elizabeth II](https://en.wikipedia.org/wiki/Death_and_state_funeral_of_Elizabeth_II) and [Coronation of Charles III](https://en.wikipedia.org/wiki/Coronation_of_Charles_III_and_Camilla), as well as normal events such as [Glastonbury](https://en.wikipedia.org/wiki/Glastonbury_Festival), [Reading](https://en.wikipedia.org/wiki/Reading_and_Leeds_Festivals) and key remote-production events like [Springwatch](https://en.wikipedia.org/wiki/Springwatch). 

### 2015 BBC Singapore Move
In 2015 the BBC moved its Asia Business operation to a new studio. I lead on the technical design and implementation of a major new international bureau for the BBC, which included the specification and implementation of
    - Resilient IP Video network supporting a variety of broadcast codecs
    - On set and lower third graphics using Caspar CG
    - In house product (Raven) to power on-set video wall and gallery playouts
    - Expansion of the video archive system
As well as the the planning and migration of existing broadcast infrastructure

### 2010-2014 International video contribution
From 2010 onwards I designed and installed the BBC's international bureau IP video contribution network, utilising NTT encoders to broadcast via low cost internet connections from approximately 20 countries on 5 continents, including the 2014 US Midterm elections
    - Design of initial operational control system to allow encoders to feed into hubs in London and Singapore
    - Design of bespoke monitoring system to identify network problems and route around them
    - Physical installation of encoders and self-op studios in a variety of locations from Gaza to Bangkok, including going straight to live in Bangkok to cover an [unexpected explosion](https://en.wikipedia.org/wiki/2013%E2%80%932014_Thai_political_crisis)

### 2010-2014 JFE
JFE is in house software for exchanging video with BBC journalists in the field. It allows them to access the BBC's production systems across approximately 20 sites and file back packages from anywhere in the world. For a decade or so, JFE put approximately half of the typical BBC News bulletin on air, and allows high quality HD to be fed back in short order thanks to a combination of FFMPEG video compression and deep integration into News workflows and production systems. JFE was developed in a responsive way in collaboration with field shoot-edits to meet real business needs. While increased bandwidth means the need to highly compress recorded material is less essential, it is still in daily use in 2023 with little extra development

### 2008 BBC News standard Linux build
Built an engineer-friendly version of Ubuntu to allow BBC News and elsewhere in the organisation to standardise our Linux estate. Based originally on Ubuntu 8.04 (and updated with every LTS release), it brought common reporting, monitoring and user management to a previous ecosystem consisting Redhat, Suse, Solaris and Mandrake machines. This allowed the department to draw on great efficiencies in its server infrastructure. 

### 2006-2008 Davina
I created a web-based interface to the internal BBC News production system "Jupiter", allowing people outside of the BBC newsroom to search, view and use every video asset that News holds, from a desktop in Exeter to a blackberry in Botswana. This was envisaged and created in direct response to end users comments. The system is still in daily use in 2023 with very little extra development beyond moving video from Flash to HTML when the iPhone started to replace the blackberry.

## Education

**BBC Engineering Training** in Computer Science<br>
[BBC Wood Norton](https://www.bbc.co.uk/academy) - Evesham, UK (2003-2006)

**Bachelor of Science** in Computer Science<br>
[Exeter University](https://www.exeter.ac.uk/) - Exeter, UK (2000-2003)
