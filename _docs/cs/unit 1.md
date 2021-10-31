---
title: System Fundamentals
description: Unit 1 of Computer Science
---
> Unit 1: System Fundamentals

# System Life Cycle

## Systems in Organizations

### System life cycle

`System Life Cycle` discusses the process of developing a new system.
- Existing System Analysis
- Requirement Specification
- Software Design
- Software Implementation
- Testing & Debugging
- New System Installation
- Maintenance

Often times, we can simplify this to the `Software Life Cycle`.
- Planning and Analysis
- Design Overview
- Development
- Evaluation

### Planning a New System

A computer system includes:
- software
- hardware
- environment and people using it

Sometimes, organizations need to upgrade their computer systems.
We can use the acronym `TELOS` to decide if a new system should be implemented.

- __Technical Feasibility__: Can we actually implement this system?
- __Economic Feasibility:__ Is the system cost effective?
- __Legal Feasibility:__ Is there any legal issues?
- __Operational Feasibility:__ Is the current practices sufficient to support the new system?
- __Schedule Feasibility:__ How long do we need to wait?

### Change Management

`Change Management` refer to the process of shifting individuals, teams, departments, and organizations.
Good change management guarantee that stakeholders can accept and embrace the change of environment.
The purpose of Change Management is move a company into a more efficient state, while minimizing the negative effects of the process.

### Compatibility Issue

There may be compatibility issues when encountering a `Legacy System`.
Legacy is a general term referring to old technology.
For example, an old printer may be called a legacy printer.
Keeping around legacy systems is troublesome, since companies may no longer support the technology (replacement parts are no longer produced, security updates are no longer issued).
There may also be compatibility issues when interacting with legacy systems, as it might not support new protocols, or have a outdated proprietary software.

Although not all legacy systems have to updated.
As long as the legacy system functions well and there are no better alternatives, they can be kept in a business.
Administrators have to be careful in the case that legacy systems cannot be upgraded (due to software/hardware incompatibility).

#### Four Strategies of Integration

1.  Keep both information system, and develop them to have the same functionality: `high maintenance cost`
2.  Replace both information systems with a new one: `increased inital cost`
3.  Select the best information system from each company and combine them: `user acceptance difficulty`
4.  Select one company's information systems and drop the other companies': `policy problems`

### SaaS

Nowadays, there is many different methods of providing business software.
Some clients install their software on their own premises, while other have the software installed on dedicated servers that provide these services.

`Software as a Service (SaaS)` is one of the methods of providing services.
Software and data is hosted on a remote data center, where clients pay fees to access the services.
SaaS relies heavily on the Internet. Some examples of SaaS are Dropbox, Gmail, and Salesforce.

#### Advantage

SaaS is less expensive and have a lower initial cost.
It is easier to install, maintain, and upgrade.
It is easily scalable, allowing for rapid growth. It requires less IT staff to manage.

#### Disadvantage

However, SaaS requires a constant Internet connection.
It is based on a monthly subscription.
Since the information is stored on a remote server, there is no guarantee of security.

### Alternative Installation Process

Installing a new system is a necessary evil in many enterprises.
Many users do not like to adjust to a new system, and changeover can cause many compatibility issue.
There are four common approaches to software changeovers:

#### Parallel

In a `Parallel Changeover`, both software work simultaneously for a period of time.
If the new system fails, the old system is usable.
Only when the new system run smoothly for an extended period of time can the old system be retired.

Parallel changeover is the safest method, but the most time consuming.
Due to both systems running at the same time, additional resources is needed to support both systems.
This method is not effective if the old system and new system perform different tasks.

#### Big Bang

`Big Bang`, or `Direct Changeover` is a risky operation where the old system is retired immediately, and the new system is immediately put in use.
This method should be only used for non critical systems.
In this case, all users need to be trained prior to the switch on the new system.

#### Pilot

A `Pilot Changeover` is used in a company with a lot of sites.
In a pilot changeover, new systems are introduced one site at a time.
This method allows for a enterprises to test out the new system before implementing it fully.
The feedback received from each system can be used to improve the changeover process at other sites.

#### Phased

A `Phased Conversion` is used with a system with many modules.
The new system is implemented one module at a time.
This approach allows for an extended training and adoption of the system, but takes more time.

### Data Migration

`Data Migration` is the process of transferring data to a different format, storage type, or computer system.
There are many problems that will occur when data is transfered between two systems.
Errors such as incompatibility, corruption, virus, etc, can cause irreparable lost to the data.
If it's possible, back up data before migrating.
To guarantee the safety of the data, following three steps when migrating data.

1.  Plan
2.  Migrate
3.  Validate

### Testing

Testing ensures that a computer system follows the user's specification, and runs well without bugs.
There are several forms of testing.

- __Functional Testing:__ test the normal functions of the program
- __Data Testing:__ test a system response to different data types
	* _Normal Data:_ data program expects
	* _Data at Limits:_ normal data that causes a program respose
	* _Extreme Data:_ normal data outside of expected range
	* _Abnormal Data:_ unexpected types of data
- __Alpha Testing:__ testing within development environment
- __Beta Testing:__ testing given to selected, small, user base, collect feedback from users
- __Dry-run Testing:__ programmer runs through algorithm with pen and paper
- __Unit Testing:__ testing individual components of a program
- __User Acceptance Testing:__ determine of system satisfies user need
- __Debugging:__ systematic progressing of finding and fixing bugs

Sometimes, programs will be designed to test other programs.
This help speed up the testing process.

#### Validation and Verification

