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


<h2>Entity Information Business Exchange Standard</h2>
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
  <td>3rdPartyInformationAddressCountryCode</td>
  <td>Second line of the 3rd party involved in the transaction's address</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationAddressLine1</td>
  <td>First line of the 3rd party involved in the transaction's address</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationAddressLine2</td>
  <td>Code for the country in which the 3rd party involved in the transaction uses, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, minus the codes listed for those territories and possessions of the United States already identified as estates'??</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationCityName</td>
  <td>Name of the city in 3rd party involved in the transaction is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactCountryCode</td>
  <td>Code for the country in which the 3rd party involved in the transaction is located, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, minus the codes listed for those territories and possessions of the United States already identified as ?states.?</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactE-MailAddress</td>
  <td>?Internet e-mail address for 3rd party involved in the transaction</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactFirstName</td>
  <td>The last for the 3rd party involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactFirstName</td>
  <td>The first name for the 3rd party involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactPartyType.</td>
  <td>The identification number for the party involved in the transaction.. The name of the party involved in the transaction. The party type, i.e., individual, business or government.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactTelephoneNumber</td>
  <td>for the 3rd party involved in the transaction. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationStateCode</td>
  <td>United States Postal Service (USPS) two-letter abbreviation for the state or territory in which the 3rd party involved in the transaction address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3rdPartyInformationZip5</td>
  <td>USPS five digit zoning code associated with the 3rd party involved in the transaction address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>3thPartyInformationZIP+4</td>
  <td>USPS four digit extension code associated with the postal address 3rd party involved in the transaction address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>AwardeeOrRecipientUniqueIdentifier</td>
  <td>The Data Universal Numbering System (DUNS) Number is a unique nine-character identification number provided by the commercial company Dun and Bradstreet (D&amp;B).</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankAccountNumber1</td>
  <td>The account number of one financial institution involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankAccountNumber2</td>
  <td>The account number for a second financial institution involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankAccountNumber3</td>
  <td>The account number of a third financial institution involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankAccountRoutingNumber#1</td>
  <td>A financial institution's nine-digit routing transit number assigned by the American Banking Association (ABA).The number must be the Electronic Funds Transfer (ETF) Routing number, not the Wire Transfer number.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankAccountRoutingNumber#2</td>
  <td>A financial institution's nine-digit routing transit number assigned by the American Banking Association (ABA).The number must be the Electronic Funds Transfer (ETF) Routing number, not the Wire Transfer number.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankAccountRoutingNumber#3</td>
  <td>A financial institution's nine-digit routing transit number assigned by the American Banking Association (ABA).The number must be the Electronic Funds Transfer (ETF) Routing number, not the Wire Transfer number.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankAccountType</td>
  <td>The code that identifies the type of account associated with the transaction, such as checking or savings.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>BankName</td>
  <td>The name of the financial institution.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>CommentField</td>
  <td>Note(s) explaining or illustrating the meaning of a record or transaction.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>CountryofIncorporation</td>
  <td>The country code the entity has residence or incorporation. This follows the ISO3166 3-digit format.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>EFTWaiver</td>
  <td>The EFT Waiver Flag indicates whether banking information is required for the entity. Per 31 ? CFR 208.1, all Federal payments made by an agency requires payments to be made by electronic funds transfer, except as specified in 31 ? 208.4, this part requires payments, other than payments made under the Internal Revenue Code of 1986.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>EntityDateofLastUpdate</td>
  <td>The date the an entity's information was last updated.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>EntityIdentificationNumber</td>
  <td>This is a number that uniquely identifies the entity and is associated with the legal entity address. Some examples of this identification number is the Social Security Number (SSN), Tax Identification Number (TIN), or unique number created by the agency to protect personally identifiable information (PII). This entity ID does not Include the DUNS # and UEI.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>EntityType</td>
  <td>Specifies the legal form of the business or entity (e.g., Sole Proprietorship, Partnership or Limited Liability Partnership, Corporate Entity (Not Tax Exempt), etc.).</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>InternalRevenueService(IRS)1099indicator</td>
  <td>Determines if the entity is IRS Form 1099 eligible. The Form 1099 is used to report payments to independent contractors, rental property income, income from interest and dividends, sales proceeds, and other miscellaneous income.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityAddressLine1</td>
  <td>First line of the entity's address.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityAddressLine2</td>
  <td>Second line of the entity's address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityCityName</td>
  <td>Name of the city in which the entity's address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityForeignCityName</td>
  <td>For foreign entities only: name of the city in which the entity's address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityForeignPostalCode</td>
  <td>For foreign entities only: foreign postal code in which the entity's address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityForeignProvinceName</td>
  <td>For foreign entities only: name of the state or province in which the entity's legal business address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityName</td>
  <td>The name of the entity associated with the Entity Identification Number, DUNS # or UEI.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityStateCode</td>
  <td>United States Postal Service (USPS) two-letter abbreviation for the state or territory in which the entity's address is located. Identify States, the District of Columbia, territories (i.e., American Samoa, Guam, Northern Mariana Islands, Puerto Rico, U.S. Virgin Islands) and associated states (i.e., Republic of the Marshall Islands, the Federated States of Micronesia, and Palau) by their USPS two-letter abbreviation.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityZIP5</td>
  <td>USPS five digit zoning code associated with the postal entity's address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>LegalEntityZIPLast4</td>
  <td>USPS four digit extension code associated with the entity's address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressCityName</td>
  <td>The name of the city of the postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressCountryCode</td>
  <td>Code for the country in which the entity receives letters or packages, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from the place where they work or live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressForeignCityName</td>
  <td>For foreign entities only: name of the city in which the entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressForeignPostalCode</td>
  <td>For foreign entities only: foreign postal code in which the entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressForeignProvinceName</td>
  <td>For foreign entities only: name of the state or province in which the which the entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressLine1</td>
  <td>First line of the postal address?at which an entity?receives?letters?or?packages, which can be different from the?place?where they?work?or?live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressLine2</td>
  <td>First line of the postal address?at which an entity?receives?letters?or?packages, which can be different from the?place?where they?work?or?live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressState</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressZipCode5</td>
  <td>USPS five digit zoning code associated with postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>MailingAddressZipLast4</td>
  <td>USPS four digit extension code associated with the postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactFirstName1</td>
  <td>The first name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactFirstName2</td>
  <td>The first name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactFirstName3</td>
  <td>The first name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactLastName1</td>
  <td>The last name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactLastName2</td>
  <td>The Last name of the party involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactLastName3</td>
  <td>The last name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactTelephoneNumber1</td>
  <td>U.S. phone number for a person serving as the coordinator or focal point of information concerning an activity or program. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactTelephoneNumber2</td>
  <td>U.S. phone number for a person serving as the coordinator or focal point of information concerning an activity or program. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactTelephoneNumber3</td>
  <td>U.S. phone number for a person serving as the coordinator or focal point of information concerning an activity or program. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactE-MailAddress1</td>
  <td>?Internet e-mail address for a person or a department serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactE-MailAddress2</td>
  <td>?Internet e-mail address for a person or a department serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PointofContactE-MailAddress3</td>
  <td>?Internet e-mail address for a person or a department serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>PromptPayIndicator</td>
  <td>When entity's are established, they are assigned an indicator that designates whether they are eligible to receive Prompt Payment interest.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressCity(1)</td>
  <td>Name of the city of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressCity(2)</td>
  <td>Name of the city of the postal address that entity uses, can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressCity(3)</td>
  <td>Name of the city of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressCountryCode(1)</td>
  <td>Code for the country in which the entity to receive payments and invoices by mail, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressCountryCode(2)</td>
  <td>Code for the country in which the entity to receive payments and invoices by mail, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressCountryCode(3)</td>
  <td>Code for the country in which the entity to receive payments and invoices by mail, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignCityName (1)</td>
  <td>For foreign entities only: name of the city in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignCityName (2)</td>
  <td>For foreign entities only: name of the city in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignCityName (3)</td>
  <td>For foreign entities only: name of the city in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (1)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (1)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (2)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (3)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignProvinceName (1)</td>
  <td>For foreign entities only: name of the state or province in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignProvinceName (2)</td>
  <td>For foreign entities only: name of the state or province in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignProvinceName (3)</td>
  <td>For foreign entities only: name of the state or province in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressLine1(1)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressLine1(2)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressLine1(3)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressLine2(1)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressLine2(2)</td>
  <td>The second line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressLine2(3)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressStateCode(1)</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressStateCode(2)</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressStateCode(3)</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressZip5(1)</td>
  <td>USPS five digit zoning code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressZip5(2)</td>
  <td>USPS five digit zoning code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressZip5(3)</td>
  <td>USPS five digit zoning code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressZipLast4(1)</td>
  <td>USPS four digit extension code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>RemittanceAddressZipLast4(2)</td>
  <td>USPS four digit extension code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>StateofIncorporation</td>
  <td>The state code the entity has residence or incorporation. This element is required if you selected the United States for the Country of Incorporation.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>UEI</td>
  <td>A Unique Entity Identifier (UEI) is a unique number assigned to all entities (public and private companies, individuals, institutions, or organizations) who register to do business with the federal government.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>VendorPaymentMethod</td>
  <td>List of payment methods which may be used in automatic payment transactions with this customer/vendor if you do not specify a payment method in the item to be paid.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
 <tr>
  <td>W2Indicator</td>
  <td>This indicator is used to classify the different types of withholding tax. Form W-2 is filed by employers to report wages, tips, and other compensation paid to employees as well as FICA and withheld income taxes.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a></ </td>
 </tr>
        </tr>
        </tbody>
    </table>
