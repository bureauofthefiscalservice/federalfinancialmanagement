---
published: true
permalink: /data-elements/
layout: article
filename: business-exchange-standards.md
title: Data Elements
---
# Business Exchange Standards Recommendations 
 
The review is grouped by the business exchange process and then by the recommended data elements because of the business exchange analysis.   
 
These business exchanges can be grouped by specific business events.  For example, the same standard can be used for a commercial invoice, travel voucher, or grants invoice.  
 
The new data elements and each business exchange process will have its own GitHub feedback page, which is where you can see the input posted during the public input period.  
 
Thank you to all who provides input on these business exchange standards. 
 
<p>            Note: We are not requesting feedback to the elements previously defined in the existing inventory of FM Standard Business Data Elements, DATA Act Information Model Schema or the Fiscal Service Data Registry as part of this public comment period.</p>
<p><h3 class="mt-0">Proposed Business Exchange Standards</h3></p> 
   <p> 
             When preparing feedback, consider the following:
        </p>
        <p>
            <strong>For the Business Exchange Standards</strong>(the data that is required to be passed from the mission support system to the financial system and vice versa.) 
        </p>
        <ul>
           <li>
                If a data element has a condition that makes it not required, the data element is being proposed as optional.  If the data element is always required in the business exchange, it is proposed as required.   
            </li>
            <li>
                Are the data elements appropriately named?
            </li>
            <li>
                Are the data element definitions accurate?
            </li>
            <li>
            Are we missing any data elements?
            </li>
            <li>
                Is the data element required when the exchange of information is done?
            </li>
    <li>
               Is this list correct and comprehensive for the necessary information to be exchanged for the related business process?
            </li>
        </ul>


