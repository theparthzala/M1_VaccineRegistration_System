# M1_VaccineRegistration_System

## Introduction

The deployment of covid-19 vaccines in India was done in a sudden burst and thus the tracking became very complicated. Due to multiple input and output commands on the server, it resulted in several slow running issues and crashes. The Aadhar details were used to allot the vaccines and hence it operated on a central server. To avoid the use of central server for all commmands, a local server will be loaded with the vaccine-registered data. Local verification and completion of vaccination data will be processed locally and will be loaded back to the main server by the end of day.

Each vaccine centre will operate locally to register and allot vaccines. The basic registration can be done online and schedules are set as desired by the patient. Assuming a vaccination centre can vaccinate around 100 people in a day. The data handling for online basic registration will be mostly done in the day time and the data acquired by the local centres of vaccinated people can be handled in the night.

The local server must store the data of around 100 people where the allocated online registration data will be loaded onto the local server of that local centre. Verification of the data is done based on the details provided by the patient. Once completed, the data of the vaccinated will be sent back for future use and reference.

## OBJECTIVE 

- This project aims to monitor and register the vaccine registration status of people.

## Codacy and Codiga Scores

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/7603e730c6b34961935590ebb8c71867)](https://www.codacy.com/gh/theparthzala/M1_VaccineRegistration_System/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=theparthzala/M1_VaccineRegistration_System&amp;utm_campaign=Badge_Grade)

![CODEQUALITYSCORE](https://api.codiga.io/project/32259/score/svg)

![CODEGRADE](https://api.codiga.io/project/32259/status/svg)

## Code Inspector

<a href="https://app.codiga.io/public/user/github/theparthzala">
   <img src="https://api.codiga.io/public/badge/user/github/theparthzala?style=light" alt="codiga badge" />
</a>

![vrs_code Inspector](https://user-images.githubusercontent.com/101014587/160985485-1415dbf5-f24b-42c6-8070-ee557b633dbb.png)

## Badges

[![Valgrind](https://github.com/theparthzala/M1_VaccineRegistration_System/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/theparthzala/M1_VaccineRegistration_System/actions/workflows/Valgrind.yml)

[![Build Linux](https://github.com/theparthzala/M1_VaccineRegistration_System/actions/workflows/Linux.yml/badge.svg)](https://github.com/theparthzala/M1_VaccineRegistration_System/actions/workflows/Linux.yml)

[![CI](https://github.com/theparthzala/M1_VaccineRegistration_System/actions/workflows/C-cpp.yml/badge.svg)](https://github.com/theparthzala/M1_VaccineRegistration_System/actions/workflows/C-cpp.yml)

## Folder Structure

| Folder | Description |
| ------ | ----------- |
| 1_Requirements | Documents detailing requirements and research |
| 2_Architecture |	Documents specifying design details |
| 3_Implementation	| All code and documentation |
| 4_TestPlan |	Documents with test plans and procedures |
| 5_Report |	Report of the whole project |
| 6_Images | Images of the Output |

## Contributors List and Summary 

* Some Test Cases are similar functions and are merged

| S No | Name | Features | Issues Raised | Issues Resolved | Number of Test Cases | Test Case Pass |
| ---- | ---- | -------- | ------------- | --------------- | -------------------- | -------------- |
| 1 | Parth Zala | All | 1 | 1 | 6 | 6 | 

## Integrated Tools to Github

- [codacy](https://app.codacy.com/organizations)
- [codiga](https://app.codiga.io)

## Challenges Faced and How Did I Overcome

| S No |	Challenge | Solution |
| ------ | ----------- | --------- |
| 1 | Implementation of SDLC and making UML diagrams |	Exploring them and linking with the architechture of my project |
| 2 |	issues in running test cases | specifying correct return values for functions |
| 3 |	Issues in workflows |	fixed them by updating the path to all files correctly |

## GitHub Actions

- Build using Make for CI
- Unit testing 
- Static code analysis using cppcheck
- Dynamic Code analysis using Valgrind

## References

* You tube C programming learning 
* Geeks for Geeks 
* Reference from C text books

## Learning Resources

- [markdownCheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [markdownBasics](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [git inspector](https://github.com/ejwa/gitinspector)
- [github workflow](https://docs.github.com/en/actions/learn-github-action)
