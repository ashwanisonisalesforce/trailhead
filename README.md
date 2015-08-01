<div class="WordSection1">

# Learning Objective

<span style="font-size:11.0pt;
font-family:&quot;Calibri&quot;,&quot;sans-serif&quot;;color:black"> </span>

<span style="font-size:10.0pt;
font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;color:black">After completing this Quick Start tutorial you will be able to:</span>

<span style="font-size:10.0pt;
font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;
color:black">Create Visualforce page for Salesforce1 mobile</span>

<span style="font-size:10.0pt;
font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;
color:black">Creating publisher action, mobile tab and mobile card</span>

<span style="font-size:10.0pt;
font-family:Symbol;color:black">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;
color:black">Use visualforce page to various places in Salesforce1</span>

<span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,&quot;sans-serif&quot;;
color:black"> </span>

# Ready a Visualforce Page<span style="font-size:11.0pt;line-height:107%;
font-family:&quot;Calibri&quot;,&quot;sans-serif&quot;;color:black"> </span>

<span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,&quot;sans-serif&quot;;
color:black"> </span>

<span style="font-size:10.0pt;
font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;color:black">1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;
color:black">Create Visualforce page for Salesforce1 mobile</span>

<span style="font-size:10.0pt;
font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;color:black">2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;;
color:black">From Setup, **Develop** | **Pages**, and then clicking **New**.</span>

<span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Copy following code in Visualforce editor window</span>

<span style="color:#C55A11"><apex:page title="Trailhead QuickStart" standardController="Account" showHeader="false"></span>

<span style="color:#C55A11"><h1> Hello World, Hello Dreamforce! </h1></span>

<span style="color:#C55A11"></apex:page></span>

<span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">4.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span>**<span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Check</span>** <span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">the **Available for Salesforce mobile apps** checkbox</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image001.png)

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">5.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Save** button</span>

<span style="font-size:10.0pt;line-height:107%;font-family:
&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Great! You just created your first Visualforce page.</span>

# Create a Salesforce1 Mobile Tab

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">1.<span style="font:7.0pt &quot;Times New Roman&quot;">       </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">From **Setup**, click **Create** | **Tabs**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">2.<span style="font:7.0pt &quot;Times New Roman&quot;">       </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **New** on **Visuaforce Tabs** section</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">3.<span style="font:7.0pt &quot;Times New Roman&quot;">       </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Select **HelloDreamforce** page from **Visualforce Page** dropdown</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">4.<span style="font:7.0pt &quot;Times New Roman&quot;">       </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Name the tab “Trailhead Demo” in **Tab Label**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">5.<span style="font:7.0pt &quot;Times New Roman&quot;">       </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Select any Tab Style from **Tab Style** lookup</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image002.png)

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">6.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Next** until you don’t reach to **Step 3: Add to Custom Apps**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">7.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Deselect **Include Tab** checkbox</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">8.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Save**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:
&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Great! You have just created Salesforce1 Mobile Tab.</span>

## Now let’s add the mobile tab to Salesforce1 Mobile

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">From **Setup**, click **Create** | **Tabs**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Edit** before to the tab “Trailhead Demo” on **Visuaforce Tabs** section</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Check the **Salesforce Classic Ready** checkbox</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image003.png)

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">4.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Save**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">5.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">From Setup, click **Selesforce1 Setup** | **Navigation Menu** link</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image004.png)

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">6.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Select Trailhead Demo and click Add to move into **Selected** list</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">7.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Use **Up** and **Down** to put it as first item in list</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">8.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Save**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:
&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Awesome! You have just enabled the visualforce page for Salesforce1 mobile App. Login to the app, you would see your page as:</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image005.png)

# Create the Visualforce page as an Action in Salesforce1 App

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">From Setup, click on **Customize | Accounts | Buttons, Links and Actions**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **New Action**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Select **Action Type** “Custom Visualforce” from dropdown</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">4.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Select **Visualforce Page** “HelloDreamforce” from dropdown</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">5.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Set **Label** “Say Hello Trailhead”</span>

