## Cascade Technical Test

Welcome to Cascade's take home test for developers. We're excited to see what you can do!

We want you to develop a Web application for medical practioners to take over appointment requests from their patients in a web interface. The time it takes to implement this will vary depending on your familiarity with the domain and FHIR standards. But even if you're not familiar we want to give you a chance to show us what you can do and maybe learn someting new along the way.

## Requirements

By the end of this exercise we want you to present us with a simple web application running on your local machine. You don't need to implement login and signup. And we prefer function over form as part of this test. We just want you to show us your skills and ideas.

Your solution should:

- Be presented in a public GitHub repository
- Present a UI for accepting patient appointment requests  as a medical practioner
- Consist of a barebones fullstack web application with a frontend and backend
- Store created data in an Medplum instance using the FHIR API.

## Instructions

1. Signup for a trial of [Medplum's cloud offering](https://app.medplum.com/)
2. Create a [ClientApplication](https://www.medplum.com/docs/api/fhir/medplum/clientapplication) resource in the Medplum dashboard to generate a client ID and secret for making API calls to your Medplum instance
   To shorten time: these are the right resources in FHIR xxxxxx Nich to refine 
4. Develop your application in any language you want so long as it runs in the browser (😉)
5. Come up with a way for the patient to schedule the request and connect with your API
6. Commit your code to a git repository that you can share with us
4. Insure that you can provide a live demo with working code at least from your local machine.

Elements that we are curious about: 
How will you structure the appointment booking logic to make the best use of the doctor's valuable time? 
How will you set this up so that the process can scale reliably and cheaply and onboard 1.000 doctors? 
How do you think about analytics? How would you measure if your setup is successful? What tools would you use? 
How do you think about data storage, especially when thinking about more data being included in the booking process on both the patient and the doctor side, e.g. the patient sharing his medical history? 
What applications of AI do you see for this flow and usecases adjacent to the booking process that will make the journey more joyful for patients and providers?  

## How your work will be evaluated by our team

1. Our priority is that it works and you can demo it to us
2. We want to see your ability to develop in the medical domain using the FHIR standard.
3. Even though authentication is out of scope we're going to make sure there aren't any glaring security flaws (E.g., like API keys shipped to the client)
4. We want you to be able to walk us through your code and explain your technical decisions and what you would change if you were building for production instead of a PoC.

## Key concepts and helpful resources

- [FHIR](https://www.medplum.com/docs/fhir-basics)
- [Medplum](https://www.medplum.com/docs).

Libraries for interacting with FHIR (optional)

- [https://bonfhir.dev/packages/core/fhir-client](https://bonfhir.dev/packages/core/fhir-client)
- [https://www.medplum.com/docs/sdk/core.medplumclient](https://www.medplum.com/docs/sdk/core.medplumclient)
- [API docs](https://www.medplum.com/docs/api)

