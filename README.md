# Static-website

**Project Overview**

A project demonstrating the use of Azure to host a static website, as well as configuring budget alerts to monitor and control subscription costs.

**Architecture/Design decisions**

Before producing any resources for this project I configured a Budget alert, this would help me monitor how much I spend on Azure each month for all projects.

A pre existing Resource group within a nearby region was usedto deploy the Static Web App.

Linking my github account allowed me to use this repository as a host for all storage files, this avoids the need to manually provision and managae Azure Blob Storage or other Storage services that Azure offers.

<img width="1632" height="687" alt="image" src="https://github.com/user-attachments/assets/65552668-fcfa-439b-8d80-24b00e6ab171" />

*Screenshot showing configuring the static web app to use github in regards to deployment information*

<img width="1503" height="757" alt="image" src="https://github.com/user-attachments/assets/9e58a83c-4878-4852-bafd-edc7082aea21" />
*Screenshot showing the summary of configuration for the Static Web App*

<img width="1912" height="1019" alt="image" src="https://github.com/user-attachments/assets/15410e8a-1072-4280-b0d2-3b88eb148a40" />
*Screenshot of Static Web App summary screen(Clicking visit your site presented a welcome screen instead of my website example*

**Issues Encountered**

To resolve the website not being presented problem we first needed to go back to my github respositry.

After Investigation, **I realised two issues**:

My webpage initially was not called index.html(Default name that web servers search for)

The App Location was incorrect(A local pathway instead of linking to github repository)

<img width="1872" height="912" alt="image" src="https://github.com/user-attachments/assets/1569bcb9-93fa-485f-92b3-6179e2d525dc" />

*Screenshot of workflow code that was produced when the web app was formed and linked to Github*

After correcting these issues, the workflow on github completed sucessfuly and the website was deployed as expected.

<img width="1919" height="920" alt="image" src="https://github.com/user-attachments/assets/02a76eb2-93b6-4be3-99a0-1554277463ab" />

*Successful deployment of website shown by workflow status tick*

**What I learnt**

I Learnt the importance of organisation during troubleshooting and how valuable the skill is to have

How to configure and provision an Azure Static Web App

How to troubleshoot deployment issues using Github Actions

How to manage cloud cost through various management systems such as Budget Alerts

**Cleanup and Cost Management**

As best industry practice I deleted all resources used except the website included in this respositry this avoid any unwanted space being used up and any unecessary costs occuring.
