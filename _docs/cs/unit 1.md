---
title: System Fundamentals
description: Unit 1 of Computer Science
---

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