<h2>Requisition Business Exchange Standard</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Required Optional</strong>
            </th>
            <th>
                <strong>&nbsp; Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                ActivityIdentifier
            </td>
            <td>
                An activity is a series of events, tasks, or units of work that are linked to perform a specific objective.
            </td>
            <td>
                Optional
            </td> 
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                AgencyIdentifier
            </td>
            <td>
                The Treasury Account Symbol (TAS) component that identifies the department, agency or establishment of the U.S. Government that is responsible for the TAS. Agency Identifier is also used apart from the TAS to identify a major department or independent agency of the Federal government.
            </td>
            <td>
                Required 
            </td> 
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                AllocationTransferAgencyIdentifier
            </td>
            <td>
               The Treasury Account Symbol (TAS) component that identifies the agency receiving funds through an allocation transfer.
            </td>
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                AvailabilityTypeCode
            </td>
            <td>
                The Treasury Account Symbol (TAS) component that identifies no-year accounts (X), clearing/suspense accounts (F), Treasury central summary general ledger accounts (A), and merged-surplus accounts (M).
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                BeginningPeriodOfAvailability
            </td>
            <td> 
             The Treasury Account Symbol (TAS) component that identifies the first year of availability under law that an account may incur new obligations, in annual and multiyear accounts.
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                CostCenterWorkUnitCode
            </td>
            <td>
                A Cost Center is a clearly defined responsibility area where costs are incurred.
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                Description
            </td>
            <td>
                A brief description of the requisition, order or invoice.
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                DocumentApprovalDate     
            </td>
            <td>
                The date which the agreement was approved.            
            </td>
            <td>
                Required
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                DocumentLineAmount             
            </td>
            <td>
                The total price is the quantity x unit price for each itemized line within the requisition, order or invoice.  
            </td>
            <td>
                Required 
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                DocumentLineDescription
            </td>
            <td>
                The description of goods/services associated with each itemized line within the requisition, order or invoice.
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                DocumentLineNumber
            </td>
            <td>
                Identifies the line number on the requisition, order, receipt or invoice for each separate product or service.
            </td>
            <td>
                Optional 
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                DocumentLineQuantity
            </td>
            <td>
                The quantity of goods/services associated with each itemized line within the requisition, order or invoice.
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                DocumentLineUnitofMeasure
            </td>
            <td>
                The means a quantity is accounted for and expressed on each itemized line within the requisition, order or invoice for a good/service. 
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ 
            </td>
        </tr>
        <tr>
            <td>
                DocumentReferenceNumber
            </td>
            <td>
                Details a unique identifying number created by a system for a document, e.g. payment or collection document. 
            </td>
            <td>
                Required
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ 
            </td>
        </tr>
        <tr>
             <td>
                 EndingPeriodOfAvailability
             </td>
             <td>
                 The Treasury Account Symbol (TAS) component that identifies the last year of availability under law that an account may incur new obligations, in annual and multiyear accounts.
             </td>
             <td>
                 Optional
             </td>
             <td>
                 <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
             </td>
        </tr>
        <tr>
            <td>
                FiscalYear 
            </td>
            <td>
                The budget or financial year, as opposed to a calendar year. The U.S. Government's fiscal year runs from October 1 of the prior year through September 30 of the next year. For example, FY 2015 was from October 2014 through September 2015.
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ 
            </td>
        </tr>
        <tr>
            <td>
                InternalOrganizationCode
            </td>
            <td>
                The code that identifies the entity that manages resources below the agency and bureau level, such as an office or a division. 
            </td>
            <td>
                Required
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                MainAccountCode
            </td>
            <td>
                The Treasury Account Symbol (TAS) component that represents the type and purpose of the fund.
            </td>
            <td>
                Required
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                ObjectClass
            </td>
            <td>
                Categories in a classification system that presents obligations by the items or services purchased by the Federal Government
            </td>
            <td>
               Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                ProgramActivityCode
            </td>
            <td>
                The definition for this element appears in Section 200of OMB Circular A-11 issued June 2015; a brief summary from A-11 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.  
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
       </tr>
        <tr>
            <td>
                ProjectIdentifier
            </td>
            <td>
                A planned undertaking of work to be performed or product to be produced having a finite beginning and end. 
            </td>
            <td>
                Optional
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                SubAccountCode
            </td>
            <td>
                This is a component of the TAS. Identifies a Treasury-defined subdivision of the main account. This field cannot be blank. Subaccount 000 indicates the Parent account.
            </td>
            <td>
                Required 
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        <tr>
            <td>
                Unitprice
            </td>
            <td>
                The price of one purchase unit on a requisition, order or invoice. 
            </td>
            <td>
                Optional 
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/21"
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></
            </td>
        </tr>
        </tbody>
    </table>
</div>



<h2>Order Business Exchange Standard</h2> 
<div class="table-responsive"> 
    <table class="table-bordered"> 
        <thead> 
        <tr> 
            <th> 
                <strong>Recommended Data Element Name</strong> 
            </th> 
            <th> 
                <strong>Recommended Definition</strong> 
            </th> 
            <th> 
                <strong>Required Optional</strong> 
            </th> 
            <th> 
                <strong>&nbsp; Provide Feedback</strong> 
            </th> 
        </tr> 
        </thead> 
        <tbody> 
