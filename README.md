
---

# ***MTXTD2509AA - Resource Identification Code Format***

- **ID**: *MTXTD2509AA*
- **Title**: *Resource Identification Code Format*
- **Author**: *Siddhant Shah*
- **Date Updated**: *29th December 2025*
- **Resource Type**: *User Manual*
- **Resource Core**: *Text Document*
- **Resource Date**: *September 2025*
- **Resource Name**: *AA \(001\)*

## **TABLE OF CONTENTS**

- [**1: List of Resources**](#1-list-of-resources)

- [**2: Segments & Order**](#2-segments--order)

  - [2.1: Segment Breakdown](#21-segment-breakdown)

    - [2.1.1: Type](#211-type-1)

    - [2.1.2: Core](#212-core-4)

    - [2.1.3: Date](#213-date-4)

    - [2.1.4: Name](#214-name-2)

- [**3: Summary**](#3-summary)

  - [3.1: Segment Specific Character Limit](#31-segment-specific-character-limit)

    - [3.1.1: With Subsegments](#311-with-subsegments)

  - [3.2: Total Character Count](#32-total-character-count)

- [**4: Examples**](#4-examples)

  - [4.1: MTXTD2509AA](#41-mtxtd2509aa-this-manuals-identification-code)

  - [4.2: LINOE0000AH](#42-linoe0000ah)

  - [4.3: PESYE1800BQ](#43-pesye1800bq)

  - [4.4: WHWRP2412AK](#44-whwrp2412ak)

---

## **1: LIST OF RESOURCES**

> [*Back to TOC*](#table-of-contents)

- **Articles / Listicles**

- **Blogs**

- **Images / Illustrations**

- **Journal** / **Technical Report**

- **Libraries / Modules / Packages**

- \(User\) **Manuals** / **Handbooks**

- **Patents**

- **Projects**

- **Tutorials**

- **Videos**

- **White Papers** / **Research Papers**

## **2: SEGMENTS & ORDER**

> [*Back to TOC*](#table-of-contents)

\<***Type***\>\<***Core***\>\<***Date***\>\<***Name***\>

### **2.1: Segment Breakdown**

> **Note:**
>
> - Segment Format: **\-\-\-\-** *\[n\]*
>
>   *Where,*
>
>   **\-\-\-\-**: *Segment Name*
>
>   *n*: *Segment Specific Character Length*

- #### **2.1.1: Type** *\[1\]*
    
  The type of resource:

  - **A**: *Article / Listicle*
  - **B**: *Blog*
  - **I**: *Image / Illustration*
  - **J**: *Journal / Technical Report*
  - **L**: *Library / Module / Package*
  - **M**: *\(User\) Manual / Handbook*
  - **P**: *Project*
  - **T**: *Tutorial*
  - **V**: *Video*
  - **W**: *White Paper / Research Paper*
  - **X**: *Patent*

- #### **2.1.2: Core** *\[4\]*
    
  The core or base of the resource:

  > **Format**: \<***Abbreviation***\>\<***Category***\>
  >
  > - **Abbreviation** *\[3\]*: Core's Abbreviation
  >   - **ALT**: *Altium Designer*
  >   - **CCC**: *C*
  >   - **CPP**: *C++*
  >   - **ESY**: *EasyEDA / EasyEDA Pro*
  >   - **HTM**: *HTML*
  >   - **HWR**: *Hardware Only*
  >   - **INO**: *Arduino IDE*
  >   - **JAV**: *Java*
  >   - **JSC**: *JavaScript*
  >   - **MIT**: *MIT App Inventor*
  >   - **NOD**: *Node-RED*
  >   - **PRO**: *Proteus*
  >   - **PYT**: *Python*
  >   - **RST**: *Rust*
  >   - **STM**: *STM32CubeIDE*
  >   - **TXT**: *Text / Markdown*
  >   - **XML**: *XML*
  >   - **YAM**: *YAML*
  >
  > - **Category** *\[1\]*: Core's Category
  >   - **D**: *Design / \(Generic\) Document / \(File / Data\) Format*
  >   - **E**: *Environment / Integrated Development Environment \(IDE\) / Electronic Design Automation \(EDA\)*
  >   - **F**: *Framework*
  >   - **L**: *\(Programming\) Language*
  >   - **P**: *Platform*
  >   - **T**: *Toolchain*
  >   - **X**: *Mixed / Miscellaneous / Unknown*

  - **ALTE**: *Altium Designer*
  - **CCCL**: *C*
  - **CPPL**: *C++*
  - **ESYE**: *EasyEDA / EasyEDA Pro*
  - **HTML**: *HTML*
  - **HWRP**: *Hardware Only*
  - **INOE**: *Arduino IDE*
  - **JAVL**: *Java*
  - **JSCL**: *JavaScript*
  - **MITE**: *MIT App Inventor*
  - **NODP**: *Node-RED*
  - **PROE**: *Proteus*
  - **PYTL**: *Python*
  - **RSTL**: *Rust*
  - **STME**: *STM32CubeIDE*
  - **TXTD**: *Text / Markdown*
  - **XMLL**: *XML*
  - **YAML**: *YAML*

  ##### **Special Case**
  - **MCRX**: *Multi-Core*

- #### **2.1.3: Date** *\[4\]*

  > *Date of Commencement or Resource Creation*
  >
  > **Format**: <***Year***><***Month***>
  >
  > - **Year** *\[2\]*:
  >   - **Format**: "***YY***"
  >   - **Range**: ***00 - 99*** *\(Where, 00: Unknown\)*
  >
  > - **Month** *\[2\]*:
  >   - **Format**: "***MM***"
  >   - **Range**: ***00 - 12*** *\(Where, 00: Unknown\)*

  - **0000**: *Unkown*
  - **0001**: *January of Unkown Year*
  - **0800**: *Unkown Month of Year 2008*
  - **0801**: *January 2008*
  - \<\.\.\.\>
  - **9909**: *September 2099*
  - **9910**: *October 2099*
  - **9911**: *November 2099*
  - **9912**: *December 2099 \(Last Possible Date\)*

- #### **2.1.4: Name** *\[2\]*

  > *Index / Identifier \(1 to 676\) of the resource in the specified month, year & core*
  >
  > **Format**: *Bijective Base-26 System*
  >
  > **Range**: ***AA - ZZ*** *\(26^2 = 676 Unique Names Possible\)*
  >
  > **Formula**: *\(\(**LCA1Z26** \- 1\) \* 26\) \+ **RCA1Z26***
  >   - Where,
  >     - **LCA1Z26**: *Left Column A1Z26 Cipher*
  >     - **RCA1Z26**: *Right Column A1Z26 Cipher*
  >     - **A1Z26**:
  >       - **A**: *1*
  >       - **B**: *2*
  >       - **C**: *3*
  >       - **D**: *4*
  >       - **E**: *5*
  >       - **F**: *6*
  >       - **G**: *7*
  >       - **H**: *8*
  >       - **I**: *9*
  >       - **J**: *10*
  >       - **K**: *11*
  >       - **L**: *12*
  >       - **M**: *13*
  >       - **N**: *14*
  >       - **O**: *15*
  >       - **P**: *16*
  >       - **Q**: *17*
  >       - **R**: *18*
  >       - **S**: *19*
  >       - **T**: *20*
  >       - **U**: *21*
  >       - **V**: *22*
  >       - **W**: *23*
  >       - **X**: *24*
  >       - **Y**: *25*
  >       - **Z**: *26*

  - **AA**: *First \(1st\)*
  - **AB**: *Second \(2nd\)*
  - **AC**: *Third \(3rd\)*
  - \<\.\.\.\>
  - **ZX**: *Third Last \(674th\)*
  - **ZY**: *Second Last \(675th\)*
  - **ZZ**: *Last \(676th\)*

## **3: SUMMARY**

> [*Back to TOC*](#table-of-contents)

### **3.1: Segment Specific Character Limit**

**TCCCCDDDDNN**: *\<Type \[**1**\]\>\<Core \[**4**\]\>\<Date \[**4**\]\>\<Name \[**2**\]\>*

#### **3.1.1: With Subsegments**

**TAAACYYMMNN**: *\<Type \[**1**\]\>\{\<Abbreviation \[**3**\]\>\<Category \[**1**\]\>\}\{\<Year \[**2**\]\>\<Month \[**2**\]\>\}\<Name \[**2**\]\>*

### **3.2: Total Character Count**

> - **Type**: *1*
>
> - **Core**: *4*
>   - **Abbreviation**: *3*
>   - **Category**: *1*
>
> - **Date**: *4*
>   - **Year**: *2*
>   - **Month**: *2*
>
> - **Name**: *2*

**Total Characters**: *11*

## **4: EXAMPLES**

> [*Back to TOC*](#table-of-contents)

> ### **4.1: MTXTD2509AA** *\(This Manual's Identification Code\)*
>
> - **M**: *it is either a manual or handbook.*
> - **TXTD**: *it is a text document.*
> - **2509**: *it was created in September 2025.*
> - **AA**: *it is the 1st manual or handbook of that month.*

- ### **4.2: LINOE0000AH**

  - **L**: *it is either a Library or a Module or a Package.*
  - **INOE**: *it is for / based-on Arduino IDE.*
  - **0000**: *it is not known when it was created.*
  - **AH**: *it is the 8th \(\(\(A1 \- 1\) \* 26\) \+ H8\) arduino library in the unknown date category.*

- ### **4.3: PESYE1800BQ**

  - **P**: *it is a Project.*
  - **ESYE**: *it is for / based-on EasyEDA or EasyEDA Pro.*
  - **1800**: *it was created in an unknown month of year 2018.*
  - **BQ**: *it is the 43rd \(\(\(B2 \- 1\) \* 26) \+ Q17) easyeda project of that year in the unknown month category.*

- ### **4.4: WHWRP2412AK**

  - **W**: *it is either a White Paper or Research Paper.*
  - **HWRP**: *it is based-on some type of Hardware.*
  - **2412**: *it was created in December 2024.*
  - **AK**: *it is the 11th \(\(\(A1 \- 1\) \* 26\) \+ K11\) White Paper or Research Paper based on some hardware in the month of December in 2024.*

---

> [*Back to Top*](#mtxtd2509aa---resource-identification-code-format)

# *End of File*
