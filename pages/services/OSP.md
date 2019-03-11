## Official Search of Part

### Technical documents for software developers to integrate Official Search of Part with Priority OS(P) service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

#### Provides an official search with priority of part of the land in a registered title or a pending first registration application.

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
- timeshare details
- alternative despatch details

The following parameters will also be necessary if there are any complications, and may be supplied to keep transaction calls and processing times to a minimum.

- continue despite name mismatch?
- continue if developing or part?
- continue if fee confirmation exceeds fee amount?
- fee confirmation?

#### Output
Responds with a confirmation that the request for documents has been sent to Land Registry. The user is also informed of any entitlement due to commonhold.

### Schemas

<h3><a href="../../schemas/RequestOfficialSearchOfPartWithPriorityV2_1.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/RequestOfficialSearchOfPartWithPriorityV2_1.xsd">RequestOfficialSearchOfPartWithPriorityV2_1.xsd</a></h3>
<a download="RequestOfficialSearchOfPartWithPriorityV2_1.xsd" href="../../schemas/RequestOfficialSearchOfPartWithPriorityV2_1.xsd">Download</a>

XSD, 34KB

<br/>
<h3><a href="../../schemas/ResponseOfficialSearchOfPartWithPriorityV2_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/ResponseOfficialSearchOfPartWithPriorityV2_0.xsd">Schema: ResponseOfficialSearchOfPartWithPriorityV2_0.xsd</a></h3>
<a download="ResponseOfficialSearchOfPartWithPriorityV2_0.xsd" href="../../schemas/ResponseOfficialSearchOfPartWithPriorityV2_0.xsd">Download</a>

XSD, 22KB

<br/>

<h3><a href="../../pdfs/services/OSofPartWithPv2.1_SchemaExplain.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/OSofPartWithPSchemaExplain.pdf.png"></a>
<a href="../../pdfs/services/OSofPartWithPv2.1_SchemaExplain.pdf">Schema explain</a></h3>
<a download="OSofPartWithPv2.1_SchemaExplain.pdf" href="../../pdfs/services/OSofPartWithPv2.1_SchemaExplain.pdf">Download</a>

PDF, 277KB, 29 pages

#### Schema explain describes the request schema for the service.

### Vendor testing

#### Documents the data required for testing the service.

<h3><a href="../../pdfs/services/OSofPartWithP_v2.1_Test_v1.0.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/Official_Search_Whole_Priority_OS1_v2_1_VendorTest_v1_3.pdf.png"></a>
<a href="../../pdfs/services/OSofPartWithP_v2.1_Test_v1.0.pdf">Vendor Test Data (Request Official Search of Part)</a></h3>
<a download="OSofPartWithP_v2.1_Test_v1.0.pdf" href="../../pdfs/services/OSofPartWithP_v2.1_Test_v1.0.pdf">Download</a>

PDF, 303KB, 13 pages