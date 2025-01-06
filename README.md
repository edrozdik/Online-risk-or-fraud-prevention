## Task 1

**Description of the Task 1:**
Earlier today 3 new registrations were flagged by our monitoring system and sent to you for manual review. 
Below are the details, as entered by the applicants themselves during the registration flow (IP addresses were collected by our system). 
For each registration, please find at least 5 suspicious elements (red flags or discrepancies), decide whether to approve or decline the registration and explain why. 
You may use the internet to search for information that will assist you to assess the risk (please use only publicly available information and only free of charge resources).

<img width="1440" alt="Снимок экрана 2024-12-24 в 19 10 21" src="https://github.com/user-attachments/assets/e095b0ae-8681-4540-a6a5-b7707c03f09c" />

**Solution to Task 1:**

**A. Bhardreshkumar Chetanbhai Patel**  
**Email domain:** "hundi_Sudan@protonmail.com" suggests potential anonymity and "hundi" might imply a financial system associated with informal or illegal activities.  
**Mobile number:** The mobile number begins with "+91", indicating India, but the country is listed as Russia.  
**Address:** "ABK-1" is vague and doesn't seem like a verifiable address.  
**IP address:** The IP "46.151.47.2" is traced to Russia, inconsistent with the mobile number's country code.  
**Company name:** "Aurum Ship Management FZC" could be legitimate, but no strong online presence could make it questionable.    

**B. Kim Yo-Jong Cheburashka**  
**Full name:** "Cheburashka" is a fictional character from Russian animation, not a typical name.
**Landline:** The number "+850-23814937" corresponds to North Korea, while the listed country is China.
**City:** "Pipa Island" is not a recognized city in China.
**Email domain:** "kimmie@accounting-iata.com" suggests a specific professional domain, but verification indicates no connection with the International Air Transport Association (IATA).
**IP address:** "175.45.176.0" is linked to North Korea, which is incongruent with the listed country, China.  

**C. Leonard Williams Jr.**
**Date of birth:** "29 Feb 2002" is invalid because 2002 was not a leap year.
**Mobile number:** "+966502627313" is Saudi Arabian, while the country listed is the United States.
**Postal code:** "12345" is too generic to verify as legitimate.
**Email domain:** "wleonard@deca.mil" uses a military domain (.mil), which is unusual for a civilian application.
**IP address:** "94.97.84.155" resolves to Saudi Arabia, not the United States.

**Approval or Rejection:**
A: Reject due to conflicting country information, questionable email, and vague address.  
B: Reject due to clearly fictitious name, mismatched location details, and IP inconsistencies.  
C: Reject due to invalid date of birth, mismatched geographical information, and inappropriate use of a .mil domain.  

## Task 2

**Description of the Task 2:**
The business team has asked you to evaluate the risks associated with the onboarding of a financial partner.   
The company is considering to partner with a financial short-term consumer credit provider in India and is conducting due diligence on several potential candidates.     
You were asked to look into one of shortlisted candidates, evaluate the risks of doing business with Golden Lightning Loan and recommend whether to engage or not.  

Please write a short narrative/summary with a recommendation (2-3 short paragraphs in English).  

**Solution to Task 2:**  

**Golden Lighting Loan** is a financial short-term consumer credit provider in India.  
While assessing the risks of partnering with this entity, it is important to evaluate several key factors, including the company’s regulatory compliance, financial health, reputation in the market, customer satisfaction levels, and operational transparency.   
Public records and reviews indicate a mixed reputation, with concerns around customer complaints, potential predatory lending practices, and a lack of detailed financial disclosures. 
 Furthermore, any partnerships in the Indian financial sector should be compliant with Reserve Bank of India (RBI) regulations to mitigate legal and operational risks.

Based on the due diligence findings, it is recommended to proceed cautiously.  
Further in-depth research is needed to verify Golden Lighting Loan's financial stability, adherence to regulatory requirements, and ethical business practices.   
Until these aspects are confirmed, entering into a partnership carries significant reputational and operational risks.

## Task 3

**Description of the Task 3**
Yerkish is an artificial language developed for use by non-human primates. It employs a keyboard whose keys contain lexigrams, symbols corresponding to objects or ideas (unlike letters or signs that represent sounds, a lexigram is a graphic design which represents a word but is not necessarily indicative of the object to which it refers).  
As part of an effort to mitigate risks, you were asked to help in building a Yerkish computer model to detect money laundering typologies.  
Your endeavor is to design lexigrams of fraudulent behavioral patterns. Each lexigram will describe a fraudulent MO/typology/pattern and would be comprised as a set of 3-5 data discrepancies.  

For example, a lexigram to represent a risk of an account being hacked (aka account takeover) can be represented as a set of:  

Geolocation mismatch - IP country at login is >1,000 miles away from the billing country, and  
Device fingerprint at login is new/unknown, and  
Attempt to withdraw >80% of the funds on balance within 2 hours, and  
A bank account used for withdrawals is of a bank located outside of the billing country.  
Your task: please choose one typology/MO from the list below (or suggest a different typology that you thought of) and propose a short lexigram (3-5 data discrepancies) to be used as part of a detection model (please refrain from using the example set). In your answer mention the typology/MO of your choice and 3-5 short sets of the proposed lexigram.  

Typologies/MOs to choose from (choose only one):  

