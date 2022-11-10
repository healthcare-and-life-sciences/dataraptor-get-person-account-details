<h1 id='HGRACAyLDZV'>A-HLS - DataRaptor Library Documentation - DRgetPersonAccountDetails</h1>

<i>This DataRaptor acts as a base for developers to get information about a Person Account quickly.</i><br/>

<hr style='width:100%'><h2 id='HGRACAjGTf6'>Overview</h2>

A DataRaptor is a mapping tool to help read, transform, and write Salesforce data. There are four types of DataRaptors: <span style="color:#1e1e1c" textcolor="#1e1e1c">Turbo Extract, Extract, Load, and Transform. You can use these four methods to extract data for digital customer interactions and business processes to present data. </span><br/>

<br/>

This Data Raptor Extract collects meaningful information about a specific "Person Account".<br/>

<hr style='width:100%'><h2 id='HGRACAff6SQ'>Business Objective</h2>

The Business objective is to quickly extract information about a specific ‘Person Account’ that can be meaningful to achieve the jobs to be done for a business user or reporting.<br/>

<h2 id='HGRACALLfBL'><span style="color:#333333" textcolor="#333333">Business Value and Benefits</span></h2>

<div class="" data-section-style='5' style=""><ul id='HGRACA0C4wG'><li id='temp:C:HGRf5ae8e98c54a4c2bb743e474b' class='' value='1'><span style="color:#0e101a" textcolor="#0e101a">Decrease IT costs associated with custom build</span>

<br/></li><li id='temp:C:HGR12e2d37185794ba6915d8c1c1' class=''>Improve user experience

<br/></li></ul></div><hr style='width:100%'><h2 id='HGRACASaRnG'>Export-Package Includes</h2>

<h3 id='HGRACAXWiWs'><b>DataRaptor (1)</b></h3>

<div class="" data-section-style='5' style=""><ul id='HGRACATtwcx'><li id='HGRACARNBVh' class='' value='1'>DRgetPersonAccountDetails

<br/></li></ul></div><h2 id='HGRACAYTHMr'><b>JSON Reference</b></h2>

<div class="" data-section-style='5' style=""><ul id='HGRACAnqpEh'><li id='HGRACAD2Ug7' class='' value='1'>{<br>  "PersonAccount": {<br>    "AccountNumber": "Text",<br>    "FirstName": "Text",<br>    "LastName": "Text",<br>    "Name": "Text",<br>    "Phone": "Text",<br>    "Email": "Text",<br>    "City": "Text",<br>    "PostalCode": "Text",<br>    "State": "Text",<br>    "Street": "Text",<br>    "FullAddress": "Text",<br>    "CustomerSinceDate": "Text",<br>    "Birthdate": "Text",<br>    "MiddleName": "Text",<br>    "PersonAccountId": "Text",<br>    "Gender": "Text",<br>    "PrimaryPlanName": "Text",<br>    "SecondaryPlanName": "Text"<br>  },<br>  "PersonAccountId": "Text",<br>  "Account": {<br>    "Case": {<br>      "Subject": "Text"<br>    }<br>  }<br>}

<br/></li></ul></div><hr style='width:100%'><h2 id='HGRACASkWZt'>Configuration Requirements</h2>

<div class="" data-section-style='5' style=""><ul id='HGRACAYyp3c'><li id='HGRACAClHtD' class='' value='1'>The Data Raptor is ready to be imported and customized. No further base configuration requirements are necessary.

<br/></li></ul></div><h4 id='HGRACAyusbE'>Install the Data Pack</h4>

<div class="" data-section-style='6' style=""><ul id='HGRACAxrESi'><li id='HGRACAISVsW' class='' value='1'>The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: <a href="https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetPersonAccountDetails">https://github.com/HLS-Accelerate/DataRaptor-Library/tree/main/DRgetPersonAccountDetails</a>

<br/></li><li id='HGRACA62csq' class='parent'>Then, complete the following steps to import them into your Salesforce org.

<br/></li><ul><li id='HGRACAoB9bp' class=''>To Import, in your destination Salesforce org, Click on <b>App Launcher</b> → Search for '<b>OmniStudio DataPacks</b>' and click on it.

<br/></li><li id='HGRACARicfT' class=''>Click on '<b>Installed</b>' and on the right side click on '<b>Import from</b>'.

<br/></li><li id='HGRACAntvNR' class=''>Select '<b>From File</b>' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '<b>Install</b>'.

<br/></li></ul><li id='HGRACAok4OE' class=''>More about DataRaptors: <a href="https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors">https://trailhead.salesforce.com/content/learn/modules/omnistudio-dataraptors</a>

<br/></li></ul></div><hr style='width:100%'><h2 id='HGRACAoGOGW'><span style="color:#333333" textcolor="#333333">Assumptions</span></h2>

<div class="" data-section-style='5' style=""><ul id='HGRACAqZuSp'><li id='HGRACASs28u' class='' value='1'>A customer has licenses for Health Cloud and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.

<br/></li><li id='HGRACAnWpkv' class=''>A customer is assuming Salesforce Lightning Experience — not Classic.

<br/></li><li id='HGRACAlcF9Y' class=''>Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are available.

<br/></li><li id='HGRACAnis0m' class=''>The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their branding.

<br/></li><li id='HGRACAPaWZW' class=''><span style="color:#0e101a" textcolor="#0e101a">Objects’ Case’, Account, and ‘CareDignosis’ are available, and access is permitted to these objects to make changes at any time.</span>

<br/></li></ul></div><h2 id='HGRACAOkDhy'>Installed Packages Requirement</h2>

<div class="" data-section-style='5' style=""><ul id='HGRACAShKSx'><li id='HGRACACtWr9' class='' value='1'>HealthCloud (HealthCloudGA) - Version 236.1 or higher

<br/></li><li id='HGRACAW96ul' class=''>Vlocity Insurance (vlocity_ins) - Version 890.317 or higher

<br/></li></ul></div><hr style='width:100%'><h2 id='HGRACAUnGtJ'>Revision History</h2>

<div class="" data-section-style='5' style=""><ul id='HGRACAUIiRz'><li id='HGRACAdZ159' class='parent' value='1'><b>Revision Short Description (May 12, 2022)</b>

<br/></li><ul><li id='HGRACAxpkA2' class=''>Error correction from previous versions to adapt to the new Data Model.

<br/></li><li id='HGRACAQJ7vG' class=''>Initial export with QA.

<br/></li></ul><li id='HGRACAXsfYp' class='parent'><b>Revision Short Description (June 21, 2022)</b>

<br/></li><ul><li id='HGRACAEoVjo' class=''>Updated Documentation.
