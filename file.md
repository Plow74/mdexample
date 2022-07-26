<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 19%" />
<col style="width: 19%" />
<col style="width: 19%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="5"><h1 id="edition-cures-update">2015 Edition Cures Update
</h1>
<h1 id="g10">§ 170.315(g)(10)</h1>
<h1
id="standardized-api-for-patient-and-population-services">Standardized
API for patient and population services</h1></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td colspan="5">Testing Components:</td>
</tr>
<tr class="even">
<td></td>
<td><img src="./media/image1.png"
style="width:0.36458in;height:0.46042in" /></td>
<td><img src="./media/image2.png" style="width:0.4375in;height:0.4375in"
alt="Visual inspection is an acceptable method to demonstrate compliance for this criteria." /></td>
<td><img src="./media/image3.png"
style="width:0.39583in;height:0.46875in"
alt="Test tool(s) must be used to test a portion or all of the Health IT Module’s conformance. " /></td>
<td><img src="./media/image4.PNG"
style="width:0.65634in;height:0.51049in"
alt="Test data for this criteria is supplied by ONC or the test tool. " /></td>
</tr>
<tr class="odd">
<td colspan="5">Version 2.0 Updated 04-06-2022</td>
</tr>
</tbody>
</table>

Please consult the final rule entitled: *21st Century Cures Act:
Interoperability, Information Blocking, and the ONC Health IT
Certification Program* and the Interim Final Rule (IFR) *Information
Blocking and the ONC Health IT Certification Program: Extension of
Compliance Dates and Timeframes in Response to the COVID-19 Public
Health Emergency,* for associated regulations and a detailed description
of the certification criterion with which these testing steps are
associated. Developers are encouraged to consult the Certification
Companion Guide in tandem with the test procedure as these provide
clarifications that may be useful for product development and testing.

**Note:** The order in which the test steps are listed reflects the
sequence of the certification criterion and does not necessarily
prescribe the order in which the test should take place.

## Revision History

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 70%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th>Version #</th>
<th>Description of Change</th>
<th>Version Date</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1.0</td>
<td>Final Test Procedure</td>
<td>06-01-2020</td>
</tr>
<tr class="even">
<td>1.1</td>
<td>Corrected typos. Corrected internal document references in Steps 12,
13, and 19 of “Authentication and Authorization for Patient and User
Scopes.” Corrected applicable launch scenarios in Step 13 of
“Authentication and Authorization for Patient and User Scopes.” Amended
Step 10 of “Authentication and Authorization for Patient and User
Scopes” by removing non-USCDI mapped US Core IG FHIR resources.</td>
<td>08-07-2020</td>
</tr>
<tr class="odd">
<td>1.2</td>
<td>Updated compliance date, regulation text, and standard for trial use
(STU) 3 Release 3.1.1 at § 170.215(2), per the IFR, <em>Information
Blocking and the ONC Health IT Certification Program: Extension of
Compliance Dates and Timeframes in Response to the COVID-19 Public
Health Emergency</em>.</td>
<td>11-02-2020</td>
</tr>
<tr class="even">
<td>1.3</td>
<td>Added step for issuance of a refresh token to native apps that are
capable of storing a refresh token (Step 21 of “Paragraph (g)(10)(v)(A)
– Authentication and authorization for patient and user scopes”).
Removed “PractitionerRole” and “RelatedPerson” from multiple patient
services data support list (Step 8 of “Paragraph (g)(10)(i) – Data
response”).</td>
<td>12-16-2020</td>
</tr>
<tr class="odd">
<td>1.4</td>
<td>Updated test procedure step regarding “offline_access” scope,
enabling health IT developer to demonstrate either support for the
end-user to explicitly enable / disable the “offline_access” scope, or
information communicating the application’s request for the
“offline_access” scope.</td>
<td>04-02-2021</td>
</tr>
<tr class="even">
<td>1.5</td>
<td>Corrected typo in Step 5 of “Paragraph (g)(10)(v)(B) –
Authentication and authorization for system scopes” to indicate that the
“cache-control” header is sent by the application. Added step for health
IT developer to demonstrate the public location of its certified API
technology service base URLs that can be used by patients to access
their Electronic Health Information.</td>
<td>05-12-2021</td>
</tr>
<tr class="odd">
<td>1.6</td>
<td>Updated Step 13 of “Paragraph (g)(10)(v)(A) – Authentication and
authorization for patient and user scopes” to indicate that only the
“launch” parameter, in EHR-Launch mode, is tested against the “launch”
parameter provided in Step 8. Added a new Step 14 to this section to
indicate how the “aud” parameter is tested. Corrected a typo in Step 22
of this section to indicate refresh tokens are granted to native
applications capable of securing a refresh token.</td>
<td>XX-XX-2021</td>
</tr>
<tr class="even">
<td>1.7</td>
<td>Updated “Missing Data” requirements in section “<u>Data Response
Checks for Single and Multiple Patients” to clarify that health IT
developers must demonstrate that Health IT Modules support “Missing
Data” according to the US Core IG, including for non-coded and coded
data elements.</u></td>
<td>08-02-2021</td>
</tr>
<tr class="odd">
<td>1.8</td>
<td><blockquote>
<p>Updated the link for § 170.215(a)(2) FHIR® US Core Implementation
Guide STU V3.1.1</p>
</blockquote></td>
<td>11-03-21</td>
</tr>
<tr class="even">
<td>1.9</td>
<td><blockquote>
<p>Updated the Bulk Data IG references in “Standard(s) Referenced” from
“HL7® FHIR® Bulk Data Access (Flat FHIR®) (V1.0.0:STU 1)” to the
ONC-approved errata version “HL7® FHIR® Bulk Data Access (Flat FHIR®)
(V1.0.1:STU 1)” that is now effective for testing.</p>
</blockquote></td>
<td>12-08-21</td>
</tr>
<tr class="odd">
<td>2.0</td>
<td><blockquote>
<p>Updated Testing Tool and Test Tool Documentation links.</p>
</blockquote></td>
<td>04-06-2022</td>
</tr>
</tbody>
</table>

## Regulation Text

> § 170.315 (g)(10) *Standardized API for patient and population
> services*.

The following technical outcomes and conditions must be met through the
demonstration of application programming interface technology.

1)  *Data response*.

    1.  Respond to requests for a single patient’s data according to the
        standard adopted in § 170.215(a)(1) and implementation
        specification adopted at § 170.215(a)(2), including the
        mandatory capabilities described in “US Core Server
        CapabilityStatement,” for each of the data included in the
        standard adopted in § 170.213. All data elements indicated as
        “mandatory” and “must support” by the standards and
        implementation specifications must be supported.

    2.  Respond to requests for multiple patients’ data as a group
        according to the standard adopted in § 170.215(a)(1) and
        implementation specifications adopted at § 170.215(a)(2) and
        (a)(4), for each of the data included in the standard adopted in
        § 170.213. All data elements indicated as “mandatory” and “must
        support” by the standards and implementation specifications must
        be supported.