- `Validation` is the process of evaluating if the data is _correct_
- `Verification` is the process of evaluating if the data _make sense_

In the context of checking for password:
A validation method is asking the user to type the password twice.
A verification method is checking for the password strength.

## User Focus and Documentation

Programs and systems become increasingly complex as more and more features are added.
Often times, this will result in a confusing mess for users.
Systematic and organized documentation can help with this issue.
In fact, documentation also help with further development of the software.

There are two types of documentation:
- __Internal Documentation:__ provide information on the source code
- __External Documentation:__ separate document on the design and implementation of the program

Documentation is provided by:
- manuals
- email support
- embedded assistance/integrated user assistance
- frequently asked questions
- live chat sessions
- online portals
- remote desktop connections

Users can learn to use a program by:
- self study
- formal classes
- distance learning

## Data Loss

`Data loss` is an unavoidable part of systems.
System back up is a method of preventing data loss.

Possible reasons of data loss are:
- accidental deletion
- administrative errors
- data misplacement
- building fires
- closing program without saving 
- computer virus
- continued use after signs of failure
- data corruption
- firmware corruption
- natural disasters
- physical damage
- power failure

Data loss can cause serious consequences.
Consider the data loss of patient records in a hospital, or data loss from a bank.

We can prevent data loss by:
- backup files
- offsite storage
- using a firewall
- remove hard copy (printed data)
- use anti-virus software

`Redundency` is the term describing duplication of hardware.
Redundancy allows for failsafe in case of hardware failure, reducing downtime.
A `fail over` system will switch a failed device to its redundant failsafe.

Back ups should follow the 3-2-1 rule:
- 3 copies of data, 1 primary copy and 2 back ups
- storing in 2 different types of media, (tape, NAS, etc)
- Store one copy off site (cloud or other location)

## Software Deployment

Updating software is essential for maintaining a system.
There are several methods of providing automatic updates:
- __Patches:__ contains small changes that fix bugs and vulnerability
- __Upgrades:__ contains new features
- __Updates:__ improves the product in a minor way
- __Releases:__ final working versions of a software

# System Design Basics

## Components of a Computer System

A computer system is made up of several components:
- __Hardware:__ physical elements
- __Software:__ programs and instructions
- __Peripheral Devices:__ auxiliary devices that can work with a computer (usb/screen)
- __Computer Network:__ a group of computers connected together to share resources and data
- __Human Resources:__ workers required in a computer system

### Client and Server

There are many types of computer in a computer system, they mostly follow under the category of `client` and `server`.
- __Client:__ a computer that request and receive data on a network
	* _Dumb Terminal_: terminal used for connecting to other computers
	* _Thin Client:_ client with a certain amount of processing power, used similar to a dumb terminal
- __Server:__ a computer that responds to requests and sends information to other computers on the network
	* _Email Server:_ send and receive electronic mail
	* _Domain Name System:_ record down domain names to ip address

In a `Client-Server` network, clients are connected to a server.
Where all the data and resources are stored on the server, the clients request the data from the server.

In a `Peer to Peer` network, computers can be both clients and servers.
Each computer send and requesting data.

### Social and Ethical Issues

As the use of IT become more and more common, there are more and more ethical and social issues rising.
Below is a list of some issues to be careful of:
- __Reliability:__ when IT systems fails, there may be serious consequences
- __Integrity:__ if an IT system provides inaccurate data, there may be serious consequences
- __Privacy:__ IT systems gather large amounts of personal data, this data have to be private
- __Anonymity:__ Whether the privacy issues with IT system can reveal a person's identity
- __Intellectual Property:__ does the development of IT make stealing IP easier? (copy and paste, pirated software/media)
- __Security:__  if an IT system is unsecure, it may cause the issues above
- __The Digital Divide and Equality of Access:__ does everyone around the world have the same access to IT?

One must consider the social and ethical problems of IT before implementing a system.

## System Design and Analysis

### Stakeholders

`Stakeholders` are people who are affected by an computer system.
An `end-user` is a person who will use the computer system.
Computer systems must be designed according to the needs of the stakeholders and the end-users.

We can gather information on the stakeholders by direct observation, conducting interviews, and questionnaires.
On the other hand, we can analyze existing systems or competing products.

### System Requirements

There are many system requirements to designing a computer system.

It is often useful to determine the type of processing a computer system have to perform beforehand:
- __Online Processing:__ interactive processing performed by a single processor
- __Real Time Processing:__ Data processed and generated in real time, effect program as data change
- __Batch Processing:__ groups of data are processed as a single unit

Flow charts can describe the process of a computer program:
**TODO**

We can check if a proposed system matches the client's expectation by creating `prototypes`.
Prototypes are a bare-bones, working version of the system for testing purposes.
Prototypes can give the clients a general idea of what will the final system look like.

Often times, a system will be redesigned many times.
Each prototypes will refine the product, until it reaches the client's specification.
Stakeholders may be involved in this process. 

### Ethical Issues with Introducing a New System

## Human Interaction with the System

### Accessibility 

`Accessibility` is many people can use a certain program. 
A system with high accessibility means many people can use it.
Often times, accessibility of computer systems also refer to if people with different physical and mental attributes can use it.
For example, can a blind person use said software?

Some methods of improving accessibility are:
- text to speech
- braille display
- subtitles
- large buttons

### Usability

`Usability` is how easy a program is to be used.
Some common usability metrics are:
- complexity of program
- efficiency
- effectiveness
- errors
- learn-ability
- memorability
- readability
- satisfaction

Some common usability issues are:
- having a small screen
- hard to click
- too many buttons
- too bright/dark
- short battery life
