## Application Enquiry

### Technical documents for software developers to integrate Application Enquiry service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

Reveals any pending applications that are lodged against the title.

### Process flow

#### Input
Request an application enquiry by sending the following parameters:

- login details
- external reference number
- title number

The following parameters will also be necessary if there are any complications, and may be supplied to keep transaction calls and processing times to a minimum.

- continue if title is closed and continued

#### Validation
Validation diagram details the validation that the request undergoes.

<h3><a href="../../pdfs/services/ApplicationEnquiryv1_0_Validation Diagram.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/AE_thumbnail.png"></a>
<a href="../../pdfs/services/ApplicationEnquiryv1_0_Validation Diagram.pdf">Validation diagram</a></h3>
<a download="ApplicationEnquiryv1_0_Validation Diagram.pdf" href="../../pdfs/services/ApplicationEnquiryv1_0_Validation Diagram.pdf">Download</a>

PDF
<br />
#### Output
A list of entries found against the supplied title number.

### Schemas

<h3><a href="../../schemas/RequestApplicationEnquiryV1_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/RequestApplicationEnquiryV1_0.xsd">RequestApplicationEnquiryV1_0.xsd</a></h3>
<a download="RequestApplicationEnquiryV1_0.xsd" href="../../schemas/RequestApplicationEnquiryV1_0.xsd">Download</a>

XSD

<br/>
<h3><a href="../../schemas/ResponseApplicationEnquiryV1_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/ResponseApplicationEnquiryV1_0.xsd">ResponseApplicationEnquiryV1_0.xsd</a></h3>
<a download="ResponseApplicationEnquiryV1_0.xsd" href="../../schemas/ResponseApplicationEnquiryV1_0.xsd">Download</a>

XSD

<br/>

<h3><a href="../../pdfs/services/ApplicationEnquiryv1_0_SchemaExplain.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/AE_thumbnail.png"></a>
<a href="../../pdfs/services/ApplicationEnquiryv1_0_SchemaExplain.pdf">Schema explain</a></h3>
<a download="ApplicationEnquiryv1_0_SchemaExplain.pdf" href="../../pdfs/services/ApplicationEnquiryv1_0_SchemaExplain.pdf">Download</a>

PDF

#### Schema explain describes the request schema for the service.

### Vendor testing

#### Documents the data required for testing the service.

<h3><a href="../../pdfs/services/ApplicationEnquiryv1_0_VendorTest.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/AE_thumbnail.png"></a>
<a href="../../pdfs/services/ApplicationEnquiryv1_0_VendorTest.pdf">Vendor Test Data</a></h3>
<a download="ApplicationEnquiryv1_0_VendorTest.pdf" href="../../pdfs/services/ApplicationEnquiryv1_0_VendorTest.pdf">Download</a>

PDF