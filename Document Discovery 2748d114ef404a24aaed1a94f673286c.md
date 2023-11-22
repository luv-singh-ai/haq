## **Objective -**

Ensure accessible and equitable documentation support to all

## **Problem Statement -**

Can we redesign the documentation stage of scheme delivery in effective way? How can we demystify and diminish the confusion and obstacles that people commonly encounter?

**Current Process Overview:**

With over 90% of the Indian population earning less than ₹25,000 per month, the Central and State Governments launch approximately **13,000+ schemes annually, totaling an investment of around ₹20 lakh crore**

But the Current Process is fraught with bottlenecks and inefficiencies like -  

- Varied Document Requirements: Each scheme necessitates a different set of documents. For instance, educational schemes require board mark sheets, while MGNREGA demands job cards. This leads to confusion among citizens on what documents is needed for what schemes.
- Document Storage and Loss: Documents are often stored in physical formats and are susceptible to loss or damage due to natural disasters like floods or migration.
- Update and Issuance Challenges: Even if users do have one, they don’t know how to get it updated or issue a new one. Form Filling for issuance of new document is a complex process with high rate of rejections and bureaucratic red tape. They brave scorching heat for hours in serpentine queues, only to get rejected over minuscule technicalities. Rejection happen for simple reasons like documents not readable (especially if they’re old) or incorrect photo specifications.
- Time poverty of certain sections like women, daily wage labourers - They cannot afford to sacrifice working hours to navigate the lengthy document processing.

> “*Often we face local discrimination when we go to get our work done. Even though I’m working in Bangalore for 10 years, all my documents still belong to my native place Bihar. Due to migration, we are devoid of benefits of all government schemes. If I could update my documents in say, like an hour, that would be a great boon* ” -  Ram Manohar, a migrant worker who works as cook in Bangalore
> 

### Our experience at Haqdarshak Kendra in Bengaluru highlights the necessity of a "people first" approach:

- Trust in Local Agents: Local agents are pivotal in scheme discovery due to the trust they garner within communities.
- Technological Limitations Even if people have access to technology, they might not necessarily have the capacity to fill the form themselves. Maybe out of fear, or ignorance, they rather prefer a person do it for them. So whatever solution we build will involve ‘people-in-the-loop’ approach.

### ****Proposed Approaches:****

*"A nation's greatness is measured by how it treats its weakest members"* – Mahatma Gandhi

Our solution must align with people's habits and limitations, in line with “**plus one**” approach: 

### Conversational Bot

- We are assuming most of our user base is not highly digitally literate. When they need a scheme benefit, they most likely go asking for help from someone they trust in their locality.
- Let’s say they visit local panchayat office or BDO office to get the work done. If they want admission for their son, they might visit local school. If they want treatment for their family members, they might visit local hospital.
- Since Haqdarshak agents can’t be available at all times and all places , How about we build a conversational bot that talks to people in their native language to understand their concerns.
- Can we give a phone number to which they can call and our AI conversational bot will answer on other end. It will first understand the pain they are facing in current situation and then try to give solutions. We can also explore putting a scannable QR code that links to a WhatsApp chat with Bot.
- To expand awareness, we can provide link to a YouTube video explaining the process of issuing documents for the scheme-of-interest in vernacular languages.
- If it’s at the first point of contact where users go to issue new documents, then that would make it around their established behaviour and usage pattern. This facilitates assistance at their point of need through a channel they find intuitive. It also expands reach to the millions not digitally literate.
- eg let’s say a tribal person wants to issue patta rights to get 4 ha land under FRA. In the current process, he might visit local forest and land revenue department officials to get his land. Here in these offices if we provide a helpline number(useful for those having feature phones) or SMS number they can message their pain, our system will connect back with the user. If it’s a smartphone, we may start a Whatsapp chat. The chatbot will understand his situation, take all his details and then give helpful guidance.

**Critical analysis** - 

Benefits - 

- Massive reach and impact at population scale.
    - only 100 million can read and understand English and only 200 million can recognise words. Thus to include 1.4 billion people, we need adopt voice based approach.
- Alignment with User Behaviour: emphasising “people first” approach - one that resonates with established habits and needs of the target demographic.

Challenges - 

- Initial Adoption: Gradual uptake might be observed initially.
- Digital Literacy and Connectivity: Varies across regions

### **Amplifying Haq agents impact**

Our on-ground agents are pivotal in scheme discovery due to their deep community ties. We can equip them with AI tools to expedite document retrieval and form-filling.

- AI avatar to train Haq agents : Can we can utilise an AI based avatar to train Haq agents in document discovery and data collection? We can also use LLM-based agents to take users' inputs and fill form fields. This would still be a 'human-in-the-loop' system but much more streamlined, increasing productivity and potential impact.
- eg if an agent has to manually add each person data, the agent can utilise Computer Vision techniques like object detection, to we auto-extract information from documents and validate info from submitted documents. This boosts productivity while retaining the human touch.

**Other approaches -** 

- Automated Document Retrieval: Can we build a system to automatically retrieve documents from a user's connected storage services like a gallery and tag them?
- Document Version Control: Can we implement a system to ensure that the most current version of a document is used, like checking the date in documents and informing the user if it's old? Can we build an offline version of it so it might work even without internet connection.
- Interactive GenAI Avatars: Can we introduce GenAI avatars or personas to explain the friction points to users in an interactive fashion?

**Benefits:**

- Expedited Discovery: *recommending major schemes a person can get through their existing set of documents, which is a reverse mapping of the usual process where one is often recommended documents based on schemes.*
- Empowerment : Verifiable credentials will also lead to empowering users at their end, bridging gaps such as the digital divide and gender divide.

**Audience Mapping:**
Intended users can be divided into groups:

1. Users who know how to use a smartphone decently.
2. Users who are reliant on others to use it.
3. Users who are hesitant to use it and prefer the offline process more.

**Incentive structure:**
We can gamify the document discovery process. For every document correctly uploaded, we can give users some points. Upon full completion, a token badge may be given, motivating user engagement.

**Conclusion** - 

Together, we can architect systems centered around citizens' constraints and trusted intermediaries. Our goal is to revolutionise the document discovery process, making it more efficient and user-friendly. Each step towards a more accessible and empathetic system is a step towards a more inclusive and equitable India. This initiative aims to provide citizens with seamless, last-mile application and document support, thereby enhancing their access to vital government schemes and services. Together, we have the power to bridge divides and light the way to a brighter future, where no citizen is left behind in their pursuit of rightful benefits and support.



**Citations -** 

Data points - ‘State of Inequality in India' report prepared using government data by the India arm of a global competitiveness initiative, the Institute for Competitiveness, shows that 90% of the country do not earn even Rs 25,000 per month.