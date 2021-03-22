# SAP Identity Management - Business Extensions Service

## Description
This repository contains the content of the SAP Identity Management Business Extensions Service from SAP Consulting. The aim is to make its content available for customers and partners.
Considerations:
* The content can be downloaded and used without any license charges.
* If you require support during installation, configuration or when using, modifying or extending the content you need to open an SAP support incident under support component XX-PROJ-CON-SEC.
* If you did not purchase the service from SAP Consulting, you will get charged for the support activities. 

## Requirements
SAP Identity Management 8.0 SP07 (latest version)

## Download and Installation
Please reffer to the Configuration Guide inside the package.

## Known Issues
* When using SP08 of Identity Management 8.0 certain java class imports inside javascript will lead to errors due to the changed javascript engine version (fix planned for SP05)
* MX_DISABLED and SAPC_IDEN_REP_DISABLED_<repName> not in list of modify trigger attributes of ABAP and ABAP BusinessSuite connector (fix planned for SP05)
* Attribute MX_ACADEMMIC_TITLE_1 is using value help which has been removed in standard schema. This can lead to errors using new standard version of HCM Staging Area package (fix planned for SP05)

## How to obtain support

[Create an issue](https://github.com/SAP-samples/<repository-name>/issues) in this repository if you find a bug or have questions about the content.
 
For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## Contributing

## License
Copyright (c) 2021 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
