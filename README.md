# API-Testing

This repository contains API testing artifacts for *REST* and *SOAP* services, including manual test cases, reports, and Postman collections.

The goal of this project was to validate API functionality, data integrity, and response behavior using different types of APIs.

<strong>Tested APIs:</strong>
<ol>
    <li><a href="https://petstore3.swagger.io/">Swagger Petstore (OpenAPI 3.0)</a></li>
    <li><a href="http://webservices.oorsprong.org/websamples.countryinfo/CountryInfoService.wso?WSDL">Country Info SOAP Service</a></li>
    <li><a href="http://users.bugred.ru/tasks/soap/WrapperSoapServer.php?wsdl">Users Bugred SOAP Service</a></li>
</ol>

> #### Included Artifacts
<strong>REST API (Petstore):</strong>
<ul>
    <li><a href="https://drive.google.com/file/d/1zZD6gVWsdzWzwR6T-4E2zoBuqPrBxV_r/view?usp=sharing">Test Cases (Petstore)</a>. Covers CRUD operations, validation, and negative scenarios.</li>
    <li><a href="https://drive.google.com/file/d/1dLr6XgsbJSVCH-S9_-Nk7WttNOSGfN7u/view?usp=sharing">Test Report (Test IT)</a>. Execution results and defect tracking.</li>
    <li><a href="https://www.postman.com/olehsobol/workspace/personal-workspace/collection/46557110-0c03d0c9-3fa7-481f-a277-420921ea972b">Postman Collection</a></li>
</ul>

<strong>SOAP API:</strong>

*Country Info Service*
<ul>
    <li><a href="https://www.postman.com/olehsobol/workspace/personal-workspace/collection/46557110-b3c97b9a-82d6-4392-8498-708a88b2fde7?action=share\&creator=46557110">Postman SOAP Collection</a></li>
</ul>

*Users Bugred*
<ul>
    <li><a href="https://drive.google.com/file/d/1vAm9X_8btv2zv8PbXXJmy8Nk_iyfeiec/view?usp=sharing">Test Cases (User Bugred)</a>. SOAP request validation and response checks.</li>
    <li><a href="https://www.postman.com/olehsobol/workspace/personal-workspace/collection/46557110-e61be34e-c1ee-4676-aebd-59caeaf1a997?action=share\&creator=46557110">Postman Collection</a></li>
</ul>

<strong>Additional Setup</strong>
- Petstore was deployed locally using Docker (<a href="https://drive.google.com/file/d/1qvKBMPWhVbHAjnMfQCi1f7wI5EpD7gzI/view?usp=sharing">docker-compose.yml</a>)
- SOAP requests tested via Postman using WSDL schemas