# Zeller Coding Challenge - Frontend

## OVERVIEW

This coding challenge is to build a simple react app with Typescript (optional), integrated with GraphQL APIs.

## HIGH LEVEL REQUIREMENTS

Need to build a simple react app to show Zeller customers. Customers should be fetched with the GraphQL APIs provided.
List of customers need to be filtered based on the selection of user type - Admin/Manager.
- Radio button selection of `Admin` should list `admin` customers as per the design.
- If the selection is `Manager`, customers with a role `Manager` need to be listed.


Please refer to - [zeller-customers-design.png](zeller-customers-design.png) for the design.

## RECOMMENDATIONS

1. Use ‘Create React App’ (for Typescript) for the project setup. No need to set the project up from the scratch.
2. Use a familiar UI library such as Styled-Components if required. No need to be pixel perfect with the design.
3. GraphQL APIs are hosted in AWS. Use the attached `aws-exports.js` file for configurations. Authentication type is API-KEY. Please replace `<API_KEY>` in `aws-exports.js` with the actual API key provided.
4. Refer attached [graphql/queries.ts](graphql/queries.ts) for queries.

## ZELLER CHECKLIST

1. Proper test coverage
2. Best practises for performance optimisation
3. Code quality
4. UI Quality and Responsiveness
5. Documentation describing the approach and setup.
   
## RESOURCES PROVIDED

1. Design for the required screen --  [zeller-customers-design.png](/zeller-customers-design.png).
2. GraphQL folder with queries.
3. Configuration file to use AWS AppSync GraphQL APIs -- aws-exports.js
4. API key to access the GraphQL APIs. - provided separately

Please send us the documentation with access to your repo such as a Github link with README. If you have any questions, kindly reach out to us.

Good Luck!!