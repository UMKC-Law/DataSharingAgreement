At the heart of our project is a desire to connect privacy requirements to individual requests for data.

We plan to accomplish this by creating a system that can produce Data Sharing Agreements for people based on information they put into the system. These agreements will connect the information from their unique request with a corresponding set of privacy standards.

To inform us of what types of standards exist and what those standards look like, we have looked over a number of different Data Sharing Agreements. All of the Data Sharing Agreement Examples that we have collected are in two places: 

   1) The SampleAgreements sub-repo https://github.com/UMKC-Law/DataSharingAgreement/tree/master/SampleAgreements
   
   2) "Data Sharing Agreements" Issue page: https://github.com/UMKC-Law/DataSharingAgreement/issues/8

As we researched issues that might arise from Data Sharing in the context of Smart Cities, we began compiling a glossary. The glossary we have created is here: https://github.com/UMKC-Law/DataSharingAgreement/blob/master/glossary.md

Conceptually, our project suggests that any given agreement is a deck of cards. Each different clause within that agreement can be thought of as a card within the deck that completes a certain function. And there will always be a minimum number of cards that will be required to make up the deck of any agreement. So far we have created a top-level document, which is essentially a collection of the minimum number of cards that are needed for any data sharing agreement.The Master, top-level Document ("NDoCH-DSA.md") that we created is under the drafts folder, here: https://github.com/UMKC-Law/DataSharingAgreement/blob/master/Drafts/NDoCH-DSA.md 

By reducing the document to a collection of clauses, we have given future users of this system the ability to add and subtract cards as they see fit based on factors like jurisdictional requirements or new legislation. For this, we have created a folder of clauses, titled "Clause Bank." That folder is located here: https://github.com/UMKC-Law/DataSharingAgreement/tree/master/ClauseBank Currently, the numbering system we have is based on the clauses we included in our top-level document. As we move forward, there will be more and more clauses added to the clause bank in order to give creators of DSA agreements a wider range of clauses to choose from when creating their decks.This is how our project will be able to maximize its potential -- by not only becoming a system but by becoming a library that creators of agreements must rely upon when creating their own decks.

As our document grows beyond a top-level document, we will need to create a set of system rules that assign additional privacy standards to users that request data sets that are governed by federal laws like FERPA and HIPAA. Following that there will need to be additional system rules created that address the differing privacy standards among people that have higher and lower levels of authorization -- for instance, people in educational settings using data for research, people in federal agencies using data for inter-departmental purposes, or people using data for commercial purposes.

Some things we would like to accomplish in the future:
- Integrate everything in a better, more cohesive manner
- Create a landing page for System Operators to choose a template and clauses that are suitable for their particular agreement
  - The clauses and templates will be formatted as webcomponents 
- Create an API that will allow Applicants to answer a set of questions based on the types of data they are interested in accessing 
- Produce a Smart Document using CommonAccord based on the Applicant's answers which will allow the user to better explore and understand the agreement 
