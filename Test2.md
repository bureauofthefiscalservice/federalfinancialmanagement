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
    <td>Existing FFM Data Element Name</td>
    <td>Existing Data Element Definition</td>
    <td>Proposed Definition </td>
    <td>Rationale</td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
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
    <td>For foreign recipients only: name of the state or province in which the awardee or recipient�s legal business address is located.</td>
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
    <td>This data does not map to any of the other FM data elements.  In DAIMS and SAM this element is associated with a UltimateParentUniqueIdentifier which is different than AwardeeOrRecipientUniqueIdentifier.  AwardeeOrRecipientUniqueIdentifier maps to AwardeeOrRecipientLegalEntityName and the Legal Entity address elements already included in the FFM standards.  Recommend replacing with LegalEntityName.  </td>
    <td><a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/28">Provide Feedback</a></td>
  </tr>
        </tbody>
    </table>
</div>
