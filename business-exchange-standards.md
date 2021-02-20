---
published: true
permalink: /data-elements/
layout: article
filename: business-exchange-standards.md
title: Business Exchanges
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a> 
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
                   target="_blank" rel=“noopener noreferrer”>Provide Feedback</a>
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
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>AgencyIdentifier</td>
    <td>The Treasury Account Symbol (TAS) component that identifies the department, agency or establishment of the U.S. Government that is responsible for the TAS.  Agency Identifier is also used apart from the TAS to identify a major department or independent agency of the Federal government.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MainAccountCode</td>
    <td>The Treasury Account Symbol (TAS) component that represents the type and purpose of the fund.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>AvailabilityTypeCode</td>
    <td>The Treasury Account Symbol (TAS) component that identifies no-year accounts (X), clearing/suspense accounts (F), Treasury central summary general ledger accounts (A), and merged-surplus accounts (M).</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>BeginningPeriodOfAvailability</td>
    <td>The Treasury Account Symbol (TAS) component that identifies the first year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>EndingPeriodOfAvailability</td>
    <td>The Treasury Account Symbol (TAS) component that identifies the last year of availability under law that an account may incur new obligations, in annual and multiyear accounts.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>SubAccountCode</td>
    <td>This is a component of the TAS. Identifies a Treasury-defined subdivision of the main account. This field cannot be blank. Subaccount 000 indicates the Parent account.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>FiscalYear</td>
    <td>The budget or financial year, as opposed to a calendar year. The U.S. Government's fiscal year runs from October 1 of the prior year through September 30 of the next year. For example, FY 2015 was from October 2014 through September 2015.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>InternalOrganizationCode</td>
    <td>The code that identifies the entity that manages resources below the agency and bureau level, such as an office or a division.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ProgramActivityCode</td>
    <td>The definition for this element appears in <a href="https://obamawhitehouse.archives.gov/sites/default/files/omb/assets/a11_current_year/s200.pdf">Section 200 of OMB Circular A-11</a> issued June 2015; a brief summary from A-11 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.  </td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>CostCenterWorkUnitCode</td>
    <td>A Cost Center is a clearly defined responsibility area where costs are incurred.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ActivityIdentifier</td>
    <td>An activity is a series of events, tasks, or units of work that are linked to perform a specific objective. (data registry, not in the FFM)</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ProjectIdentifier</td>
    <td>A planned undertaking of work to be performed or product to be produced having a finite beginning and end.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ObjectClass</td>
    <td>Categories in a classification system that presents obligations by the items or services purchased by the Federal Government</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodorServiceAcceptedDate</td>
    <td>Identifies the date the goods and services were accepted.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PIID</td>
    <td>The unique identifier of the specific award being reported.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ParentAwardID</td>
    <td>The identifier of the procurement award under which the specific award is issued (such as a Federal Supply Schedule). Term currently applies to procurement actions only</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>URI</td>
    <td>Unique Record Identifier. An agency defined identifier that (when provided) is unique for every reported action.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>FAIN</td>
    <td>The Federal Award Identification Number (FAIN) is the unique ID within the Federal agency for each (non-aggregate) financial assistance award.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodorserviceAmountReceived</td>
    <td>Currency amount from the receipt for goods or services.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>Comments</td>
    <td>Note(s) explaining or illustrating the meaning of a record or transaction.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DeliveryDate</td>
    <td>The date on which the item/service is received and signed for delivery as described in the Prompt Payment Act</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentReferenceNumber</td>
    <td>Details a unique identifying number created by a system for a document, e.g. payment or collection document .</td>
    <td>Derived</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodorServiceServiceQuantityReceived</td>
    <td>Quantity of goods or services received.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodsorservicesRecieptDate</td>
    <td>Receipt date for the goods or services during the receipt of goods process. </td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentReferenceNumber</td>
    <td>Details a unique identifying number created by a system for a document, e.g. payment or collection document.</td>
    <td>Required</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PrecedingReferenceDocumentLineNumber</td>
    <td>The associated line from the preceding related document.  For example for an order,  the PreviousDocumentLine Number would be the associated line from the related requisition. </td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PrecedingReferenceDocumentNumber</td>
    <td>The number of the preceding DocumentReferenceNumber.  For example for an invoice, the preceding document number would be the order number.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentLineNumber</td>
    <td>Identifies the line number on the requisition, order or receipt invoice for each separate product or service.</td>
    <td>Optional</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/25">Provide Feedback</a></td>
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
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a> </td>
 </tr>
 <tr>
  <td>3rdPartyInformationAddressLine1</td>
  <td>First line of the 3rd party involved in the transaction's address</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a> </td>
 </tr>
 <tr>
  <td>3rdPartyInformationAddressLine2</td>
  <td>Code for the country in which the 3rd party involved in the transaction uses, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, minus the codes listed for those territories and possessions of the United States already identified as estates'??</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a> </td>
 </tr>
 <tr>
  <td>3rdPartyInformationCityName</td>
  <td>Name of the city in 3rd party involved in the transaction is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback</a> </td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactCountryCode</td>
  <td>Code for the country in which the 3rd party involved in the transaction is located, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, minus the codes listed for those territories and possessions of the United States already identified as ?states.?</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactE-MailAddress</td>
  <td>?Internet e-mail address for 3rd party involved in the transaction</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactFirstName</td>
  <td>The last for the 3rd party involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactFirstName</td>
  <td>The first name for the 3rd party involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactPartyType.</td>
  <td>The identification number for the party involved in the transaction.. The name of the party involved in the transaction. The party type, i.e., individual, business or government.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3rdPartyInformationContactTelephoneNumber</td>
  <td>for the 3rd party involved in the transaction. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3rdPartyInformationStateCode</td>
  <td>United States Postal Service (USPS) two-letter abbreviation for the state or territory in which the 3rd party involved in the transaction address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3rdPartyInformationZip5</td>
  <td>USPS five digit zoning code associated with the 3rd party involved in the transaction address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>3thPartyInformationZIP+4</td>
  <td>USPS four digit extension code associated with the postal address 3rd party involved in the transaction address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>AwardeeOrRecipientUniqueIdentifier</td>
  <td>The Data Universal Numbering System (DUNS) Number is a unique nine-character identification number provided by the commercial company Dun and Bradstreet (D&amp;B).</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankAccountNumber1</td>
  <td>The account number of one financial institution involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankAccountNumber2</td>
  <td>The account number for a second financial institution involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankAccountNumber3</td>
  <td>The account number of a third financial institution involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankAccountRoutingNumber#1</td>
  <td>A financial institution's nine-digit routing transit number assigned by the American Banking Association (ABA).The number must be the Electronic Funds Transfer (ETF) Routing number, not the Wire Transfer number.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankAccountRoutingNumber#2</td>
  <td>A financial institution's nine-digit routing transit number assigned by the American Banking Association (ABA).The number must be the Electronic Funds Transfer (ETF) Routing number, not the Wire Transfer number.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankAccountRoutingNumber#3</td>
  <td>A financial institution's nine-digit routing transit number assigned by the American Banking Association (ABA).The number must be the Electronic Funds Transfer (ETF) Routing number, not the Wire Transfer number.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankAccountType</td>
  <td>The code that identifies the type of account associated with the transaction, such as checking or savings.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>BankName</td>
  <td>The name of the financial institution.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>CommentField</td>
  <td>Note(s) explaining or illustrating the meaning of a record or transaction.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>CountryofIncorporation</td>
  <td>The country code the entity has residence or incorporation. This follows the ISO3166 3-digit format.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>EFTWaiver</td>
  <td>The EFT Waiver Flag indicates whether banking information is required for the entity. Per 31 ? CFR 208.1, all Federal payments made by an agency requires payments to be made by electronic funds transfer, except as specified in 31 ? 208.4, this part requires payments, other than payments made under the Internal Revenue Code of 1986.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>EntityDateofLastUpdate</td>
  <td>The date the an entity's information was last updated.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>EntityIdentificationNumber</td>
  <td>This is a number that uniquely identifies the entity and is associated with the legal entity address. Some examples of this identification number is the Social Security Number (SSN), Tax Identification Number (TIN), or unique number created by the agency to protect personally identifiable information (PII). This entity ID does not Include the DUNS # and UEI.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>EntityType</td>
  <td>Specifies the legal form of the business or entity (e.g., Sole Proprietorship, Partnership or Limited Liability Partnership, Corporate Entity (Not Tax Exempt), etc.).</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>InternalRevenueService(IRS)1099indicator</td>
  <td>Determines if the entity is IRS Form 1099 eligible. The Form 1099 is used to report payments to independent contractors, rental property income, income from interest and dividends, sales proceeds, and other miscellaneous income.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityAddressLine1</td>
  <td>First line of the entity's address.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityAddressLine2</td>
  <td>Second line of the entity's address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityCityName</td>
  <td>Name of the city in which the entity's address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityForeignCityName</td>
  <td>For foreign entities only: name of the city in which the entity's address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityForeignPostalCode</td>
  <td>For foreign entities only: foreign postal code in which the entity's address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityForeignProvinceName</td>
  <td>For foreign entities only: name of the state or province in which the entity's legal business address is located.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityName</td>
  <td>The name of the entity associated with the Entity Identification Number, DUNS # or UEI.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityStateCode</td>
  <td>United States Postal Service (USPS) two-letter abbreviation for the state or territory in which the entity's address is located. Identify States, the District of Columbia, territories (i.e., American Samoa, Guam, Northern Mariana Islands, Puerto Rico, U.S. Virgin Islands) and associated states (i.e., Republic of the Marshall Islands, the Federated States of Micronesia, and Palau) by their USPS two-letter abbreviation.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityZIP5</td>
  <td>USPS five digit zoning code associated with the postal entity's address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>LegalEntityZIPLast4</td>
  <td>USPS four digit extension code associated with the entity's address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressCityName</td>
  <td>The name of the city of the postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressCountryCode</td>
  <td>Code for the country in which the entity receives letters or packages, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from the place where they work or live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressForeignCityName</td>
  <td>For foreign entities only: name of the city in which the entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressForeignPostalCode</td>
  <td>For foreign entities only: foreign postal code in which the entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressForeignProvinceName</td>
  <td>For foreign entities only: name of the state or province in which the which the entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressLine1</td>
  <td>First line of the postal address?at which an entity?receives?letters?or?packages, which can be different from the?place?where they?work?or?live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressLine2</td>
  <td>First line of the postal address?at which an entity?receives?letters?or?packages, which can be different from the?place?where they?work?or?live.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressState</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressZipCode5</td>
  <td>USPS five digit zoning code associated with postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>MailingAddressZipLast4</td>
  <td>USPS four digit extension code associated with the postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactFirstName1</td>
  <td>The first name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactFirstName2</td>
  <td>The first name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactFirstName3</td>
  <td>The first name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactLastName1</td>
  <td>The last name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactLastName2</td>
  <td>The Last name of the party involved in the transaction.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactLastName3</td>
  <td>The last name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactTelephoneNumber1</td>
  <td>U.S. phone number for a person serving as the coordinator or focal point of information concerning an activity or program. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactTelephoneNumber2</td>
  <td>U.S. phone number for a person serving as the coordinator or focal point of information concerning an activity or program. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactTelephoneNumber3</td>
  <td>U.S. phone number for a person serving as the coordinator or focal point of information concerning an activity or program. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactE-MailAddress1</td>
  <td>?Internet e-mail address for a person or a department serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactE-MailAddress2</td>
  <td>?Internet e-mail address for a person or a department serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PointofContactE-MailAddress3</td>
  <td>?Internet e-mail address for a person or a department serving as the coordinator or focal point of information concerning an activity or program.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>PromptPayIndicator</td>
  <td>When entity's are established, they are assigned an indicator that designates whether they are eligible to receive Prompt Payment interest.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressCity(1)</td>
  <td>Name of the city of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressCity(2)</td>
  <td>Name of the city of the postal address that entity uses, can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressCity(3)</td>
  <td>Name of the city of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressCountryCode(1)</td>
  <td>Code for the country in which the entity to receive payments and invoices by mail, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressCountryCode(2)</td>
  <td>Code for the country in which the entity to receive payments and invoices by mail, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressCountryCode(3)</td>
  <td>Code for the country in which the entity to receive payments and invoices by mail, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignCityName (1)</td>
  <td>For foreign entities only: name of the city in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignCityName (2)</td>
  <td>For foreign entities only: name of the city in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignCityName (3)</td>
  <td>For foreign entities only: name of the city in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (1)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (1)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (2)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignPostalCode (3)</td>
  <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignProvinceName (1)</td>
  <td>For foreign entities only: name of the state or province in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignProvinceName (2)</td>
  <td>For foreign entities only: name of the state or province in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressForeignProvinceName (3)</td>
  <td>For foreign entities only: name of the state or province in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressLine1(1)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressLine1(2)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressLine1(3)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressLine2(1)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressLine2(2)</td>
  <td>The second line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressLine2(3)</td>
  <td>The first line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressStateCode(1)</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressStateCode(2)</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressStateCode(3)</td>
  <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressZip5(1)</td>
  <td>USPS five digit zoning code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressZip5(2)</td>
  <td>USPS five digit zoning code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressZip5(3)</td>
  <td>USPS five digit zoning code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressZipLast4(1)</td>
  <td>USPS four digit extension code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>RemittanceAddressZipLast4(2)</td>
  <td>USPS four digit extension code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>StateofIncorporation</td>
  <td>The state code the entity has residence or incorporation. This element is required if you selected the United States for the Country of Incorporation.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>UEI</td>
  <td>A Unique Entity Identifier (UEI) is a unique number assigned to all entities (public and private companies, individuals, institutions, or organizations) who register to do business with the federal government.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>VendorPaymentMethod</td>
  <td>List of payment methods which may be used in automatic payment transactions with this customer/vendor if you do not specify a payment method in the item to be paid.</td>
  <td>Required</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
 <tr>
  <td>W2Indicator</td>
  <td>This indicator is used to classify the different types of withholding tax. Form W-2 is filed by employers to report wages, tips, and other compensation paid to employees as well as FICA and withheld income taxes.</td>
  <td>Optional</td>
  <td>                <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/22"                      target="_blank" rel=“noopener noreferrer”>Provide Feedback </a></td>
 </tr>
        </tr>
        </tbody>
    </table>
