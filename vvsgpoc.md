
# <a name="_18_5_3_43701b0_1520018963930_650896_11156"></a>VVSG


## <a name="_18_5_3_43701b0_1520029835498_942129_9502"></a>Business


### <a name="_19_0beta_43701b0_1525644354155_734605_13002"></a>Interoperability


#### <a name="_19_0beta_43701b0_1525644393086_87534_13003"></a>4.1-A Data export and exchange format

Voting devices must provide support for the non-restrictive, publicly-available NIST SP Common Data Format (CDF) specifications for data inputs and output:
•	Election programming data, NIST SP 1500-100
•	Election results data, NIST SP 1500-100 
•	Election event logging data, NIST SP 1500-101
•	Voter registration-related data, NIST SP 1500-102
•	Cast vote records, NIST SP 1500-103
•	Ballot definition data, NIST SP 1500-104 





Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)


#### <a name="_19_0beta_43701b0_1525644509683_163761_13009"></a>4.1-B Election programming data input and output

•	input or output of election programming data;
•	input or output of ballot programming data; and
•	pre-election reports.





Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)


#### <a name="_19_0beta_43701b0_1525645223077_988217_15601"></a>4.1-C Tabulator report data

Tabulators must include support for the NIST CDF specifications for election results reporting data. 




Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Refined By:**

