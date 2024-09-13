
# Ledgible Data API Docs - V2

## Overview
This repository serves to provide helpful resources and augmentary documentation to support users of the Ledgible V2 Data API.

Detailed API documentation can be found here: [Ledgible Data API V2 Documentation](https://data-api.ledgible.io/api/v2/docs#tag/Welcome)

## API Testing

To test locally with this API, you can utilize the included collection documents or the buttons below to populate the collection in your preferred API testing tool. These collections are updated periodically, but are not guaranteed to be in sync with the latest changes. Please refer to the official documentation link above for the most up-to-date reference.

**NOTE:** Requests must contain a [signed JWT Bearer token](https://data-api.ledgible.io/api/v2/docs#tag/Authentication) for each request, based on a pre-defined pub/private key pair. The Postman collection below includes a sample pre-request script to assist in generation of these tokens. If using a different API client tool or if the script does not meet your organization's requirements, you will need to generate these tokens independently.

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://app.getpostman.com/run-collection/838548-6e0efaff-a670-4d50-b168-86082c051e93?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D838548-6e0efaff-a670-4d50-b168-86082c051e93%26entityType%3Dcollection%26workspaceId%3D423814dc-d61e-49ec-8ede-2017d333e81f)

[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Ledgible%20Data%20API%20V2&uri=https%3A%2F%2Fdata-api.ledgible.io%2Fapi%2Fv2%2Fdocs.json)

## Data Flow Diagram
<img width="2254" alt="Ledgible V2 API Consumer_Customer Flow" src="https://github.com/user-attachments/assets/a290db4e-d835-4bf2-9865-28948d45e7b3">
