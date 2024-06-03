# Cascade Technical Test

Welcome to Cascade's take home test for developers. We're excited to see what you can do!

We want you to develop a Web application for medical practioners to write prescriptions and submit those presciptions to a system using the FHIR API. The time it takes to implement this will vary depending on your familiarity with the domain and FHIR standards. But even if you're not familiar we want to give you a chance to show us what you can do and maybe learn someting new along the way.

## Requirements

By the end of this exercise we want you to present us with a simple web application running on your local machine. You don't need to implement login and signup. And we prefer function over form as part of this test. We just want you to show us a working web app for submitting perscriptions to an instance of the open source EHR Medplum.

Your solution should:

- Be presented in a public GitHub repository
- Present a UI for submitting perscriptions as a medical practioner
- Consist of a barebones fullstack web application with a frontend and backend
- Submit a [MedicationRequest](https://www.medplum.com/docs/api/fhir/resources/medicationrequest) to your Medplum instance using the FHIR API.

## Instructions

1. Signup for a trial of [Medplum's cloud offering](https://app.medplum.com/)
2. Create a [ClientApplication](https://www.medplum.com/docs/api/fhir/medplum/clientapplication) resource in the Medplum dashboard to generate a client ID and secret for making API calls to your Medplum instance
3. Develop your application in any language you want so long as it runs in the browser (😉)
4. Commit your code to a git repository that you can share with us
4. Insure that you can provide a live demo with working code at least from your local machine.

## How your work will be evaluated by our team

1. Our priority is that it works and you can demo it to us
2. We want to see your ability to develop in the medical domain using , even if it's new to you using the FHIR standard.
3. Even though authentication is out of scope we're going to make sure there aren't any glaring security flaws (E.g., like API keys shipped to the client)
4. We want you to be able to walk us through your code and explain your technical decisions and what you would cange if you were building for production instead of a PoC.

## Key concepts and helpful resources

- [Perscriptions](https://www.ncbi.nlm.nih.gov/books/NBK538424/)
- [FHIR](https://www.medplum.com/docs/fhir-basics)
- [Medplum](https://www.medplum.com/docs).

Libraries for interacting with FHIR (optional)

- [https://bonfhir.dev/packages/core/fhir-client](https://bonfhir.dev/packages/core/fhir-client)
- [https://www.medplum.com/docs/sdk/core.medplumclient](https://www.medplum.com/docs/sdk/core.medplumclient)
- [API docs](https://www.medplum.com/docs/api)