<tr> 
    <td>ActivityIdentifier</td> 
    <td>An activity is a series of events, tasks, or units of work that are linked to perform a specific objective. (data registry, not in the FFM)</td> 
    <td>ActivityIdentifier</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AgencyIdentifier</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the department, agency or establishment of the U.S. Government that is responsible for the TAS.  Agency Identifier is also used apart from the TAS to identify a major department or independent agency of the Federal government.</td> 
    <td>AgencyIdentifier</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AllocationTransferAgencyIdentifier</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the agency receiving funds through an allocation transfer.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AvailabilityTypeCode</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies no-year accounts (X), clearing/suspense accounts (F), Treasury central summary general ledger accounts (A), and merged-surplus accounts (M).</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardeeOrRecipientUniqueIdentifier</td> 
    <td>The unique identification number for an awardee or recipient. Currently the identifier is the 9-digit number assigned by Dun and Bradstreet (D&amp;B) referred to as the DUNS's number.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardPeriodofPerformanceEndDate</td> 
    <td>The current date on which, for the order referred to by the order or invoice being reported, the effort completes or the order is otherwise ended. Administrative actions related to this award may continue to occur after this date. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardPeriodofPerformanceStartDate</td> 
    <td>The date on which, for the order or invoice being reported, effort begins or the award is otherwise effective.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>BeginningPeriodOfAvailability</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the first year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>CostCenterWorkUnitCode</td> 
    <td>A Cost Center is a clearly defined responsibility area where costs are incurred.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Description</td> 
    <td>A brief description of the requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentApprovalDate</td> 
    <td>The date which the requisition, order or invoice was approved.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>FederalActionObligation</td> 
    <td>Amount of Federal government's obligation, de-obligation, or liability, in dollars, for an award transaction.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineAmount</td> 
    <td>The total price is the quantity x unit price for each itemized line within the requisition, order or invoice on a requisition, order, or invoice.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineDescription</td> 
    <td>The description of goods/services associated with each itemized line within the requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineNumber</td> 
    <td>Identifies the line number on the requisition, order or receipt invoice for each separate product or service.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
    <tr> 
    <td>DocumentLineQuantity</td> 
    <td>The quantity of goods/services associated with each itemized line within the requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineUnitofMeasure</td> 
    <td>The means a quantity is accounted for and expressed on each itemized line within the requisition, order or invoice for a good/service.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentReferenceNumber</td> 
    <td>Details a unique identifying number created by a system for a document, e.g. payment or collection document .</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>EndingPeriodOfAvailability</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the last year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>FAIN</td> 
    <td>The Federal Award Identification Number (FAIN) is the unique ID within the Federal agency for each (non-aggregate) financial assistance award.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>FiscalYear</td> 
    <td>The budget or financial year, as opposed to a calendar year. The U.S. Government's fiscal year runs from October 1 of the prior year through September 30 of the next year. For example, FY 2015 was from October 2014 through September 2015.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>InternalOrganizationCode</td> 
    <td>The code that identifies the entity that manages resources below the agency and bureau level, such as an office or a division.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>LegalEntityName</td> 
    <td>The name of the entity.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>MainAccountCode</td> 
    <td>The Treasury Account Symbol (TAS) component that represents the type and purpose of the fund.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ModificationNumber</td> 
    <td>An identifier issued by an agency that uniquely identifies one modification for one contract, agreement, order, etc.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ObjectClass</td> 
    <td>Categories in a classification system that presents obligations by the items or services purchased by the Federal Government</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ParentAwardID</td> 
    <td>The identifier of the procurement award under which the specific award is issued (such as a Federal Supply Schedule). Term currently applies to procurement actions only</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>PIID</td> 
    <td>The unique identifier of the specific award being reported.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>PrecedingReferenceDocumentNumber</td> 
    <td>The number of the preceding DocumentReferenceNumber.  For example for an invoice, the preceding document number would be the order number.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>PrecedingviousReferenceDocumentLineNumber</td> 
    <td>The associated line from the preceding related document.  For example for an order,  the PreviousDocumentLine Number would be the associated line from the related requisition. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ProgramActivityCode</td> 
    <td>The definition for this element appears in <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/assets/a11_current_year/s200.pdf">Section 200 of OMB Circular A-11</a> issued June 2015; a brief summary from A-11 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.  </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ProjectIdentifier</td> 
    <td>A planned undertaking of work to be performed or product to be produced having a finite beginning and end.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ReferenceDocumentLineNumber</td> 
    <td>DocumentLineNumber from the associated preceding requisition, order, or invoice </td> 
    <td>Required</td> 
   <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>SubAccountCode</td> 
    <td>This is a component of the TAS. Identifies a Treasury-defined subdivision of the main account. This field cannot be blank. Subaccount 000 indicates the Parent account.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>TravelPeriodEndDate</td> 
    <td>End date of an event associated with the travel process, such as the travel period or reservation. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>TravelPeriodStartDate</td> 
    <td>Start date of an event associated with the travel process, such as the travel period or reservation. </td> 
   <td>Optional</td> 
   <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
 </tr> 
  <tr> 
    <td>Unitprice</td> 
    <td>The price of one purchase unit on a requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>URI</td> 
    <td>Unique Record Identifier. An agency defined identifier that (when provided) is unique for every reported action.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/23">Provide Feedback</a></td> 
  </tr> 
       </tbody> 
    </table> 
