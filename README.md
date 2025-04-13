# Status of Selected States Regarding ICJ Compulsory Jurisdiction

## I. Introduction

### A. Overview of the International Court of Justice (ICJ)

The International Court of Justice (ICJ), commonly known as the World Court, stands as the principal judicial organ of the United Nations (UN).<sup>1</sup> Established by the Charter of the United Nations in June 1945, its seat is located at the Peace Palace in The Hague, Netherlands.<sup>1</sup> The Court fulfills a dual mandate within the international legal system. Firstly, it settles, in accordance with international law, legal disputes submitted to it by States (contentious jurisdiction). Secondly, it provides advisory opinions on legal questions referred to it by duly authorized United Nations organs and specialized agencies (advisory jurisdiction).<sup>2</sup>

### B. The ICJ Statute and State Participation

The Statute of the International Court of Justice forms an integral part of the UN Charter. Consequently, all Member States of the United Nations are automatically *ipso facto* parties to the ICJ Statute.<sup>4</sup> This linkage ensures that the 193 current UN member states are entitled to appear before the Court in contentious cases, provided a basis for jurisdiction exists.<sup>1</sup> This foundational structure connects UN membership directly with access to the Court's mechanisms.

### C. Compulsory Jurisdiction under Article 36(2) - The "Optional Clause"

While all state parties to the Statute can bring cases before the Court if a specific basis for jurisdiction exists (e.g., a special agreement or a compromissory clause in a treaty), Article 36, paragraph 2, of the Statute provides for a distinct mechanism known as the "optional clause".<sup>5</sup> This provision allows States parties to the Statute to declare unilaterally, at any time, that they recognize the Court's jurisdiction as compulsory *ipso facto* and without special agreement, concerning legal disputes involving:

* the interpretation of a treaty;
* any question of international law;
* the existence of any fact which, if established, would constitute a breach of an international obligation;
* the nature or extent of the reparation to be made for the breach of an international obligation.<sup>7</sup>

Crucially, this acceptance operates on the principle of reciprocity: the declaration binds the declaring State only "in relation to any other State accepting the same obligation".<sup>5</sup> Therefore, a case can only be initiated under the optional clause if both the applicant and respondent states have valid declarations in force. Furthermore, the Court's jurisdiction in such cases is often limited by the narrower scope of the two declarations involved, considering any reservations attached. These unilateral declarations are formally deposited with the Secretary-General of the United Nations.<sup>5</sup>

The entirely voluntary nature of this mechanism underscores the fundamental principle of state sovereignty in international law. States are generally not subject to the binding jurisdiction of international tribunals without their explicit consent. The optional clause represents a significant potential delegation of jurisdictional authority, but one that states must actively choose to make. The fact that only a minority of UN member states—currently 74 according to the ICJ's official list as of June 2023—have made such declarations highlights a widespread reluctance among states to submit unconditionally to the Court's compulsory jurisdiction.<sup>5</sup>

### D. Purpose and Scope of the Report

This report aims to determine the current status of seven specific countries—Afghanistan, Albania, Algeria, Angola, Argentina, Armenia, and Azerbaijan—concerning their participation in the ICJ Statute and, critically, whether they have accepted the Court's general compulsory jurisdiction under Article 36, paragraph 2. The analysis relies exclusively on official information published by the ICJ and the United Nations Treaty Collection. The findings will be presented, culminating in a structured JSON output containing the following data points for each country: the intergovernmental organization (IGO) identified as "ICJ", the country's English name (country\_EN), its ISO 3166-1 alpha-3 code (ISO\_A3), its status as a party to the Statute (status), a boolean value indicating acceptance of general compulsory jurisdiction (accepting general compulsory jurisdiction), the year it became a party to the Statute (joinDate), the date it might have withdrawn a declaration (leftDate, expected to be null), and any relevant notes (membershipNotes).

It is important to clarify that information regarding state participation in the International Criminal Court (ICC), mentioned in some background materials <sup>9</sup>, is distinct from the ICJ and has no bearing on a state's acceptance of the ICJ's compulsory jurisdiction under Article 36(2).

## II. ICJ Statute Membership and Admission Dates

### A. Confirmation of Statute Membership

