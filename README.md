This guide provides a comprehensive, step-by-step process for creating a custom configuration profile in Microsoft Intune using a JSON file. This method is essential for configuring application settings that are not available in a standard Intune template, such as specific browser policies from a CIS benchmark.

Prerequisites
A JSON file containing the application configuration settings (e.g., from a security benchmark).

Administrative access to the Microsoft Endpoint Manager admin center (Intune).

Step-by-Step Guide
Follow these steps to create a custom profile and apply your JSON file's settings.

Step 1: Navigate to the Intune Admin Center
Log in to the Microsoft Endpoint Manager admin center.

In the left navigation pane, select Devices > Windows > Configuration profiles.

Step 2: Create a New Profile
Click the Create profile button.

On the Platform dropdown, select Windows 10 and later.

On the Profile dropdown, select Templates.

Choose the Custom template from the list and click Create.

Step 3: Configure Profile Basics
On the Basics page, provide a meaningful Name for your profile (e.g., CIS Chrome Hardening via JSON).

Add an optional, but recommended, Description to explain the profile's purpose.

Click Next.

Step 4: Download the JSON file and upload into your Intune tenent.

After uploading the details, click Save. You can repeat this process to add more OMA-URI settings if your configuration requires it.

Once finished, click Next.

Step 5: Assign the Profile
On the Assignments page, select the groups of users or devices that will receive this profile.

Click Next.

Step 6: Review and Create
On the Review + create page, double-check all the settings you have configured.

When you are confident everything is correct, click Create to save and deploy the profile.
