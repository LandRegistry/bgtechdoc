## Search of the Index Map

### Technical documents for software developers to integrate Search the Index Map SIM service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

Provides an official search of the Index Map to confirm whether property is registered.

### Process flow

#### Input
Request a search of the index map by sending the following parameters:

- login details
- external reference number
- customer reference
- contact details
- address details
- alternative despatch details

The following parameters will also be necessary if there are any complications, and may be supplied to keep transaction calls and processing times to a minimum.

- continue if fee confirmation exceeds fee amount?
- fee expectation
- plan (of the area to search)

#### Output

Confirmation that the application has been lodged.

### Schemas

<h3><a href="../../schemas/RequestSearchOfIndexMapV2_1.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/RequestSearchOfIndexMapV2_1.xsd">RequestSearchOfIndexMapV2_1.xsd</a></h3>
<a download="RequestSearchOfIndexMapV2_1.xsd" href="../../schemas/RequestSearchOfIndexMapV2_1.xsd">Download</a>

XSD, 33KB

<br/>
<h3><a href="../../schemas/ResponseSearchOfIndexMapV2_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/ResponseSearchOfIndexMapV2_0.xsd">ResponseSearchOfIndexMapV2_0.xsd</a></h3>
<a download="ResponseSearchOfIndexMapV2_0.xsd" href="../../schemas/ResponseSearchOfIndexMapV2_0.xsd">Download</a>

XSD, 22KB

<br/>

<h3><a href="../../pdfs/services/SearchIndexMap_v2.1_SchemaExplain.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/SearchIndexMap_2.1SchemaExplain.pdf.png"></a>
<a href="../../pdfs/services/SearchIndexMap_v2.1_SchemaExplain.pdf">Schema explain</a></h3>
<a download="SearchIndexMap_v2.1_SchemaExplain.pdf" href="../../pdfs/services/SearchIndexMap_v2.1_SchemaExplain.pdf">Download</a>

PDF, 298KB, 26 pages

#### Schema explain describes the request schema for the service.

### Vendor testing

#### Documents the data required for testing the service.

<h3><a href="../../pdfs/services/SearchIndexMap_VendorTest_v1.1.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/SearchoftheIndexMap_VendorTest.pdf.png"></a>
<a href="../../pdfs/services/SearchIndexMap_VendorTest_v1.1.pdf">Vendor Test Data</a></h3>
<a download="SearchIndexMap_VendorTest_v1.1.pdf" href="../../pdfs/services/SearchIndexMap_VendorTest_v1.1.pdf">Download</a>

PDF, 181KB, 5 pages