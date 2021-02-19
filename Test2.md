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