All seven countries under review—Afghanistan, Albania, Algeria, Angola, Argentina, Armenia, and Azerbaijan—are Member States of the United Nations. As established previously, UN membership confers automatic *ipso facto* status as parties to the Statute of the International Court of Justice.<sup>4</sup> Consequently, all seven states are entitled to appear before the Court, subject to the existence of a valid jurisdictional basis for any given case.<sup>2</sup> For the purposes of the requested JSON output, this confirms that the "status" field, indicating adherence to the Statute, should reflect their status as parties (represented by the user's term "signed").

### B. Admission Dates

The dates on which these states became parties to the ICJ Statute correspond to their admission to the United Nations. Based on official UN and ICJ records, these dates are as follows <sup>4</sup>:

1.  Afghanistan: 19 November 1946 (Year: 1946)
2.  Albania: 14 December 1955 (Year: 1955)
3.  Algeria: 8 October 1962 (Year: 1962)
4.  Angola: 1 December 1976 (Year: 1976)
5.  Argentina: Original Member (The UN Charter was signed on 26 June 1945 and entered into force on 24 October 1945. Year: 1945)
6.  Armenia: 2 March 1992 (Year: 1992)
7.  Azerbaijan: 2 March 1992 (Year: 1992)

These admission dates are not merely administrative data points; they reflect distinct periods of global political transformation and the expansion of the United Nations system. Argentina's status as an original member places it among the founding states of the post-World War II international order. Afghanistan joined shortly thereafter. Albania's admission occurred during a period of Cold War bloc politics and gradual UN expansion. Algeria and Angola joined following their independence, representing the major wave of decolonization in the mid-20th century. Armenia and Azerbaijan became members following the dissolution of the Soviet Union, under which they were previously subsumed.<sup>13</sup> Understanding these historical contexts can provide background for appreciating a state's subsequent engagement with international institutions, including its stance on mechanisms like the ICJ's optional clause.

## III. Status Regarding Compulsory Jurisdiction (Article 36(2))

### A. Review of Official Declaration Lists

The definitive source for determining which states have accepted the ICJ's compulsory jurisdiction under Article 36(2) is the list maintained by the United Nations Secretary-General, as depository, and published by the ICJ itself.<sup>2</sup> The ICJ website provides a dedicated section listing the texts of declarations made under Article 36(2) that were considered valid and in force as of a specific date (most recently cited as 1 June 2023, listing 74 states).<sup>5</sup> Older lists and related documents confirm this mechanism and the general number of participating states.<sup>6</sup> The United Nations Treaty Collection website also provides access to the status of these declarations.<sup>8</sup>

### B. Determination for Target Countries

A thorough examination of the official lists of states with declarations currently in force under Article 36(2), as provided by the ICJ and the UN Treaty Collection <sup>5</sup>, confirms that none of the seven target countries—Afghanistan, Albania, Algeria, Angola, Argentina, Armenia, and Azerbaijan—are included.

Therefore, for all seven countries, the JSON field "accepting general compulsory jurisdiction" must be set to `false`. As none of these states have deposited a declaration under Article 36(2), there is no declaration to withdraw from, meaning the "leftDate" field should appropriately be `null`. The "membershipNotes" field can remain empty or explicitly state the absence of an Article 36(2) declaration.

### C. Contextualizing Non-Acceptance

The finding that none of these seven countries accept the ICJ's compulsory jurisdiction is noteworthy. This group includes states with diverse political histories, geographical locations, and international profiles: post-conflict states (Afghanistan), nations that transitioned from specific political systems (Albania, Armenia, Azerbaijan), post-colonial states (Algeria, Angola), and a significant regional power and original UN member (Argentina). Their collective decision not to opt into the compulsory jurisdiction system suggests that the reasons for hesitation are widespread and likely varied. Common motivations often include a strong emphasis on national sovereignty, concerns about potential exposure to unwanted litigation (particularly regarding sensitive issues like territorial boundaries, historical events, or resource disputes), and potentially a preference for alternative dispute resolution methods such as political negotiation, regional courts, or ad hoc arbitration. Argentina's non-acceptance is particularly notable given its long history with the UN and the ICJ, including having nationals serve as judges and even President of the Court.<sup>1</sup>

Furthermore, it is essential to contextualize this non-acceptance by considering the practice of states that have made declarations under Article 36(2). Even among the 74 states currently listed, acceptance is frequently qualified by significant reservations.<sup>14</sup> These reservations often exclude specific categories of disputes from the Court's compulsory jurisdiction, such as those arising before a certain date (*ratione temporis*), disputes with particular groups of states like Commonwealth members (*ratione personae*) <sup>3</sup>, or disputes concerning specific subject matters like territorial sovereignty, maritime boundaries, or military activities (*ratione materiae*) <sup>3</sup>. This extensive use of reservations demonstrates how even states willing to make a declaration carefully circumscribe their consent to jurisdiction, preserving significant control over their potential exposure. This widespread practice of qualified acceptance reinforces the primacy of state consent in the system and highlights the practical limitations of the "compulsory" jurisdiction. Understanding this broader landscape helps illuminate why states like the seven under review might choose not to opt-in at all, potentially viewing the complexities and perceived risks as outweighing the benefits, even with the possibility of tailoring a declaration through reservations.

## IV. ISO 3166-1 Alpha-3 Codes

### A. Importance of Standardized Codes

ISO 3166-1 alpha-3 codes are three-letter codes established by the International Organization for Standardization (ISO) to represent countries, dependent territories, and special areas of geographical interest.<sup>20</sup> Their primary purpose is to provide a universally recognized, unique, and standardized identifier for geopolitical entities, thereby facilitating unambiguous data processing and exchange in various international applications, including trade, finance, shipping, and computing.<sup>20</sup> These codes offer a better visual association with country names compared to the two-letter alpha-2 codes and are notably used in specifications for machine-readable passports.<sup>21</sup>

### B. Identification for Target Countries

The ISO 3166-1 alpha-3 codes for the seven target countries have been verified across multiple authoritative sources, including standards repositories and official lists.<sup>13</sup> The codes are as follows:

* Afghanistan: AFG
* Albania: ALB
* Algeria: DZA
* Angola: AGO
* Argentina: ARG
* Armenia: ARM
* Azerbaijan: AZE

The remarkable consistency of these codes across numerous independent databases and official standards documents <sup>20</sup> demonstrates the robustness, reliability, and widespread adoption of the ISO 3166-1 standard. This high degree of data integrity ensures that these specific identifiers are stable and suitable for use in structured data formats like the requested JSON output, contrasting with the potentially more fluid nature of legal statuses concerning international court jurisdiction.

## V. Summary Table of Findings

The following table provides a concise overview of the key findings regarding the ICJ Statute membership and acceptance of compulsory jurisdiction for the seven specified countries, consolidating the information detailed in the preceding sections.

| Country     | ISO\_A3 | ICJ Statute Join Year | Accepts General Compulsory Jurisdiction (Art. 36(2))? |
| ----------- | ------- | ----------------------- | ---------------------------------------------------- |
| Afghanistan | AFG     | 1946                    | No                                                   |
| Albania     | ALB     | 1955                    | No                                                   |
| Algeria     | DZA     | 1962                    | No                                                   |
| Angola      | AGO     | 1976                    | No                                                   |
| Argentina   | ARG     | 1945                    | No                                                   |
| Armenia     | ARM     | 1992                    | No                                                   |
| Azerbaijan  | AZE     | 1992                    | No                                                   |

This table serves as a clear, human-readable summary and confirms the data points used to generate the final JSON array below.

## VI. Consolidated Data in JSON Format

### A. Adherence to User Specification

The JSON array presented below compiles the verified information for each of the seven target countries, strictly adhering to the structure and field names requested in the user query.

### B. Presentation of JSON Array

```json
[
  {
    "IGO": "ICJ",
    "country_EN": "Afghanistan",
    "ISO_A3": "AFG",
    "status": "signed",
    "accepting general compulsory jurisdiction": false,
    "joinDate": 1946,
    "leftDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "ICJ",
    "country_EN": "Albania",
    "ISO_A3": "ALB",
    "status": "signed",
    "accepting general compulsory jurisdiction": false,
    "joinDate": 1955,
    "leftDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "ICJ",
    "country_EN": "Algeria",
    "ISO_A3": "DZA",
    "status": "signed",
    "accepting general compulsory jurisdiction": false,
    "joinDate": 1962,
    "leftDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "ICJ",
    "country_EN": "Angola",
    "ISO_A3": "AGO",
    "status": "signed",
    "accepting general compulsory jurisdiction": false,
    "joinDate": 1976,
    "leftDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "ICJ",
    "country_EN": "Argentina",
    "ISO_A3": "ARG",
    "status": "signed",
    "accepting general compulsory jurisdiction": false,
    "joinDate": 1945,
    "leftDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "ICJ",
    "country_EN": "Armenia",
    "ISO_A3": "ARM",
    "status": "signed",
    "accepting general compulsory jurisdiction": false,
    "joinDate": 1992,
    "leftDate": null,
    "membershipNotes": null
  },
  {
    "IGO": "ICJ",
    "country_EN": "Azerbaijan",
    "ISO_A3": "AZE",
    "status": "signed",
    "accepting general compulsory jurisdiction": false,
    "joinDate": 1992,
    "leftDate": null,
    "membershipNotes": null
  }
]
```
## VII. Concluding Remarks

### A. Summary of Findings

The analysis conducted confirms that while all seven specified countries—Afghanistan, Albania, Algeria, Angola, Argentina, Armenia, and Azerbaijan—are parties to the Statute of the International Court of Justice by virtue of their membership in the United Nations <sup>4</sup>, none of them currently accept the Court's general compulsory jurisdiction through a declaration made under Article 36, paragraph 2, of the Statute.<sup>5</sup> They are entitled to participate in cases before the Court where jurisdiction is founded on other bases, but they have not opted into the system of general compulsory jurisdiction established by the optional clause.

### B. Confirmation of Deliverable

This report has addressed the specific query regarding the status of the seven listed countries concerning the ICJ's compulsory jurisdiction. The findings are based on verifiable information from official ICJ and UN sources.<sup>4</sup> The consolidated data has been presented in the precise JSON format requested, accurately reflecting the research outcomes.
