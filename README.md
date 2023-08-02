<!DOCTYPE html>
<html>
<head>
  <title>Netsuite Forms Manual and Documentation</title>
  <style>

   @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;500;700&display=swap');


    h1 {
        font-family: 'Montserrat', sans-serif;
        font-weight: 700;

    }

    h2, h3 {
        font-family: 'Montserrat', sans-serif;
        font-weight: 500;
        
    }
    .titles {
    background-color: #e9e9e9;
    padding: 5px;
    
  }

  .titles2 {
    border-left: 2px solid black;
    padding: 5px;
  }
    p, h4, h5 {
        font-family: 'Montserrat', sans-serif;
        font-weight: 300;
        font-size: 16px;
    }

    ul li {
        font-family: 'Montserrat', sans-serif;
        font-weight: 400;
    }



    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      
      
    }
    .menu {
      
      background-color: #f0f0f0;
      padding: 20px;
      
      width: 25%;
    }
    .content {
      flex: 3;
      background-color: #ffffff;
      padding: 20px;
      overflow-y: auto; /* Add vertical scroll to the content */
    }

    .menulist {
        position: fixed;
        flex: 1;
      
      padding: 20px;
      
      width: 20%;
    }
    

    .logo1{
        width: 60%;
               
    }

    .menu h2 {
  font-family: 'Montserrat', sans-serif;
  font-size: 24px;
  font-weight: 500;
  margin-bottom: 10px;
  
}

.menu ul {
  list-style-type: none;
  padding-left: 0;
  
}

.menu li {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  font-weight: 400;
  margin-bottom: 5px;
  margin-top: 15px; /* Add margin to separate topics vertically */

}

.menu a {
  text-decoration: none;
  color: #333;
  font-size: 13px;
}

.menu a:hover {
  color: #007bff;
}

.font-body{
  font-size: 14px;
}


  </style>
</head>


<body>
   
<!-- Menu Column -->

  <div class="container">
    
  
    
    <div class="menu">
         
        
      <div class="menulist">
        <img class="logo1" src="https://4800298.app.netsuite.com/core/media/media.nl?id=11267451&c=4800298&h=cO9emzspzETZrl70tKedWNEYB2Gp1Rp2f3e-4LIlJI7zRDCo&fcts=20230730222219&whence=" alt="Imagem">
        
        <h4>Netsuite Forms Menu:</h4>
        <p style="font-size:14px "><strong>1: Documentation</strong> </p>
<ul>
  <li><a href="#about-documentaton">Objective</a></li>
  <li><a href="#summary"><strong>Summary</strong></a></li>
  <li><a href="#founder-forms-list">Founder Forms List</a></li>
  <li><a href="#general-changes">Changes Made</a></li>
  

</ul>

<p style="font-size:14px; padding-top: 15px;"><strong>2: Manual</p>
<ul>
  <li><a href="#languages">Netsuite Forms Programming Languages Used</a></li>
  <li><a href="#sandbox">Sandbox and Good Practices</a></li>
  <li><a href="#basic-structure">Basic Structure</a></li>
  <li><a href="#css">CSS Customization</a></li>
  <li><a href="#images">Inserting Images</a></li>
  <li><a href="#placeholders">Placeholders</a></li>
  <li><a href="#functions">Functions</a></li>
  
</ul>

    </div>

    </div>



<!-- Content Collumn -->

    <div class="content">
      <h2 id="about-documentaton">&nbsp;</h2>
        <h1>Netsuite Forms</h1>
        <h1>Founder Documentation and Manual</h1>
        <h3><strong>FORTUS / DEKK / ITC AGRICULTURE  / FWT</strong></h3>
        <p>August / 2023</p>
        <br>
    
        
        <h2 class="titles">Comprehensive Documentation of NetSuite Form Changes</h2>
        
    
        <p>The objective of this documentation is to provide a detailed and accessible guide to the modifications made to the 8 NetSuite forms by Conrado and Marketing Team.
           By documenting the custom CSS, HTML elements, and JavaScript functionality implemented, this guide aims to empower future team members to:</p>
<br>
        <ul>
            <li>
              <strong>Understand Form Modifications:</strong>
              <p>Gain a clear understanding of each NetSuite form's purpose, significance, and role in the company's operations.</p>
              <p>Comprehend the specific changes made to each form, including custom CSS styles, HTML elements, and JavaScript enhancements.</p>
            </li>
            <li>
              <strong>Maintain and Update Forms:</strong>
              <p>Effectively maintain and troubleshoot the modified forms, ensuring seamless operation and user experience.</p>
              <p>Make informed updates or improvements to the forms in alignment with evolving business requirements.</p>
            </li>
            <li>
              <strong>Enhance User Experience and Functionality:</strong>
              <p>Leverage the documented changes to enhance the user experience of customers and internal users interacting with the forms.</p>
              <p>Expand the functionality of the forms as needed, supporting efficient business processes.</p>
            </li>
            <li>
              <strong>Promote Collaboration and Knowledge Sharing:</strong>
              <p>Facilitate effective collaboration among team members by providing a centralized and comprehensive reference for form modifications.</p>
              <p>Encourage knowledge sharing and cross-training within the team to ensure collective expertise in handling the modified forms.</p>
            </li>
            <li>
              <strong>Ensure Continuity and Legacy:</strong>
              <p>Preserve the legacy of form modifications made by [Your Name or Team Name], ensuring that valuable insights are retained for the benefit of future team members.</p>
              <p>Guarantee continuity and consistency in form management, reducing the learning curve for new team members joining the project.</p>
            </li>
          </ul><br>
          <hr>