</div>




<h2>Automated Journal Entry Business Exchange Standar</h2>
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



<p><h3 class="mt-0">Proposed Additions and Changes to Federal Financial Standard Data Elements </h3></p> 
   <p> 
             As a result of the business exchange analysis, there are also data elements that need to be added or modified in the Federal Financial Standard Data Elements for these business exchanges to properly perform the necessary exchange of data between systems.  
        </p>
        <p> 
             When preparing feedback, consider the following:
        </p>
        <p>
            <strong>For the new standard data elements identified and defined: </strong>
        </p>
        <ul>
            <li>
                Are the data elements appropriately named?
            </li>
            <li>
                Are the data element definitions accurate?
            </li>
             <li>
               Is the Authoritative Reference(s) listed correct and comprehensive? 
            </li>
             <li>
               Are we missing any data elements
            </li>
             </p>
              <p> 
         Note: We are not requesting feedback to the elements previously defined in the DATA Act Information Model Schema or the Fiscal Service Data Registry at this time. 
        </p>
        </ul>



<h2>New Proposed Data Elements as a Result of the Business Exchange Analysis</h2>
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
    <td>DocumentApprovalDate</td>
    <td>The date which the requisition, order or invoice was approved.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ModificationNumber</td>
    <td>An identifier issued by an agency that uniquely identifies one modification for one contract, agreement, order, etc.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityName</td>
    <td>The name of the entity.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity<br>  Name generalized so that it can be used for both Payee and Payer</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentLineNumber</td>
    <td>Identifies the line number on the requisition, order or receipt invoice for each separate product or service.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>Description</td>
    <td>A brief description of the requisition, order or invoice.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentLineDescription</td>
    <td>The description of goods/services associated with each itemized line within the requisition, order or invoice.</td>
    <td>Req, Order, Invoice</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>AwardPeriodofPerformanceStartDate</td>
    <td>The date on which, for the order or invoice being reported, effort begins or the award is otherwise effective.</td>
    <td>DATA Act Information Model Schema (DAIMS) AwardPeriodofPerformanceStartDate generalized so that it can be used for both Payee and Payer</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>AwardPeriodofPerformanceEndDate</td>
    <td>The current date on which, for the order referred to by the order or invoice being reported, the effort completes or the order is otherwise ended. Administrative actions related to this award may continue to occur after this date. </td>
    <td>DATA Act Information Model Schema (DAIMS) AwardPeriodofPerformanceEndDate generalized so that it can be used for both Payee and Payer</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>TravelPeriodEndDate</td>
    <td>End date of an event associated with the travel process, such as the travel period or reservation.</td>
    <td>Federal Integrated Business Framework (FIBF) Travel and Expense Standard Data Elements</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>TravelPeriodStartDate</td>
    <td>Start date of an event associated with the travel process, such as the travel period or reservation.</td>
    <td>Federal Integrated Business Framework (FIBF) Travel and Expense Standard Data Elements</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentLineQuantity</td>
    <td>The quantity of goods/services associated with each itemized line within the requisition, order or invoice.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentLineUnitofMeasure</td>
    <td>The means a quantity is accounted for and expressed on each itemized line within the requisition, order or invoice for a good/service.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>UnitPrice</td>
    <td>The price of one purchase unit on a requisition, order or invoice</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>DocumentLineAmount</td>
    <td>The total price is the quantity x unit price for each itemized line within the requisition, order or invoice.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>SubObjectClass</td>
    <td>Categories in a classification system that presents obligations by the items or services purchased by the Federal Government.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ProjectIdentifier</td>
    <td>A planned undertaking of work to be performed or product to be produced having a finite beginning and end.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>ActivityIdentifier</td>
    <td>An activity is a series of events, tasks, or units of work that are linked to perform a specific objective</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RevenueSourceCode</td>
    <td>This element is useful in tracking the source of revenue earned by agencies. It is also used by many agencies in allocating revenue to their strategic goals for the preparation of the Statement of Net Costs.</td>
    <td>USSGL Account Attribute</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PrecedingReferenceDocumentLineNumber</td>
    <td>The associated line from the preceding related document.  For example for an order,  the PreviousDocumentLineNumber would be the associated line from the related requisition. </td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PrecedingReferenceDocumentNumber</td>
    <td>The number of the preceding DocumentReferenceNumber.  For example for an invoice, the preceding document number would be the order number.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>Unitprice</td>
    <td>The price of one purchase unit on a requisition, order or invoice.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodorServiceAcceptedDate</td>
    <td>Identifies the date the goods and services were accepted.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodorServiceQuantityAccepted</td>
    <td>Quantity of goods or services accepted during the receipt of goods process.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodorserviceAmountReceived</td>
    <td>Currency amount from the receipt for goods or services.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>GoodsorservicesRecieptDate</td>
    <td>Receipt date for the goods or services during the receipt of goods process. </td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>VoucherType</td>
    <td>Identifies the type of journal voucher. </td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationContactLastName</td>
    <td>The last for the 3rd party involved in the transaction.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationContactFirstName</td>
    <td>The first name for the 3rd party involved in the transaction.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationContactCountryCode</td>
    <td>Code for the country in which the 3rd party involved in the transaction is located, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationCountryName</td>
    <td>The name corresponding to the country code for the 3rd party involved in the transaction.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationAddressLine1</td>
    <td>First line of the 3rd party involved in the transaction's address </td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationAddressCountryCode</td>
    <td>Second  line of the 3rd party involved in the transaction's address </td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationCityName</td>
    <td>Name of the city in 3rd party involved in the transaction is located.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationStateCode</td>
    <td>United States Postal Service (USPS) two-letter abbreviation for the state or territory in which the 3rd party involved in the transaction address is located.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationZip5</td>
    <td>USPS five digit zoning code associated with  the 3rd party involved in the transaction address. </td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3thPartyInformationZIP+4</td>
    <td>USPS four digit extension code associated with the postal address  3rd party involved in the transaction address. </td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationContactTelephoneNumber</td>
    <td>for the 3rd party involved in the transaction. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationAddressLine2</td>
    <td>Code for the country in which the 3rd party involved in the transaction uses, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, minus the codes listed for those territories and possessions of the United States already identified as estates</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationContactE-MailAddress</td>
    <td>Internet e-mail address for 3rd party involved in the transaction</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationForeignCityName</td>
    <td>For foreign entities only: name of the city in which the 3rd party involved in the transaction.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationForeignProvinceName</td>
    <td>For foreign entities only: name of the state or province in which the 3rd party involved in the transaction.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>3rdPartyInformationForeignPostalCode</td>
    <td>For foreign entities only: foreign postal code in which the 3rd party involved in the transaction.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized so that it can be used for a third party involved in a transaction </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressLine1</td>
    <td>The first line of the postal address that entity uses, which can  be different from their main mailing address, to receive payments and invoices by mail.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressLine2</td>
    <td>The second line of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressCity</td>
    <td>Name of the city of the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressStateCode</td>
    <td>United States Postal Service (USPS) address two-letter abbreviation for the state or territory in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressZip5</td>
    <td>USPS five digit zoning code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressCountryCode</td>
    <td>Code for the country in which the entity to receive payments and invoices by mail, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from their main mailing address.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressZipLast4</td>
    <td>USPS four digit extension code associated with the postal address that entity uses, which can be different from their main mailing address, to receive payments and invoices by mail.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressForeignCityName</td>
    <td>For foreign entities only: name of the city in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressForeignProvinceName</td>
    <td>For foreign entities only: name of the state or province in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>RemittanceAddressForeignPostalCode</td>
    <td>For foreign entities only: foreign postal code in which the entity receives payments and invoices by mail, which can be different from their main mailing address.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Remittance Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PointofContactFirstName</td>
    <td>The first name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PointofContactLastName</td>
    <td>The last name of a person serving as the coordinator or focal point of information concerning an activity or program.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PointofContactTelephoneNumber</td>
    <td>U.S. phone number for a person serving as the coordinator or focal point of information concerning an activity or program. Enter the phone number in this exact format: (xxx)xxx-xxxx</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PointofPointofContactE-MailAddress</td>
    <td>Internet e-mail address for a person or a department serving as the coordinator or focal point of information concerning an activity or program.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>EntityDateofLastUpdate</td>
    <td>The date the an entity's information was last updated.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>EFTWaiver</td>
    <td>The EFT Waiver Flag indicates whether banking information is required for the entity. Per 31 CFR 208.1, all Federal payments made by an agency requires payments to be made by electronic funds transfer, except as specified in 31 208.4, this part requires payments, other than payments made under the Internal Revenue Code of 1986.</td>
    <td>TFM Volume I Green Book</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>EntityType</td>
    <td>Specifies the legal form of the business or entity (e.g., Sole Proprietorship, Partnership or Limited Liability Partnership, Corporate Entity (Not Tax Exempt), etc.). </td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>InternalRevenueService(IRS)1099indicator</td>
    <td>Determines if the entity is  IRS Form 1099 eligible.  The Form 1099 is used to report payments to independent contractors, rental property income, income from interest and dividends, sales proceeds, and other miscellaneous income.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressLine2</td>
    <td>First line of the postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressCity</td>
    <td>The name of the city of the postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressCountryCode</td>
    <td>Code for the country in which the entity receives letters or packages, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile, which can be different from the place where they work or live.<br>  </td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressZipCode5</td>
    <td>USPS five digit zoning code associated with postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressZipLast4</td>
    <td>USPS four digit extension code associated with the postal address at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressForeignCityName</td>
    <td>For foreign entities only: name of the city in which the entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressForeignProvinceName</td>
    <td>For foreign entities only: name of the state or province in which the which the entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressForeignPostalCode</td>
    <td>For foreign entities only: foreign postal code in which the entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>MailingAddressState</td>
    <td>United States Postal Service (USPS) address  two-letter abbreviation for the state or territory in which the at which an entity receives letters or packages, which can be different from the place where they work or live.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Legal Entity Address  generalized and transformed to apply to a Mailing Address</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>BankAccountRoutingNumber</td>
    <td>A financial institution's nine-digit routing transit number assigned by the American Banking Association (ABA).The number must be the Electronic Funds Transfer (ETF)  Routing number, not the Wire Transfer number. </td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>StateofIncorporation</td>
    <td>The state code the entity has residence or incorporation.  This element is required if you selected the United States for the Country of Incorporation. </td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PromptPayIndicator</td>
    <td>When entity's are established,  they are assigned an indicator that designates whether they are eligible to receive Prompt Payment interest.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>VendorPaymentMethod</td>
    <td>List of payment methods which may be used in automatic payment transactions with this customer/vendor if you do not specify a payment method in the item to be paid.</td>
    <td>Entity</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>W2Indicator</td>
    <td>This indicator is used to classify the different types of withholding tax.  Form W-2 is filed by employers to report wages, tips, and other compensation paid to employees as well as FICA and withheld income taxes.</td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>CountryofIncorporation</td>
    <td>The country code the entity has residence or incorporation. This follows the ISO3166 3-digit format. </td>
    <td>TBD</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>EntityIdentificationNumber</td>
    <td>This is a number that uniquely identifies the entity and is associated with the legal entity address.  Some examples of this identification number is the Social Security Number (SSN), Tax Identification Number (TIN), or unique number created by the agency to protect personally identifiable information (PII).  This entity ID does not Include the DUNS # and UEI.</td>
    <td>DATA Act Information Model Schema (DAIMS) Awardee/Recipient<br>  Unique Identifier  generalized and transformed to so that a unique identifier could be applied to other Entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/27">Provide Feedback</a></td>
  </tr>
        </tbody>
    </table>