</div> 



<h2>Invoice Business Exchange Standard</h2> 
<div class="table-responsive"> 
    <table class="table-bordered"> 
        <thead> 
        <tr> 
            <th> 
                <strong>Recommended Data Element Name</strong> 
            </th> 
            <th> 
                <strong>Recommended Definition</strong> 
            </th> 
            <th> 
                <strong>Required Optional</strong> 
            </th> 
            <th> 
                <strong>&nbsp; Provide Feedback</strong> 
            </th> 
        </tr> 
        </thead> 
        <tbody> 
<tr> 
    <td>ActivityIdentifier</td> 
    <td>An activity is a series of events, tasks, or units of work that are linked to perform a specific objective. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AgencyIdentifier</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the department, agency or establishment of the U.S. Government that is responsible for the TAS.  Agency Identifier is also used apart from the TAS to identify a major department or independent agency of the Federal government.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AllocationTransferAgencyIdentifier</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the agency receiving funds through an allocation transfer.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AvailabilityTypeCode</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies no-year accounts (X), clearing/suspense accounts (F), Treasury central summary general ledger accounts (A), and merged-surplus accounts (M).</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardeeOrRecipientUniqueIdentifier</td> 
    <td>The unique identification number for an awardee or recipient. Currently the identifier is the 9-digit number assigned by Dun and Bradstreet (D&amp;B) referred to as the DUNS number.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardPeriodofPerformanceEndDate</td> 
    <td>The current date on which, for the order referred to by the order or invoice being reported, the effort completes or the order is otherwise ended. Administrative actions related to this award may continue to occur after this date. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardPeriodofPerformanceStartDate</td> 
    <td>The date on which, for the order or invoice being reported, effort begins or the award is otherwise effective.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>BeginningPeriodOfAvailability</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the first year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>CostCenterWorkUnitCode</td> 
    <td>A Cost Center is a clearly defined responsibility area where costs are incurred.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Description</td> 
    <td>A brief description of the requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentApprovalDate</td> 
    <td>The date which the requisition, order or invoice was approved.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineAmount</td> 
    <td>The total price is the quantity x unit price for each itemized line within the requisition, order or invoice on a requisition, order, or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineDescription</td> 
    <td>The description of goods/services associated with each itemized line within the requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineNumber</td> 
    <td>Identifies the line number on the requisition, order or receipt invoice for each separate product or service.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineQuantity</td> 
    <td>The quantity of goods/services associated with each itemized line within the requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentLineUnitofMeasure</td> 
    <td>The means a quantity is accounted for and expressed on each itemized line within the requisition, order or invoice for a good/service.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>DocumentReferenceNumber</td> 
    <td>Details a unique identifying number created by a system for a document, e.g. payment or collection document .</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>EndingPeriodOfAvailability</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the last year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>FAIN</td> 
    <td>The Federal Award Identification Number (FAIN) is the unique ID within the Federal agency for each (non-aggregate) financial assistance award.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Fiscal Year</td> 
    <td>The budget or financial year, as opposed to a calendar year. The U.S. Government's fiscal year runs from October 1 of the prior year through September 30 of the next year. For example, FY 2015 was from October 2014 through September 2015.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Internal Organization Code</td> 
    <td>The code that identifies the entity that manages resources below the agency and bureau level, such as an office or a division.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>InvoiceQuantity</td> 
    <td>Identifies the quantity invoiced as of the date of the order.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Legal Entity Name</td> 
    <td>The name of the entity.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>MainAccountCode</td> 
    <td>The Treasury Account Symbol (TAS) component that represents the type and purpose of the fund.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ModificationNumber</td> 
    <td>An identifier issued by an agency that uniquely identifies one modification for one contract, agreement, order, etc.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ObjectClass</td> 
    <td>Categories in a classification system that presents obligations by the items or services purchased by the Federal Government</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ParentAwardID</td> 
    <td>The identifier of the procurement award under which the specific award is issued (such as a Federal Supply Schedule). Term currently applies to procurement actions only</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>PIID</td> 
    <td>The unique identifier of the specific award being reported.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>PrecedingReferenceDocumentLineNumber</td> 
    <td>The associated line from the preceding related document.  For example for an order,  the PreviousDocumentLine Number would be the associated line from the related requisition. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>PrecedingReferenceDocumentNumber</td> 
    <td>The number of the preceding DocumentReferenceNumber.  For example for an invoice, the preceding document number would be the order number.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ProgramActivityCode </td> 
    <td>The definition for this element appears in <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/assets/a11_current_year/s200.pdf">Section 200 of OMB Circular A-11</a> issued June 2015; a brief summary from A-11 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.  </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Project Identifier</td> 
    <td>A planned undertaking of work to be performed or product to be produced having a finite beginning and end.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>SubAccountCode</td> 
    <td>This is a component of the TAS. Identifies a Treasury-defined subdivision of the main account. This field cannot be blank. Subaccount 000 indicates the Parent account.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>TravelPeriodEndDate</td> 
    <td>End date of an event associated with the travel process, such as the travel period or reservation. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>TravelPeriodStartDate</td> 
    <td>Start date of an event associated with the travel process, such as the travel period or reservation. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Unitprice</td> 
    <td>The price of one purchase unit on a requisition, order or invoice.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>URI</td> 
    <td>Unique Record Identifier. An agency defined identifier that (when provided) is unique for every reported action.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/24">Provide Feedback</a></td> 
  </tr> 