<br>
<br>

<!-- DIVIDER -->


<!-- SUMMARY -->

<h2 id="summary" >&nbsp;</h2>
<h2 class="titles">Summary:</h2>
    
<h3>Objective: Comprehensive Documentation of NetSuite Form Changes</h3>

<p>To view a form, click on the corresponding link below. This will take you to the form's detail page, where you can see all the related information.</p>

            <ul>
                <li><a href="#about-documentaton">Comprehensive Documentation of NetSuite Form Changes</a></li>
                <li><a href="#founder-forms-list">Founder Forms List</a></li>
                <li><a href="#general-changes">Changes Made</a></li>
                <li><a href="#languages">Which Languages are uses on Netsuite forms?</a></li>
                <li><a href="#sandbox">Sandbox and Good Practices</a></li>
                <li><a href="#basic-structure">Basic Structure</a></li>
                <li><a href="#css">CSS Customization</a></li>
                <li><a href="#images">Inserting Images</a></li>
                <li><a href="#placeholders">Placeholders</a></li>
                <li><a href="#functions">Functions</a></li>
    <!-- Add more items as needed -->
            </ul>






<BR><BR>

    <!-- SPACE -->

    <!-- Founder Forms Changes List -->
          
           <h2 id="founder-forms-list">&nbsp;</h2>
          <h2 class="titles">Founder Forms List</h2>
    
          <h3>Welcome to the list of forms filled out by the founders. Below are the forms available for viewing:</h3>

          <p>To view a form, click on the corresponding link below. This will take you to the form's detail page, where you can see all the related information.</p>

            <ul>
                <li><a href="#general-changes">Changes Made</a></li>
                <li><a href="#credit-memo">FD: credit memo</a></li>
                <li><a href="#taxinvoice">FD: tax invoice</a></li>
                <li><a href="#packing-slip">FD : Packing Slip</a></li>
                <li><a href="#picking-ticket">FD : Picking Ticket v5</a></li>
                <li><a href="#purchase-order">FD : Purchase Order v2</a></li>
                <li><a href="#quotation">FD : Quotation</a></li>
                <li><a href="#sales-order">FD : Sales Order V3</a></li>
                <li><a href="#statement">Statement</a></li>
    <!-- Add more items as needed -->
            </ul>

<br>
<h2 id="general-changes">&nbsp;</h2>
            
<h2 class="titles">General Changes Made - Founder Forms</h2>

<p>Note: To find the updated forms, just follow the same name as here on Netsuite live version. If you need to check the code before all the changes, just access the Standard Form. <br>For example: "Standard Invoice PDF/HTML Template".</p>

<br>
<h3><li>Landscape Orientation:</li></h3>

<p>One of the notable modifications I made in NetSuite Forms was first made to the TAX Invoice and than applied for the all the other ones. We enhanced the display by changing it<strong> from portrait to landscape orientation</strong>, providing a more user-friendly and visually appealing layout for the invoice.</p>
<p><strong>CSS:</strong></p>
<pre><code>size=A4-landscape</code></pre>

<P>And after change to landscape we needed to adjust the whole layout using HTML tables, CSS and Placeholders. To know more about these languanges and how to use them on NEtsuite Forms, please read section 2 Netsuite Forms Programming and Customization Manual. And to consult general ans specific changes on each form please visit Section 1. <a href="#about-documentaton">Documentation.</a> To check all the chnages made so for, please visit this link <a href="#manual"> Manual</a> </P>



<!-- general changes break -->
<br>

<h2 id="filenametag">&nbsp;</h2>
<h3><li>Transparent Title Form Name on the footer: Filename Tag</li> </h3>

<p>Added Tag Title in white just to create a mark</p>

<p><strong>HTML:</strong></p>
<pre><code>
  &lt;td class="filename"&gt;FDI : Packing Slip&lt;/td&gt;

  </td></code></pre>


  <p><strong>CSS:</strong></p>
  <pre><code>
 .filename {
        color: #ffffff;
      }

    </code></pre>

<p style="font-size: 14px;"><i>Note: All the forms has the "filename" tag.</i></p>

<!-- general changes break -->

<br>
<h2 id="consolidated-forms-functon">&nbsp;</h2>
<h3><li>Consolidated forms functon</li> </h3>

<p><strong>Objective:</strong> Have 3 subsidiaries or more on the same code form. On the past we use to use 3 diferent forms, but now with this new function is consolidated. </p>
<p>It is applied in all forms.</p>
<p>
The Idea is to have the 3 subsidiaries on the same form.<br>

