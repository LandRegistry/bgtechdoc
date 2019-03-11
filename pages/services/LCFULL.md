## Land Charges Full Search

### Technical documents for software developers to integrate Land Charges Full Search K15 service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

Provides details of an official search of the Land Charges Register (not applicable to registered land).

### Process flow

#### Input
Request a full search by sending the following parameters:

- login details
- external reference number
- search type (private, complex names)
- contact details (reference, name, address, phone number)
- list of counties to be searched
- list of search names
- alternative despatch details

The following parameters will also be necessary if there are any complications, and may be supplied to keep transaction calls and processing times to a minimum.

- continue if fee confirmation exceeds fee amount?
- fee expectation

#### Output

The system sends a notification in the response to the CMS to confirm the request for the results. Or, the response contains the documents.

### Schemas

<h3><a href="../../schemas/RequestLandChargesFullSearchV2_1.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/RequestLandChargesFullSearchV2_1.xsd">RequestLandChargesFullSearchV2_1.xsd</a></h3>
<a download="RequestLandChargesFullSearchV2_1.xsd" href="../../schemas/RequestLandChargesFullSearchV2_1.xsd">Download</a>

XSD, 21KB

<br/>
<h3><a href="../../schemas/ResponseLandChargesFullSearchV2_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/ResponseLandChargesFullSearchV2_0.xsd">ResponseLandChargesFullSearchV2_0.xsd</a></h3>
<a download="ResponseLandChargesFullSearchV2_0.xsd" href="../../schemas/ResponseLandChargesFullSearchV2_0.xsd">Download</a>

XSD, 22KB

<br/>

<h3><a href="../../pdfs/services/LandChargesFullSearch_2.1_SchemaExplain.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/LCFullSearch_2.1_SchemaExplain.pdf.png"></a>
<a href="../../pdfs/services/LandChargesFullSearch_2.1_SchemaExplain.pdf">Schema explain</a></h3>
<a download="LandChargesFullSearch_2.1_SchemaExplain.pdf" href="../../pdfs/services/LandChargesFullSearch_2.1_SchemaExplain.pdf">Download</a>

PDF, 201KB, 22 pages

#### Schema explain describes the request schema for the service.

### Vendor testing

#### Documents the data required for testing the service.

<h3><a href="../../pdfs/services/LandChargesFullSearch_v2.1_VendorTest_v1.0.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/LandChargesFullSearchv2_0VendorTest.pdf.png"></a>
<a href="../../pdfs/services/LandChargesFullSearch_v2.1_VendorTest_v1.0.pdf">Vendor Test Data</a></h3>
<a download="LandChargesFullSearch_v2.1_VendorTest_v1.0.pdf" href="../../pdfs/services/LandChargesFullSearch_v2.1_VendorTest_v1.0.pdf">Download</a>

PDF, 276KB, 17 pages