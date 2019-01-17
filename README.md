# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Yvonne LIU

_Student NetID_: yl125

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: TSA
- Assumptions:
  - Current security inspection machines has the ability to detect common items that are forbidden on flights, such as the existence of liquid over 100ml, sharp items, lighters and other kinds of flammable and combustible.
- Assets:
  - The safety and well-being of passengers on flights
  - The reputation of the airline and the airport, as well as people’s level of trust towards using planes as a means of transportation
  - The security of the nation (when defending against terrorist hijacking planes)
- Threats:
  - People may try to bring weapons (e.g. sharp items, liquid bombs) on flight and use it for dangerous purposes, for example hijacking a plane 
  - Passengers may carry forbidden items unintentionally
  - Drug dealers may try to bring drugs or raw materials to produce drugs
  - Passengers carrying infectious diseases unknowingly
- Countermeasures:
  - Each person needs to go through one round of security check before boarding. All the baggages are inspected by machines and each person also has to go inside a machine to check for dangerous personal belongings.
    - cost: designing and building the appropriate machineries could be expensive and the implementation of it in the airport can be troublesome; hiring and training staff to assist in the process is also time-consuming
    - benefit: In general, most of the forbidden items can be detect by machines
  
  In general, I think this countermeasure if rather effective, because once the appropriate machineries are set up, it is almost impossible to take forbidden items onboard a flight, whether intentionally or unintentionally. The corresponding cost of building and setting up the system is thus worthwhile.
  - To deal with infectious diseases, there can be a body temperature check for all passengers as part of the inspection process. Additional health check should be performed for passengers who have just been to certain dangerous places or countries
    - cost: building appropriate machineries and setting it up in a space in the airport; hiring additional health professionals
    - Benefit: can detect passengers with abnormal body temperature and reduce the probability of people carrying infectious diseases from entering
  
  This countermeasure is less effective than the previous one. Not all infectious diseases will cause abnormal body temperature, and the effectiveness of doing additional checks relies on the person being honest about the places he or she recently visited. It is difficult to define what kind of places are dangerous, so some people would not know that they should do a health check. However, this countermeasure does deal with infectious diseases to some extent, and the cost of it is understandable, so I think it is still a justifiable countermeasure.

## Problem 2
- Scenario: Documents
- Assumptions:
  - The information on some sensitive documents should not be exposed to the public or unrelated individuals
  - The workers and people who rightly have access to the documents are trustworthy and will not reveal it to others
- Assets:
  - The confidentiality of the information on important documents
  - The privacy and safety of people whose information is on the documents
  - The reputation of this international law firm
- Threats:
  - Some people may try to get hold of the information on the documents for personal uses, which may be illegal or unethical and may potentially cause harm to the society. In this case, a person only need to have access to the document at some point of time and remember the rough content in his or her brain. 
  - Some people may try to take sensitive information and sell it to other people or nations that want to know the details about certain sensitive matters. In this case, a person will need to have access to the document and prove its reliability, so that the buyer of the information can trust it. 
- Countermeasures:
  - If there is a physical storage room, we can design a system that only allow certain trusted individuals to enter the room, for example via access cards or passwords. There can be security inspection outside the room to make sure no recording devices are brought in and no documents are brought out, so that no evidence of the documents can be obtained even if someone sneaks in to take a look.
    - cost: there is the design and implementation difficulties of building such a security system, and such a system will likely cost much money. In addition, it is hard to find trustworthy (and potentially armed) staff at the inspection place 24/7
    - benefit: can successfully reduce the probability of suspicious people entering the storage room and copying contents on the documents in the room

    Although the cost of building a system like this may be high, it can largely increase the difficulty of getting information from the storage room. Access cards may be stolen and passwords may be cracked, but the probability can be reduced by technical upgrades, for example using fingerprints. Overall, I think this countermeasure is justifiable.

  - If the documents are stored digitally, it is probably better to keep the computer or hard disk completely offline or only connected to a local area network so that people on the other side of the internet do not even have the chance to attack. In addition, when transporting a document outside of the local area network, it may be better to use a usb hard drive offline to avoid potential attacks online.
    - cost: loss of convenience if the whole system is offline, but I think the convenience level, though low, will be acceptable in case of a local area network. There is also the cost of building a local area network and making it secure against standard attacks
    - Benefit: by reducing the use of the internet, we reduce the probability of exposing important documents online.
    
    It is still possible to make an attack outside a local area network, for example via a VPN, so the local area network needs to be able to handle those common attacks. In my opinion, the probability of information leaks may be lower offline, because online attackers have no chance of getting the information. Depending on the level of internet connection that is absolutely needed, this countermeasure (completely offline or local area network) may be justifiable.

## Problem 3
- Scenario: The head of two companies are discussing future plans and potential cooperation of the two companies, and I am in charge of making sure the conversation is private
- Assumptions:
  - If the conversation is leaked to another company in the same market, the two companies will face some trouble
  - The room of conversation is sound-proof, so nobody can hear the conversation from outside. Nobody except the two heads are inside the room
- Assets:
  - The confidentiality of the conversation
  - The two companies' market share and their future development, because the eavesdropper may be able to use the information obtained to create a new product before the two companies or market it better
- Threats:
  - Competitor companies will try to eavesdrop the conversation and use the information they heard against the two companies. They may hide a listening device inside the room beforehand, and the device may either be able to send audio data out or simply record the conversation to be collected by someone physically afterwards
- Countermeasures:
  - Block all wifi signals in the area of the room. Block cellular signals and other signals that may allow a listening device to transmit data outside the room. We can also place some audio jammers that can generate small noises inside the room, so that even if there is a listening device, it is likely to record only noises. 
    - cost: purchasing the delicate devices, or building them on our own to ensure confidentiality. The noise generating devices may harm the quality of the conversation.
    - benefit: reduces the probability of audio data being successfully transmitted, and reduces the probability of recording meaningful conversations
    
    If we can ensure the safety and trustworthiness of the devices we use, the cost will mainly be monetary costs. There is no large-scale implementation or staffing issues, and it does reduce the probability of eavesdropping to some extent. It is hard to ensure that all signals that can be used for data transmission is blocked, but wifi and cellular network are likely the most common ones. In terms of cost vs. benefits, I think this countermeasure is justifiable.


