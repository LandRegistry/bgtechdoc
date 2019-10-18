## Discharge Activity

### Technical documents for software developers to integrate Discharge Activity service data into their systems.

#### Contents
- [Process flow](#process-flow)
- [Schemas](#schemas)
- [Vendor testing](#vendor-testing)

Reveals any discharges against the title from the last 30 days

### Process flow

#### Input
Request a discharge activity by sending the following parameters:

- login details
- title number
- optional charge date

The following parameters will also be necessary if there are any complications, and may be supplied to keep transaction calls and processing times to a minimum.

- continue if title is closed and continued

#### Validation
Validation diagram details the validation that the request undergoes.

<h3><a href="../../pdfs/services/DischargeActivityv1_0_Validation Diagram.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/DA_thumbnail.png"></a>
<a href="../../pdfs/services/DischargeActivityv1_0_Validation Diagram.pdf">Validation diagram</a></h3>
<a download="DischargeActivityv1_0_Validation Diagram.pdf" href="../../pdfs/services/DischargeActivityv1_0_Validation Diagram.pdf">Download</a>

PDF
<br />
#### Output
A list of entries found against the supplied title number.

### Schemas

<h3><a href="../../schemas/RequestDischargeActivityV1_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/RequestDischargeActivityV1_0.xsd">RequestDischargeActivityV1_0.xsd</a></h3>
<a download="RequestDischargeActivityV1_0.xsd" href="../../schemas/RequestDischargeActivityV1_0.xsd">Download</a>

XSD

<br/>
<h3><a href="../../schemas/ResponseDischargeActivityV1_0.xsd">
<img style="float: left; margin: 0px 5px 0px 0px" src="../../images/thumbnail/file.png"></a> 
<a href="../../schemas/ResponseDischargeActivityV1_0.xsd">ResponseDischargeActivityV1_0.xsd</a></h3>
<a download="ResponseDischargeActivityV1_0.xsd" href="../../schemas/ResponseDischargeActivityV1_0.xsd">Download</a>

XSD

<br/>

<h3><a href="../../pdfs/services/DischargeActivityv1_0_SchemaExplain.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/DA_thumbnail.png"></a>
<a href="../../pdfs/services/DischargeActivityv1_0_SchemaExplain.pdf">Schema explain</a></h3>
<a download="DischargeActivityv1_0_SchemaExplain.pdf" href="../../pdfs/services/DischargeActivityv1_0_SchemaExplain.pdf">Download</a>

PDF

#### Schema explain describes the request schema for the service.

### Vendor testing

#### Documents the data required for testing the service.

<h3><a href="../../pdfs/services/DischargeActivityv1_0_VendorTest.pdf">
<img style="float: left; margin: 0px 5px 0px 0px;  border:5px solid LightGrey;" src="../../images/thumbnail/DA_thumbnail.png"></a>
<a href="../../pdfs/services/DischargeActivityv1_0_VendorTest.pdf">Vendor Test Data</a></h3>
<a download="DischargeActivityv1_0_VendorTest.pdf" href="../../pdfs/services/DischargeActivityv1_0_VendorTest.pdf">Download</a>

PDF