</tbody> 
    </table> 
</div> 



<h2>Receipt of Goods and Services Business Exchange Standard</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Required Optional</strong>
            </th>
            <th>
                <strong>&nbsp; Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
<tr>
    <td>AllocationTransferAgencyIdentifier</td>
    <td>The Treasury Account Symbol (TAS) component that identifies the agency receiving funds through an allocation transfer.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>AgencyIdentifier</td>
    <td>The Treasury Account Symbol (TAS) component that identifies the department, agency or establishment of the U.S. Government that is responsible for the TAS. Agency Identifier is also used apart from the TAS to identify a major department or independent agency of the Federal government.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>MainAccountCode</td>
    <td>The Treasury Account Symbol (TAS) component that represents the type and purpose of the fund.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>AvailabilityTypeCode</td>
    <td>The Treasury Account Symbol (TAS) component that identifies no-year accounts (X), clearing/suspense accounts (F), Treasury central summary general ledger accounts (A), and merged-surplus accounts (M).</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>BeginningPeriodOfAvailability</td>
    <td>The Treasury Account Symbol (TAS) component that identifies the first year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>EndingPeriodOfAvailability</td>
    <td>The Treasury Account Symbol (TAS) component that identifies the last year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>SubAccountCode</td>
    <td>This is a component of the TAS. Identifies a Treasury-defined subdivision of the main account. This field cannot be blank. Subaccount 000 indicates the Parent account.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>FiscalYear</td>
    <td>The budget or financial year, as opposed to a calendar year. The U.S. Government's fiscal year runs from October 1 of the prior year through September 30 of the next year. For example, FY 2015 was from October 2014 through September 2015.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>InternalOrganizationCode</td>
    <td>The code that identifies the entity that manages resources below the agency and bureau level, such as an office or a division.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>ProgramActivityCode</td>
    <td>The definition for this element appears in <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/assets/a11_current_year/s200.pdf">Section 200 of OMB Circular A-11</a> issued June 2015; a summary from A-11 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>CostCenterWorkUnitCode</td>
    <td>A Cost Center is a clearly defined responsibility area where costs are incurred.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>ActivityIdentifier</td>
    <td>An activity is a series of events, tasks, or units of work that are linked to perform a specific objective. (data registry, not in the FFM)</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>ProjectIdentifier</td>
    <td>A planned undertaking of work to be performed or product to be produced having a finite beginning and end.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>ObjectClass</td>
    <td>Categories in a classification system that presents obligations by the items or services purchased by the Federal Government</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>GoodorServiceAcceptedDate</td>
    <td>Identifies the date the goods and services were accepted.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>PIID</td>
    <td>The unique identifier of the specific award being reported.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>ParentAwardID</td>
    <td>The identifier of the procurement award under which the specific award is issued (such as a Federal Supply Schedule). Term currently applies to procurement actions only</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>URI</td>
    <td>Unique Record Identifier. An agency defined identifier that (when provided) is unique for every reported action.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>FAIN</td>
    <td>The Federal Award Identification Number (FAIN) is the unique ID within the Federal agency for each (non-aggregate) financial assistance award.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>GoodorserviceAmountReceived</td>
    <td>Currency amount from the receipt for goods or services.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>Comments</td>
    <td>Note(s) explaining or illustrating the meaning of a record or transaction.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>DeliveryDate</td>
    <td>The date on which the item/service is received and signed for delivery as described in the Prompt Payment Act</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>DocumentReferenceNumber</td>
    <td>Details a unique identifying number created by a system for a document, e.g. payment or collection document .</td>
    <td>Derived</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>GoodorServiceServiceQuantityReceived</td>
    <td>Quantity of goods or services received.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>GoodsorservicesRecieptDate</td>
    <td>Receipt date for the goods or services during the receipt of goods process.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>DocumentReferenceNumber</td>
    <td>Details a unique identifying number created by a system for a document, e.g. payment or collection document.</td>
    <td>Required</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>PrecedingReferenceDocumentLineNumber</td>
    <td>The associated line from the preceding related document. For example, for an order, the PreviousDocumentLine Number would be the associated line from the related requisition.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>PrecedingReferenceDocumentNumber</td>
    <td>The number of the preceding DocumentReferenceNumber. For example, for an invoice, the preceding document number would be the order number.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
  <tr>
    <td>DocumentLineNumber</td>
    <td>Identifies the line number on the requisition, order or receipt invoice for each separate product or service.</td>
    <td>Optional</td>
    <td>Provide Feedback</td>
  </tr>
        </tbody>
    </table>