</div>


<h2>Proposed Modifications to Data Elements as a result of the Business Exchange Analysis</h2>
<div class="table-responsive">
    <table class="table-bordered">
        <thead>
        <tr>
            <th>
                <strong> Existing FFM Data Element Name</strong>
            </th>
            <th>
                <strong>Existing Definition</strong>
            </th>
            <th>
                <strong>Proposed Definition</strong>
            </th>
            <th>
                <strong>Rationale</strong>
            </th>
            <th>
                <strong>&nbsp; Provide Feedback</strong>
            </th>
        </tr>
        </thead>
        <tbody>
  <tr>
    <td>LegalEntityCountryCode</td>
    <td>The code that identifies a country.</td>
    <td>Code for the country in which the entity is located, using the International Standard for country codes (ISO) 3166-1 Alpha-3 GENC Profile</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityAddressLine1</td>
    <td>First line of the awardee or recipient's legal business address where the office represented by the Unique Entity Identifier (as registered in the System for Award Management) is located.</td>
    <td>First line of the entity's  address.</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityAddressLine2</td>
    <td>Second line of awardee or recipient's legal business address.</td>
    <td>Second line of the entity's  address.</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityCityName</td>
    <td>The name of the city.</td>
    <td>Name of the city in which the entity's address is located.</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityStateCode</td>
    <td>The US state code and Canadian province code.</td>
    <td>United States Postal Service (USPS) two-letter abbreviation for the state or territory in which the entity's address is located. Identify States, the District of Columbia, territories (i.e., American Samoa, Guam, Northern Mariana Islands, Puerto Rico, U.S. Virgin Islands) and associated states (i.e., Republic of the Marshall Islands, the Federated States of Micronesia, and Palau) by their USPS two-letter abbreviation.</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityForeignCityName</td>
    <td>For foreign recipients only: name of the city in which the awardee or recipient's legal business address is located.</td>
    <td>For foreign entities only: name of the city in which the entity's address is located.</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityForeignProvinceName</td>
    <td>For foreign recipients only: name of the state or province in which the awardee or recipient's legal business address is located.</td>
    <td>For foreign entities only: name of the state or province in which the entity's legal business address is located.</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>LegalEntityForeignPostalCode</td>
    <td>For foreign recipients only: foreign postal code in which the awardee or recipient's legal business address is located.</td>
    <td>For foreign entities only: foreign postal code in which the entity's address is located.</td>
    <td>Recommend generalizing this definition so that it can be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PartyType</td>
    <td>Delete</td>
    <td>Delete</td>
    <td>Recommend Deleting this data element out of the FFM data standards and replace with EntityPartyType to be consistent with the other entity data elements</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>PartyIdentifier</td>
    <td>Delete</td>
    <td>Delete</td>
    <td>Recommend Deleting this data element out of the FFM data standards and replace with EntityIdentificationNumber to be consistent with the other entity data elements.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>Party Name</td>
    <td>Delete</td>
    <td>Delete</td>
    <td>Recommend Deleting this data element out of the FFM data standards and replace with LegalEntityName to be consistent with the other entity data elements.  This element can also be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>Payee Name</td>
    <td>Delete</td>
    <td>Delete</td>
    <td>Recommend Deleting this data element out of the FFM data standards and replace with LegalEntityName to be consistent with the other entity data elements.  This element can also be used for both payee and payer entities.</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
  <tr>
    <td>UltimateParentLegalEntityName</td>
    <td>Delete</td>
    <td>Delete</td>
    <td>This data elements does not map to any of the other FM data elements.  In DAIMS and SAM.gov this element is associated with a UltimateParentUniqueIdentifier which is different than AwardeeOrRecipientUniqueIdentifier.  AwardeeOrRecipientUniqueIdentifier maps to AwardeeOrRecipientLegalEntityName and the Legal Entity address elements already included in the FFM standards.  Recommend replacing with LegalEntityName.  </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
        </tbody>
    </table>
</div>

