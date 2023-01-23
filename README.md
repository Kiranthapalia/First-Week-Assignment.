# H1 First week exercises.

## 1

A summary of the given topic.

**Intrusion-Kill-Chain:**
- A kill chain is a systematic way to confront an adversary and produce the desired results. In this research, a novel kill chain model for invasions is presented.
- It includes reconnaissance, weaponization, delivery, exploitation, installation, command and control, and actions on objectives. 
- Email attachments, web sites and USB removable media are the most common delivery vectors for weaponized payloads by APT actors.
-  Increasingly, client application data files such as Adobe Portable Document Format (PDF) or Microsoft Office documents serve as the weapon's payload.

**Courses-of-Action:**
- When defenders match enterprise capabilities to the precise methods an adversary employs to target that enterprise, the intrusion kill chain becomes a model for actionable intelligence.
- Defenders can measure the performance as well as the effectiveness of these actions, and plan investment roadmapsto rectify any capability gaps. To better safeguard their own system, defenders might use intrusion kill chain to think like attackers.
- Table 1 depicts a course of action matrix using the actions of detect, deny, disrupt, degrade, deceive, and depicts in the exploitation phase, for example, that host intrusion detection systems (HIDS) can passively Illustrating the spectrum of capabilities defenders can employ, the matrix includes traditional systems like network intrusion detection systems (NIDS) and firewall access controladversaries that continually adapt their operations over time.particularly previously undisclosed “zero-day” exploits.
- Defenders can generate metrics of this resiliency by measuring the performance and effectiveness of their defenses against intruders.
- In December, defenders detect the weaponization and block the delivery but uncover a brand new, unmitigated, zero-day exploit in the process. In March, the adversary re-uses the same exploit, but evolves the weaponization technique and delivery infrastructure, circumventing detection and rendering By June, the defenders updated their capabilities sufficiently to have detections and mitigations layered from weaponization to C2. kill chain, defenders had the proper perspective of the relative effect of their defenses against the intrusion

*My thoughts*
- A security risk exists whenever a computer is connected to a network. 
- Nobody can ensure 100% safety. But we can always lessen the damage.
- Is there ever going to be a moment when information is completely safe?

## 2

**Karvinen 2020: Command Line Basics Revisited**

This was a fairly nice review read because I just finished my server technologies course, where we had to use the same commands in the Ubuntu server. I did discover some new commands that were useful.


## A) Bandit oh-five.

Our task was to solve level 0-4.(Mandatory) in the [Over The Wire Games](https://overthewire.org/wargames/bandit/bandit0.html)

*For the first level*

First i installed the ssh server using the command 

``` sudo apt install openssh-server ```

then I used the command `ssh bandit0@bandit.labs.overthewire.org -p 2220`to connect.