</div>


<h2>Automated Journal Entry Business Exchange Standard</h2> 
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
    <td>3 Agency Defined Fields</td> 
    <td>A unique classification element needed by the agency to classify financial transactions for purposes other than those defined else-where.</td> 
    <td>Optional</th> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  <tr> 
    <td>ActivityIdentifier</td> 
    <td>An activity is a series of events, tasks, or units of work that are linked to perform a specific objective. </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AgencyIdentifier</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the department, agency or establishment of the U.S. Government that is responsible for the TAS.  Agency Identifier is also used apart from the TAS to identify a major department or independent agency of the Federal government.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AllocationTransferAgencyIdentifier</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the agency receiving funds through an allocation transfer.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>Amount</td> 
    <td>The dollar amount field can be up to 21 numerical characters with no decimals. Last two places are assumed decimal.</td> 
    <td>Required </td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AvailabilityTypeCode</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies no-year accounts (X), clearing/suspense accounts (F), Treasury central summary general ledger accounts (A), and merged-surplus accounts (M).</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardeeOrRecipientUniqueIdentifier</td> 
    <td>The unique identification number for an awardee or recipient. Currently the identifier is the 9-digit number assigned by Dun and Bradstreet (D&amp;B) referred to as the DUNS? number.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>BeginningPeriodOfAvailability</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the first year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>CostCenterWorkUnitCode</td> 
    <td>A Cost Center is a clearly defined responsibility area where costs are incurred.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>EndingPeriodOfAvailability</td> 
    <td>The Treasury Account Symbol (TAS) component that identifies the last year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
   <td>FiscalYear</td> 
    <td>The budget or financial year, as opposed to a calendar year. The U.S. Government's fiscal year runs from October 1 of the prior year through September 30 of the next year. For example, FY 2015 was from October 2014 through September 2015.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
   <tr> 
    <td>InternalOrganization</td> 
    <td>The code that identifies the entity that manages resources below the agency and bureau level, such as an office or a division.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>MainAccountCode</td> 
    <td>The Treasury Account Symbol (TAS) component that represents the type and purpose of the fund.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ObjectClass</td> 
    <td>Categories in a classification system that presents obligations by the items or  services purchased by the FederalGovernment.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ParentAwardID</td> 
    <td>The identifier of the procurement award under which the specific award is issued (such as a Federal Supply Schedule). Term currently applies to procurement actions only</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td>
  </tr> 
  <tr> 
    <td>PIID</td> 
    <td>The unique identifier of the specific award being reported.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>URI</td> 
    <td>Unique Record Identifier. An agency defined identifier that (when provided) is unique for every reported action.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>FAIN</td> 
    <td>The Federal Award Identification Number (FAIN) is the unique ID within the Federal agency for each (non-aggregate) financial assistance award.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>UEI</td> 
    <td>A Unique Entity Identifier (UEI) is a unique number assigned to all entities (public and private companies, individuals, institutions, or organizations) who register to do business with the federal government.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>EntityIdentificationNumber</td> 
    <td>This is a number that uniquely identifies the entity and is associated with the legal entity address.  Some examples of this identification number is the Social Security Number (SSN), Tax Identification Number (TIN), or unique number created by the agency to protect personally identifiable information (PII).  This entity ID does not Include the DUNS # and UEI.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>AwardeeOrRecipientUniqueIdentifier</td> 
    <td>The unique identification number for an awardee or recipient. Currently the identifier is the 9-digit number assigned by Dun and Bradstreet (D&amp;B) referred to as the DUNS? number.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ProgramActivityCode</td> 
    <td>The definition for this element appears in <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/assets/a11_current_year/s200.pdf">Section 200 of OMB Circular A-11</a>
issued June 2015; a brief summary from A-11 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.  </td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ProjectIdentifier</td> 
    <td>A planned undertaking of work to be performed or product to be produced having a finite beginning and end.</td> 
    <td>Optional</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>ReportingPeriod</td> 
    <td>Designates the month for which the data is being submitted. This is  a 2 digit number that starts with 01 for October and goes through 12 for September.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>SubAccountCode</td> 
    <td>This is a component of the TAS. Identifies a Treasury-defined subdivision of the main account. This field cannot be blank. Subaccount 000 indicates the Parent account.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>USSGL_AccountNumber</td> 
    <td>A six-digit number used to identify a specific U.S. Standard General Ledger account.  The USSGL account must be in the USSGL chart of accounts.</td> 
    <td>Required</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
  </tr> 
  <tr> 
    <td>VoucherDate</td> 
    <td>The date that a depositary or agent uses for Fiscal Service reconciliation.</td> 
    <td>Derived</td> 
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/26">Provide Feedback</a></td> 
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
