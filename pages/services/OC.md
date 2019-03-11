## Official Copy Title Known

### Technical documents for software developers to integrate Official Copy Title Known (OC1/OC2) service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

The Official Copy Title known (OC1/OC2) service uses a title number (that could be obtained through Search by Property Description service) to return an Official Copy of the register, title plan or both, as a PDF. Can also return copies of documents referred to in the register e.g. conveyance, deed or lease.

### Process flow

#### Input
Request an official search by sending the following parameters:

- login details
- external reference number
- title number
- type (register, title plan, certificate or documents)
- estate plan plot number(s)
- requested official copy
- contact details (customer ref, address, name, phone)
- fee confirmation
- property description
- alternative despatch details

The following parameters will also be necessary if there are any complications, and may be supplied to keep transaction calls and processing times to a minimum.

- continue if closed and continued?
- notify if pending first registration?
- notify if pending application or send back-dated?
- continue if actual fee exceeds fee confirmation?

#### Validation
Validation diagram details the validation that the request goes through.

<h3><a href="../../pdfs/services/OfficialCopyTitleKnown_v2.1_Validation.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/OfficialCopyTitleKnown-V1_1ValidationDiagram.pdf.png"></a>
<a href="../../pdfs/services/OfficialCopyTitleKnown_v2.1_Validation.pdf">Validation diagram</a></h3>
<a download="OfficialCopyTitleKnown_v2.1_Validation.pdf" href="../../pdfs/services/OfficialCopyTitleKnown_v2.1_Validation.pdf">Download</a>

PDF, 196KB, 9 pages

#### Output
Responds with a confirmation that the request for documents has been sent to Land Registry. The user is also informed of any entitlement due to commonhold.

### Schemas

<h3><a href="../../schemas/RequestTitleKnownOfficialCopyV2_1.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/RequestTitleKnownOfficialCopyV2_1.xsd">Request Title Known Official Copy V2_1.xsd</a></h3>
<a download=".xsd" href="../../schemas/RequestTitleKnownOfficialCopyV2_1.xsd">Download</a>

XSD, 35KB

<br/>
<h3><a href="../../schemas/ResponseTitleKnownOfficialCopyV2_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/ResponseTitleKnownOfficialCopyV2_0.xsd">Schema: ResponseTitleKnownOfficialCopyV2_0.xsd</a></h3>
<a download="ResponseTitleKnownOfficialCopyV2_0.xsd" href="../../schemas/ResponseTitleKnownOfficialCopyV2_0.xsd">Download</a>

XSD, 23KB

<br/>

<h3><a href="../../pdfs/services/OfficialCopyTitleKnownV2.1_Schema_Explain.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/RequestOfficialCopyTitleKnownV2.1SchemaExplain.pdf.png"></a>
<a href="../../pdfs/services/OfficialCopyTitleKnownV2.1_Schema_Explain.pdf">Schema explain</a></h3>
<a download="OfficialCopyTitleKnownV2.1_Schema_Explain.pdf" href="../../pdfs/services/OfficialCopyTitleKnownV2.1_Schema_Explain.pdf">Download</a>

PDF, 243KB, 24 pages

#### Schema explain describes the request schema for the service.

<h3><a href="../../xml/OfficialCopyTitleKnownV2.1_Example.xml">
<img style="float: left; margin: 0px 5px 0px 0px;" src="../../images/thumbnail/file.png"></a>
<a href="../../xml/OfficialCopyTitleKnownV2.1_Example.xml">RequestSearchByPropertyDescriptionV2_0Example.xml</a></h3>
<a download="OfficialCopyTitleKnownV2.1_Example.xml" href="../../xml/OfficialCopyTitleKnownV2.1_Example.xml">Download</a>

XML, 1KB

<br/>
#### This provides example XML for the service.

### Vendor testing

#### Documents the data required for testing the service.

<h3><a href="../../pdfs/services/OfficialCopyTitleKnown_OC1_v2.1_VendorTest.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/OfficialCopyTitleKnownVendorTest.pdf.png"></a>
<a href="../../pdfs/services/OfficialCopyTitleKnown_OC1_v2.1_VendorTest.pdf">Vendor Test Data (Request Official Copy)</a></h3>
<a download="OfficialCopyTitleKnown_OC1_v2.1_VendorTest.pdf" href="../../pdfs/services/OfficialCopyTitleKnown_OC1_v2.1_VendorTest.pdf">Download</a>

PDF, 392KB, 34 pages

<h3><a href="../../pdfs/services/OfficialCopyTitleKnown_OC2_v2.1_VendorTest.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/OfficialCopyTitleKnownVendorTest_OC2.pdf.png"></a>
<a href="../../pdfs/services/OfficialCopyTitleKnown_OC2_v2.1_VendorTest.pdf">Vendor Test Data (Request Official Copy with Documents)</a></h3>
<a download="OfficialCopyTitleKnown_OC2_v2.1_VendorTest.pdf" href="../../pdfs/services/OfficialCopyTitleKnown_OC2_v2.1_VendorTest.pdf">Download</a>

PDF, 228KB, 13 pages