Smurfing and structuring  
Impersonation  
Layering  
Placement  
Integration  
Offshore shell company  
Compromised financials (credit cards, eChecks)  
Cross-border cash smuggling and cash conversion  
Arms dealing and proliferation  
Import of goods/funds into sanctioned territories  
Trade of valuable commodities (gems, precious metals)  
Bribery and corruption via PEPs  
Laundering via gaming activities (casinos, racing, gambling)  
Underground banking and alternative remittance services (hawala/hundi)  
Abuse of non-profit organizations  
Usage of nominees and trusts  
Laundering through investments or real estate  
Laundering through gatekeepers  
Laundering through virtual assets (NFTs, virtual currencies, in-game items)  

**Solution to Task 3:**  

**Typology:** Laundering Through Real Estate Investments  
**Proposed Lexigram:**    

**Unusual Transaction Volume:** Multiple high-value property purchases or sales within a short time frame, inconsistent with the buyer's stated financial profile or income.  
**Geolocation Mismatch:** The buyer's IP address is located in a high-risk jurisdiction or significantly distant from the location of the property being purchased.  
**Use of Shell Companies:** The property is purchased through offshore entities or shell companies with limited transparency regarding ownership.  
**Payment Anomalies:** Transactions are conducted using large cash deposits or payments through non-standard methods (e.g., virtual assets or cryptocurrencies).  
**Lack of Property Utilization:** The property remains unoccupied or unused for an extended period, raising suspicion about its intended purpose.  

This lexigram helps flag potential cases of money laundering through real estate by identifying discrepancies in transaction behavior, ownership structures, and payment methods. It can be integrated into a detection model to monitor and investigate suspicious activities effectively.

## Task 4

**Description of the Task 4**
Imagine that you are a member of a goods screening team working for an online marketplace.  
For the sake of this exercise, your task is to review the items being placed for sale by sellers and decide regarding each, whether you approve it to be offered for sale or not.   Please review each of the following four books and decide, for each, if you allow or not and add a short reasoning for each (up to 2 sentences for each book).   
Below are four sections for your answers, one per each book.

<img width="1292" alt="image" src="https://github.com/user-attachments/assets/fbf457d0-0dcb-494f-9b43-82573960dbd0" />

**Solution to Task 4:**  

**Book: Poiro Knows The Killer**  
**Decision: Reject**  
**Reasoning:** The suggested price of $150 is excessively high compared to identical used copies available for $10.40, which raises concerns about fair pricing. Additionally, the book has no reviews, which reduces its credibility for such a high price point.  

**Book: The Last Ticket to Paradise**   
**Decision: Reject**  
**Reasoning:** The suggested price of $989 for a Kindle book is unreasonably high, especially given that comparable digital books are usually priced much lower (e.g., $25). The lack of reviews also makes the price unjustifiable.  

**Book: Do It Yourself - Coffins for Pets and People**  
**Decision: Approve**  
**Reasoning:** The price of $14.99 is reasonable and comparable to similar used copies available for $3.64. With 43 reviews, the book demonstrates market interest and legitimacy.  

**Book: The Idiot**  
**Decision: Approve**  
**Reasoning:** The suggested price of $11.99 for a paperback edition is fair and consistent with market norms. The book has a high number of reviews (799), indicating strong demand and credibility.  

## Task 5

**Description of the Task 5**
An account holder of account number 88232323 admitted that yesterday he has attempted to create a second account with us using bogus details.  
So all the personal details (like name, address, phone, email, etc.) are fictitious.  
The individual also shared that when he tried to register his second account, our system was smart enough and blocked it.  

**Solution to Task 5:**  
To locate the second account (the blocked registration attempt), following next steps:

**IP Address Tracking:** Identify the IP address used by the account holder during the blocked registration attempt. Compare it with the IP logs associated with the original account (88232323) to check for a match or proximity.  
**Device Fingerprinting:** Analyze the device fingerprint (e.g., browser version, operating system, device type) captured during the blocked attempt and cross-check with the original account’s login history for similarities.  
**Time of Attempt:** Use the timestamp of the blocked registration attempt to narrow down events in your system logs. Filter for failed registration attempts around that time.  
**Behavioral Patterns:** Look for similar behavioral patterns, such as the same transaction types or navigation flows, between the blocked attempt and the original account.  
**Cross-Reference Partial Data:** If the individual reused any partial information (e.g., similar email domains or phone number prefixes), flag accounts with overlapping characteristics.  
These methods should help identify and verify the blocked registration attempt.

## Task 6

**Description of the Task 6**

Imagine you are one of two finalists on a famous TV show called The Superior Golden Balls. The prize on the table is $500K.  
If both of you choose Split, each will take home half the jackpot.   
If one chooses Steal and the other chooses Split, the Steal contestant wins the entire jackpot and the Split contestant leaves with nothing.  
If both choose Steal, neither contestant wins any money. You have 60 seconds to convince your opponent, afterwards each of you will make a choice separately and later on reveal your choices at the same time.  

What will be your winning strategy? (In your short answer of up to 3 sentences, refer to your choice and what will you convince your contestant to do).  

**Solution to Task 6:**  
My strategy would be to choose Split and convince my opponent to do the same.  
I would emphasize that choosing Split ensures that both of us walk away with a substantial amount of money, while Steal carries the risk that neither of us wins anything.  
I would also assure my opponent that trust and fairness lead to the best outcome, reinforcing that mutual cooperation is the most logical and rewarding choice.  


