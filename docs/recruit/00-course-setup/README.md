# 🚨 Mission 00: Course Setup

## 🕵️‍♂️ CODENAME: `OPERATION DEPLOYMENT READY`

> **⏱️ Operation Time Window:** `~30 minutes`  

## 🎯 Mission Brief

Welcome to the first mission of your training as a Copilot Studio Agent.  
Before you can start building your first AI agent, you need to establish your **field-ready development environment**.

This briefing outlines the systems, access credentials, and setup steps required to successfully operate in the Microsoft 365 ecosystem.

## 🔎 Objectives

Your mission includes:

1. Loging into a developer environment as your Copilot Studio environment to build in  
1. Creating a SharePoint site to serve as your data source in later missions

---

## Step 1: Login into the development environment

Copilot Studio resides within Microsoft 365, so you need a Microsoft 365 account to access it. You can use the existing account you have been provided as an intern, e.g. intern@axm365.com/intern@axaptamasters.com.

1. **Open Microsoft Copilot Studio**  
   1. Go to the [Microsoft Copilot Studio](https://copilotstudio.microsoft.com/)
   2. Login with your Microsoft 365 account.
   3. Once the platform is opened, change the environment to **AXM AI Playground**, this will be the environment where you will do your lab exercises and implement your project. 
   <img width="1850" height="1009" alt="image" src="https://github.com/user-attachments/assets/07b25666-9ca4-4712-84df-f67e096f4d49" />
   

> **Note:** You should only use the environment **AXM AI Playground**, do not use the default environment **Axapta Masters (default)** or any other environment (if you have access to).


---

## Step 2: Create new SharePoint site

A new SharePoint site needs to be created  which will be used in [Lesson 06 - Create a custom agent using the conversational creation experience with Copilot and grounding it with your data](/06-create-agent-from-conversation/README.md/#62-add-an-internal-knowledge-source-using-a-sharepoint-site).

1. Select the waffle icon on the top left hand side of Microsoft Copilot Studio to view the menu. Select SharePoint from the menu.

   ![Select SharePoint](images/0.4_01_SelectSharePoint.png)

1. SharePoint will load. Select **+ Create  site** to create a new SharePoint site.

   ![Create site](images/0.4_02_CreateSite.png)

1. A dialog will appear to guide you in creating a new SharePoint site. Select **Team site** or **Communication site**.

   ![Team site](images/0.4_03_SelectTeamOrCommunicationSite.png)

1. In the next step, a list of Microsoft templates will load by default. Scroll down and select the **IT help desk** template.

   ![IT help desk template](images/0.4_04_SelectITHelpDeskTemplate.png)

1. Select **Use template** to create a new SharePoint site using the IT help desk template.

   ![Use template](images/0.4_05_SelectUseTemplate.png)

1. Enter information for your site. The following is an example:

    | Field | Value |
    | --- | --- |
    | Site name | Contoso IT |
    | Site description | Copilot Studio for Beginners |
    | Site address | ContosoIT |

   ![Site information](images/0.4_06_SiteDetails.png)

1. In the final step, a language can be selected for the SharePoint site. By default it will be **English**. Leave the Language as **English** and select **Create site**,

   ![Language and other options](images/0.4_07_LanguageOtherOptions.png)

1. The SharePoint site will provision for the next few seconds. In the mean time, you can choose to add other users to your site by entering their email address in the **Add members** field. When completed, select **Finish**.

   ![Select finish](images/0.4_08_SelectFinish.png)

1. The SharePoint site home page will next load. **Copy** the SharePoint site URL.

1. This template provides pages with sample data about various IT policies and two sample lists (Tickets and Devices).

### Use Devices SharePoint list

We will use the **Devices** list for in [Lesson 07 - Add new topic with trigger and nodes](../07-add-new-topic-with-trigger/README.md#73-add-node-add-a-tool-using-a-connector).

### Add new column

Scroll to the far right in the list and select the **+ Add column** button.  Choose the **hyperlink** type, enter **Image** for the column name, and select add.

### Create sample data in Devices SharePoint list

You need to make sure you fill in this list with at least 4 sample data items and add one additional column to this list.  

When adding sample data, make sure that the following fields are filled out:

- Device photo - use the images from the [device images folder](https://github.com/microsoft/mcs-agent-academy-recruit/tree/main/docs/00-course-setup/images/device-images/)
- Title
- Status
- Manufacturer
- Model
- Asset Type
- Color
- Serial Number
- Purchase Date
- Purchase Price,
- Order #
- Image - use the following links

|Device  |URL  |
|---------|---------|
|Surface Laptop 13     | [https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/laptop-13-ocean-render-compare-fy25?scl=1](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/laptop-13-ocean-render-compare-fy25?scl=1)        |
|Surface Laptop 15     | [https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/laptop-15-black-render-compare-fy25?scl=1](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/laptop-15-black-render-compare-fy25?scl=1)        |
|Surface Pro    | [https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/pro-violet-render1-fy25?scl=1](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/pro-violet-render1-fy25?scl=1)        |
|Surface Studio    | [https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/surface-studio-2-plus-compare-render?scl=1](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/surface-studio-2-plus-compare-render?scl=1)        |

---

## ✅ Mission Complete

You’ve successfully:

- Set up a Microsoft 365 dev environment  
- Activated your Copilot Studio trial  
- Created a SharePoint site for grounding agents  
- Populated the Devices list for use in future missions

You're officially cleared to begin your **Recruit-level agent training** in [Lesson 01](../01-introduction-to-agents/README.md).  

![mcs-agent-academy-recruit-00](https://m365-visitor-stats.azurewebsites.net/?resource=https://github.com/microsoft/mcs-agent-academy-recruit/tree/main/00-course-setup)
