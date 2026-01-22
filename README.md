# Zeller Coding Challenge - Frontend

## OVERVIEW

This coding challenge is to build a simple react app with Typescript, integrated with GraphQL APIs.

## HIGH LEVEL REQUIREMENTS

Need to build a simple react app to show Zeller customers. Customers should be fetched with the GraphQL APIs provided.
List of customers need to be filtered based on the selection of user type - Admin/Manager.
- Radio button selection of `Admin` should list `admin` customers as per the design.
- If the selection is `Manager`, customers with a role `Manager` need to be listed.


Please refer to - [zeller-customers-design.png](zeller-customers-design.png) for the design.

## RECOMMENDATIONS

1. Use [create vite](https://www.npmjs.com/package/create-vite) with `react-ts` template for the project setup.
2. Use tailwindcss or styled-components if required.
3. GraphQL APIs are hosted in AWS. Use the attached `aws-exports.js` file for configurations. Authentication type is API-KEY.
Please replace `<API_KEY>` in `aws-exports.js` with the actual API key provided.
4. Refer attached [graphql/queries.ts](graphql/queries.ts) for queries.

## ZELLER SUCCESS CRITERIA

1. **Code Quality** – Clean, readable, and maintainable code following best practices.
2. **UI Quality & Responsiveness** – Polished interface with seamless adaptability across devices and screen sizes.
3. **Test Coverage** – Comprehensive unit and integration tests ensuring code reliability.
4. **TypeScript Adherence** – Strict and consistent type definitions throughout the codebase without using `any` types.
5. **Accessibility (a11y)** – Compliance with accessibility standards to support all users.
6. **Error Handling & Loading States** – Graceful error handling and intuitive loading indicators.
7. **Project Architecture** – Well-organized folder structure with modular, reusable components.
8. **Performance Optimization** – Efficient data fetching, minimal re-renders.
9. **Documentation** – Clear and thorough documentation outlining the approach and setup instructions.

## RESOURCES PROVIDED

1. Design for the required screen --  [zeller-customers-design.png](/zeller-customers-design.png).
2. GraphQL folder with queries.
3. Configuration file to use AWS AppSync GraphQL APIs -- aws-exports.js
4. API key to access the GraphQL APIs. - provided separately

Please send us the documentation with access to your repo such as a Github link with README. If you have any questions, kindly reach out to us.

Good Luck!!
