# Overview
This example contains the sample SBPA project which interacts with embed tagged object.

# Instructions:
* Project archive (MTAR) can be downloaded from ![here](https://github.com/sbpatrial/pages/raw/main/embed/EmbedTagProject.mtar).
* After that you can import the project as per this ![instruction](https://help.sap.com/docs/build-process-automation/sap-build-process-automation/importing-project) into your SBPA tenant.
* The project contains one automation: *MainAutomation* and one UIAutomation type application: *chrome*
* For the *popupScreen*, please do not distinguash the screen with *Name*. For other criteria settings, you can check them from the project directly.
* In order to run the automation, please start a chrome and open the link: *https://sbpatrial.github.io/pages/embed/embed.html*
* The MainAutomation will click on the **Print** button from the initial screen and then click on the **Save** button
* The project is validated against to Desktop Agent with version: *3.28.54* and SDK: *1.51.15*

# Caution
This is just an example project demonstrate how to interact with embed tagged object from SBPA automation. It's not a ready to use project can be directly used for productive usage. Further validation, adjustments are required from your side to make it work.
