# Software Requirements Specification

> Copy the SRS report that you received to this file, for your own convenience.
> You can change the SRS if you think it makes your life easier. It is your document now.
> This SRS file is however not a deliverable for Assignment 2.



![2e7c0b03-765b-4a1e-a311-5dbb8af17327](https://github.com/Comp2050-2023/assignment1-project-a-anglesea2/assets/95715557/059103ed-6d4b-4983-9b8b-f0db148c26e8)

# Software Requirements Specification

## Structure

# Title Page

**Project name:** ECC
  
**Team Members:** Huzaifa Faizan, Safwaan Sohail, John Galvez, Rahik Rahman, Alex Florinski

**Vision Statement:**
  
Our vision is to be green and environmentally friendly. We would like to promote the use of reusable coffee cups to the public in order to encourage sustainable living. We aim to incorporate bio-degradable RFID tags into our products so that it enables a coffee cup swap service for our consumers. 

Consumers can purchase cups from our partnering stores and drop them off at collection points. These collection points would be placed in various places such as partnering stores, train stations, shopping centers, or libraries. These locations were chosen to improve convenience for our customers. This innovation would also eliminate the need of having our customers clean up the cups themselves. Our aim is to embark on a journey where environmental sustainability is both a joy and a convenience. 


**Key Principles:**

- **Sustainability:** Our system encourages the adoption of reusable cups, reducing single-use waste and contributing to a greener planet.
  
- **Convenience:** We strive to provide a hassle-free coffee experience. Subscribers can enjoy their beverages on-the-go without the burden of carrying or cleaning cups.
  
- **Community Engagement:** By partnering with local coffee shops and creating a network of collection points, we aim to foster a sense of community and shared responsibility for environmental conservation.
  
- **Innovation:** Our RFID-based tracking technology and real-time updates bring a new level of efficiency and insight to the coffee industry, setting a standard for sustainable service models.
  
- **Empowerment:** We empower coffee shop managers with tools to manage subscriptions, monitor inventory, and participate in a rewarding loyalty program, ultimately driving sustainable growth for their businesses.

Join us in embracing a future where every coffee sip contributes to a cleaner, more sustainable world.

*Together, let's sip responsibly.*


# Change Log

| Date       | Version | Changes Made                                  | Changes By      | Changes Agreed By |
|------------|---------|-----------------------------------------------|-----------------|-------------------|
| July 31    | 1.0     | first vision statement and company picture    | John & Safwaan  | John              |
| Aug 15     | 1.1     | vision statement                              | Rahik           | John              |
| Aug 20     | 1.2     | adding puropse to introduction                | Rahik           | John              |
| Aug 21     | 2.0     | scope of the introduction                     | Alex & Safwaan  | John              |
| Aug 22     | 2.1     | use cases                                     | Rahik           | John              |
| Aug 24     | 2.2     | use cases                                     | Rahik           | John              |
| Aug 26     | 2.3     | requirements                                  | Rahik           | John              |
| Aug 28     | 3.0     | description                                   | Huzaifa         | John              |
| Aug 29     | 3.1     | update to the use case                        | Alex            | John              |
| Aug 30     | 3.2     | update of whole document                      | Safwaan         | John              |
| Sep 04     | 3.3     | Diagrams and logs                             | John, Rahik & alex| John              |
| Sep 05     | 4.0     | slight update to document                     | Safwaan         | John              |
| Sep 06     | 4.1     | Addition of Outlook                           | John            | Safwaan & Rahik   |
| Sep 07     | 4.2     | Addition of elicitation & update log          | John            | Safwaan & Rahik   |
| Sep 10     | 4.3     | Addition of elicitation & update log          | Safwaan            | Rahik   |
| Sep 10     | 4.4     | Addition of elicitation & update log          | Safwaan            | Rahik   |
| Sep 10     | 4.5     | Addition of elicitation & update log          | Safwaan            | Rahik   |

# Introduction
The purpose of this document is to inform our stakeholders about the plans and ideas of the project as well as the software requirements for the system. We intend to have a mobile application that allows users to jon a monthly subsciption to purchase resuable cups and track useful information such as purchase history and collection points. The document provides an in-depth description of our reusable coffee cup system so that our consumers are aware of the technical and professional conventions being followed. 

Scope: 
- The RFID Tags are not removable. If the RFID Tags are removed the cups will not be usable anymore. The cup's function depends on the RFID component as it's the primary cup's function. 
- Data from the tags will be stored by our company and will not be released. By only being stored by us, this allows us to improve our products and service directly from user data feedback without a third-party being invloved. The data won't be sold or distributed externally from our company, maintaining high data security and priritising our customers' data safety.
- The reusable coffee cups will have a tracking system to determine the location of the product. This system allows users who lost their cup to track it and locate it via the app. Having a useful feature such as tracking encourages purchases of reusable products such as our cup.
- An automatic cleaning system at the collection points. These collections points allow a community to be built to work with our green environment as customers explore new locations and meet like-minded people, this encourages the use of green products as it also invites customers to be part of a community. 
- The coffee cups and the RFID tags will be manufactured by the service. By us manufacturing the components directly, we have control and quality within our components to ensure our product is of highest quality while remaining green for the environment and no interference of a third-party is included. 

# Overall Description:

- **Product perspective:**

  The resusable coffee cup service is designed to be a part of a sustainable environment. The RFID tags are made with materials which are bio-degradable and
  without any harmful substances. Materials such as polylactic acid made from organic products such as sugarcane is used. Futhermore the RFID tags help create a
  link with the physical world and the software which allows tracking possible. Tracking allows better inventory management and helps the service with
  accountability which could reduce damage or any possible theft. The service is also linked with the management staff as they consistently monitor and repair
  the software after a customer reports a damage through their mobile app. The managment team recieves a notification from a customer notifying the management
  team of damage.
   
- **Product functions:**

   - RFID Tracking: A real time tracking system on each resuable cups
  
   - Alerts: Sending alerts to the management staff after a customers reports a damaged product
  
   - Inventory management: Monitor the availability of cups
  
   - Mobile app: Customers will be able to locate and subscribe to the reusable cups using the mobile app.
  
- **User characteristics:** 
  
   - Customers: People which are interested in the product.
  
   - Management staff: Team of members responsible for the overall management of the cups including services like repairing and possible cleaning.
  
   - Employees: Employees of any partnering stores who would handle the transactions and scanning the RFID tags.
  
   - Data analysts: Data analysts will be responsible for analysing important data such as studying the environmental impact or inventory management.
  
- **Constraints:**
  
   - Hardware: There could be some issues with the RFID tags or scanners. The bio degradable material of the RFID tags could cause problems with the lifespan of the tags.
  
   - Privacy of data: As the customer will be required to enter their personal information in order to access the coffee cups their data could be stolen.
  
   - Incompetency of staff: Lack of experience or knowledge could be a huge factor in the maintenance of the software.
  
- **Assumptions and dependencies:**
  
  Assumptions:
  
  - Customers will have devices which will be capable of running the mobile app
  - Partnering stores will have the devices required for scanning the RFID tags
  - Network connectivity will be available everywhere
    
  Dependencies:
  
  - Payments: To allow transactions the service might rely on third party payment methods such as Paypal
  - Maps: The mobile app might depend on other map services such as google maps
  - Trained staff: The service could depend on the skill level of the staff

# Specific Requirements

| **Number** | **Functional Requirements** |
|------------|-----------------------------|
| 1 | The RFID tags track the cup's collection points including where it was purchased from. |
| 2 | The app must indicate whether or not the user has purchased a reusable cup. |
| 3 | The app must have a login function such that users are able to sign in and create personal accounts. |
| 4 | The app must have the option to allow users to purchase both coffee and reusable cups. |
| 5 | The app must support payment methods such credit cards, debit cards, mobile wallets and PayPal. |

<br />
<br />

| **Number** | **Non-Functional Requirements** |
|------------|---------------------------------|
| 1 | Response time: The login page should grant users access to the system within 3 seconds. |
| 2 | Compliance: The system must comply with the data protection laws such as GDPR and meet environmental standards. | 
| 3 | Hardware: The system must be compatible on both IOS and Android devices. |
| 4 | Authentication and encryption: Both data encryption and authentication should be available in order to protect personal data. 
| 5 | Policy compliance: The service should provide policies such as privay policy and terms of use. The service should clearly state how certain processes such as collection of data will be performed. |

# Use cases

**Use Case Diagram:**

![image](https://github.com/Comp2050-2023/assignment1-project-a-anglesea2/assets/110147739/1a793d72-f89b-4f1e-a2db-ebbc24bf0925)
<br>
<br>


**Use case 1:** <br />
<ul>
A customer purchases coffee and a reusable cup from one of the partnering stores. The customer finishes his coffee and as a result, has no need for the coffee cup. The customer remembers that they joined the monthly subscription plan and is in possession of a reusable coffee cup which can be returned to various collection points situated around the community. The customer spots a collection point at the local train station and returns the coffee cup, other people using the same product are in the same area, the customers interact with each other about the cups to further build the community until cleaned cup is returned to them.
  
<br>
</ul>

**Use case 2:**<br />
<ul>
A customer had previously purchased a reusable coffee cup and had returned the cup to a collection point. He makes his way over to one of our partnering stores and orders a cup of coffee while displaying his information on the app to the cashier, indicating that he had already purchased a reusable cup. The cashier hands the customer his coffee together with the cup. The consumer eventually finishes his coffee and drops off the cup at a nearby collection point. 

<br>
</ul>

**Use case 3:**<br />
<ul>
A customer purchases coffee together with the reusable cup. After a while, he finishes the coffee and realises that there are no nearby collection points at his current location. Therefore, he decides to bring the cup home and washes it himself. He is then able to use the cup on a different occasion. 
  
<br>
</ul>
<br>
<br>

**Interaction Diagram for use case no. 2:**

![image](https://github.com/Comp2050-2023/assignment1-project-a-anglesea2/assets/110147739/41561aa4-423e-4fd0-96f9-098e4fa2d614)


# Discussion

## Elicitation
The main methods that the team used to elict the requirements was communication with the stakeholders. Finding out what the stakeholders wants from us (especially the outcome), helps determine the requirements for the project. Some other methods we used were research and thought experiments. Research helped clear out what was needs and was extra. Thought experiments have helped us make some requirements that we have deem necessary for the completition of the project. 

## Outlook
If the team were to continue to develop this prorject and the requirements, the information that we would require usage data to see if the project would be worth continuing. From then we would once again meet with the stakeholders to discuss about further improvements to the application and would ask for anything that they would want. This would help in developing more users stories and would help construct more requirements to develop the project. We would also get feed-back from the users to see what designs and processes can be optimised. To ensure that we do have the right requirements, the team would analyse the information recieved from all source. This is to check whether this extra development would still be inline with the applications original goal and if it would really improve. Check the feasibility and the estimated costs would also be done in this stage.

# Appendices

## 1. Log of Interactions with Stakeholders

| **Date** | **Discussion** |
|------------|-----------------------------|
| 31/07/2023 | Introductions between SRS and SDD teams |
| 07/08/2023 | Setting baseline requirements for the project |
| 14/08/2023 | Organised communication channels |
| 21/08/2023 | Disucessed project scope, use cases and brainstromed ideas for improvement |
| 04/09/2023 | Shared access of the SRS.doc with stakeholders and disscussed feedback |

## 2. References

| **References** | **Address** | 
| --- | --- |
| StackOverflow | https://stackoverflow.com/ |
| Biobased RFID Tags | https://bioplasticsnews.com/2020/01/12/stora-enso-sustainable-rfid-tag/ |
| Sustainability | https://therfidcompany.com/sustainability/ |

## 3. Third-party Resources

| **Third-Party-Resource** | **Address** | 
| --- | --- |
| Lucid Chart | https://lucid.co/ |
| Draw.io | https://www.drawio.com/ |
| Imagine.art | https://www.imagine.art/ |
| Dictionary | https://www.dictionary.com/ |
| MarkDown to PDF converter | https://www.pdfforge.org/online/en/markdown-to-pdf |
