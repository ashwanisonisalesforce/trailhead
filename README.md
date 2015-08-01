
[Source](https://raw.githubusercontent.com/ashwinopensource/trailhead/master/ShowVisualforcepageinSalesforce1Mobile.htm "Permalink to Show Visualforce page in Salesforce1 Mobile")

# Show Visualforce page in Salesforce1 Mobile

&nbsp;

## Learning Objective

After completing this Quick Start tutorial you will be able to:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Create Visualforce page for Salesforce1 mobile

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Creating publisher action, mobile tab and mobile card

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Use visualforce page to various places in Salesforce1

&nbsp;

&nbsp;
## Ready a Visualforce Page 

1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Create Visualforce page for Salesforce1 mobile

2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; From Setup, **Develop** | **Pages**, and then clicking **New**.

3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Copy following code in Visualforce editor window


		<pre>
		<apex:page title="Trailhead QuickStart" standardcontroller="Account" showheader="false">

		<h1> Hello World, Hello Dreamforce! </h1>

		</apex:page>
		</pre>

4.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Check** the **Available for Salesforce mobile apps** checkbox

&nbsp;

![][1]

&nbsp;

5.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Save** button

Great! You just created your first Visualforce page.

&nbsp; 
## Create a Salesforce1 Mobile Tab

1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; From **Setup**, click **Create** | **Tabs**

2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **New** on **Visuaforce Tabs** section

3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Select **HelloDreamforce** page from **Visualforce Page** dropdown

4.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Name the tab Trailhead Demo in **Tab Label**

5.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Select any Tab Style from **Tab Style** lookup

![][2]

6.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Next** until you dont reach to **Step 3: Add to Custom Apps**

7.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Deselect **Include Tab** checkbox

8.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Save**

Great! You have just created Salesforce1 Mobile Tab.

&nbsp;

## Now lets add the mobile tab to Salesforce1 Mobile

1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; From **Setup**, click **Create** | **Tabs**

2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Edit** before to the tab Trailhead Demo on **Visuaforce Tabs** section

3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Check the **Salesforce Classic Ready** checkbox

![][3]

&nbsp;

4.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Save**

5.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; From Setup, click **Selesforce1 Setup** | **Navigation Menu** link

![][4]

6.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Select Trailhead Demo and click Add to move into **Selected** list

7.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Use **Up** and **Down** to put it as first item in list

8.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Save**

Awesome! You have just enabled the visualforce page for Salesforce1 mobile App. Login to the app, you would see your page as:

![][5]

&nbsp;

# Show the Visualforce page as an Action in Salesforce1 App

1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; From Setup, click on **Customize | Accounts | Buttons, Links and Actions**

2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **New Action**

3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Select **Action Type** Custom Visualforce from dropdown

4.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Select **Visualforce Page** HelloDreamforce from dropdown

5.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Set **Label** Say Hello Trailhead

6.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Save**

**![][6]**

**&nbsp;**

You have just defined a new action which can be used on Account object. Lets use it in Salesforce1

1.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; From Setup, click **Customize | Accounts | Page Layouts**

2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Edit** before to **Account Layout**

3.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In page layout editor Select **Quick Action** in navigation panel

&nbsp;

4.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Drag **Say Hello Trailhead** action and drop it to **Quick Action in Publisher** section

&nbsp;

![][7]![][8]

5.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Quick Save**

You have just enabled the Visualforce as a Quick Action to your Account. Lets check it Salesforce1 by opening any Account record

![][9]

6.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Same way, in page layout editor Select **Visualforce Pages** in navigation panel

7.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Drag **Say Hello Trailhead** Visualforce page and drop it to **Mobile Cards (Salesforce1 Only)** section

![][10]

8.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Click **Save**

**&nbsp;**

You have just set Visualforce page as mobile card in Salesforce1 page. Lets check it by opening any Account records **Related** tab in Salesforce1 App

![][11]

&nbsp; 
# Summary

_Verification With this unit you have learned the ways a Visualforce can be used in Salesforce mobile1 app. Each way has its own benefits. Now whenever you need to add a Visualforce you know the ways and how to do it.

# Resources
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Global Actions][12]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Notes on Predefined Field Values for Quick Actions][13]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Assign Global Publisher Layouts to User Profiles][14]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Salesforce1 Look and Feel in Visualforce pages][15]

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Show Custom Visualforce page in Salesforce1. Setup publisher action to allow user to check-in using Salesforce1&nbsp;app][16]

&nbsp;

[1]: /ShowVisualforcepageinSalesforce1Mobile_files/image001.png
[2]: /ShowVisualforcepageinSalesforce1Mobile_files/image002.png
[3]: /ShowVisualforcepageinSalesforce1Mobile_files/image003.png
[4]: /ShowVisualforcepageinSalesforce1Mobile_files/image004.png
[5]: /ShowVisualforcepageinSalesforce1Mobile_files/image005.png
[6]: /ShowVisualforcepageinSalesforce1Mobile_files/image006.png
[7]: /ShowVisualforcepageinSalesforce1Mobile_files/image007.png
[8]: /ShowVisualforcepageinSalesforce1Mobile_files/image008.png
[9]: /ShowVisualforcepageinSalesforce1Mobile_files/image009.png
[10]: /ShowVisualforcepageinSalesforce1Mobile_files/image010.jpg
[11]: /ShowVisualforcepageinSalesforce1Mobile_files/image011.png
[12]: https://help.salesforce.com/HTViewHelpDoc?id=actions_overview_global.htm "HTML (New Window)"
[13]: https://help.salesforce.com/HTViewHelpDoc?id=predefined_field_values_notes.htm "HTML (New Window)"
[14]: https://help.salesforce.com/HTViewHelpDoc?id=assigning_global_publisher_layouts_to_profiles.htm
[15]: https://intmist.wordpress.com/2014/02/16/salesforce1-look-and-feel-customise-visualforce-pages-for-salesforce1/
[16]: https://intmist.wordpress.com/2014/03/23/show-custom-visualforce-page-in-salesforce1-setup-publisher-action-and-check-in-using-salesforce1-app/
  