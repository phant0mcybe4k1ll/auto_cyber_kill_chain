<h1 align="center">
  <br>
  <a href="https://github.com/phant0mcybe4k1ll/auto_cyber_kill_chain"><img src="https://github.com/phant0mcybe4k1ll/auto_cyber_kill_chain/blob/main/ressources/images/cyber_kill_chain.png" alt="Cyber Kill Chain" ></a>
  <br>
  Cyber Kill Chain Automatisation
  <br>
</h1>

<h4 align="center">An Open Source Project for automating  <a href="https://www.crowdstrike.com/en-us/cybersecurity-101/cyberattacks/cyber-kill-chain/" target="_blank">Cyber Kill Chain</a>.</h4>

<p align="center">
  <a href="https://badge.fury.io/js/electron-markdownify">
    <img src="https://badge.fury.io/js/electron-markdownify.svg"
         alt="Gitter">
  </a>
  <a href="https://gitter.im/amitmerchant1990/electron-markdownify"><img src="https://badges.gitter.im/amitmerchant1990/electron-markdownify.svg"></a>
  <a href="https://saythanks.io/to/bullredeyes@gmail.com">
      <img src="https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB.svg">
  </a>
  <a href="https://www.paypal.me/AmitMerchant">
    <img src="https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&amp;style=flat">
  </a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#key-features">Road Map</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#download">Download</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#license">License</a>
</p>

# Authors

- [@phant0mcybe4k1ll](https://github.com/phant0mcybe4k1ll)


# Key Features

In this project we want to try to implement some existing mecanisme and contrebute in a possible Prof Of Concept (POC) for automating the cyber kill chain (CKC) process. 

Our approche is simple, it's based on dealing with every stage of the CKC  alone, the idea is :
  - Define and undertand the Step.
  - Enumerate and test a number of OSINT Tools in the step in defferent Target classes.
  - aplay different existing mecanismes of data fusion for making the right decisions and return the possible PATHS.
  - Using AI to determine the order of the PATHs to run.
  - Optimize The mecanisme.
  - Implement the step as a module of our tool. 

# Roadmap - Done -
This is a status of Already Handled Subjects in the menu bellow.

# Roadmap

This is a road map designed to organis the work and markedown all the contributions in all defferent stages of the Cyber Kill Chain Process.

## Preparation
This stage does not belong to the CKC process, its an additional stage that we have added in order to prepare, organise and normalise all sorts of engagements.

The stage represent the Input-Output identification & categorization, any attacker needs to know his targets (Inputs) and his Objectives (Output) before entring the Pipeline of the engagement.
1. ## Target Identification :
     First of all in red teaming we need to know our target, we need to specify its classe based on the Attack surface of the Target, in order to establich the right PATH to attack it.

     In order to achieve this we gonna create a CANVAS as [xlsx](/ressources/canvas/target_identification.xlsx) file to help making a full CV of the Target, based on this CANVA the target will be assigned a classe.

     Before getting into the CANVA we need to enumorate the target possible classes.
2. ## Target categorizing :
    Those are the categories of a Target:

    - Individuals : When it cames into personnal informations gathering, credentials theft, spying & remote controling personnal devices
    - Information Systems : When it comes into Entreprises (Private or Governemental) information systems, services, networks & critical IT infrastructures.
    - Operationnal Systems : when it cames into operational technologies, firmwares, networkd and infrastructures.
    - public ressources : when it cames to unkown targets, for botnets creation.

3. ## Objectives Identification :
    Before Entering in any sort of cyber attack, the attacker needs to identify his objectives and intetions behind the attack in order to estimate the effort and time and limit actions in the last stage and ofcourse in the contexte of our tool is for helping identifying the order of the PATHS. 

    In our case we need to categories our objectives also, and for that we have prepared a baunch of questions that helps the attackes limit his objectives to a specific classe or category. 

4. ## Objectives categorizing :
    These objectives guide the attacker's actions and the strategies they employ during the cyber kill chain process : 

    - Data Exfiltration : teal sensitive data such as intellectual property, personal identifiable information (PII), financial records, or classified government documents.

    - Financial Gain : Directly or indirectly steal money or resources (blackmailing with ransomware for crypto).

    - Spying (Espionage ) : Conduct espionage to gain access to proprietary information, intellectual property, or national secrets.  

    - Reputation Damage : Damage the reputation of an individual, organization, or government entity by exposing sensitive or embarrassing information.

    - Disruption / Denial of Service : Disrupt or deny access to services, systems, or networks, causing downtime or operational disruption.

    - Sabotage / Destruction : sabotage operations, damage assets, or retaliate against an organization or government.

    - Compromising Critical Infrastructure : Gain control over or disrupt critical infrastructure, such as power grids, water supplies, or transportation systems.

    - Recruitment of Bots for Botnets : refers to the process of infecting devices with malware in order to add them to a botnet.


5. ## Anounimyzing : 
  Finnaly, we're starting some reel technical aspects. we are with you don't bother your self all cyber security community (Red teams or Blue Teams) hate the theorical part of the domaine.

  In this part we gonna take you throw the most important thing that you wanna do before engaging in an attack, and i think when we all read and learn about different type of attacks a natural emotion cames to our body that gives you energy to start and trying those attacks in reel life, but any concus person knows that those attacks are illegal and low enforcement wont go easy on you.

  So, here we are going to learn about technics that helps you anounimyze your real identity in the cybers-space. and for that we create a hol repository that contains a All In one tool that helps you anounimyzea your netwok traffic [link to our Anounimizing repository]() that descus those points:

  - Temporary emails :
  - Removable devices :
  - Proxy / VPNs :
  - Tor Network & Union browsing : (talk about the need to disable the java script + secure mail services and file sharing) 
  - Crypto currency :
  - Metadata Stripping

## Recon
  1. Passive Recon :
  2. Active Recon :
  we need to understant the tools in order to create some thing automared. 

## Weaponization
1. Implement new attack vectors
2. Enhance detection mechanisms

## Delivery
1. Implement new attack vectors
2. Enhance detection mechanisms

## Exploitation
1. Implement new attack vectors
2. Enhance detection mechanisms

## Installation
1. Implement new attack vectors
2. Enhance detection mechanisms

## C2
1. Implement new attack vectors
2. Enhance detection mechanisms

## Actions on Objctives
1. Implement new attack vectors
2. Enhance detection mechanisms
