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
    <td>The definition for this element appears in Section 200 (https://obamawhitehouse.archives.gov/sites/default/files/omb/assets/a11_current_year/s200.pdf) of OMB Circular A-11 issued June 2015; a summary from A-11 appears below. Code of a specific activity or project as listed in the program and financing schedules of the annual budget of the United States Government.</td>
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
