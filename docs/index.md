# Home

Welcome to the home of documentation for the SuperDARN Data Standards Working Group (DSWG)

Last updated: 2020-03-20

## DSWG Members

| Name                    | github username | Institution                                                                |
|-------------------------|-----------------|----------------------------------------------------------------------------|
| Marci Detwiller [chair] | @mardet987      | University of Saskatchewan, Canada                                         |
| Brian Bienvenu          | @brianbienvenu  | La Trobe University, Australia                                             |
| Emma Bland              | @ecbland        | University Centre in Svalbard (UNIS), Norway                               |
| Bill Bristow            | @wabristow      | University of Alaska Fairbanks, USA                                        |
| Angeline Burrell        | @aburrell       | Naval Research Laboratory, USA                                             |
| Xiang Deng              | @dengxiang2015  | National Space Science Center, China                                       |
| Keith Kotyk             | @kkotyk         | University of Saskatchewan, Canada                                         |
| Aurelie Marchaudon      | @SDFrance       | Institut de Recherche en Astrophysique et Planétologie (IRAP/CNRS), France |
| Nozomu Nishitani        |                 | Nagoya University, Japan                                                   |
| Marina Schmidt          | @mts299         | University of Saskatchewan, Canada                                         |
| Xueling Shi             | @Shirling-VT    | Virginia Tech, USA                                                         |
| Kevin Sterne            | @ksterne        | Virginia Tech, USA                                                         |
| Evan Thomas             | @egthomas       | Dartmouth College, USA                                                     |
| Maria-Theresia Walach   | @mtwalach       | Lancaster University, UK                                                   |
| Akira Sessai Yukimatu   | @sessaigh       | National Institute of Polar Research, Japan                                |

## DSWG Charter

Adopted Dec 20, 2019 by SuperDARN Executive Council

Last Amended Mar 20, 2020 for Membership update

### Acronyms
* DAWG - Data Analysis Working Group
* DDWG - Data Distribution Working Group
* DPTF - Data Policy Task Force
* DSWG - Data Standards Working Group
* OSWG - Operating Software Working Group
* PI - Principal Investigator
* WG - working group
* IO - input/output 

### Definitions
* Primary data format - the standard level 1 data format that is distributed within the network by the DDWG.
* Secondary data format - a level 2 (or higher) data format generated from the level 1 data by use of analysis code.
* Standard data formats - any formats deemed to be standardized by the data policy.

### Background Information
The DSWG was established after the 2019 SuperDARN Workshop in Fujiyoshida, Japan, to meet the following needs:

* Fill some of the duties left behind by the defunct [OSWG](http://vt.superdarn.org/tiki-index.php?page=Operating+Software+WG&wp_files_sort_mode1=filename_asc),
* Maintain support for a common standard distributed data format, while addressing issues created by interfacing new and independent technological advancements in radar hardware systems,
* Develop standards of practice, under the advisement of the Data Policy Task Force and corresponding data policies, to move towards FAIR (findable, accessible, interoperable, and re-usable) data practices.

According to the PI agreement, ‘Principal Investigators agree to provide data from their radar(s) in common defined formats - level 1 data.’ A major intent of this working group is to ensure that the common defined formats are documented,d easy to use, and evolve with technological advancements. Additionally, in the instance that the PI agreement is adapted to allow higher level data products to be made available to the larger scientific community, this working group will ensure that these secondary data products are standardized. In this way, any problems with changes to primary data products that carry over to commonly used secondary data products could be more quickly resolved under the scope of this WG. 

### DSWG Responsibilities
Based on this information, the responsibilities of the Data Standards Working Group are as follows:

* Bring forth all issues with the standard primary data format to the attention of the Executive Council, and suggest remedial action(s) to be voted upon, including potential changes to the primary data format.
* Support both old and new radar hardware, including technical support on new radar operating systems, to support the goal of all radars producing a standard primary data format.
* Provide the file read and write support for standard data formats (both primary and secondary), by providing and maintaining an IO code package along with supporting documentation for all standard data formats. This package can be used by all data users, including both the DAWG, for use with the analysis software, and the DDWG, for use with identifying problem files for blacklisting or otherwise.
* Ensure all standard formats (primary and secondary) are fully documented by including definitions (and units) for all data fields and providing guidelines for interpretation, in close collaboration with the DAWG.
* Review all proposals for new secondary data formats, ensuring that the data product aligns with policies and procedures, before making recommendations to the Executive Council regarding adoption as a standard (note that the review and recommendation of the software used to produce the data is the responsibility of DAWG).
* Manage the administration of radar operations metadata, including management of radar station metadata, which at this time includes station identification codes and hardware data files (hdw.dat files), and radar operating mode metadata, which at this time includes the radar control program numbers (CPIDs).
* Develop procedures and practices to meet policies set forth by the DPTF and/or enacted by the Executive Council, towards the goal of FAIR (findable, accessible, interoperable, and re-usable) data practices, and provide recommendations to other WGs based on those procedures and practices.

### DSWG Mandate
To:

* improve the findability, accessibility, interoperability, and reusability of the SuperDARN data sets for all end-users, and 
* enable greater science outcomes through standardization and regulation of SuperDARN community-approved data formats

### DSWG Membership
The chair of the WG is appointed by the Executive Council. 

The WG can be joined by any members of the SuperDARN community willing to participate in its activities. Members should be approved by a SuperDARN PI, and the maximum number of members per institution is 3.

It is recommended that groups wishing to modify and/or replace their radar operations system (e.g., away from ROS), have a representative on the DSWG to ensure that their data outputs meet the standard data formats as required by the PIs’ agreement and the data policies. 

It is also recommended that groups wishing to contribute new analysis code (that results in a new data product output that they wish to have recognized as a standard) have a representative on the DSWG (in addition to the DAWG) to ensure that their data outputs meet the standard data formats as required by the PIs’ agreement and data policies. The scope of this WG as it pertains to analysis is only to support new data outputs in file I/O and ensure that the data output and all fields are well documented. Review of the analysis code is outside of the purview of the DSWG.

## Questions/Comments?

Please review the DSWG submission forms for [issues](https://github.com/SuperDARN/dswg-info/blob/master/docs/forms/issue.md) or [new formats](https://github.com/SuperDARN/dswg-info/blob/master/docs/forms/new_data_format.md) before submitting your request, and follow the forms if possible. For other general inquiries, email us at darn-dswg@isee.nagoya-u.ac.jp. 