2)  *Supported search operations*.

    1.  Respond to search requests for a single patient’s data
        consistent with the search criteria included in the
        implementation specification adopted in § 170.215(a)(2),
        specifically the mandatory capabilities described in “US Core
        Server CapabilityStatement”.

    2.  Respond to search requests for multiple patients’ data
        consistent with the search criteria included in the
        implementation specification adopted in § 170.215(a)(4).

3)  *Application registration*. Enable an application to register with
    > the Health IT Module’s “authorization server.”

4)  *Secure connection*.

    1.  Establish a secure and trusted connection with an application
        that requests data for patient and user scopes in accordance
        with the implementation specifications adopted in §
        170.215(a)(2) and (3).

    2.  Establish a secure and trusted connection with an application
        that requests data for system scopes in accordance with the
        implementation specification adopted in § 170.215(a)(4).

5)  *Authentication and authorization.*

    1.  *Authentication and authorization for patient and user scopes.*

        1.  *First time connections.*

            1.  Authentication and authorization must occur during the
                process of granting access to patient data in accordance
                with the implementation specification adopted in §
                170.215(a)(3) and standard adopted in § 170.215(b).

            2.  A Health IT Module’s authorization server must issue a
                refresh token valid for a period of no less than three
                months to applications capable of storing a client
                secret.

            3.  A Health IT Module’s authorization server must issue a
                refresh token for a period of no less than three months
                to native applications capable of securing a refresh
                token.

        2.  *Subsequent connections*.

            1.  Access must be granted to patient data in accordance
                with the implementation specification adopted in §
                170.215(a)(3) without requiring re-authorization and
                re-authentication when a valid refresh token is supplied
                by the application.

            2.  A Health IT Module’s authorization server must issue a
                refresh token valid for a new period of no less than
                three months to applications capable of storing a client
                secret.

    2.  *Authentication and authorization for system scopes.*
        Authentication and authorization must occur during the process
        of granting an application access to patient data in accordance
        with the “SMART Backend Services: Authorization Guide” section
        of the implementation specification adopted in § 170.215(a)(4)
        and the application must be issued a valid access token.

6)  *Patient authorization revocation.* A Health IT Module’s
    > authorization server must be able to revoke an authorized
    > application’s access at a patient’s direction.

7)  *Token introspection.* A Health IT Module’s authorization server
    must be able to receive and validate tokens it has issued.

8)  *Documentation*.

    1.  The API(s) must include complete accompanying documentation that
        > contains, at a minimum:

        1.  API syntax, function names, required and optional parameters
            > supported and their data types, return variables and their
            > types/structures, exceptions and exception handling
            > methods and their returns.

        2.  The software components and configurations that would be
            > necessary for an application to implement in order to be
            > able to successfully interact with the API and process its
            > response(s).

        3.  All applicable technical requirements and attributes
            > necessary for an application to be registered with a
            > Health IT Module’s authorization server.

    2.  The documentation used to meet paragraph (g)(10)(viii)(A) of
        > this section must be available via a publicly accessible
        > hyperlink without any preconditions or additional steps.

## **Standard(s) Referenced**

Paragraph (g)(10)(i)(A)