</div>







<h2>020 - Acquire-to-Dispose</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>&nbsp; Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                AssetRecognitionDate
            </td>
            <td>
                The date that the acquiring entity receives the title for Property, Plants, and Equipment (PP&amp;E) or
                the
                date that the PP&amp;E is delivered to the entity or to an agent of the entity. Constructed PP&amp;E is
                recorded as construction work in progress until it is placed in service, at which time the balance shall
                be
                transferred to general PP&amp;E.
            </td>
            <td>
                SFFAS 6: Accounting for Property, Plant, and Equipment;
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                AssetCategoryName
            </td>
            <td>
                Name of a common grouping of assets based on asset characteristics. The categories include Property,
                Plant,
                and Equipment (PP&amp;E); additional categorization for major classes of PP&amp;E (e.g. buildings,
                equipment, land, etc.); additional categorization for physical custody of PP&amp;E (e.g. contractor-held
                or
                government-held); inventory; heritage assets; stewardship land; and other assets.
            </td>
            <td>
                Definition (compiled from)<br> - OMB Circular A-136 Section II.4.9.10 (Note 10, General Property, Plant
                and
                Equipment, Net)<br> - FASAB Standards SFFAS 1, 2, 3, 6, 8, 10, 11, 18, 19, 29, 38
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                AssetValueAmount
            </td>
            <td>
                A current value of an asset as determined by the Property Management Process using appropriate FASAB
                guidance.
            </td>
            <td>
                FASAB Standards SFFAS 1, 2, 3, 6, 8, 10, 11, 18, 19, 29, 38
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                AssetCategoryQuantity
            </td>
            <td>
                A number of asset units as determined by the property management process using appropriate FASAB
                guidance.
            </td>
            <td>
                FASAB Standards SFFAS 1, 10, 11, 18, 19, 2, 29
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                AssetValueAdjustmentAmount
            </td>
            <td>
                A modification to the current value of an asset based on value change (e.g., impact on current value of
                depreciation, impairment, allowance for uncollectable amounts, subsidy allowance).
            </td>
            <td>
                FASAB Standards SFFAS 1, 2, 3, 6, 8, 10, 11, 18, 19, 29, 38
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                EntityNonEntityIndicator
            </td>
            <td>
                Indicates that a reporting entity has authority to use an asset in its operations or if the asset is not
                available to the entity.
            </td>
            <td>
                OMB Circular A-136, II.4.3.3 Assets
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>030 - Request-to-Procure</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                Pre-obligationApportionmentAmount
            </td>
            <td>
                An amount applied to budgetary resources on a pre-obligation basis anticipating an obligation (e.g., a
                request or an order such as a Request for Proposal). OMB usually apportions the budgetary resources of a
                Treasury Account Fund Symbol (TAFS) with respect to the authority to incur new obligations.
            </td>
            <td>
                OMB Circular No. A-11, Part 4, Instructions on Budget Execution, Section 120.64
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/9"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>040 - Procure-to-Pay</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                GoodsAndServicesAcceptanceDate
            </td>
            <td>
                Date that goods and/or services are inspected and accepted by the agency.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                PaymentTermsText
            </td>
            <td>
                Text from a contract or invoice that specifies the time period for a payment and the discount, if
                applicable.
            </td>
            <td>
                5 CFR 1315, Prompt Payment: 1315.7 Discounts
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                CurrentValueOfFundsRate
            </td>
            <td>
                A percentage rate based on the current value of funds to the Department of Treasury. It is used for
                Federal
                debt collection, cash discounts, and rebate evaluation.
            </td>
            <td>
                5 CFR 1315, Prompt Payment: 1315.7 Discounts
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                DeliveryDate
            </td>
            <td>
                The date on which the item/service is received and signed for delivery as described in the Prompt
                Payment
                Act.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties,1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                InvoiceReceiptDate
            </td>
            <td>
                The date on which the proper payment invoice is received by the designated agency office as described in
                the
                Prompt Payment Act.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.4 Prompt Payment Standards and
                Required
                Notices to Vendors.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                AdditionalPenaltyPaymentAmount
            </td>
            <td>
                Amount of additional penalties owed to the vendor under the Prompt Payment Act if the late payment
                interest
                was not paid by the due date and the vendor submits a written demand for the additional penalty.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                LateInterestPenaltyPaymentAmount
            </td>
            <td>
                The interest amount owed to the vendor under the Prompt Payment Act for late payments.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                AcceleratedPaymentIndicator
            </td>
            <td>
                Indicates that a payment may be made prior to the due date as defined by the accelerated payment methods
                under the Prompt Payment Act.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                OfferedDiscountRate
            </td>
            <td>
                The discount rate offered by the vendor for early invoice payment under the Prompt Payment Act.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                DiscountDate
            </td>
            <td>
                The date by which an early payment must be made in order to receive a specified payment reduction, or a
                discount, under the Prompt Payment Act. The decision to take the discount should be made based on the
                best
                interest of the government, as determined by Prompt Payment guidelines.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                DiscountTakenAmount
            </td>
            <td>
                The amount of the invoice payment reduction offered by the vendor for early payment that was taken in
                disbursement made to the vendor.
            </td>
            <td>
                Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
                payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
                Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>050 - Bill-to-Collect</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                DebtStatusName
            </td>
            <td>
                A name for a classification of debt as defined in the Treasury Report on Receivables and Debt Collection
                Activities. Examples include but are not limited to debt in bankruptcy, in forbearance or in formal
                appeals,
                in foreclosure, at a private collection agency, in litigation, in the process of internal offset, in
                wage
                garnishment, at Treasury for cross-servicing or offset, and collected at the agency.
            </td>
            <td>
                TFM Volume I, Part 2, Chapter 4100, Section 4120, Reporting Requirements, and the Instructional Workbook
                for
                Preparing the Treasury Report on Receivables and Debt Collection Activities, Part I, Status of
                Receivables,
                and Part II, Debt Management Tool and Technique Performance Data referenced therein.
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/7"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                TreasuryReportOnReceivablesDebtCategoryName
            </td>
            <td>
                The name of a classification of receivable debt based on the type of activity receiving the debt and
                reported on the Treasury Report on Receivables. This includes Commercial, Consumer, Foreign sovereign
                government, and State and Local Government categories.
            </td>
            <td>
                TFM Volume I, Part 2, Chapter 4100, Section 4120, Reporting Requirements, and the Instructional Workbook
                for
                Preparing the Treasury Report on Receivables and Debt Collection Activities, Part I, Status of
                Receivables,
                and Part II, Debt Management Tool and Technique Performance Data referenced therein.
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/7"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                ReceivableTransactionAdjustmentAmount
            </td>
            <td>
                An amount applied to a receivable to increase or reduce the amount that the debtor owes based on a
                change in
                position between issuance of the original invoice and creation of the receivable (e.g., from the
                application
                of a credit memo or an offer in compromise).
            </td>
            <td>
                OMB Circular No. A-129, Policies for Federal Credit Programs and Non-Tax Receivables, Appendix A, Part
                IV,
                Managing the Federal Government&rsquo;s Receivables;
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/7"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>060 - Record-to-Report</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                UniqueInvestmentIdentifier
            </td>
            <td>
                A persistent numeric code applied to an Investment that allows the identification and tracking of an
                Investment across multiple fiscal years (FYs) of an Agency&rsquo;s information technology (IT)
                portfolio.
            </td>
            <td>
                Definition (compiled from)
                - FY2019 IT Budget -- Capital Planning Guidance, APPENDIX C. DEFINITIONS (source for definition)
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/6"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        <tr>
            <td>
                AccrualAdjustmentAmount
            </td>
            <td>
                For accrual-basis accounting, the amount applied to an accrual accumulated in a prior period in order to
                provide more accurate and timely information for planning and control of operations and understanding of
                net
                position and cost of operations.
            </td>
            <td>
                SFFAS 7: Accounting for Revenue and Other Financing Sources and Concepts for Reconciling Budgetary and
                Financial Accounting.
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/6"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>070 - Agree-to-Reimburse (Reimbursable Management)</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/5"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>080 - Apply-to-Perform (Grants Management)</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/4"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>090 - Hire-to-Retire</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/3"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>100 - Book-to-Reimburse (Travel)</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/2"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
<h2>110 - Apply-to-Repay</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong>Recommended Data Element Name</strong>
            </th>
            <th>
                <strong>Recommended Definition</strong>
            </th>
            <th>
                <strong>Authoritative Reference</strong>
            </th>
            <th>
                <strong>Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                N/A
            </td>
            <td>
                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/1"
                   target="_blank">Feedback Period is Closed</a>
            </td>
        </tr>
        </tbody>
    </table>
</div>
