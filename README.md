# EGI_DataHub-training

This repository contains the exercises for the internal training on the EGI DataHub.

## Requirements

* A valid account to access the [EGI Training infrastructure](https://wiki.egi.eu/wiki/Training_infrastructure).
* Basic knowledge of Linux user environment, [Docker container](https://docs.docker.com/engine/reference/commandline/container/) and the [requests](http://docs.python-requests.org/en/v2.7.0/) library of Python (v2.7.2+) are requested.
* An access token to access the volume space in [Onedata](https://onedata.org/).

## Generate a token to access the Onedata volume space

To generate your personal access token using the web interface, please follow these steps:
* Log in the EGI DataHub service at: https://datahub.egi.eu/ using the [EGI AAI Check-In service](https://www.egi.eu/services/check-in/).
* Click on the <b>"ACCESS TOKENS"</b> menu.
* Clink on <b>"Create new access token"</b>.
* Store the token somewehere safe.

How to generate your access token with REST API will be introduced in Exercise no.4 (see below)

## Access the EGI Training Infrastructure
Use your personal account to access the [EGI Training infrastructure](https://wiki.egi.eu/wiki/Training_infrastructure)

<pre>
]$ ssh -X your_user_account@212.189.145.XX
</pre>

if you do not have a valid account, please contact: giuseppe.larocca@egi.eu

## Exercises

This repository includes the following exercises:
- [Install the oneclient Docker container to access the volume space](Exercise_01)
- [Analyse the datasets in the volume space](Exercise_02)
- [Register the result of the analysis in Zenodo general-purpose open-access repository](Exercise_03)
- [How to generate an ACCESS_TOKEN via REST API](Exercise_04)

## License
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this project except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

