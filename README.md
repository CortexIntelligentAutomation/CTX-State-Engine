
<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# State Engine Cortex Module
The current Cortex State Engine module focuses on the parallelisation of Cortex flow executions based on a complex system of dependencies.

The module allows users to perform the following functionality:
* Configure a process and the automated or manual stages that comprise it
* Configure the start conditions of each stage
* Monitor the executions of processes and their stages using a custom user interface


## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
1) [Support and Warranty](#support-and-warranty)
2) [Installation](#installation)
3) [How to use](#how-to-use)
4) [How you can contribute](#how-you-can-contribute)
5) [Versioning](#versioning)
6) [Licensing](#licensing)


## Dependencies
### Cortex Version
This version of the Continuous Integration module was developed in Cortex version 6.4. Some functionality may not be available on different versions of Cortex.

### OCIs
The  module requires the following Cortex OCIs:
* PowerShell
* HTTP

### Files
The Continuous Integration module requires the following files:
* [CTX-State-Engine.studiopkg](https://github.com/CortexIntelligentAutomation/CTX-State-Engine/releases/download/v1.0/CTX-State-Engine.studiopkg)
* [CTX-State-Engine Database create script](https://github.com/CortexIntelligentAutomation/CTX-State-Engine/releases/download/v1.0/Cortex-State-Engine-Install.sql)

### Other
The Continuous Integration module has the following additional requirements:
* CTX-Logging module
* CTX-Configuration-Store module
* CTX-Email module
* CTX-Gateway module

## Support and Warranty 
This module is supplied as a template that you can amend and extend to fit your requirements, as such it is not supported as part of the Cortex Product suite under the Cortex product support agreement.

## Installation
Details of the installation can be found in the [State Engine Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-State-Engine/blob/main/CTX-State-Engine%20-%20Deployment%20Plan.pdf).
## How to use
A detailed User Guide has been provided with instructions on how to use the flows/subtasks, available [here](https://github.com/CortexIntelligentAutomation/CTX-State-Engine/blob/main/CTX-State-Engine%20%20-%20%20User%20Guide.pdf). Configuration of subtask inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
Continuous Integration has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 21/05/2021 | State-Engine Manage-Executions-UI | Created 
v1.0 | 21/05/2021 | State-Engine-Log-Browser-UI | Created 
v1.0 | 21/05/2021 | State-Engine-Monitor-Stage-Executions | Created 
v1.0 | 21/05/2021 | State-Engine-Start-Process-Execution | Created 
v1.0 | 21/05/2021 | State-Engine-Convert-List-To-HTML | Created 
v1.0 | 21/05/2021 | State-Engine-Convert-Structure-To-HTML | Created 
v1.0 | 21/05/2021 | EDBQ-State-Engine-Execute-DB-Query | Created
v1.0 | 21/05/2021 | ES-State-Engine-End-Stage | Created 
v1.0 | 21/05/2021 | State-Engine-Params-to-HTML | Created 
v1.0 | 21/05/2021 | ES-State-Engine-Escalate-Stage | Created 
v1.0 | 21/05/2021 | CCI-Test-Cases-Execution | Created 
v1.0 | 21/05/2021 | ES-State-Engine-Stage-Completed | Created
v1.0 | 09/11/2021 | State-Engine-Configure-Definitions-UI | Created
 


## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
