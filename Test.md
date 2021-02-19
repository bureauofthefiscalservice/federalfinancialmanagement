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
                The definition for this element appears in Section 200of OMB Circular A-21 issued June 2015; a brief summary from A-21 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.  
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
