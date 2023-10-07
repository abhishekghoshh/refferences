Open source contribution


https://www.hackerearth.com/getstarted-opensource/

Hactober fest introduction
https://thoughtworks.zoom.us/rec/share/Toor7HTGP9r6azbLdVqi23V5hdXnl1yXKCXCaGf8csOArszEIj4Km15D4dcWm84.3D-eCmdWVNrh9CLH?startTime=1664790355000
Passcode: pFKKsp6.


ONDC 

https://docs.google.com/document/d/1IqhfRuQZdnSP6agEILnbBlA4k7PC7S-xDjdpppm3yoI/edit -> ONDC - DPG
https://docs.google.com/document/d/10ymOPc3anjLRb24S7lMRPYi0IrRHd6t2Df5uI2Dn_qc/edit -> Dialects of India - Summary Document
https://drive.google.com/file/d/1a-AlGHwSaDwlAR9GjOpZIByJPIlSRn2S/view -> Dialects of India video 
Local Language support DPG
https://thoughtworks.zoom.us/rec/share/bOAzUk_VWTch9qnuQvnhhjWFsoymhnEWXkGoN2RpU0BK3xom7_h6iA4Hk7JBqq6d.2EDcbIj3f74QLH16 
Passcode: 0u4Q%18A
https://github.com/reshmisaji/Conversational-Commerce
https://github.com/shyamsathyanathan/innovation-hackathon-jan22
https://github.com/tirthankarbiswas24/innovation-hackathon-jan22

It would be great if someone would be interested to collaborate and contribute to the development of Local Language support for DPGA / ONDC.. 
1. vakyansh model training - looking for someone to explore the whether vakyansh can be used to detect local languages automatically . 
2. Looking for suggestion or alternate tool for conversation AI . Currently we are using Rasa . 
3. Trello board also have lot of stories under label Local Language support



Kubernetes

some good beginner friendly issues in the Kubernetes world(specifically K8s dashboard, which is the UI for K8s).
ref: https://github.com/kubernetes/dashboard/labels/good%20first%20issue
Some of these might require a good 1week hands on exp with k8s, but there're a few which are strictly UI(i.e. JS & CSS) issues and later one can try taking a stab at K8s specified issues.
Pre-requisites: There're some legal requirements before you can contribute to K8s, you'd need to sign-off your commits(just a -s flag) and sign the Contributor License Agreement, the process is slightly long but the k8s-ci-bot will guide you to complete it if you haven't already done it.
https://github.com/kubernetes/community/blob/master/mentoring/programs/meet-our-contributors.md

https://github.com/search?q=user%3Akubernetes+user%3Akubernetes-sigs+user%3Akubernetes-csi+user%3Akubernetes-client+label%3A%22good+first+issue%22+state%3Aopen&type=Issues&ref=advsearch&l=&l= 

Check Kubernetes slack



Backstage App

What's Backstage? Read more here: https://backstage.io/docs/overview/what-is-backstage
What's done so far? Kathir has done initialy analysis of the tool, repo etc and has identified few Good First Issues
What help is needed? Need folks with typescript knowledge to pair with Kathir, do further filtering of issues and start working on them.

Basics : 

* It is a developer Portal. It is one collective place where a developer can put all the documentation, infrastructure details, tools and system details. It is to increase productivity.
* Problem Statement - Jumping between multiple developer tools, segregated documentation. This was hampering the productivity.
* Backstage provides plugins to the developers.
* It came as Open Source Software as the problem statement was not limited to Spotify.
* BackStage offers multiple templates for different developer support, like, Spring Boot Service, Apollo Service, Documentation, Websites, Data Pipelines.
* It provides informative Dashboard for monitoring different data aspects.
* It even sets up new Starters for us in form of a service, eg, Spring Boot Service, ReactJs, etc.

Setting Up BackStage for the Contributor Mode : 

* Installations needed :
* Node JS
* Yarn
* Docker
* Run locally :
 
    # Start from your local development folder
    git clone --depth 1 git@github.com:backstage/backstage.git
    cd backstage

    # Fetch our dependencies and run an initial build
    yarn install
    yarn tsc
    yarn build

* We are now going to launch two things: an example Backstage frontend app, and an example Backstage backend that the frontend talks to. You are going to need two terminal windows, both starting from the Backstage project root.

    In the first window, run : 
    
    # From your Backstage root directory
    yarn --cwd packages/backend start

    In the other window, we will then launch the frontend. This command     is run from the project root, not inside the backend directory.

    yarn start

    That starts up the frontend on port 3000, and should automatically         open a browser window showing it.


Wiremock
Check GitHub page


Cloud carbon footprint 

Read more about CCF here: https://www.cloudcarbonfootprint.org/
Tech stack requirements: https://github.com/cloud-carbon-footprint/cloud-carbon-footprint/blob/trunk/Tech-Stack.png
Other git links:
https://github.com/cloud-carbon-footprint/cloud-carbon-footprint/issues?q=is%3Aopen+is%3Aissue+label%3Ahacktoberfest https://github.com/cloud-carbon-footprint/cloud-carbon-footprint