6.<span style="font:7.0pt &quot;Times New Roman&quot;">       </span> <span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Save**</span>

**![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image006.png)**

<span style="font-size:10.0pt;line-height:107%;font-family:
&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">You have just defined a new action which can be used on Account object. Let’s use it in Salesforce1</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">1.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">From Setup, click **Customize | Accounts | Page Layouts**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">2.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Edit** before to **Account Layout**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">3.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">In page layout editor Select **Quick Action** in navigation panel</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;"> </span>

4.<span style="font:7.0pt &quot;Times New Roman&quot;">       </span> <span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Drag **Say Hello Trailhead** action and drop it to **Quick Action in Publisher** section</span>

<span style="position:absolute;z-index:251662336;left:0px;margin-left:309px;
margin-top:463px;width:373px;height:265px">![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image007.png)</span> ![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image008.png) 

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">5.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Quick Save**</span>

<span style="font-size:10.0pt;line-height:107%;font-family:
&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">You have just enabled the Visualforce as a Quick Action to your Account. Let’s check it Salesforce1 by opening any Account record</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image009.png)

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">6.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Same way, in page layout editor Select **Visualforce Pages** in navigation panel</span>

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">7.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Drag **Say Hello Trailhead** Visualforce page and drop it to **Mobile Cards (Salesforce1 Only)** section</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image010.jpg)

<span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">8.<span style="font:7.0pt &quot;Times New Roman&quot;">     </span> </span><span style="font-size:10.0pt;line-height:107%;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">Click **Save**</span>

**<span style="font-size:10.0pt;line-height:107%;
font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;"> </span>**

<span style="font-size:10.0pt;line-height:107%;font-family:
&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">You have just set Visualforce page as mobile card in Salesforce1 page. Let’s check it by opening any Account record’s **Related** tab in Salesforce1 App</span>

![](Show%20Visualforce%20page%20in%20Salesforce1%20Mobile_files/image011.png)

# Summary

With Tutorial you have learned the ways a Visualforce can be used in Salesforce mobile1 app. Each way has its own benefits. Now whenever you need to add a Visualforce you know the ways and how to do it.

# Resources

<span style="font-size:10.0pt;font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">[<span style="text-decoration:none">Global Actions</span>](https://help.salesforce.com/HTViewHelpDoc?id=actions_overview_global.htm "HTML (New Window)")</span>

<span style="font-size:10.0pt;font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">[<span style="text-decoration:none">Notes on Predefined Field Values for Quick Actions</span>](https://help.salesforce.com/HTViewHelpDoc?id=predefined_field_values_notes.htm "HTML (New Window)")</span>

<span style="font-size:10.0pt;font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">[<span style="text-decoration:none">Assign Global Publisher Layouts to User Profiles</span>](https://help.salesforce.com/HTViewHelpDoc?id=assigning_global_publisher_layouts_to_profiles.htm)</span>

<span style="font-size:10.0pt;font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">[<span style="text-decoration:none">Salesforce1 Look and Feel in Visualforce pages</span>](https://intmist.wordpress.com/2014/02/16/salesforce1-look-and-feel-customise-visualforce-pages-for-salesforce1/)</span>

<span style="font-size:10.0pt;font-family:Symbol">·<span style="font:7.0pt &quot;Times New Roman&quot;">      </span> </span><span style="font-size:10.0pt;font-family:&quot;Segoe UI Semilight&quot;,&quot;sans-serif&quot;">[<span style="text-decoration:none">Show Custom Visualforce page in Salesforce1\. Setup publisher action to allow user to check-in using Salesforce1 app</span>](https://intmist.wordpress.com/2014/03/23/show-custom-visualforce-page-in-salesforce1-setup-publisher-action-and-check-in-using-salesforce1-app/)</span>

</div>