- [Election Management System](#_19_0beta_43701b0_1528124439592_57284_20646)

**Satisfied By:**

- [Election Results Reporting CDF](#_19_0beta_43701b0_1528127157688_702511_33578)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)
- [4.1-D Exchange of cast vote records](#_19_0beta_43701b0_1525645295325_870029_15608)

**Traced From:**

- [Election Results Reporting CDF](#_19_0beta_43701b0_1528127157688_702511_33578)


#### <a name="_19_0beta_43701b0_1525645295325_870029_15608"></a>4.1-D Exchange of cast vote records

Devices that export or import CVRs must support the NIST CDF specifications that apply to export and import of CVRs.




Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced From:**

- [4.1-C Tabulator report data](#_19_0beta_43701b0_1525645223077_988217_15601)


#### <a name="_19_0beta_43701b0_1525645323818_266352_15615"></a>4.1-E Exchange of voting device election logs

Voting devices must support the export or import of election log data using the NIST SP 1500-101 specification.




Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)


#### <a name="_19_0beta_43701b0_1525645343539_931969_15622"></a>4.1-F Specification of common format usage

The voting device or election system manufacturer must provide a specification describing how the manufacturer has implemented a NIST SP 1500 CDF specification that applies to the manufacturer’s specific voting devices and data. This includes  such items as descriptions of elements, attributes, constraints, extensions, syntax and semantics of the format, and definitions for data fields and schemas.




Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Verified By:**

- [My test case](#_19_0beta_43701b0_1528061542197_821294_9976)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced From:**

- [My test case](#_19_0beta_43701b0_1528061542197_821294_9976)
- [4.1-G Public specification of manufacturer native formats](#_19_0beta_43701b0_1525645375620_140639_15629)


#### <a name="_19_0beta_43701b0_1525645375620_140639_15629"></a>4.1-G Public specification of manufacturer native formats

Where a NIST SP 1500 CDF specification or other interoperable interchange specification does not exist for a particular area of data interchange,  the voting device manufacturer must provide a specification for its native format, describing how the manufacturer has implemented the native format that applies  to the manufacturer’s specific voting devices and data. This includes such items as descriptions of elements, attributes, constraints, extensions, syntax and semantics of the format, and definitions for data fields and schemas. 




Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)
- [4.1-F Specification of common format usage](#_19_0beta_43701b0_1525645343539_931969_15622)


#### <a name="_19_0beta_43701b0_1525645524629_492757_15636"></a>4.1-H Common format across manufacturers

The voting system manufacturer must support the NIST SP 1500 CDF specifications for export and interchange of data and reports across its major device categories.




Source:
New requirement
**Derived From:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)

**Traced To:**

- [4.1 Interoperable Formats](#_19_0beta_43701b0_1525644117735_948734_12981)


### <a name="_19_0beta_43701b0_1525565876944_868860_10364"></a> User-centered design process

The manufacturer must submit a report providing documentation that the system was developed following best practices for a user-centered design process. 
The report must include, at a minimum:

•A listing of user-centered design methods used
•The types of voters and election workers included in those methods
•How those methods were integrated into the overall implementation process
•How the results of those methods contributed to developing the final features and design of the voting system			




**Derived From:**

- [2.2 User Centered](#_19_0beta_43701b0_1525565790374_415540_10357)

**Traced To:**

- [2.2 User Centered](#_19_0beta_43701b0_1525565790374_415540_10357)


## <a name="_18_5_3_43701b0_1520020759990_545095_12939"></a>classes


## <a name="_18_5_3_43701b0_1520020733840_632681_12933"></a>Principles


### <a name="_18_5_3_43701b0_1520018976128_808259_11157"></a>section5


#### <a name="_18_5_3_43701b0_1520019182414_823285_11345"></a>17 Election definition devices, ballot definition

The election definition device MUST provide for the logical definition of the ballot, including the definition of the number of allowable votes for each contest.




##### <a name="_18_5_3_43701b0_1520019852799_227590_11794"></a> Election definition devices, administrative subdivisions 

The election definition device MUST provide for the logical definition of administrative subdivisions, where the list contests varies between subdivisions.




##### <a name="_18_5_3_43701b0_1520019776098_403926_11736"></a> Election definition devices, ballot definition details

The election definition device MUST be capable of collecting and maintaining
Contests and their associated labels and instructions;
Candidate names and their associated labels; and
Ballot questions and their associated text.





##### <a name="_18_5_3_43701b0_1520020941274_82223_13171"></a> Election definition devices, election districts

The election definition device MUST enable EOs to define multiple election districts.




##### <a name="_18_5_3_43701b0_1520020979904_518970_13180"></a> Election definition devices, identifiers

The election definition device MUST enable EOs to associate a minimum of 3 identifiers each for administration subdivisions, election districts, contests, and candidates.




### <a name="_19_0beta_43701b0_1525565139857_259285_8317"></a>1 High Quality Design

The voting system is designed to accurately, completely, and robustly carry out election processes.




#### <a name="_19_0beta_43701b0_1525564959768_985960_8208"></a>1.1 Process Specifications

The voting system is designed using commonly-accepted election process specifications.




#### <a name="_19_0beta_43701b0_1525565078994_53898_8216"></a>1.2 Real World

The voting system is designed to function correctly under real-world operating conditions.




#### <a name="_19_0beta_43701b0_1525565324255_169706_8457"></a>1.3 Identify correct implementations

Voting system design supports evaluation methods enabling testers to clearly distinguish systems that correctly implement specified properties from those that do
not.




### <a name="_19_0beta_43701b0_1525565712216_947223_10341"></a>2 High Quality Implementation

The voting system is implemented using high quality best practices.




#### <a name="_19_0beta_43701b0_1525565765894_162745_10348"></a>2.1 Best Practices

The voting system and its software are implemented using trustworthy materials and best practices in software development. 




#### <a name="_19_0beta_43701b0_1525565790374_415540_10357"></a>2.2 User Centered

The voting system is implemented using best practice user-centered design methods, for a wide range of representative voters, including those with and without disabilities, and election workers.




**Derived:**

- [ User-centered design process](#_19_0beta_43701b0_1525565876944_868860_10364)

**Traced From:**

- [ User-centered design process](#_19_0beta_43701b0_1525565876944_868860_10364)


### <a name="_19_0beta_43701b0_1525644062886_348125_12974"></a>4 Interoperable

The voting system is designed to support interoperability in its interfaces to external systems, its interfaces to internal components, its data, and its peripherals.




#### <a name="_19_0beta_43701b0_1525644117735_948734_12981"></a>4.1 Interoperable Formats

Voting system data that is imported, exported, or otherwise reported, is in an interoperable format. 











**Derived:**

- [4.1-A Data export and exchange format](#_19_0beta_43701b0_1525644393086_87534_13003)
- [4.1-B Election programming data input and output](#_19_0beta_43701b0_1525644509683_163761_13009)
- [4.1-C Tabulator report data](#_19_0beta_43701b0_1525645223077_988217_15601)
- [4.1-D Exchange of cast vote records](#_19_0beta_43701b0_1525645295325_870029_15608)
- [4.1-E Exchange of voting device election logs](#_19_0beta_43701b0_1525645323818_266352_15615)
- [4.1-F Specification of common format usage](#_19_0beta_43701b0_1525645343539_931969_15622)
- [4.1-G Public specification of manufacturer native formats](#_19_0beta_43701b0_1525645375620_140639_15629)
- [4.1-H Common format across manufacturers](#_19_0beta_43701b0_1525645524629_492757_15636)

**Traced From:**

- [4.1-A Data export and exchange format](#_19_0beta_43701b0_1525644393086_87534_13003)
- [4.1-B Election programming data input and output](#_19_0beta_43701b0_1525644509683_163761_13009)
- [4.1-C Tabulator report data](#_19_0beta_43701b0_1525645223077_988217_15601)
- [4.1-D Exchange of cast vote records](#_19_0beta_43701b0_1525645295325_870029_15608)
- [4.1-E Exchange of voting device election logs](#_19_0beta_43701b0_1525645323818_266352_15615)
- [4.1-F Specification of common format usage](#_19_0beta_43701b0_1525645343539_931969_15622)
- [4.1-G Public specification of manufacturer native formats](#_19_0beta_43701b0_1525645375620_140639_15629)
- [4.1-H Common format across manufacturers](#_19_0beta_43701b0_1525645524629_492757_15636)


#### <a name="_19_0beta_43701b0_1525644163244_69914_12988"></a>4.2 Standard Formats

Standard, publicly-available formats for other types of data are used, where available. 




#### <a name="_19_0beta_43701b0_1525644190271_190779_12995"></a>4.3 Widely-used protocols

Widely-used hardware interfaces and communications protocols are used. 




## <a name="_19_0beta_43701b0_1528124439590_803493_20643"></a>Use cases

