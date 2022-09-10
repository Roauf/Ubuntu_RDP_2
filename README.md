# About
This is a github action to get a ubuntu virtual machine through Chrome Remote Desktop.

# Disclaimer
I am not responsible if you're account is banned. 
Don't use this vps for :
* Cryptomining
* Using our servers to disrupt, or to gain or to attempt to gain unauthorized access to, any service, device, data, account, or network (other than those authorized by the GitHub Bug Bounty program)
* The provision of a stand-alone or integrated application or service offering Actions or any elements of Actions for commercial purposes
* Any activity that places a burden on our servers, where that burden is disproportionate to the benefits provided to users (for example, don't use Actions as a content delivery network or as part of a serverless application, but a low benefit Action could be ok if it’s also low burden)
* Any other activity unrelated to the production, testing, deployment, or publication of the software project associated with the repository where GitHub Actions are used.

## How To Run ?

# Setting up:

Variables Name | Uses | Notes
----- | ----- | -----
`NGROK AUTH TOKEN` | For **ngrok** tunnel uses | Go to website login or signup & copy Your Authtoken from https://dashboard.ngrok.com/auth/your-authtoken
`USER NAME` | For VPS username | Type any name you want
`USER PASSWORD` | For VPS user password | Type any password you want
`MACHINE NAME` | For VPS system `Machine` name | Type any name you want
`AUTH CODE` | For chrome remote desktop | Visit and copy the command after Authentication from http://remotedesktop.google.com/headless
`PIN CODE` | For chrome remote desktop | Type a Pin (more or equal to 6 digits)
***

* Fork this project.
* Go to `Actions` Tab and select one of system workflow.
* Fill the gaps.
* Click `Run Workflow` button.
* Wait until a few minutes.
* Go to `https://dashboard.ngrok.com/endpoints/status` and check if theres a one online tunnel running.
* Go to `http://remotedesktop.google.com/headless` and you can see the machine in the list then login using `PIN CODE`.
* Copy the IP and connect through any software that supports SSH sonnection.
* Fill in those login info, within username from `USERNAME`and password from `USER PASSWORD` you typed.

# License

        Copyright (c) 2022 Diwas007

       Licensed under the Apache License, Version 2.0 (the "License");
       you may not use this file except in compliance with the License.
       You may obtain a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

       Unless required by applicable law or agreed to in writing, software
       distributed under the License is distributed on an "AS IS" BASIS,
       WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
       See the License for the specific language governing permissions and
       limitations under the License.
