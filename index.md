This site contains course materials for SISG Module 17: Computational Pipeline for WGS Data, July 27-29, 2022. **Course evaluations and certificates of completion will be available via the [official SISG course web page](https://si.biostat.washington.edu/about/sisg/SM2217)** (requires login).

- **Instructors:** Ken Rice, Laura Raffield, and Matthew Conomos
- **TAs:** Deepti Jain and Anya Mikhaylova
- **Zoom Link:** [https://washington.zoom.us/j/91863603677](https://washington.zoom.us/j/91863603677)
- **[Join the Slack Discussion](https://uwbiostatisticssisg.slack.com/archives/C03KLGG4XRV)**

## Course Format

#### Lectures
Course material will be presented through lectures given via Zoom. Slides for lectures are linked in the schedule below, and recordings of the lectures will be posted afterwards.

#### Exercises
Many of the lectures will be followed with hands-on exercises. Students will be split into Zoom breakout rooms where they can work through the exercises together. Afterwards, the instructors will walk through the exercises and lead a discussion.

To run the exercises, log into [NHLBI BioData Catalyst powered by Seven Bridges](https://platform.sb.biodatacatalyst.nhlbi.nih.gov) with your username and password -- we will use this platform for all live demonstrations during the course.

- You will retain access to the Seven Bridges platform, including your SISG Project with all of the course materials even after the course ends. The SISG22 Workshop billing group will remain available to you for a short period of time, after which you will need to set up another payment method to run analyses. You can [request pilot cloud credits](https://biodatacatalyst.nhlbi.nih.gov/resources/cloud-credits) ($500 worth) from BioData Catalyst. Additionally, there is guidance available for [writing BioData Catalyst cloud costs into your grant proposal budget](https://bdcatalyst.gitbook.io/biodata-catalyst-documentation/written-documentation/getting-started/writing-biodata-catalyst-into-a-grant-proposal). 

All of the R code and data can also be downloaded from the [github repository](https://github.com/UW-GAC/SISG_2022) from which the site is built and run on your local machine. Download the complete workshop data and exercises: [https://github.com/UW-GAC/SISG_2022/archive/master.zip](https://github.com/UW-GAC/SISG_2022/archive/master.zip)


## Schedule

NOTE: All times are Pacific Daylight Time (GMT-07:00)

**Wednesday, July 27th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 11:30am-11:40am | Introduction | [Slides](https://docs.google.com/presentation/d/1QMS6cSLso9eMl96P7A7OHmkDpN3g1qFyupQE7cOA4Fk/edit?usp=sharing), [Recording](https://washington.zoom.us/rec/share/c6C5waiqjiQpe1-tjdyeZS1i4tSxTEnFPuQchzJkDIf_jCuajultVCeZtQdUrtZ6.m9BQTA4kZJ4xru4I?startTime=1658946853000) | |
| 11:40am-12:30pm | Using BioData Catalyst powered by Seven Bridges | [Slides](https://docs.google.com/presentation/d/1hyWz19Q2AlKX3dCZ1boOLf07-e0UTQPb2jSqXsctnvE/edit?usp=sharing), [Recording](https://washington.zoom.us/rec/play/Q-iGd9ML-omsBbr15IYRj1Uj2bFmYmF57Pqi-B0VG7nFisievtqnwtuljAnkdeCMUINqq8jJo-PnrDu4.WtU8h5mJCoXBtcO7?startTime=1658947757000&_x_zm_rtaid=HPyzAFjaQB2lkSPPv10ndQ.1658967472251.e1488b9b00b9fb91e68acc546cab2c7f&_x_zm_rhtaid=426) | |
| 12:30pm-1:30pm | Intro to Genomic Data Structure Format | [Slides](https://drive.google.com/file/d/1SpB4X5dBxKlCsLfQqAB6lm0cnnNbiEPJ/view?usp=sharing), [Recording](https://washington.zoom.us/rec/play/TIXnTau5p56RdjD-Az9GyfW_D6xcCRDdfCVmoXKD4fJDMSmbP5wjIPVocvayE5bJoccAPL4wR-mrXzri._ePzSBMtRAVPGWBo?startTime=1658950005000&_x_zm_rtaid=HPyzAFjaQB2lkSPPv10ndQ.1658967472251.e1488b9b00b9fb91e68acc546cab2c7f&_x_zm_rhtaid=426) | [.Rmd](https://github.com/UW-GAC/SISG_2022/blob/main/01_gds_intro.Rmd), [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2022/blob/main/01_gds_intro.html), [Recording](https://washington.zoom.us/rec/play/akAtKD_Gq7dgPWnnRToqtMAuCHU1WQGy11u_U8I9Yl1VHOkB1aUSNvWn2VfnMbzzevrmtFQbdDtlGIzi.Z-lZPd8yDzXVm_4M?startTime=1658953235000&_x_zm_rtaid=HPyzAFjaQB2lkSPPv10ndQ.1658967472251.e1488b9b00b9fb91e68acc546cab2c7f&_x_zm_rhtaid=426) |
| 1:30pm-1:45pm | _Break_ | | |
| 1:45pm-2:30pm | Association Tests Part I: Background | [Slides](https://drive.google.com/file/d/13zwtz8ZEK5LqglkbZjf4OSf2GPPCRmoG/view?usp=sharing), [Recording](https://washington.zoom.us/rec/play/cL2qlR4UUgl8DPdWldjXR8A0yvtfpaFeXA9pIjXTD2s8Y58iswU4BwWKcPA-CXmUZxi_b-2oGaTu9yD-.IS7BjaWAhBTq1UpL?startTime=1658954748000&_x_zm_rtaid=HPyzAFjaQB2lkSPPv10ndQ.1658967472251.e1488b9b00b9fb91e68acc546cab2c7f&_x_zm_rhtaid=426) | |

**Thursday, July 28th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 8:00am-8:50am | Association Tests Part II: Single Variant Tests | [Slides](https://drive.google.com/file/d/13zwtz8ZEK5LqglkbZjf4OSf2GPPCRmoG/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659020598000) | |
| 8:50am-9:45am | Single Variant Association Tests with GENESIS | [Slides](https://drive.google.com/file/d/1bF5fFQMrrWt1SdQyBdpgUW8Hnpbld451/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659023972000) | [.Rmd](https://github.com/UW-GAC/SISG_2022/blob/main/02_single_variant_tests.Rmd), [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2022/blob/main/02_single_variant_tests.html), [Recording](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659026102000) |
| 9:45am-10:15am | _Break_ | | |
| 10:15am-11:45am | Population Structure and Relatedness <br /> Inference for Association Studies | [Slides](https://drive.google.com/file/d/1o8cueO0dwVn_PP3TQgceu0tabwjpqOfg/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659028615000) | [.Rmd](https://github.com/UW-GAC/SISG_2022/blob/main/03_pop_structure_relatedness.Rmd), [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2022/blob/main/03_pop_structure_relatedness.html), [Recording](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659033001000) |
| 11:45am-12:45pm | _Lunch_ | | |
| 12:45pm-2:00pm | Mixed Model Association Testing | [Slides](https://drive.google.com/file/d/15F4ZDUs575MqZ3VwBef4W_3lLcNhEmIo/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659037652000) | [.Rmd](https://github.com/UW-GAC/SISG_2022/blob/main/04_mixed_models.Rmd), [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2022/blob/main/04_mixed_models.html), [Recording](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659041805000) |
| 2:00pm-2:30pm | R shiny Apps for Exploring Results Demo | [Recording 1](https://washington.zoom.us/rec/share/YHxFo4-xqKrRW6uX23HF4KqF2vULE_BHsplro6_xHeuWTJonH_DTQRJWvK11UIDI.O_SudZyVCAaup84v?startTime=1659043029000), [Recording 2](https://washington.zoom.us/rec/share/GOq9yUco7E1-XS4xeAzvttBZK5w86JVFAU4lOGzgUmPH07X4OdqYYPGczDx_Cfpe.Y2P8gUjevt7Q3AGY?startTime=1659052683000) | [.Rmd](https://github.com/UW-GAC/SISG_2022/blob/main/05_exploring_association_results.Rmd), [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2022/blob/main/05_exploring_association_results.html) |

**Friday, July 29th**

| Time | Topic | Lecture | Exercises/Discussion |
| --- | --- | --- | --- |
| 8:00am-9:00am | Association Tests Part III: Multiple Variant Tests | [Slides](https://drive.google.com/file/d/13zwtz8ZEK5LqglkbZjf4OSf2GPPCRmoG/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/MFnywAIue1TU7WX6nV6hUp8N7_l68KQQHFtBGzCCFM441wwMIxm5p-YFpZgw-ZS7.VsFaeyWxCd_50TmC?startTime=1659075010000) | |
| 9:00am-9:20am | Variant Annotation for Aggregate Association Testing  | [Slides](https://drive.google.com/file/d/18cqwxTBxoBv2cNh6rdiRjl5nflmP5noA/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/iuNJWKgmmq9soQW2EgTygwx9hEpM5YJ0af7y336eDB3i_3l3RSKD-cDPqLendvT3.Uab8UriKRZ8vMJCn?startTime=1659110634000) | |
| 9:20am-10:00am | Aggregate Association Tests with GENESIS | [Slides](https://drive.google.com/file/d/13o-7MrSFmWS4bie8hrBIXHKGiWZa3HFi/view?usp=sharing) | [.Rmd](https://github.com/UW-GAC/SISG_2022/blob/main/06_aggregate_tests.Rmd), [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2022/blob/main/06_aggregate_tests.html), [Recording](https://washington.zoom.us/rec/share/iuNJWKgmmq9soQW2EgTygwx9hEpM5YJ0af7y336eDB3i_3l3RSKD-cDPqLendvT3.Uab8UriKRZ8vMJCn?startTime=1659113532000) |
| 10:00am-10:30am | _Break_ | | |
| 10:30am-11:15am | Annotation Explorer Demo | [Recording](https://washington.zoom.us/rec/share/iuNJWKgmmq9soQW2EgTygwx9hEpM5YJ0af7y336eDB3i_3l3RSKD-cDPqLendvT3.Uab8UriKRZ8vMJCn?startTime=1659115915000) | [.Rmd](https://github.com/UW-GAC/SISG_2022/blob/main/07_annotation_explorer.Rmd), [.html](https://htmlpreview.github.io/?https://github.com/UW-GAC/SISG_2022/blob/main/07_annotation_explorer.html) |
| 11:15am-12:00pm | Advanced Annotation Strategies for Association Testing | [Slides](https://drive.google.com/file/d/142SSmVz99uHVimXKsKoK1Nh2TFWKrt-u/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/iuNJWKgmmq9soQW2EgTygwx9hEpM5YJ0af7y336eDB3i_3l3RSKD-cDPqLendvT3.Uab8UriKRZ8vMJCn?startTime=1659118196000) |  |
| 12:00pm-1:00pm | _Lunch_ | | |
| 1:00pm-2:00pm <br /> 2:00pm-2:30pm | Recent Findings for WGS Studies <br /> Open Q&A| [Slides](https://drive.google.com/file/d/1tvJ317L_Dnx3VjN29RhCCgIyMXkkV4lL/view?usp=sharing), [Recording](https://washington.zoom.us/rec/share/iuNJWKgmmq9soQW2EgTygwx9hEpM5YJ0af7y336eDB3i_3l3RSKD-cDPqLendvT3.Uab8UriKRZ8vMJCn?startTime=1659124914000) |  |


## R packages used

- [GENESIS](http://bioconductor.org/packages/release/bioc/html/GENESIS.html)
- [SeqArray](http://bioconductor.org/packages/release/bioc/html/SeqArray.html)
- [SeqVarTools](http://bioconductor.org/packages/release/bioc/html/SeqVarTools.html)
- [SNPRelate](http://bioconductor.org/packages/release/bioc/html/SNPRelate.html)
- [Biobase](https://bioconductor.org/packages/release/bioc/html/Biobase.html)
- [GGally](https://cran.r-project.org/web/packages/GGally)


## Resources

NHLBI BioData Catalyst Powered by Seven Bridges

- [Getting Started Guide for SISG22 Module 17](https://drive.google.com/file/d/1VjIFxEfF6tvlkIVCjFGeIiBRDmGNLbvn/view?usp=sharing)

A detailed tutorial and relevant R scripts for STAAR pipeline are available at [https://github.com/xihaoli/STAARpipeline-Tutorial](https://github.com/xihaoli/STAARpipeline-Tutorial). STAAR pipeline apps will also be released soon on BioData Catalyst.

If you are new to R, you might find the following material helpful:

- [Introduction to R](http://faculty.washington.edu/kenrice/rintro/) materials from SISG Module 3
- Graphics with [ggplot2](https://ggplot2.tidyverse.org/)
- Data manipulation with [dplyr](http://dplyr.tidyverse.org/)
