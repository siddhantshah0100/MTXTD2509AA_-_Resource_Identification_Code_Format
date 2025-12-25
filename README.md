# MXXXX2509AA-Resource_Identification_Code_Format
MXXXX2509AA - Resource Identification Code Format

# **Resource Identification Code Format** for:

- #### Articles

- #### Blogs

- #### Handbooks

- #### Images

- #### Illustrations

- #### Libraries

- #### Listicles

- #### Manuals

- #### Projects

- #### Videos

## Format Segments & Order:

> \<***Type***>\<***Core***>\<***Date***>\<***Name***>

### Segment Breakdown:

> Note:
>
> - Format: **----** *\[n\]*
>
>   Where,
>
>   ---- = Segment Name
>
>   n = Maximum Number of Characters Allowed for that Segment of the Code.

1. **Type** *\[1\]*: Type of Resource
    - **A** \-\> Article/Listicle
    - **B** \-\> Blog
    - **L** \-\> Library
    - **M** \-\> \(User\) Manual \/ Handbook
    - **P** \-\> Project
    - **V** \-\> Video

2. **Core** *\[4\]*: The Core/Base of the Resource
    > \<***Abbreviation***\>\<***Category***\>
    - **Abbreviation** *\[3\]*: Core's Abbreviation
    - **Category** *\[1\]*: Core's Category

    - Core Categories and their Codes:
        - ***E*** \-\> *Environment \/ Integrated Development Environment (IDE)*
        - ***F*** \-\> *Framework*
        - ***L*** \-\> *(Programming) Language*
        - ***P*** \-\> *Platform*
        - ***T*** \-\> *Toolchain*

    - **ARDE** \-\> *Arduino IDE*
    - **CPPL** \-\> *C/C++*
    - **HTML** \-\> *HTML*
    - **HWRP** \-\> *Hardware Only*
    - **JAVL** \-\> *Java*
    - **JSCL** \-\> *JavaScript*
    - **MITE** \-\> *MIT App Inventor*
    - **NODP** \-\> *Node-RED*
    - **PRO?** \-\> *Proteus*
    - **PYTL** \-\> *Python*
    - **RSTL** \-\> *Rust*
    - **STME** \-\> *STM32CubeIDE*
    - **XMLL** \-\> *XML*
    - **YAML** \-\> *YAML*
    - **XXXX** \-\> *Unknown/Generic*

3. **Date** *[4]*: Date of Commencement

    > <***Year***><***Month***>

    - **Year** *[2]*: Format: "**YY**" | Range: **00-99** (00 = Unknown)
    - **Month** *[2]*: Format: "**MM**" | Range: **00-12** (00 = Unknown)

4. **Name** *[2]*: Index (1 to 676) of the Resource in the Specified Month, Year \& Core

    > Standard English Alphabets | Range: **AA-ZZ** (26^2 = 676 Unique Names Possible)

    - **AA** \-\> *First  \(1st\)*
    - **AB** \-\> *Second \(2nd\)*
    - **AC** \-\> *Third  \(3rd\)*
    - \<...>
    - **ZX** \-\> *Third Last  \(674th\)*
    - **ZY** \-\> *Second Last \(675th\)*
    - **ZZ** \-\> *Last        \(676th\)*

### Summary:

> **TCCCCDDDDNN** \<\- *Segment Specific Character Limit \(\<Type \[**1**]>\<Core \[**4**]>\<Date \[**4**]>\<Name \[**2**]>)*
>
> **TAAACYYMMNN** \<\- *with Subsegments \(\<Type>{\<Abbreviation>\<Category>}{\<Year>\<Month>}\<Name>) = (<**1**>{\<3<<b>1</b>>}{<<b>2</b>><<b>2</b>>}<<b>2</b>>)*
>> Total Character Count = **11**

## Examples:

> **MXXXX2509A** \<\- *This Manual's Identification Code*

1. ###### Everything is Unknown:
2. ###### a
