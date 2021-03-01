## Chapter 3: Exercises ##

### 3.1 Explain how the principles underlying agile methods can lead to the accelerated development and deployment of software. (2 points) ###

Underlying agile methods are sometimes difficult to realize in practice. The ideas underlying agile methods were developed around the same time by a number of different people in the 1990s. Perhaps the most significant approach to changing software development culture was the development of Extreme Programming (XP). In XP, requirements are expressed as scenarios (called user stories), which are implemented directly as a series of tasks. Programmers work in pairs and develop tests for each task before writing the code. All tests must be successfully executed when new code is integrated into the system. There is a short time gap between releases of the system. 

Extreme programming was controversial as it introduced a number of agile practices that were quite different from the development practice of that time. In practice, the application of Extreme Programming as originally proposed has proved to be more difficult than anticipated. It cannot be readily integrated with the management practices and culture of most businesses. Therefore, companies adopting agile methods pick and choose those XP practices that are most appropriate for their way of working. Sometimes these are incorporated into their own development processes but, more commonly, they are used in conjunction with a managementfocused agile method such as Scrum.

A fundamental requirement of scaling agile methods is to integrate them with plandriven approaches. Small startup companies can work with informal and short-term planning, but larger companies have to have longer-term plans and budgets for investment, staffing, and business development. Their software development must support these plans, so longer-term software planning is essential.
[[Sommerville, Ian. Software Engineering, Global Edition, Pearson Education, Limited, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655.
Created from turkuamk-ebooks on 2021-03-01 06:08:02.]](http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655)

So all in all it's generally accepted that one benefits from using agile methods but the adaptation has to be thought so that the process is right for your unique business case and the existing team. There's no silver bullet here, but rather a conversation and guidelines that are there to help you mold something that works with your setup but not necessary with others. 
### 3.2 Explain what kinds of practical problems you may face with agile methods and when. (2 points) ###

In some areas, particularly in the development of software products and apps, agile development has been incredibly successful. It is by far the best approach to use for this type of system. However, agile methods may not be suitable for other types of software development, such as embedded systems engineering or the development
[[Sommerville, Ian. Software Engineering, Global Edition, Pearson Education, Limited, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655.
Created from turkuamk-ebooks on 2021-03-01 06:15:19.]](http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655)

You may run into problems with agile methods because they perform best in certain situations and not so well with others. The informality of agile development is incompatible with the legal approach to contract definition that is commonly used in large companies. Agile methods are most appropriate for new software development rather than for software maintenance. And yet the majority of software costs in large companies come from maintaining their existing software systems. Agile methods are designed for small co-located teams, yet much software development now involves worldwide distributed teams. Contractual issues can be a major problem when agile methods.
[[Sommerville, Ian. Software Engineering, Global Edition, Pearson Education, Limited, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655.
Created from turkuamk-ebooks on 2021-03-01 06:18:03.]](http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655)

Agile methods have to rely on contracts in which the customer pays for the time required for system development rather than the development of a specific set of requirements. As long as all goes well, this benefits both the customer and the developer. However, if problems arise, then there may be difficult disputes over who is to blame and who should pay for the extra time and resources required to resolve the problems.
[[Sommerville, Ian. Software Engineering, Global Edition, Pearson Education, Limited, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655.
Created from turkuamk-ebooks on 2021-03-01 06:23:52.]](http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655)
## Chapter: 4 Exercises ## 

### 4.1 Explain 1) difficulties related to requirements elicitation and understanding and 2) techniques to solve them. (2 points) ###

- Requirements elicitation and analysis is the process of deriving the system requirements through observation of existing systems, discussions with potential users and procurers, task analysis, and so on. This may involve the development of one or more system models and prototypes. These help you understand the system to be specified.
[[Sommerville, Ian. Software Engineering, Global Edition, Pearson Education, Limited, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655.
Created from turkuamk-ebooks on 2021-03-01 06:25:12.]](http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655)

  The difficulties related to requirements elicitation lie on communication and understanding. If you don't even know what you should be asking how on earth can you succeed utilizing the knowledge of your stakeholders and potential users. Similarly the deeper understanding about the issue in hand brings you more coherence when prioritizing and scheduling the work.

- Requirements elicitation involves meeting with stakeholders of different kinds to discover information about the proposed system. You may supplement this information with knowledge of existing systems and their usage and information from documents of various kinds. You need to spend time understanding how people work, what they produce, how they use other systems, and how they may need to change to accommodate a new system. There are two fundamental approaches to requirements elicitation: 
  -  Interviewing, where you talk to people about what they do. 
  -  Observation or ethnography, where you watch people doing their job to see what artifacts they use, how they use them, and so on. 
  
  You should use a mix of interviewing and observation to collect information and, from that, you derive the requirements, which are then the basis for further discussions.
[[Sommerville, Ian. Software Engineering, Global Edition, Pearson Education, Limited, 2015. ProQuest Ebook Central, http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655.
Created from turkuamk-ebooks on 2021-03-01 06:37:25.]](http://ebookcentral.proquest.com/lib/turkuamk-ebooks/detail.action?docID=5185655)


### 4.2 Write plausible user requirements in natural language and in a standard format for the following function: An unattended petrol (gas) pump system that includes a credit card reader. The customer swipes the card through the reader, then specifies the amount of fuel required. The fuel is delivered and the customer’s account debited. (1 point) ###

1. A user should be able to start the buy by interacting with creadig card reader
2. A user credit card swipe should prompt option to specify the amount of fuel required
3. After user inputs the amount of fuel he or she desires to purchase the credit gets checked
4. If the credit check passes the fuel is delivered.
5. If the credit check does not pass default to the start
6. After fuel is delivered given credit card gets charged proper amount based on the fuel delivered