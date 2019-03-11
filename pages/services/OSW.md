## Official Search of Whole

### Technical documents for software developers to integrate Official Search of Whole with Priority OS(W) service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

#### Protects the register for the applicant for a period of 28 days.

### Process flow

#### Input
Request an official search by sending the following parameters:

- login details
- external reference number
- title number
- search start date
- registered proprietors
- customer reference
- applicant name
- priority type
- contact details
- property description
- alternative despatch details

The following parameters will also be necessary if there are any complications, and may be supplied to keep transaction calls and processing times to a minimum.

- continue despite name mismatch?
- continue if developing or part?
- continue if fee confirmation exceeds fee amount?
- fee confirmation?

#### Validation
Validation diagram details the validation that the request goes through.

<h3><a href="../../pdfs/services/Official_Search_Whole_Priority_Validation_v1.3.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/OSWholeWithPrioirtyValidationDiagramV1_2.pdf.png"></a>
<a href="../../pdfs/services/Official_Search_Whole_Priority_Validation_v1.3.pdf">Validation diagram</a></h3>
<a download="OfficialCopyTitleKnown_v2.1_Validation.pdf" href="../../pdfs/services/Official_Search_Whole_Priority_Validation_v1.3.pdf">Download</a>

PDF, 167KB, 7 pages

#### Output
Responds with a confirmation that the request for documents has been sent to Land Registry. The user is also informed of any entitlement due to commonhold.

### Schemas

<h3><a href="../../schemas/RequestOfficialSearchOfWholeWithPriorityV2_1.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/RequestOfficialSearchOfWholeWithPriorityV2_1.xsd">RequestOfficialSearchofWholeWithPriorityV2_1.xsd</a></h3>
<a download=".xsd" href="../../schemas/RequestOfficialSearchOfWholeWithPriorityV2_1.xsd">Download</a>

XSD, 25KB

<br/>
<h3><a href="../../schemas/ResponseOfficialSearchOfWholeWithPriorityV2_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/ResponseOfficialSearchOfWholeWithPriorityV2_0.xsd">Schema: ResponseOfficialSearchOfWholeWithPriorityV2_0.xsd</a></h3>
<a download="ResponseOfficialSearchOfWholeWithPriorityV2_0.xsd" href="../../schemas/ResponseOfficialSearchOfWholeWithPriorityV2_0.xsd">Download</a>

XSD, 22KB

<br/>

<h3><a href="../../pdfs/services/Official_Search_Whole_Priority_SchemaExplain.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/OSofWholeWithPSchemaExplain.pdf.png"></a>
<a href="../../pdfs/services/Official_Search_Whole_Priority_SchemaExplain.pdf">Schema explain</a></h3>
<a download="OfficialCopyTitleKnownV2.1_Schema_Explain.pdf" href="../../pdfs/services/Official_Search_Whole_Priority_SchemaExplain.pdf">Download</a>

PDF, 257KB, 21 pages

#### Schema explain describes the request schema for the service.

<h3><a href="../../xml/Official_Search_Whole_Priority_v2.1_example.xml">
<img style="float: left; margin: 0px 5px 0px 0px;" src="../../images/thumbnail/file.png"></a>
<a href="../../xml/Official_Search_Whole_Priority_v2.1_example.xml">Official_Search_Whole_Priority_v2.1_example.xml</a></h3>
<a download="Official_Search_Whole_Priority_v2.1_example.xml" href="../../xml/Official_Search_Whole_Priority_v2.1_example.xml">Download</a>

XML, 2KB

<br/>
#### This provides example XML for the service.

### Vendor testing

#### Documents the data required for testing the service.

<h3><a href="../../pdfs/services/Official_Search_Whole_Priority_OS1_v2.1_VendorTest_v1.3.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/Official_Search_Whole_Priority_OS1_v2_1_VendorTest_v1_3.pdf.png"></a>
<a href="../../pdfs/services/Official_Search_Whole_Priority_OS1_v2.1_VendorTest_v1.3.pdf">Vendor Test Data (Request Official Search of Whole)</a></h3>
<a download="OfficialCopyTitleKnown_OC1_v2.1_VendorTest.pdf" href="../../pdfs/services/Official_Search_Whole_Priority_OS1_v2.1_VendorTest_v1.3.pdf">Download</a>

PDF, 356KB, 24 pages