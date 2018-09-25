# sFractal Consulting Use Cases 

This directory contains use cases for the OpenC2 language as contributed by sFractal Consulting.
These use cases are of particular interest to sFractal Consulting.
Other members are welcome to utilize these use cases as they fit, 
including modifying them to fit their organization's interests.

## 1. C4 - Collective Code Construction Contract 
### 1.1 Ground Rules
Please read README in parent directory for groundrules on LSC use cases.

### 1.2 Licensing
All text contributed here by sFractal Consulting is released under the 
[Creative Commons CC0 License](https://creativecommons.org/share-your-work/public-domain/cc0/).

![Creative Commons CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)


### 1.3 Contact 
Contact Duncan Sparrell, Chief Cyber Curmudgeon, sFractal Consulting with any comments or suggestions.


### 1.4 Style 
Use Case is a very overloaded term and means different things to different people.
A scenario approach will be used for what is presented here.
Each file will contain one scenario, sometimes based on initial conditions
set up in previous scenarios, but intending to stand on it's own
to show a particular desire.
Each scenario will be told in narrative (like chapters in a book)
and will have endnotes for:
 * references
 * explanatory text, asides
 * "stories"
The narrative will attempt to be from an OpenC2 paroachial viewpoint - glossing over details
not relevant to OpenC2 and diving deeper into requirements on OpenC2.
OpenC2 requirements and examples will attempt to be shown on separate referenced pages in
Agile SDLC (Software Development Life Cycle) 'user story' 
format<sup>[1](#endnote1)</sup>
eg
> As a {role}, I want {feature} so that {reason}.

> As sFractal's  orchestrator, I want to use an OpenC2 command to tell the firewall to block ip=whaterver so that the hacker can't get in.

> As the Small Business Administration, I want to use OpenC2 to tell sFractal to mitigate evildomain.com so that evildomainowner can be thwarted in attacking small buinsess webservers.

## 2. Description and  Organization 
The scenarios are:
 * 00.websvr_basecase.md
   - the intial condition to start the narrative 
   - TL;DR - some resources in a cloud which is accessed from internet via an API
 * 01.another_user.md
   - TL;DR - allow second user access from internet
 * 02.sensing.md
   - TL;DR - increase logging for a particular event
 * 03.sensemaking_basecase.md
   - TL;DR - some more base case info - add sensemaking app
 * 04.sensemaking.md
   - TL;DR - request metadata about suspicious ip attempting wierd stuff
 * 05.risk_basecase.md
   - TL;DR - some more base case info - add risk/value app
 * 06.risk.md
   - TL;DR - query risk manager about effect of current state on loss exceedance curves
 * 07.new_fw_vendor.md
   - TL;DR - spin up new fw vendor to replace old due to some new attack
 * 08.interdomain_basecase.md
   - TL;DR - some more base case info - add link to SBA
 * 09.interdomain.md
   - TL;DR - SBA stix COA to sFractal to mitigate evildomain.com
 * 10.deception_basecase.md
   - TL;DR - some more base case info (more machines not needed for previous use cases)
 * 11.deception.md
   - TL;DR - some neat deception stuff that needs to be thought up
 * 12.idam_basecase.md
   - TL;DR - some more base case info (more machines not needed for previous use cases)
 * 13.idam.md
   - TL;DR - some idam stuff that needs to be thought up, maybe use KMIP?
 * 14.init.md
   - TL;DR - Commands to setup (or re-setup) 01.another_user.md. Note this is a 'build' usecase not an 'incremental' or 'response' use case (and hence my be for distant future, if ever), wrt OpenC2.
 * 15.abuseJson.md
   - TL;DR - Abuse cases for Malformed JSON, or malformed OpenC2, or command not supported
 * 16.iot_basecase.md
   - the intial condition to start the IoT narrative
   - TL;DR - a bunch of home IoT devices managed from the internet
 * 17.no_resp_procid.md
   - TL;DR - security manager kills rogue process
 * 18.no_resp_update_sw.md
   - TL;DR - security manager does mass software update
 * 19.resp_update_sw.md
   - TL;DR - security manager does single software update
 * 20.bad_url.md
   - TL;DR - security manager adds bad url to webproxy
 * 21.bad_email.md
   - TL;DR - security manager quarantines a bad email
 * 22.bad_file.md
   - TL;DR - security manager deletes bad file
 * 23.detonate_file.md
   - TL;DR - security manager detonates potential malware
 * 24.version.md
   - TL;DR - get OpenC2 version
 * 25.create_vm.md
   - TL;DR - create AWS VM
 * 26.dos_epic.md
   - TL;DR - epic (ie multiple use cases/stories) about attack response
 * 27.cancel_command.md
   - TL;DR - cancel previously issued command

## Endnotes
 1. <a name="endnote1">See</a> http://www.agilemodeling.com/artifacts/userStory.htm
