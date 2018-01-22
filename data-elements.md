---
published: true
permalink: /data-elements/
layout: article
filename: data-elements.md
title: Data Elements
---
The data elements are grouped by End-to-End Business Process. We have placed the elements in their primary business process for ease of review, but we realize that many may be used in more than one process. Each End-to-End Business Process will have it’s own GitHub issue, which is where you can see the input posted during the public input period. Thank you to all who provides input on these data elements.
<h2>010 - Budget Formulation-to-Execution</h2>
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
            BudgetAllotmentAmount
        </td>
        <td>
            A subdivision of an apportionment that is made by the head of an agency.
        </td>
        <td>
            OMB Circular No. A-11, Appendix H, Checklist for Fund Control Regulations, Section 4: Definitions,
            Terminology, and Concepts
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/11" target="_blank">Click
                here; Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            BudgetSubAllotmentAmount
        </td>
        <td>
            A subdivision of an allotment.
        </td>
        <td>
            OMB Circular No. A-11, Appendix H, Checklist for Fund Control Regulations, Section 4: Definitions,
            Terminology, and Concepts
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/11" target="_blank">Click
                here; Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            AgencyFundCode
        </td>
        <td>
            A code designated by the agency to a fund. It is a shorthand code entered on transactions that enables the
            derivation of the account identification codes required for reporting externally to Treasury (the TAS) and
            OMB (the budget account) as well as the derivation of USSGL account attributes. It can be used for
            segregating funds that have multiple apportionment categories, or that have both discretionary and mandatory
            authority.
        </td>
        <td>
            Common Government-wide Accounting Classification Structure, Version 1.0, July 2007
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/11" target="_blank">Click
                here; Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            ReductionTypeCode
        </td>
        <td>
            The code representing the USSGL attribute for a type of reduction being reported (e.g., Across The Board,
            Sequestration or Other) in detailed financial information.
        </td>
        <td>
            USSGL, Section IV Account Attributes for USSGL Proprietary Account and Budgetary Account Reporting
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/11" target="_blank">Click
                here; Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>020 - Acquire-to-Dispose</h2>
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
            The date that the acquiring entity receives the title for Property, Plants, and Equipment (PP&amp;E) or the
            date that the PP&amp;E is delivered to the entity or to an agent of the entity. Constructed PP&amp;E is
            recorded as construction work in progress until it is placed in service, at which time the balance shall be
            transferred to general PP&amp;E.
        </td>
        <td>
            SFFAS 6: Accounting for Property, Plant, and Equipment;
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            AssetCategoryName
        </td>
        <td>
            Name of a common grouping of assets based on asset characteristics. The categories include Property, Plant,
            and Equipment (PP&amp;E); additional categorization for major classes of PP&amp;E (e.g. buildings,
            equipment, land, etc.); additional categorization for physical custody of PP&amp;E (e.g. contractor-held or
            government-held); inventory; heritage assets; stewardship land; and other assets.
        </td>
        <td>
            Definition (compiled from)<br> - OMB Circular A-136 Section II.4.9.10 (Note 10, General Property, Plant and
            Equipment, Net)<br> - FASAB Standards SFFAS 1, 2, 3, 6, 8, 10, 11, 18, 19, 29, 38
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            AssetCategoryQuantity
        </td>
        <td>
            A number of asset units as determined by the property management process using appropriate FASAB guidance.
        </td>
        <td>
            FASAB Standards SFFAS 1, 10, 11, 18, 19, 2, 29
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/10" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>030 - Request-to-Procure</h2>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/9" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>040 - Procure-to-Pay</h2>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            CurrentValueOfFundsRate
        </td>
        <td>
            A percentage rate based on the current value of funds to the Department of Treasury. It is used for Federal
            debt collection, cash discounts, and rebate evaluation.
        </td>
        <td>
            5 CFR 1315, Prompt Payment: 1315.7 Discounts
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            DeliveryDate
        </td>
        <td>
            The date on which the item/service is received and signed for delivery as described in the Prompt Payment
            Act.
        </td>
        <td>
            Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
            payment interest penalties, 1315.11 Additional penalties,1315.5 Accelerated payment methods, and 1315.2
            Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            InvoiceReceiptDate
        </td>
        <td>
            The date on which the proper payment invoice is received by the designated agency office as described in the
            Prompt Payment Act.
        </td>
        <td>
            Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.4 Prompt Payment Standards and Required
            Notices to Vendors.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            AdditionalPenaltyPaymentAmount
        </td>
        <td>
            Amount of additional penalties owed to the vendor under the Prompt Payment Act if the late payment interest
            was not paid by the due date and the vendor submits a written demand for the additional penalty.
        </td>
        <td>
            Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
            payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
            Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            DiscountDate
        </td>
        <td>
            The date by which an early payment must be made in order to receive a specified payment reduction, or a
            discount, under the Prompt Payment Act. The decision to take the discount should be made based on the best
            interest of the government, as determined by Prompt Payment guidelines.
        </td>
        <td>
            Definition (compiled from)<br> - 5 CFR 1315, Prompt Payment: 1315.9 Required documentation, 1315.10 Late
            payment interest penalties, 1315.11 Additional penalties, 1315.5 Accelerated payment methods, and 1315.2
            Definitions. (a) Accelerated Payment.<br> - 31 U.S. Code Chapter 39 - PROMPT PAYMENT
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/8" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>050 - Bill-to-Collect</h2>
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
            Activities. Examples include but are not limited to debt in bankruptcy, in forbearance or in formal appeals,
            in foreclosure, at a private collection agency, in litigation, in the process of internal offset, in wage
            garnishment, at Treasury for cross-servicing or offset, and collected at the agency.
        </td>
        <td>
            TFM Volume I, Part 2, Chapter 4100, Section 4120, Reporting Requirements, and the Instructional Workbook for
            Preparing the Treasury Report on Receivables and Debt Collection Activities, Part I, Status of Receivables,
            and Part II, Debt Management Tool and Technique Performance Data referenced therein.
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/7" target="_blank">Closes 2/16/2018</a>
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
            TFM Volume I, Part 2, Chapter 4100, Section 4120, Reporting Requirements, and the Instructional Workbook for
            Preparing the Treasury Report on Receivables and Debt Collection Activities, Part I, Status of Receivables,
            and Part II, Debt Management Tool and Technique Performance Data referenced therein.
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/7" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            ReceivableTransactionAdjustmentAmount
        </td>
        <td>
            An amount applied to a receivable to increase or reduce the amount that the debtor owes based on a change in
            position between issuance of the original invoice and creation of the receivable (e.g., from the application
            of a credit memo or an offer in compromise).
        </td>
        <td>
            OMB Circular No. A-129, Policies for Federal Credit Programs and Non-Tax Receivables, Appendix A, Part IV,
            Managing the Federal Government&rsquo;s Receivables;
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/7" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>060 - Record-to-Report</h2>
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
            Investment across multiple fiscal years (FYs) of an Agency&rsquo;s information technology (IT) portfolio.
        </td>
        <td>
            Definition (compiled from)
            - FY2019 IT Budget -- Capital Planning Guidance, APPENDIX C. DEFINITIONS (source for definition)
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/6" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    <tr>
        <td>
            AccrualAdjustmentAmount
        </td>
        <td>
            For accrual-basis accounting, the amount applied to an accrual accumulated in a prior period in order to
            provide more accurate and timely information for planning and control of operations and understanding of net
            position and cost of operations.
        </td>
        <td>
            SFFAS 7: Accounting for Revenue and Other Financing Sources and Concepts for Reconciling Budgetary and
            Financial Accounting.
        </td>
        <td>
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/6" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>070 - Agree-to-Reimburse (Reimbursable Management)</h2>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/5" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>080 - Apply-to-Perform (Grants Management)</h2>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/4" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>090 - Hire-to-Retire</h2>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/3" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>100 - Book-to-Reimburse (Travel)</h2>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/2" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>
<h2>110 - Apply-to-Repay</h2>
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
            <a href="https://github.com/bureauofthefiscalservice/federalfinancialmanagement/issues/1" target="_blank">Closes 2/16/2018</a>
        </td>
    </tr>
    </tbody>
</table>