§ 170.215(a)(1) [Health Level 7 (HL7®) Version 4.0.1 Fast Healthcare
Interoperability Resources Specification (FHIR®) Release 4, October 30,
2019](http://hl7.org/fhir/directory.html)

> § 170.215(a)(2) [FHIR® US Core Implementation Guide STU
> V3.1.1](http://hl7.org/fhir/us/core/STU3.1.1/)

§ 170.213 [United States Core Data for Interoperability
(USCDI)](https://www.healthit.gov/isa/us-core-data-interoperability-uscdi)

Paragraph (g)(10)(i)(B)

§ 170.215(a)(1) [*HL7® Version 4.0.1 FHIR® Release 4, October 30,
2019*](http://hl7.org/fhir/directory.html)

> § 170.215(a)(2) [FHIR® US Core Implementation Guide STU
> V3.1.1](http://hl7.org/fhir/us/core/STU3.1.1/)

§ 170.213
[USCDI](https://www.healthit.gov/isa/us-core-data-interoperability-uscdi)

§ 170.215(a)(4) [[HL7® FHIR® Bulk Data Access (Flat FHIR®) (V1.0.1:STU
1)](https://hl7.org/fhir/uv/bulkdata/STU1.0.1/)](https://hl7.org/fhir/uv/bulkdata/STU1.0.1/)

Paragraph (g)(10)(ii)(A)

§ 170.215(a)(2) [FHIR® US Core Implementation Guide STU
V3.1.1](http://hl7.org/fhir/us/core/STU3.1.1/)

Paragraph (g)(10)(ii)(B)

§ 170.215(a)(4) [HL7® FHIR® Bulk Data Access (Flat FHIR®) (V1.0.1:STU
1)](https://hl7.org/fhir/uv/bulkdata/STU1.0.1/)

Paragraph (g)(10)(iii)

None

Paragraph (g)(10)(iv)(A)

> § 170.215(a)(2) [FHIR® US Core Implementation Guide STU
> V3.1.1](http://hl7.org/fhir/us/core/STU3.1.1/)

§ 170.215(a)(3) HL7® [SMART Application Launch Framework Implementation
Guide Release 1.0.0](https://hl7.org/fhir/smart-app-launch/1.0.0/)

Paragraph (g)(10)(iv)(B)

§ 170.215(a)(4) [[HL7® FHIR® Bulk Data Access (Flat FHIR®) (V1.0.1:STU
1)](https://hl7.org/fhir/uv/bulkdata/STU1.0.1/)](https://hl7.org/fhir/uv/bulkdata/STU1.0.1/)

Paragraph (g)(10)(v)(A)(1)

> § 170.215(a)(3) HL7® [SMART Application Launch Framework
> Implementation Guide Release
> 1.0.0](https://hl7.org/fhir/smart-app-launch/1.0.0/)
>
> § 170.215(b) [OpenID Connect Core 1.0 incorporating errata set
> 1](https://openid.net/specs/openid-connect-core-1_0.html)

Paragraph (g)(10)(v)(A)(2)

> § 170.215(a)(3) HL7® [SMART Application Launch Framework
> Implementation Guide Release
> 1.0.0](https://hl7.org/fhir/smart-app-launch/1.0.0/)

Paragraph (g)(10)(v)(B)

§ 170.215(a)(4) [[HL7® FHIR® Bulk Data Access (Flat FHIR®) (V1.0.1:STU
1)](https://hl7.org/fhir/uv/bulkdata/STU1.0.1/)](https://hl7.org/fhir/uv/bulkdata/STU1.0.1/)

Paragraph (g)(10)(vi)

None

Paragraph (g)(10)(vii)

None

Paragraph (g)(10)(viii)

None

## **Required Tests**

> Paragraph (g)(10)(iii) – Application registration

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Application Registration</u></strong></p>
<ol type="1">
<li><p>The health IT developer demonstrates the Health IT Module
supports application registration with an authorization server for the
purposes of Electronic Health Information (EHI) access for single
patients, including support for application registration functions to
enable authentication and authorization in § 170.315(g)(10)(v).</p></li>
<li><p>The health IT developer demonstrates the Health IT Module
supports application registration with an authorization server for the
purposes of EHI access for multiple patients including support for
application registration functions to enable authentication and
authorization in § 170.315(g)(10)(v).</p></li>
</ol></td>
<td><p><strong><u>Application Registration</u></strong></p>
<ol type="1">
<li><p>The tester verifies the Health IT Module supports application
registration with an authorization server for the purposes of EHI access
for single patients, including support for application registration
functions to enable authentication and authorization in §
170.315(g)(10)(v).</p></li>
<li><p>The tester verifies the Health IT Module supports application
registration with an authorization server for the purposes of EHI access
for multiple patients including support for application registration
functions to enable authentication and authorization in §
170.315(g)(10)(v).</p></li>
</ol></td>
</tr>
</tbody>
</table>

Paragraph (g)(10)(iv) – Secure connection

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Secure Connection</u></strong></p>
<ol type="1">
<li><p>For all transmissions between the Health IT Module and the
application, the health IT developer demonstrates the use of a secure
and trusted connection in accordance with the implementation
specifications adopted in § 170.215(a)(2) and § 170.215(a)(3),
including:</p></li>
</ol>
<ul>
<li><p>Using TLS version 1.2 or higher; and</p></li>
<li><p>Conformance to FHIR Communications Security
requirements.</p></li>
</ul></td>
<td><p><strong><u>Secure Connection</u></strong></p>
<ol type="1">
<li><p>For all transmissions between the Health IT Module and the
application, the tester verifies the use of a secure and trusted
connection in accordance with the implementation specifications adopted
in § 170.215(a)(2) and § 170.215(a)(3), including:</p></li>
</ol>
<ul>
<li><p>Using TLS version 1.2 or higher; and</p></li>
<li><p>Conformance to FHIR Communications Security
requirements.</p></li>
</ul></td>
</tr>
</tbody>
</table>

> Paragraph (g)(10)(v)(A) – Authentication and authorization for patient
> and user scopes

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Authentication and Authorization for Patient and User
Scopes</u></strong></p>
<ol type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support the following for “EHR-Launch,” “Standalone-Launch,”
and “Both” (“EHR-Launch” and “Standalone-Launch”) as specified in the
implementation specification adopted in § 170.215(a)(3).</p></li>
<li><p>[EHR-Launch] The health IT developer demonstrates the ability of
the Health IT Module to initiate a “launch sequence” using the
“launch-ehr" “SMART on FHIR Core Capability” SMART EHR Launch mode
detailed in the implementation specification adopted in § 170.215(a)(3),
including:</p></li>
</ol>
<ul>
<li><p>Launching the registered launch URL of the application;
and</p></li>
<li><p>Passing the parameters: “iss” and “launch”.</p></li>
</ul>
<ol start="3" type="1">
<li><p>[Standalone-Launch] The health IT developer demonstrates the
ability of the Health IT Module to launch using the “launch-standalone"
“SMART on FHIR Core Capability” SMART Standalone Launch mode detailed in
the implementation specification adopted in § 170.215(a)(3).</p></li>
<li><p>[Standalone-Launch] The health IT developer demonstrates the
ability of the Health IT Module to support SMART’s public client
profile.</p></li>
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to support the following as detailed in the
implementation specification adopted in § 170.215(a)(3) and standard
adopted in § 170.215(a)(1):</p></li>
</ol>
<ul>
<li><p>The “.well-known/smart-configuration.json” path; and</p></li>
<li><p>A FHIR “CapabilityStatement”.</p></li>
</ul>
<ol start="6" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
“.well-known/smart-configuration.json” path to support at least the
following as detailed in the implementation specification adopted in §
170.215(a)(3):</p></li>
</ol>
<ul>
<li><p>“authorization_endpoint”;</p></li>
<li><p>“token_endpoint”; and</p></li>
<li><p>“capabilities” (including support for all the “SMART on FHIR Core
Capabilities”).</p></li>
</ul>
<ol start="7" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
FHIR “CapabilityStatement” to support at least the following components
as detailed in the implementation specification adopted in §
170.215(a)(3) and standard adopted in § 170.215(a)(1),
including:</p></li>
</ol>
<ul>
<li><p>“authorize”; and</p></li>
<li><p>“token”.</p></li>
</ul>
<ol start="8" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to receive an authorization request according to the
implementation specification adopted in § 170.215(a)(3), including
support for the following parameters:</p></li>
</ol>
<ul>
<li><p>“response_type”;</p></li>
<li><p>“client_id”;</p></li>
<li><p>“redirect_uri”;</p></li>
<li><p>“launch” (for EHR-Launch mode only);</p></li>
<li><p>“scope”;</p></li>
<li><p>“state”; and</p></li>
<li><p>“aud”.</p></li>
</ul>
<ol start="9" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to support the receipt of the following scopes and
capabilities according to the implementation specification adopted in §
170.215(a)(3) and standard adopted in § 170.215(b):</p></li>
</ol>
<ul>
<li><p>“openid” (to support “sso-openid-connect” “SMART on FHIR Core
Capability”);</p></li>
<li><p>“fhirUser” (to support “sso-openid-connect” “SMART on FHIR Core
Capability”);</p></li>
<li><p>“need_patient_banner” (to support “context-banner” “SMART on FHIR
Core Capability” for EHR-Launch mode only);</p></li>
<li><p>“smart_style_url” (to support “context-style” “SMART on FHIR Core
Capability” for EHR-Launch mode only);</p></li>
<li><p>“launch/patient” (to support “context-standalone-patient” “SMART
on FHIR Core Capability” for Standalone-Launch mode only);</p></li>
<li><p>“launch” (for EHR-Launch mode only);</p></li>
<li><p>“offline_access” (to support “permission-offline” “SMART on FHIR
Core Capability”);</p></li>
<li><p>Patient-level scopes (to support “permission-patient” “SMART on
FHIR Core Capability”); and</p></li>
<li><p>User-level scopes (to support “permission-user” “SMART on FHIR
Core Capability”).</p></li>
</ul>
<ol start="10" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to evaluate the authorization request and request
end-user input, if applicable (required for patient-facing
applications), including the ability for the end-user to authorize an
application to receive EHI based on FHIR resource-level scopes for all
of the FHIR resources associated with the profiles specified in the
standard adopted in § 170.213 and implementation specification adopted
in § 170.215(a)(2), including:</p></li>
</ol>
<ul>
<li><p>“AllergyIntolerance”;</p></li>
<li><p>“CarePlan”;</p></li>
<li><p>“CareTeam”;</p></li>
<li><p>“Condition”;</p></li>
<li><p>“Device”;</p></li>
<li><p>“DiagnosticReport”;</p></li>
<li><p>“DocumentReference”;</p></li>
<li><p>“Goal”;</p></li>
<li><p>“Immunization”;</p></li>
<li><p>“Medication” (if supported);</p></li>
<li><p>“MedicationRequest”;</p></li>
<li><p>“Observation”;</p></li>
<li><p>“Patient”;</p></li>
<li><p>“Procedure”; and</p></li>
<li><p>“Provenance”.</p></li>
</ul>
<ol start="11" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to evaluate the authorization request and request
end-user input, if applicable (required for patient-facing
applications), including either the ability for the end-user to
explicitly enable / disable the “offline_access” scope or information
communicating the application’s request for the “offline_access”
scope.</p></li>
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to deny an application’s authorization request
according to a patient’s preferences selected in steps 10 and 11 of this
section in accordance with the implementation specification adopted in §
170.215(a)(3).</p></li>
<li><p>[EHR-Launch] The health IT developer demonstrates the ability of
the Health IT Module to return an error response if the “launch”
parameter provided by an application to the Health IT Module in step 8
of this section does not match the “launch” parameter originally
provided to an application by the Health IT Module in step 2 of this
section according to the implementation specification adopted in §
170.215(a)(3).</p></li>
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to return an error response if the "aud" parameter
provided by an application to the Health IT Module in Step 8 is not a
valid FHIR resource server associated with the Health IT Module's
authorization server.</p></li>
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to grant an application access to EHI by returning an
authorization code to the application according to the implementation
specification adopted in § 170.215(a)(3), including the following
parameters:</p></li>
</ol>
<ul>
<li><p>“code”; and</p></li>
<li><p>“state”.</p></li>
</ul>
<ol start="16" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to receive the following parameters from an application
according to the implementation specification adopted in §
170.215(a)(3):</p></li>
</ol>
<ul>
<li><p>“grant_type”;</p></li>
<li><p>“code”;</p></li>
<li><p>“redirect_uri”;</p></li>
<li><p>“client_id”; and</p></li>
<li><p>Authorization header including “client_id” and
“client_secret”.</p></li>
</ul>
<ol start="17" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to return a JSON object to applications according to
the implementation specification adopted in § 170.215(a)(3) and standard
adopted in § 170.215(b), including the following:</p></li>
</ol>
<ul>
<li><p>“access_token”;</p></li>
<li><p>“token_type”;</p></li>
<li><p>“scope”;</p></li>
<li><p>“id_token”;</p></li>
<li><p>“refresh_token” (valid for a period of no shorter than three
months);</p></li>
<li><p>HTTP “Cache-Control” response header field with a value of
“no-store”;</p></li>
<li><p>HTTP “Pragma” response header field with a value of
“no-cache”;</p></li>
<li><p>“patient” (to support “context-ehr-patient” and
“context-standalone-patient” “SMART on FHIR Core
Capabilities”);</p></li>
<li><p>“need_patient_banner” (to support “context-banner” “SMART on FHIR
Core Capability” for EHR-Launch mode only); and</p></li>
<li><p>“smart_style_url” (to support “context-style” “SMART on FHIR Core
Capability” for EHR-Launch mode only).</p></li>
</ul>
<ol start="18" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to provide an OpenID Connect well-known URI in
accordance with the implementation specification adopted in §
170.215(b), including:</p></li>
</ol>
<ul>
<li><p>All required fields populated according to implementation
specification adopted in § 170.215(b); and</p></li>
<li><p>Valid JWKS populated according to implementation specification
can be retrieved via JWKS URI.</p></li>
</ul>
<ol start="19" type="1">
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to deny an application’s authorization request in
accordance with the implementation specification adopted in §
170.215(a)(3).</p></li>
<li><p>[Standalone-Launch] The health IT developer demonstrates the
ability of the Health IT Module to return a “Patient” FHIR resource that
matches the patient context provided in step 9 of this section according
to the implementation specification adopted in § 170.215(a)(2).</p></li>
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to grant an access token when a refresh token is
supplied according to the implementation specification adopted in §
170.215(a)(2).</p></li>
<li><p>[Both] The health IT developer demonstrates the ability of the
Health IT Module to grant a refresh token valid for a period of no less
than three months to native applications capable of securing a refresh
token.</p></li>
</ol>
<p><strong><u>Subsequent Connections: Authentication and Authorization
for Patient and User Scopes</u></strong></p>
<ol start="23" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to issue a refresh token valid for a new period of no shorter
than three months without requiring re-authentication and
re-authorization when a valid refresh token is supplied by the
application according to the implementation specification adopted in §
170.215(a)(3).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to return an error response when supplied an invalid refresh
token as specified in the implementation specification adopted in §
170.215(a)(3).</p></li>
</ol></td>
<td><p><strong><u>Authentication and Authorization for Patient and User
Scopes</u></strong></p>
<ol type="1">
<li><p>The tester verifies the ability of the Health IT Module to
support the following for “EHR-Launch,” “Standalone-Launch,” and “Both”
(“EHR-Launch” and “Standalone-Launch”) as specified in the
implementation specification adopted in § 170.215(a)(3).</p></li>
<li><p>[EHR-Launch] The tester verifies the ability of the Health IT
Module to initiate a “launch sequence” using the “launch-ehr" “SMART on
FHIR Core Capability” SMART EHR Launch mode detailed in the
implementation specification adopted in § 170.215(a)(3),
including:</p></li>
</ol>
<ul>
<li><p>Launching the registered launch URL of the application;
and</p></li>
<li><p>Passing the parameters: “iss” and “launch”.</p></li>
</ul>
<ol start="3" type="1">
<li><p>[Standalone-Launch] The tester verifies the ability of the Health
IT Module to launch using the “launch-standalone" “SMART on FHIR Core
Capability” SMART Standalone Launch mode detailed in the implementation
specification adopted in § 170.215(a)(3).</p></li>
<li><p>[Standalone-Launch] The tester verifies the ability of the Health
IT Module to support SMART’s public client profile.</p></li>
<li><p>[Both] The tester verifies the ability of the Health IT Module to
support the following as detailed in the implementation specification
adopted in § 170.215(a)(3) and standard adopted in §
170.215(a)(1):</p></li>
</ol>
<ul>
<li><p>The “.well-known/smart-configuration.json” path; and</p></li>
<li><p>A FHIR “CapabilityStatement”.</p></li>
</ul>
<ol start="6" type="1">
<li><p>[Both] The tester verifies the ability of the
“.well-known/smart-configuration.json” path to support at least the
following as detailed in the implementation specification adopted in §
170.215(a)(3):</p></li>
</ol>
<ul>
<li><p>“authorization_endpoint”;</p></li>
<li><p>“token_endpoint”; and</p></li>
<li><p>“capabilities” (including support for all the “SMART on FHIR Core
Capabilities”).</p></li>
</ul>
<ol start="7" type="1">
<li><p>[Both] The tester verifies the ability of the FHIR
“CapabilityStatement” to support at least the following components as
detailed in the implementation specification adopted in § 170.215(a)(3)
and standard adopted in § 170.215(a)(1), including:</p></li>
</ol>
<ul>
<li><p>“authorize”; and</p></li>
<li><p>“token”.</p></li>
</ul>
<ol start="8" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
receive an authorization request according to the implementation
specification adopted in § 170.215(a)(3), including support for the
following parameters:</p></li>
</ol>
<ul>
<li><p>“response_type”;</p></li>
<li><p>“client_id”;</p></li>
<li><p>“redirect_uri”;</p></li>
<li><p>“launch” (for EHR-Launch mode only);</p></li>
<li><p>“scope”;</p></li>
<li><p>“state”; and</p></li>
<li><p>“aud”.</p></li>
</ul>
<ol start="9" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
support the receipt of the following scopes according to the
implementation specification adopted in § 170.215(a)(3) and standard
adopted in § 170.215(b):</p></li>
</ol>
<ul>
<li><p>“openid” (to support “sso-openid-connect” “SMART on FHIR Core
Capability”);</p></li>
<li><p>“fhirUser” (to support “sso-openid-connect” “SMART on FHIR Core
Capability”);</p></li>
<li><p>“need_patient_banner” (to support “context-banner” “SMART on FHIR
Core Capability” for EHR-Launch mode only);</p></li>
<li><p>“smart_style_url” (to support “context-style” “SMART on FHIR Core
Capability” for EHR-Launch mode only);</p></li>
<li><p>“launch/patient” (to support “context-standalone-patient” “SMART
on FHIR Core Capability” for Standalone-Launch mode only);</p></li>
<li><p>“launch” (for EHR-Launch mode only);</p></li>
<li><p>“offline_access” (to support “permission-offline” “SMART on FHIR
Core Capability”);</p></li>
<li><p>Patient-level scopes (to support “permission-patient” “SMART on
FHIR Core Capability”); and</p></li>
<li><p>User-level scopes (to support “permission-user” “SMART on FHIR
Core Capability”).</p></li>
</ul>
<ol start="10" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
evaluate the authorization request and request end-user input, if
applicable (required for patient-facing applications), including the
ability for the end-user to authorize an application to receive EHI
based on FHIR resource-level scopes for all of the FHIR resources
associated with the profiles specified in the standard adopted in
§ 170.213 and implementation specification adopted in § 170.215(a)(2),
including:</p></li>
</ol>
<ul>
<li><p>“AllergyIntolerance”;</p></li>
<li><p>“CarePlan”;</p></li>
<li><p>“CareTeam”;</p></li>
<li><p>“Condition”;</p></li>
<li><p>“Device”;</p></li>
<li><p>“DiagnosticReport”;</p></li>
<li><p>“DocumentReference”;</p></li>
<li><p>“Goal”;</p></li>
<li><p>“Immunization”;</p></li>
<li><p>“Medication” (if supported);</p></li>
<li><p>“MedicationRequest”;</p></li>
<li><p>“Observation”;</p></li>
<li><p>“Patient”;</p></li>
<li><p>“Procedure”; and</p></li>
<li><p>“Provenance”.</p></li>
</ul>
<ol start="11" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
evaluate the authorization request and request end-user input, if
applicable (required for patient-facing applications), including either
the ability for the end-user to explicitly enable / disable the
“offline_access” scope or information communicating the application’s
request for the “offline_access” scope.</p></li>
<li><p>[Both] The tester verifies the ability of the Health IT Module to
deny an application’s authorization request according to a patient’s
preferences selected in steps 10 and 11 of this section in accordance
with the implementation specification adopted in §
170.215(a)(3).</p></li>
<li><p>[EHR-Launch] The tester verifies the ability of the Health IT
Module to return an error response if the “launch” parameter provided by
an application to the Health IT Module in step 8 of this section does
not match the “launch” parameter originally provided to an application
by the Health IT Module in step 2 of this section according to the
implementation specification adopted in § 170.215(a)(3).</p></li>
<li><p>[Both] The tester verifies the ability of the Health IT Module to
return an error response if the "aud" parameter provided by an
application to the Health IT Module in Step 8 is not a valid FHIR
resource server associated with the Health IT Module's authorization
server.</p></li>
<li><p>[Both] The tester verifies the ability of the Health IT Module to
grant an application access to EHI by returning an authorization code to
the application according to the implementation specification adopted in
§ 170.215(a)(3), including the following parameters:</p></li>
</ol>
<ul>
<li><p>“code”; and</p></li>
<li><p>“state”.</p></li>
</ul>
<ol start="16" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
receive the following parameters from an application according to the
implementation specification adopted in § 170.215(a)(3):</p></li>
</ol>
<ul>
<li><p>“grant_type”;</p></li>
<li><p>“code”;</p></li>
<li><p>“redirect_uri”;</p></li>
<li><p>“client_id”; and</p></li>
<li><p>Authorization header including “client_id” and
“client_secret”.</p></li>
</ul>
<ol start="17" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
return a JSON object to applications according to the implementation
specification adopted in § 170.215(a)(3) and standard adopted in §
170.215(b), including the following:</p></li>
</ol>
<ul>
<li><p>“access_token”;</p></li>
<li><p>“token_type”;</p></li>
<li><p>“scope”;</p></li>
<li><p>“id_token”;</p></li>
<li><p>“refresh_token” (valid for a period of no shorter than three
months);</p></li>
<li><p>HTTP “Cache-Control” response header field with a value of
“no-store”;</p></li>
<li><p>HTTP “Pragma” response header field with a value of
“no-cache”;</p></li>
<li><p>“patient” (to support “context-ehr-patient” and
“context-standalone-patient” “SMART on FHIR Core
Capabilities”);</p></li>
<li><p>“need_patient_banner” (to support “context-banner” “SMART on FHIR
Core Capability” for EHR-Launch mode only); and</p></li>
<li><p>“smart_style_url” (to support “context-style” “SMART on FHIR Core
Capability” for EHR-Launch mode only).</p></li>
</ul>
<ol start="18" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
provide an OpenID Connect well-known URI in accordance with the
implementation specification adopted in § 170.215(b),
including:</p></li>
</ol>
<ul>
<li><p>All required fields populated according to implementation
specification adopted in § 170.215(b); and</p></li>
<li><p>Valid JWKS populated according to implementation specification
can be retrieved via JWKS URI.</p></li>
</ul>
<ol start="19" type="1">
<li><p>[Both] The tester verifies the ability of the Health IT Module to
deny an application’s authorization request in accordance with the
implementation specification adopted in § 170.215(a)(3).</p></li>
<li><p>[Standalone-Launch] The tester verifies the ability of the Health
IT Module to return a “Patient” FHIR resource that matches the patient
context provided in step 9 of this section according to the
implementation specification adopted in § 170.215(a)(2).</p></li>
<li><p>[Both] The tester verifies the ability of the Health IT Module to
grant an access token when a refresh token is supplied according to the
implementation specification adopted in § 170.215(a)(2).</p></li>
<li><p>[Both] The tester verifies the ability of the Health IT Module to
grant a refresh token valid for a period of no less than three months to
native applications capable of securing a refresh token.</p></li>
</ol>
<p><strong><u>Subsequent Connections: Authentication and Authorization
for Patient and User Scopes</u></strong></p>
<ol start="23" type="1">
<li><p>The tester verifies the ability of the Health IT Module to issue
a refresh token valid for a new period of no shorter than three months
without requiring re-authentication and re-authorization when a valid
refresh token is supplied by the application according to the
implementation specification adopted in § 170.215(a)(3).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to return
an error response when supplied an invalid refresh token as specified in
the implementation specification adopted in § 170.215(a)(3).</p></li>
</ol></td>
</tr>
</tbody>
</table>

> Paragraph (g)(10)(vi) – Patient authorization revocation

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Patient Authorization Revocation</u></strong></p>
<ol type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to revoke access to an authorized application at a patient’s
direction, including a demonstration of the inability of the application
with revoked access to receive patient EHI.</p></li>
</ol></td>
<td><p><strong><u>Patient Authorization Revocation</u></strong></p>
<ol type="1">
<li><p>The tester verifies the ability of the Health IT Module to revoke
access to an authorized application at a patient’s direction, including
a demonstration of the inability of the application with revoked access
to receive patient EHI.</p></li>
</ol></td>
</tr>
</tbody>
</table>

Paragraph (g)(10)(v)(B) – Authentication and authorization for system
scopes

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Authentication and Authorization for System
Scopes</u></strong></p>
<ol type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support OAuth 2.0 client credentials grant flow in accordance
with the implementation specification adopted in §
170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support the following parameters according to the
implementation specification adopted in § 170.215(a)(4):</p></li>
</ol>
<ul>
<li><p>“scope”;</p></li>
<li><p>“grant_type”;</p></li>
<li><p>“client_assertion_type”; and</p></li>
<li><p>“client_assertion”.</p></li>
</ul>
<ol start="3" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support the following JSON Web Token (JWT) Headers and Claims
according to the implementation specification adopted in §
170.215(a)(4):</p></li>
</ol>
<ul>
<li><p>“alg” header;</p></li>
<li><p>“kid” header;</p></li>
<li><p>“typ” header;</p></li>
<li><p>“iss” claim;</p></li>
<li><p>“sub” claim;</p></li>
<li><p>“aud” claim;</p></li>
<li><p>“exp” claim; and</p></li>
<li><p>“jti” claim.</p></li>
</ul>
<ol start="4" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to receive and process the JSON Web Key (JWK) Set via a
TLS-protected URL to support authorization for system scopes in §
170.315(g)(10)(v)(B).</p></li>
<li><p>The health IT developer demonstrates that the Health IT Module
does not cache a JWK Set received via a TLS-protected URL for longer
than the “cache-control” header sent by an application
indicates.</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to validate an application’s JWT, including its JSON Web
Signatures, according to the implementation specification adopted in §
170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to respond with an “invalid_client” error for errors encountered
during the authentication process according to the implementation
specification adopted in § 170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to assure the scope granted based on the scope requested by an
application is no greater than the pre-authorized scope for multiple
patients according to the implementation specification adopted in §
170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to issue an access token to an application as a JSON object in
accordance with the implementation specification adopted in §
170.215(a)(4), including the following property names:</p></li>
</ol>
<ul>
<li><p>“access_token”;</p></li>
<li><p>“token_type”;</p></li>
<li><p>“expires_in”; and</p></li>
<li><p>“scope”.</p></li>
</ul>
<ol start="10" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to respond to errors using the appropriate error messages as
specified in the implementation specification adopted in §
170.215(a)(4).</p></li>
</ol></td>
<td><p><strong><u>Authentication and Authorization for System
Scopes</u></strong></p>
<ol type="1">
<li><p>The tester verifies the ability of the Health IT Module to
support OAuth 2.0 client credentials grant flow in accordance with the
implementation specification adopted in § 170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support the following parameters according to the implementation
specification adopted in § 170.215(a)(4):</p></li>
</ol>
<ul>
<li><p>“scope”;</p></li>
<li><p>“grant_type”;</p></li>
<li><p>“client_assertion_type”; and</p></li>
<li><p>“client_assertion”.</p></li>
</ul>
<ol start="3" type="1">
<li><p>The tester verifies the ability of the Health IT Module to
support the following JSON Web Token (JWT) Headers and Claims according
to the implementation specification adopted in § 170.215(a)(4):</p></li>
</ol>
<ul>
<li><p>“alg” header;</p></li>
<li><p>“kid” header;</p></li>
<li><p>“typ” header;</p></li>
<li><p>“iss” claim;</p></li>
<li><p>“sub” claim;</p></li>
<li><p>“aud” claim;</p></li>
<li><p>“exp” claim; and</p></li>
<li><p>“jti” claim.</p></li>
</ul>
<ol start="4" type="1">
<li><p>The tester verifies the ability of the Health IT Module to
receive and process the JWK structure via a TLS-protected URL to support
authorization for system scopes in § 170.315(g)(10)(v)(B).</p></li>
<li><p>The tester verifies that the Health IT Module does not cache a
JWK Set received via a TLS-protected URL for longer than the
“cache-control” header sent by an application indicates.</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
validate an application’s JWT, including its JSON Web Signatures,
according to the implementation specification adopted in §
170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
respond with an “invalid_client” error for errors encountered during the
authentication process according to the implementation specification
adopted in § 170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to assure
the scope granted based on the scope requested by an application is no
greater than the pre-authorized scope for multiple patients according to
the implementation specification adopted in § 170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to issue
an access token to an application as a JSON object in accordance with
the implementation specification adopted in § 170.215(a)(4), including
the following property names:</p></li>
</ol>
<ul>
<li><p>“access_token”;</p></li>
<li><p>“token_type”;</p></li>
<li><p>“expires_in”; and</p></li>
<li><p>“scope”.</p></li>
</ul>
<ol start="10" type="1">
<li><p>The tester verifies the ability of the Health IT Module to
respond to errors using the appropriate error messages as specified in
the implementation specification adopted in § 170.215(a)(4).</p></li>
</ol></td>
</tr>
</tbody>
</table>

> Paragraph (g)(10)(vii) – Token introspection

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Token Introspection</u></strong></p>
<ol type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to receive and validate a token it has issued.</p></li>
</ol></td>
<td><p><strong><u>Token Introspection</u></strong></p>
<ol type="1">
<li><p>The tester verifies the ability of the Health IT Module to
receive and validate a token it has issued.</p></li>
</ol></td>
</tr>
</tbody>
</table>

## 

> Paragraph (g)(10)(ii) – Supported search operations

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Supported Search Operations for a Single Patient’s
Data</u></strong></p>
<ol type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support the “capabilities” interaction as specified in the
standard adopted in § 170.215(a)(1), including support for a
“CapabilityStatement” as specified in the standard adopted in §
170.215(a)(1) and implementation specification adopted in §
170.215(a)(2).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to respond to requests for a single patient’s data consistent
with the search criteria detailed in the “US Core Server
CapabilityStatement” section of the implementation specification adopted
in § 170.215(a)(2), including demonstrating search support for “SHALL”
operations and parameters for all the data included in the standard
adopted in § 170.213.</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a resource search for the provenance target
“(_revIncludes: Provenance:target)” for all the FHIR resources included
in the standard adopted in § 170.213 and implementation specification
adopted in § 170.215(a)(2) according to the “Basic Provenance Guidance”
section of the implementation specification adopted in §
170.215(a)(2).</p></li>
</ol>
<p><strong><u>Supported Search Operations for Multiple Patients’
Data</u></strong></p>
<ol start="4" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support the “capabilities” interaction as specified in the
standard adopted in § 170.215(a)(1), including support for a
“CapabilityStatement” as specified in the standard adopted in §
170.215(a)(1) and implementation specification adopted in §
170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support requests for multiple patients’ data as a group using
the “group-export” operation as detailed in the implementation
specification adopted in § 170.215(a)(4).</p></li>
</ol></td>
<td><p><strong><u>Supported Search Operations for a Single Patient’s
Data</u></strong></p>
<ol type="1">
<li><p>The tester verifies the ability of the Health IT Module to
support the “capabilities” interaction as specified in the standard
adopted in § 170.215(a)(1), including support for a
“CapabilityStatement” as specified in the standard adopted in §
170.215(a)(1) and implementation specification adopted in §
170.215(a)(2).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
respond to requests for a single patient’s data consistent with the
search criteria detailed in the “US Core Server CapabilityStatement”
section of the implementation specification adopted in § 170.215(a)(2),
including demonstrating search support for “SHALL” operations and
parameters for all the data included in the standard adopted in §
170.213.</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support a resource search for the provenance target “(_revIncludes:
Provenance:target)” for all the FHIR resources included in the standard
adopted in § 170.213 and implementation specification adopted in §
170.215(a)(2) according to the “Basic Provenance Guidance” section of
the implementation specification adopted in § 170.215(a)(2).</p></li>
</ol>
<p><strong><u>Supported Search Operations for Multiple Patients’
Data</u></strong></p>
<ol start="4" type="1">
<li><p>The tester verifies the ability of the Health IT Module to
support the “capabilities” interaction as specified in the standard
adopted in § 170.215(a)(1), including support for a
“CapabilityStatement” as specified in the standard adopted in §
170.215(a)(1) and implementation specification adopted in §
170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support requests for multiple patients’ data as a group using the
“group-export” operation as detailed in the implementation specification
adopted in § 170.215(a)(4).</p></li>
</ol></td>
</tr>
</tbody>
</table>

## 

Paragraph (g)(10)(i) – Data response

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>Data Response Checks for Single and Multiple
Patients</u></strong></p>
<ol type="1">
<li><p>For responses to data for single and multiple patients as
described in steps 7 and 8 of this section respectively, the health IT
developer demonstrates the ability of the Health IT Module to respond to
requests for data according to the implementation specification adopted
in § 170.215(a)(2), including the following steps.</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to respond with data that meet the following conditions:</p></li>
</ol>
<ul>
<li><p>All data elements indicated with a cardinality of one or greater
and / or “must support” are included;</p></li>
<li><p>Content is structurally correct;</p></li>
<li><p>All invariant rules are met;</p></li>
<li><p>All data elements with required “ValueSet” bindings contain codes
within the bound “ValueSet”;</p></li>
<li><p>All information is accurate and without omission; and</p></li>
<li><p>All references within the resources can be resolved and
validated, as applicable, according to steps 2-6 of this
section.</p></li>
</ul>
<ol start="3" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a “Provenance” FHIR resource for all the FHIR
resources included in the standard adopted in § 170.213 and
implementation specification adopted in § 170.215(a)(2) according to the
“Basic Provenance Guidance” section of the implementation specification
adopted in § 170.215(a)(2).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a “DocumentReference” and/or “DiagnosticReport” FHIR
resource for each of the “Clinical Notes” and “Diagnostic Reports”
included in and according to the “Clinical Notes Guidance” section of
the implementation specification adopted in § 170.215(a)(2).</p></li>
<li><p>If supported, and for responses to data for a single patient
only, the health IT developer demonstrates the ability of the Health IT
Module to support a “Medication” FHIR resource according to the
“Medication List Guidance” section of the implementation specification
adopted in § 170.215(a)(2).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support “Missing Data” according to the implementation
specification adopted in § 170. 215(a)(2), including:</p></li>
</ol>
<ul>
<li><p>For non-coded data elements; and</p></li>
<li><p>For coded data elements, including support for the
“DataAbsentReason” Code System.</p></li>
</ul>
<p>Note: We require the health IT developers to demonstrate support for
the tests above for both responses to requests for a single patient’s
data and responses to requests for multiple patients’ data because we
make no assumption regarding the re-use of technical infrastructure for
“read” services for single and multiple patients in Health IT
Modules.</p>
<p><strong><u>Response to Requests for a Single Patient’s
Data</u></strong></p>
<ol start="7" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to return all of the data associated with requests for a single
patient’s data according to the “US Core Server CapabilityStatement”
section of the implementation specification adopted in § 170.215(a)(2)
for all the data included in the standard adopted in § 170.213.</p></li>
</ol>
<p><strong><u>Response to Requests for Multiple Patients’
Data</u></strong></p>
<ol start="8" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to respond to requests for multiple patients’ data according to
the implementation specification adopted in § 170.215(a)(4) for all of
the FHIR resources associated with the profiles and Data Elements
specified in and according to the standard adopted in § 170.213 and
implementation specification adopted in § 170.215(a)(2), including the
following FHIR resources:</p></li>
</ol>
<ul>
<li><p>“AllergyIntolerance”;</p></li>
<li><p>“CarePlan”;</p></li>
<li><p>“CareTeam”;</p></li>
<li><p>“Condition”;</p></li>
<li><p>“Device”;</p></li>
<li><p>“DiagnosticReport”;</p></li>
<li><p>“DocumentReference”;</p></li>
<li><p>“Encounter”;</p></li>
<li><p>“Goal”;</p></li>
<li><p>“Immunization”;</p></li>
<li><p>“Location”;</p></li>
<li><p>“Medication” (if supported);</p></li>
<li><p>“MedicationRequest”;</p></li>
<li><p>“Observation”;</p></li>
<li><p>“Organization”;</p></li>
<li><p>“Patient”;</p></li>
<li><p>“Practitioner”;</p></li>
<li><p>“Procedure”; and</p></li>
<li><p>“Provenance”.</p></li>
</ul>
<ol start="9" type="1">
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to limit the data returned to only those FHIR resources for which
the client is authorized according to the implementation specification
adopted in § 170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a successful data response according to the
implementation adopted in § 170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a data response error according to the implementation
adopted in § 170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a bulk data delete request according to the
implementation specification adopted in § 170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a bulk data status request according to the
implementation specification adopted in § 170.215(a)(4).</p></li>
<li><p>The health IT developer demonstrates the ability of the Health IT
Module to support a file request according to the implementation
specification adopted in § 170.215(a)(4), including support for the
“ndjson” format for files provided.</p></li>
<li><p>The health IT developer demonstrates that the information
provided as part of this data response includes data for patients in the
group identifier provided during the “group-export” request.</p></li>
</ol></td>
<td><p><strong><u>Data Response Checks for Single and Multiple
Patients</u></strong></p>
<ol type="1">
<li><p>For responses to data for single and multiple patients as
described in steps 7 and 8 of this section respectively, the tester
verifies the ability of the Health IT Module to respond to requests for
data according to the implementation specification adopted in §
170.215(a)(2), including the following steps.</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
respond with data that meet the following conditions:</p></li>
</ol>
<ul>
<li><p>All data elements indicated with a cardinality of one or greater
and / or “must support” are included;</p></li>
<li><p>Content is structurally correct;</p></li>
<li><p>All invariant rules are met;</p></li>
<li><p>All data elements with required “ValueSet” bindings contain codes
within the bound “ValueSet”;</p></li>
<li><p>All information is accurate and without omission; and</p></li>
<li><p>All references within the resources can be resolved and
validated, as applicable, according to steps 2-6 of this
section.</p></li>
</ul>
<ol start="3" type="1">
<li><p>The tester verifies the ability of the Health IT Module to
support a “Provenance” FHIR resource for all the FHIR resources included
in the standard adopted in § 170.213 and implementation specification
adopted in § 170.215(a)(2) according to the “Basic Provenance Guidance”
section of the implementation specification adopted in §
170.215(a)(2).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support a “DocumentReference” and/or “DiagnosticReport” FHIR resource
for each of the “Clinical Notes” and “Diagnostic Reports” included in
and according to the “Clinical Notes Guidance” section of the
implementation specification adopted in § 170.215(a)(2).</p></li>
<li><p>If supported, and for responses to data for a single patient
only, the tester verifies the ability of the Health IT Module to support
a “Medication” FHIR resource according to the “Medication List Guidance”
section of the implementation specification adopted in §
170.215(a)(2).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support “Missing Data” according to the implementation specification
adopted in § 170. 215(a)(2), including:</p></li>
</ol>
<ul>
<li><p>For non-coded data elements; and</p></li>
<li><p>For coded data elements, including support for the
“DataAbsentReason” Code System.</p></li>
</ul>
<p>Note: We require the tester to verify support for the tests above for
both responses to requests for a single patient’s data and responses to
requests for multiple patients’ data because we make no assumption
regarding the re-use of technical infrastructure for “read” services for
single and multiple patients in Health IT Modules.</p>
<p><strong><u>Response to Requests for a Single Patient’s
Data</u></strong></p>
<ol start="7" type="1">
<li><p>The tester verifies the ability of the Health IT Module to return
all of the data associated with requests for a single patient’s data
according to the “US Core Server CapabilityStatement” section of the
implementation specification adopted in § 170.215(a)(2) for all the data
included in the standard adopted in § 170.213.</p></li>
</ol>
<p><strong><u>Response to Requests for Multiple Patients’
Data</u></strong></p>
<ol start="8" type="1">
<li><p>The tester verifies the ability of the Health IT Module to
respond to requests for multiple patients’ data according to the
implementation specification adopted in § 170.215(a)(4) for all of the
FHIR resources associated with the profiles and Data Elements specified
in and according to the standard adopted in § 170.213 and implementation
specification adopted in § 170.215(a)(2), including the following FHIR
resources:</p></li>
</ol>
<ul>
<li><p>“AllergyIntolerance”;</p></li>
<li><p>“CarePlan”;</p></li>
<li><p>“CareTeam”;</p></li>
<li><p>“Condition”;</p></li>
<li><p>“Device”;</p></li>
<li><p>“DiagnosticReport”;</p></li>
<li><p>“DocumentReference”;</p></li>
<li><p>“Encounter”;</p></li>
<li><p>“Goal”;</p></li>
<li><p>“Immunization”;</p></li>
<li><p>“Location”;</p></li>
<li><p>“Medication” (if supported);</p></li>
<li><p>“MedicationRequest”;</p></li>
<li><p>“Observation”;</p></li>
<li><p>“Organization”;</p></li>
<li><p>“Patient”;</p></li>
<li><p>“Practitioner”;</p></li>
<li><p>“Procedure”; and</p></li>
<li><p>“Provenance”.</p></li>
</ul>
<ol start="9" type="1">
<li><p>The tester verifies the ability of the Health IT Module to limit
the data returned to only those FHIR resources for which the client is
authorized according to the implementation specification adopted in §
170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support a successful data response according to the implementation
adopted in § 170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support a data response error according to the implementation adopted in
§ 170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support a bulk data delete request according to the implementation
specification adopted in § 170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support a bulk data status request according to the implementation
specification adopted in § 170.215(a)(4).</p></li>
<li><p>The tester verifies the ability of the Health IT Module to
support a file request according to the implementation specification
adopted in § 170.215(a)(4), including support for the “ndjson” format
for files provided.</p></li>
<li><p>The tester verifies that the information provided as part of this
data response includes data for patients in the group identifier
provided during the “group-export” request.</p></li>
</ol></td>
</tr>
</tbody>
</table>

**  
**

> Paragraph (g)(10)(viii) – Documentation

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>System Under Test</th>
<th>Test Lab Verification</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong><u>API Documentation Requirements</u></strong></p>
<ol type="1">
<li><p>The health IT developer supplies documentation describing the
API(s) of the Health IT Module and includes at a minimum:</p></li>
</ol>
<ul>
<li><p>API syntax;</p></li>
<li><p>Function names;</p></li>
<li><p>Required and optional parameters supported and their data
types;</p></li>
<li><p>Return variables and their types/structures;</p></li>
<li><p>Exceptions and exception handling methods and their
returns;</p></li>
<li><p>Mandatory software components;</p></li>
<li><p>Mandatory software configurations; and</p></li>
<li><p>All technical requirements and attributes necessary for
registration.</p></li>
</ul>
<ol start="2" type="1">
<li><p>The health IT developer demonstrates that the documentation
described in step 1 of this section is available via a publicly
accessible hyperlink that does not require preconditions or additional
steps to access.</p></li>
<li><p>To fulfill the API Maintenance of Certification requirement at §
170.404(b)(2), the health IT developer demonstrates the public location
of its certified API technology service base URLs.</p></li>
</ol></td>
<td><p><strong><u>API Documentation Requirements</u></strong></p>
<ol type="1">
<li><p>The tester verifies that the documentation supplied by the health
IT developer describing the API(s) of the Health IT Module includes at a
minimum:</p></li>
</ol>
<ul>
<li><p>API syntax;</p></li>
<li><p>Function names;</p></li>
<li><p>Required and optional parameters supported and their data
types;</p></li>
<li><p>Return variables and their types/structures;</p></li>
<li><p>Exceptions and exception handling methods and their
returns;</p></li>
<li><p>Mandatory software components;</p></li>
<li><p>Mandatory software configurations; and</p></li>
<li><p>All technical requirements and attributes necessary for
registration.</p></li>
</ul>
<ol start="2" type="1">
<li><p>The tester verifies that the documentation described in step 1 of
this section is available via a publicly accessible hyperlink that does
not require preconditions or additional steps to access.</p></li>
<li><p>To fulfill the API Maintenance of Certification requirement at §
170.404(b)(2), the tester verifies the public location of the health IT
developer’s certified API technology service base URLs.</p></li>
</ol></td>
</tr>
</tbody>
</table>

# Testing tab 

## **Testing Tool**

[ONC Certification (g)(10) Standardized API Test
Kit](https://inferno.healthit.gov/onc-certification-g10-test-kit) using
Inferno Framework

[(Legacy) Inferno Program Edition](https://inferno.healthit.gov/inferno)

## **Test Tool Documentation** 

[ONC Certification (g)(10) Standardized API Test Kit User’s
Guide](https://github.com/onc-healthit/onc-certification-g10-test-kit)

[(Legacy) Inferno Program Edition User’s
Guide](https://github.com/onc-healthit/inferno-program)