<strong>Function idea:</strong><br> IF subsidiary is "DEKK" DEKK details, ELSE iniciate new condition:<br>
IF subsidiary is FORTUS, show Fortus details, ELSE show ITC.
<br><br>
(if/else(if/else)
<br><br>
So, the system will check for DEKK, than Fortus and Than ITC. 

</p>
<p><strong>HTML:</strong></p>
  <pre><code>
    <tr>
      <td rowspan="4">
        <#if subsidiary == "Dekk Rubber Tracks and Pads">
          &lt;!-- Dekk Rubber Tracks and Pads --&gt;
          &lt;img class="logo-dekk" src="https://4800298.app.netsuite.com/core/media/media.nl?id=1070854&amp;c=4800298&amp;h=9254139c6d17e5e5eee3" /&gt;
            
            <#else> 
              
              <#if subsidiary == "ITC Agriculture">
                &lt;!-- ITC --> 
                &lt;img class="logo-itc" src="https://4800298.app.netsuite.com/core/media/media.nl?id=1663999&amp;c=4800298&amp;h=3ZyATM3qFMJus3827nK4b9zbs8SUfvp-ZFffUhhSFANnekEw" /&gt;
                  <#else>
                  &lt;img class="logo-fortus" src="https://4800298.app.netsuite.com/core/media/media.nl?id=240264&amp;c=4800298&amp;h=7e74323af66dfa029cd5" /&gt;
                 </#if>
                  </#if>
      </td>
    </tr>
 
  
  </td></code></pre>

  <p><strong>Note:</strong>  The logic used is called "Conditional Control Structure" or "Conditional Statement." In programming languages like JavaScript, C++, Python, and others, this structure is commonly implemented using if, else if, and else statements.

  This conditional control structure allows the program to execute different blocks of code based on certain conditions. In the provided HTML code, the use of <#if>, <#else>, <#else if>, and </#if> represents the implementation of a conditional control structure within a NetSuite template. This conditional logic is used to determine which image will be displayed based on the value of the subsidiary variable.</p>
 

<!-- general changes break -->


  <br>
  <h2 id="branch-name-function">&nbsp;</h2>
  <h3><li>Branch Name function</li> </h3>
  <p> *** This is applied on Quotation Form. *** </p>
  <p><strong>Objective:</strong> We wanted to abreviate the branch locations, so always when a location name saved on the System is called, we abreviate the information on the related branch: </p>
  
<p>Assing variables on the head:</p>
<pre>
  &lt;#assign subsidiary= record.subsidiary /&gt;
  &lt;#assign branch= record.location /&gt;

  <p>Note: record.subsidiary is the placeholder to get subsidiary name saved on Netsuite and record.location is the placeholder to get the location saved on Netsuite:</p>

  <p> Function Example: </p>
  &lt;#if branch = "NSW (Consolidated) : NSW (DT) : Sydney - DT"&gt;
    &lt;#assign branchname="Sydney - NSW" /&gt;

    <p> Function applied: </p>



    &lt;table style="width: 100%;"&gt;
      &lt;tr&gt;
        &lt;td class="addressheader"&gt;&lt;b&gt;FORTUS BRANCH:&lt;/b&gt;&lt;/td&gt;
      &lt;/tr&gt;
      &lt;tr&gt;
        &lt;td class="address"&gt;  
          &lt;p&gt;  
            ${branchname} &lt;br&gt;&lt;/br&gt; ${street} &lt;br&gt;&lt;/br&gt;${citypostcode}
          &lt;/p&gt;
        &lt;/td&gt;
      &lt;/tr&gt;
</pre>



<br><br>
<hr>
<!-- Form details -->

<h1>Forms:</h1>
 <p>Check here specific details changes on each form.</p>
<ul>
  <li><a href="#general-changes">Changes Made</a></li>
  <li><a href="#credit-memo">FD: credit memo</a></li>
  <li><a href="#taxinvoice">FD: tax invoice</a></li>
  <li><a href="#packing-slip">FD : Packing Slip</a></li>
  <li><a href="#picking-ticket">FD : Picking Ticket v5</a></li>
  <li><a href="#purchase-order">FD : Purchase Order v2</a></li>
  <li><a href="#quotation">FD : Quotation</a></li>
  <li><a href="#sales-order">FD : Sales Order V3</a></li>
  <li><a href="#statement">Statement</a></li>
<!-- Add more items as needed -->
</ul>


<h2 id="credit-memo" >&nbsp;</h2>
            <h2 class="titles2">FD : Credit Memo</h2>
            <h3>Form Structure</h3>
            <p>Important details relevant to this invoice:</p>
            <ul>
              <li>ABN</li>
              <li>logo</li>
              <li>Footer</li>
              <li>Message only for Fortus Subsidiary: <span style="font-size: 12px;"><br>
                <i>"All manufacturer’s names, numbers, symbols and descriptions are used for reference purposes only and it is not implied that any part listed is the product of these manufacturers."</i></span></li>
            </ul>

            <P>
              <span style="font-size: 12px;"><br>
                <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus and <a href="#filenametag">Filename tag</a> .</i></span></p>
            

            <br>

                <!-- Separator -->
                <hr style="width: 50%; margin: 0;">
                <!-- Separator -->

            <h2 id="taxinvoice" >&nbsp;</h2>
            <h2  class="titles2">FD: tax invoice</h2>

                <h3>Form Structure</h3>
                <p>Important details relevant to this invoice:</p>
                <ul>
                  <li>ABN</li>
                  <li>logo</li>
                  <li>Footer</li>
                  <li>Bank Details and Contact</li>
                  <li>Branch Name Function</li>
                  <li>Message only for Fortus Subsidiary: <span style="font-size: 12px;"><br>
                    <i>"All manufacturer’s names, numbers, symbols and descriptions are used for reference purposes only and it is not implied that any part listed is the product of these manufacturers."</i></span></li>
               
                </ul>

                <P>
                  <span style="font-size: 12px;"><br>
                    <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus and <a href="#filenametag">Filename tag</a> .</i></span></p>
<br>
              <h3>August 2023:</h3><p class="font-body"> Added one more subsidiary on the TAX Invoice: Fortus Wear Technology (FWT)</p> </h3>                
                <pre><code>
                <!-- FWT -->
                <#if subsidiary = "Fortus Wear Technology">
                <#assign bankname="ANZ Bank" />
                <#assign bsb="016-318" />
                <#assign accno="641-591-795" />
                <#assign phone="1300 363 969" />
                <#assign email="accountsrec@fortusgroup.com.au" />
        
                <#else></pre></code>




                



                <br>


                <!-- Separator -->
                <hr style="width: 50%; margin: 0;">
                <!-- Separator -->


                <h2 id="packing-slip" >&nbsp;</h2>
                <h2 class="titles2">FD : Packing Slip</h2>
                <p>Here are the details of Form 3...</p>
  
                <h3>Form Structure</h3>
                <p>Important details relevant to this invoice:</p>
                <ul>
                  <li>ABN</li>
                  <li>logo</li>
                  <li>Footer</li>
                  <li>Bank Details and Contact</li>
                  
</ul>
<P>
  <span style="font-size: 12px;"><br>
    <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus and <a href="#filenametag">Filename tag</a> .</i></span></p>



                <!-- Separator -->
                <hr style="width: 50%; margin: 0;">
                <!-- Separator -->

                <h2 id="picking-ticket" >&nbsp;</h2>
                <h2 class="titles2">FD : Picking Ticket v5</h2>
                <h3>Form Structure</h3>
                <p>Important details relevant to this invoice:</p>
                <ul>
                  <li>logo</li>
                  <li>Footer</li>
                 <li>Created:</li>
                  <li>Last Modified:</li>
                  </ul>

                  <P>
                    <span style="font-size: 12px;"><br>
                      <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus and <a href="#filenametag">Filename tag</a> .</i></span></p>
  


<br>
                <!-- Separator -->
                <hr style="width: 50%; margin: 0;">
                <!-- Separator -->

                <h2 id="purchase-order" >&nbsp;</h2>
                <h2 class="titles2">FD : Purchase Order v2</h2>
                <p>Important details relevant to this invoice:</p>
                <ul>
                  <li>logo</li>
                  <li>Footer</li>
                  <li>ABN</li>
                  </ul>
                <P>
                  <span style="font-size: 12px;"><br>
                    <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus and <a href="#filenametag">Filename tag</a> .</i></span></p>

                <!-- Separator -->
                <hr style="width: 50%; margin: 0;">
                <!-- Separator -->

                <h2 id="quotation" >&nbsp;</h2>
                <h2 class="titles2">FD : Quotation</h2>
                <ul>
                  <li>ABN</li>
                  <li>logo</li>
                  <li>Footer</li>
                  <li>Bank Details and Contact</li>
                  <li>Message only for Fortus Subsidiary: <span style="font-size: 12px;"><br>
                    <i>"All manufacturer’s names, numbers, symbols and descriptions are used for reference purposes only and it is not implied that any part listed is the product of these manufacturers."</i></span></li>
               
                </ul>

                <P>
                  <span style="font-size: 12px;"><br>
                    <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus. <a href="#branch-name-function">Branch Name Function</a> and <a href="#filenametag">Filename tag</a> .</i></span></p>


                <!-- Separator -->
                <hr style="width: 50%; margin: 0;">
                <!-- Separator -->

                <h2 id="sales-order" >&nbsp;</h2>
                <h2 class="titles2">FD : Sales Order V3</h2>
                <li>ABN</li>
                  <li>logo</li>
                  <li>Footer</li>
                  <li>Bank Details and Contact</li>

                <P>
                  <span style="font-size: 12px;"><br>
                    <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus. <a href="#branch-name-function">Branch Name Function</a> and <a href="#filenametag">Filename tag</a> .</i></span></p>



                <!-- Separator -->
                <hr style="width: 50%; margin: 0;">
                <!-- Separator -->

                <h2 id="statement" >&nbsp;</h2>
                <h2 class="titles2">FD : Statement</h2>
                <li>ABN</li>
                  <li>logo</li>
                  <li>Footer</li>

                <P>
                  <span style="font-size: 12px;"><br>
                    <i>Functions: <a href="#consolidated-forms-functon">Consolidated forms functon</a> for DEKK, ITC and Fortus and <a href="#filenametag">Filename tag</a> .</i></span></p>





  <!-- Add more form details as needed -->

<br>


    <!-- DIVIDER -->
          <hr>
         


            <h1 id="manual">&nbsp;</h1>
            <h1>2. Founder Forms Manual</h1>

            <h1 id="read-me">
              <h1 id="languages">
              <p>- Read me -</p>
         
            <h2 class="titles">
            Which Programing Languages Does NetSuite Use for These Forms?</h2>
            <p>CSS, HTML, Javascript and Fremarker template as template engine:  </p>
            
            <h3>Fremarker Brief:</h3>
            <p>
            <strong>Freemarker is an open-source template engine widely used for creating document templates in various applications, including web development.</strong> It allows developers to separate the presentation layer from the data, making it easier to generate dynamic content.</p>
            
            <p>
                <strong> In the context of NetSuite, Freemarker is utilized for creating custom forms and templates. When designing forms, developers mainly use HTML and CSS to define the structure and style of the form's layout.</strong></strong> Freemarker acts as the template engine that enables the insertion of dynamic data into these HTML and CSS templates. This dynamic data can be sourced from NetSuite records, transactions, or custom data sets.</p>
            
            <p>
            Freemarker's syntax <strong> allows you to embed placeholders, known as variables or expressions, inside the HTML/CSS templates. </strong> These placeholders are then replaced with actual data when the form is rendered, generating a customized and dynamic form that corresponds to the specific data within NetSuite.</p>
            
            <p>
            Additionally, <strong>JavaScript can be integrated into the Freemarker templates to create small functions and interactivity within the forms.</strong> This enables developers to add dynamic behavior, validation, and user interactions to enhance the user experience.</p>
            
            <p>
            <strong>Overall, Freemarker in NetSuite is a powerful tool that enables the creation of personalized and data-driven forms by combining HTML, CSS, and JavaScript with dynamic data from NetSuite's backend, resulting in a seamless user interface and streamlined data presentation.</strong>
            </p>

          
<br>
          <!-- DIVIDER -->


              <h2 id="sandbox">&nbsp;</h2>
              <h2 class="titles">
                Sandbox and Good Practices</h2>
            
            
            <h3>What is Sandbox:</h3>
            <p>
            A sandbox is a separate and isolated environment that allows developers, administrators, and businesses to safely test, develop, and experiment with changes and customizations without affecting the live or production system. In the context of NetSuite, a sandbox is a non-production environment where you can make changes to your NetSuite account without risking the integrity of your live data. </p>
              <h3>How to access it?</h3>
              <p>you need to login using your email and password from the Netsuite site.<br>
              Best to use incognito mode or a differrent browser</p>
              
              <p>Open this in a incognito window to access Sandbox. You can use your Netsuite Login details</p>


  <a href="https://system.netsuite.com/pages/customerlogin.jsp">https://system.netsuite.com/pages/customerlogin.jsp</a>
   
  </p>
<br>
 <!-- Separator -->
 <hr style="width: 50%; margin: 0;">
 <!-- Separator -->
<br>
             <h2> Some reasons why sandboxes are important:</h2>

             <p>

              <strong>Risk-Free Testing:</strong> Sandboxes provide a safe space to test new configurations, customizations, and third-party integrations without impacting real data or processes. This minimizes the risk of errors, data corruption, or system downtime in the live environment.
              
              <br><br>
              <strong>Development and Customization: </strong>Sandboxes are essential for customizing NetSuite forms, workflows, scripts, and other functionalities. Developers can work freely in the sandbox environment to build and fine-tune solutions before deploying them to the production environment.
              
              <br><br>
              <strong>Training and Learning: </strong>Sandboxes are valuable for training purposes, as users can experiment with the system and learn new features without affecting the live data. It is particularly useful for onboarding new employees and teaching them how to use NetSuite effectively.
              
              <br><br>
              <strong>Version Upgrades:</strong> Before performing a major version upgrade of NetSuite, it is advisable to test the new version in a sandbox first. This ensures that existing customizations and configurations are compatible with the new release.
              
              <br><br>
              <strong>Regression Testing:</strong> Whenever changes are made to the NetSuite account, such as applying a bundle or updating scripts, sandbox environments are used to perform regression testing to ensure that the changes do not cause unintended consequences.
              
              <br><br>
              <strong>Compliance and Auditing: </strong>For businesses operating in regulated industries, a sandbox provides an ideal environment for compliance testing and auditing purposes.
              
              When creating NetSuite forms, it's essential to follow some best practices to ensure they are efficient, user-friendly, and consistent with the rest of the system. Here are some good practices for creating NetSuite forms:
              
              Keep it Simple and Intuitive: </strong>Design forms with a clean and straightforward layout. Avoid clutter and unnecessary fields, so users can easily navigate and understand the information presented.
              
              <br><br>
              <strong>Consistency:</strong> Maintain consistency in form design across your NetSuite account. Consistent layouts, field names, and field order enhance the user experience and make the system more user-friendly.
              <br><br>
             <strong> Group Related Fields:</strong> Organize fields logically into groups or sections based on their relevance or purpose. This makes it easier for users to comprehend and fill out the form.
             <br><br>
             <strong>Use Field Help and Tooltips:</strong> Provide helpful descriptions and tooltips for fields to guide users in filling out the form correctly. This reduces the chances of user errors and misunderstandings.
              
              <br><br>
              <strong>Validate Data:</strong> Implement data validation to ensure that users enter valid and appropriate data. Use field-level validations or client scripts to enforce data rules and prevent incorrect data entry.
              
              <br>
              <strong>Responsive Design: </strong>If your organization uses NetSuite on multiple devices, design your forms with responsive layout techniques to ensure they work well on different screen sizes, such as desktops, tablets, and smartphones.
              
              Performance Considerations: </strong>Avoid adding unnecessary customizations or complex scripts that may slow down the form's loading time. Optimize the form for performance to ensure a smooth user experience.
              
              <br><br>
              <strong>Security: </strong>Be mindful of the security settings when creating forms. Limit access to sensitive data and actions to authorized users only.
              
              <br><br>
              <strong>User Testing:</strong> Before deploying the form to the production environment, thoroughly test it in the sandbox with representative users to gather feedback and make necessary improvements.
              
              By adhering to these best practices, you can create effective and user-friendly NetSuite forms that streamline data entry and improve user productivity.


              
        

            </p>

<!-- DIVIDER -->

<h2 id="basic-structure">&nbsp;</h2>

  <h2 class="titles">
    Basic Structure</h2>




<!-- What does a form look like? -->

<br>

            <h2 >What does a Netsuite form look like?</h2>

            <h3>Form reference: FD : Tax Invoice (01/08/2023)</h3>

            <p>This is an example of Fortus TAX Invoice </p>
            <a href="https://4800298.app.netsuite.com/core/media/media.nl?id=11300678&c=4800298&h=9E-_qg-BSHnOGszkkR0DwwreROV_YEyp8NPsWKJW_n53ikzv&fcts=20230731185657&whence=" target="_blank">
              <img style="width: 90%;" src="https://4800298.app.netsuite.com/core/media/media.nl?id=11300678&c=4800298&h=9E-_qg-BSHnOGszkkR0DwwreROV_YEyp8NPsWKJW_n53ikzv&fcts=20230731185657&whence=" alt="Imagem">
            </a>
            

<h4>Basic HTML Structure</h4>
<H3>Head:</H3>
<ul>

<li>Variables</li>
<li>Logo / ABN / Form Number / Form Name</li>
<li>Footer: Company Details / Mini Banner / Page Number / Filename tag</li>
<li>Style</li>
<li>Script</li>
</ul>
<H3>Body:</H3><ul>
<li>Tables with functionalities related to the form code.</li></ul>
</Ul>

<br>

<h2 >HTML Tables on Netsuite:</h2>
<h3>Using HTML tables on Netsuite forms can provide several benefits:</h3>

  <p><strong>Data Organization:</strong> Tables are an excellent way to organize and present tabular data in a structured manner. On Netsuite forms, tables can be used to display information such as lists, reports, or data summaries, making it easier for users to understand and interpret the data.
    <br>
  <strong> Layout Control:</strong> HTML tables allow you to create consistent and well-structured layouts for your forms. You can arrange form elements, fields, and sections within the table cells, ensuring a clean and organized appearance. This consistency enhances the user experience and improves navigation on the form.
  <br>
<strong> Responsive Design:</strong> Tables can be designed to be responsive, meaning they adjust and display properly on various screen sizes and devices. This ensures that your Netsuite forms look good and remain usable, whether users access them from desktops, laptops, tablets, or smartphones.
  <br>
<strong> Alignment and Formatting: </strong>Tables offer precise control over the alignment and formatting of data. You can easily set column widths, adjust cell padding, and apply specific styles to headers, rows, and columns. This level of control helps create a professional and visually appealing form.
  <br>
<strong> Integration with Netsuite Data:</strong> Netsuite forms often contain data retrieved from the Netsuite system. Tables allow you to present this data in a structured manner, making it easier for users to comprehend and work with the information.
  <br>
<strong>Customization:</strong> HTML tables are highly customizable. You can apply CSS styles to tables, rows, cells, and other elements within the table to match the form's branding or tailor the appearance to your organization's preferences.
  <br> 
<strong>Consistency with HTML Standards: </strong>Using HTML tables in Netsuite forms follows the standard practices of web development. This ensures that your forms will be compatible with various browsers and platforms, providing a consistent experience to all users.
  <br>
  <p>However, it's important to use tables judiciously and appropriately. For layout purposes, consider using modern CSS-based layout techniques like Flexbox or Grid, which are more flexible and offer better control over the form's responsiveness and overall design. Tables are best suited for displaying tabular data, where their structured layout is most beneficial.</p>

<br>

<h2 >Suite Answers:</h2>
<p>This tool is very useful, and you can find almost everything you need about Netsuite.</p>
<p>Whether you are a Netsuite user, developer, or administrator, Suite Answers is designed to cater to your needs. It offers a wide range of topics, including tips and tricks, best practices, troubleshooting guides, and frequently asked questions. From basic functionalities to advanced customization, Suite Answers covers almost everything you might need to know about Netsuite.</p>
<p>If you ever encounter challenges while working with Netsuite or wish to explore its features more deeply, Suite Answers is the go-to place to seek assistance and gain a better understanding of the platform.</p>
<p>For more information, you can visit the <a href="https://suiteanswers.custhelp.com/app/home">Suite Answers page</a>.</p>

              



<!-- DIVIDER -->

<h2 id="css">&nbsp;</h2>

  <h2 class="titles">
    CSS Customization</h2>


<p><strong>CSS stands for "Cascading Style Sheets." </strong>It's a set of instructions that tell a website or webpage how it should look and be displayed on your computer or device. CSS helps designers and developers control the colors, fonts, layouts, and other visual aspects of a website, making it attractive and easy to use. Think of it as a styling tool that enhances the appearance of a website and makes it more appealing to users. Without CSS, websites would look plain and less engaging.</p>
<p><strong>In Netsuite, CSS (Cascading Style Sheets) is used to control the presentation and layout of forms. </strong>CSS works by defining rules that specify how the HTML elements within the form should be displayed. These rules determine the font styles, colors, margins, padding, alignment, and other visual aspects of the form elements.</p>
<br>
<p>CSS applications:</p>
<p><strong>Inline Styles: </strong>In some cases, CSS styles can be applied directly to individual form elements using inline styles. This means that the CSS rules are directly embedded within the HTML code of the form. While this method allows for quick and specific styling changes, it can become cumbersome to manage if you have many elements with different styles.
</p>
<p><strong>Style Tags: </strong>For more structured and organized styling, you can use style tags within the form's HTML to define CSS rules. The style tags can be placed in the head section of the form's HTML code. This method allows you to centralize and group CSS rules together, making it easier to maintain and modify the styles across the form.
</p>
<!-- DIVIDER -->


<h2 id="images">&nbsp;</h2>

  <h2 class="titles">
    Inserting Images</h2>

   
        <div id="insertImageInstructions">
            <p>To insert an image on NetSuite, you can follow these steps:</p>
    
            <ul>
                <li>Log in to your NetSuite account: First, access your NetSuite account by entering your login credentials.</li>
    
                <li>Navigate to the "Images" section: Once you are logged in, click on the "Menu" button to open the main menu. From there, go to "Documents" and then select "Files." In the "Files" section, choose "Images."</li>
    
                <li>Upload and organize images: In the "Images" section, you can upload images by clicking on the "Upload" button and selecting the image file from your local computer. You can also create folders to organize your images better.</li>
    
                <li>Save the image: After uploading the image, click on the "Save" button to store it in your NetSuite account.</li>
    
                <li>Using images on forms: Now that the image is saved in the "Images" section, you can use it on various forms within NetSuite. For example, you can use an image as a logo on invoices, sales orders, or any other form by referencing its URL or internal ID in the HTML/CSS code of the form.</li>
            </ul>
    
            <p>Here's a brief explanation of each step:</p>
    
            <ul>
                <li>Logging in: Simply enter your NetSuite login credentials on the NetSuite website to access your account.</li>
    
                <li>Navigating to "Images" section: Once logged in, the "Menu" button will open the main menu, and you can find the "Documents" option. Clicking on it will reveal the "Files" menu, where you can select "Images" to access the section where you manage your images.</li>
    
                <li>Uploading images: In the "Images" section, you can upload images from your local computer by clicking the "Upload" button. This allows you to choose an image file stored on your computer and save it to your NetSuite account.</li>
    
                <li>Organizing images with folders: To keep your images organized, you can create folders in the "Images" section. Group related images into these folders to easily find and manage them in the future.</li>
    
                <li>Saving the image: After selecting and uploading the image file, clicking the "Save" button ensures that the image is stored in your NetSuite account and available for use.</li>
    
                <li>Using images on forms: Once an image is saved in the "Images" section, you can reference it in the HTML/CSS code of your forms. For example, you can set an image as a logo in the header or footer of invoices, sales orders, or any other custom forms within NetSuite.</li>
            </ul>
    
            <p>By following these steps, you can upload and use images in your NetSuite account, making it convenient to include logos, graphics, and other visual elements in your business forms and documents.</p>
        </div>
   

<!-- DIVIDER -->

<h2 id="placeholders">&nbsp;</h2>


  <h2 class="titles">
    Placeholders</h2>


<!DOCTYPE html>
<html>
<head>
    <title>My HTML File</title>
</head>
<body>
    <div id="placeholderExplanation">
        <p>In programming and web development, a placeholder is a special symbol, token, or text used to represent dynamic content or data that will be inserted into a specific location within a document or template. The purpose of using placeholders is to create reusable templates or structures that can be filled with actual data at runtime or during rendering.</p>

        <p>In the context of NetSuite, which is an enterprise resource planning (ERP) software suite, placeholders are used to display dynamic data from records or objects within the application. These placeholders are often represented by variables enclosed in curly braces, such as ${record.trandate} or ${record.salesrep}, as seen in the provided HTML code.</p>

        <p>Here's a brief explanation of how placeholders are used in NetSuite:</p>

        <ul>
            <li>Dynamic Data Display: Placeholders allow you to display data from records and transactions stored in the NetSuite database. For example, ${record.trandate} would represent the transaction date, and ${record.salesrep} would represent the sales representative associated with the transaction.</li>

            <li>Templates: Within NetSuite, placeholders are commonly used in email templates, print templates, advanced PDF templates, and other customized forms. They enable you to create standardized templates with dynamic content, making it easy to generate documents like invoices, sales orders, and reports with accurate data for each specific record.</li>

            <li>Scripting and Customization: Placeholders are often used in SuiteScript, NetSuite's scripting language, to dynamically access and display data. They facilitate the process of customizing records and forms, allowing developers to generate personalized outputs based on specific data conditions.</li>

            <li>Reporting: When building custom reports or dashboards, placeholders can be utilized to dynamically fetch and display data, providing real-time insights and analytics.</li>
        </ul>

        <p>By using placeholders in NetSuite, you can create flexible and dynamic templates that adapt to different data scenarios, making it easier to generate and display accurate information for various records and transactions within your organization.</p>
    </div>
</body>
</html>



<!-- DIVIDER -->

<h2 id="functions">&nbsp;</h2>

  <h2 class="titles">
    Functions</h2>



    
        <div id="explanationDiv">
            <p><strong>Functions:</strong></p>
            <p>In programming, a function is a reusable block of code that performs a specific task or set of tasks. It takes inputs (called parameters or arguments) and can return an output. Functions help break down complex problems into smaller, more manageable pieces, making the code easier to read, understand, and maintain.</p>
    
            <p><strong>How to use functions in NetSuite:</strong></p>
            <p>In NetSuite, functions are used extensively in SuiteScript, the scripting language used for customizing and extending NetSuite's functionalities. You can create custom functions to perform specific actions, manipulate data, or calculate values. Functions can be called from other scripts or event triggers, allowing you to execute the same block of code multiple times throughout your application.</p>
    
            <p>Here's a simple example of a function in SuiteScript that calculates the total price of an item based on its quantity and unit price:</p>
    
            <pre><code>
    function calculateTotalPrice(quantity, unitPrice) {
        return quantity * unitPrice;
    }
            </code></pre>
    
            <p>In this example, we defined a function called <code>calculateTotalPrice</code> that takes two parameters (<code>quantity</code> and <code>unitPrice</code>). It then returns the total price by multiplying the quantity and unit price. You can call this function from other parts of your SuiteScript code to calculate the total price for different items.</p>
    
            <p><strong>Conditional Statements (if/else, if/else if):</strong></p>
            <p>Conditional statements allow a program to make decisions based on certain conditions. They execute different blocks of code depending on whether a condition is true or false. The most common conditional statement is the <code>if</code> statement, which evaluates a condition and executes a code block if the condition is true. The <code>else</code> and <code>else if</code> statements provide additional options for executing code when the initial condition is false or when there are multiple conditions to check.</p>
    
            <p>Here's a simple explanation using a real-life example:</p>
            <p>Imagine you want to buy a coffee, and the cashier tells you the price. You can make a decision based on the price:</p>
            <pre><code>
    if (price <= 5) {
        // Buy the coffee
    } else if (price > 5 && price <= 10) {
        // Think about it
    } else {
        // Skip buying the coffee
    }
            </code></pre>
    
            <p>In NetSuite, you can use conditional statements like <code>if</code>, <code>else</code>, and <code>else if</code> in SuiteScript to control the flow of your program based on specific conditions. This allows you to execute different actions or logic depending on the data or context you are working with.</p>
        
        <p>To see an example of function used on one of our forms, please click this here:<br><br> <a href="#consolidated-forms-functon">Consolidated Forms Functon</a> </p>
        
          </div>
    
    










<!-- END -->






<!-- FOOTER - FINAL - NOTE -->

<div style="width: 400px; padding-top: 200px;">&nbsp;<h4 ><strong>Final Note:</strong><br><p class="font-body"> This manual was made by Founder Marketing Team. Any requests, please call the Founder Marketing Manager or Founder Netsuite Administrator.</p></h4>
</div>


<div style="height: 500px;"></div>
    
    </div>
  



</div>





</body>
</html>
