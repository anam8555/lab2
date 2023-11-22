**Weather-App-README.md**:

# Weather App README

This Weather App is a simple web application that allows users to retrieve weather information for a specified city. Below are answers to the questions:

## Questions

### i. Assume that in your API call you received a 401 status code. Which part of your code most probably is not correct?

A 401 status code typically indicates an unauthorized error. If you receive a 401 status code, the most likely part of the code that is incorrect is the authentication mechanism, specifically the API key used in the headers. In our code, the part that could be incorrect in such a scenario is:

headers: {
'X-RapidAPI-Key': 'a19def8a46msh97d5c020478d57fp1b6333jsn14d11adab06d',
'X-RapidAPI-Host': 'open-weather13.p.rapidapi.com'
}

You should verify that the API key is correct and that you have access to the API service with the provided key. Additionally, make sure that the host and endpoint URLs are accurate and match the API service you are trying to access.

### ii. Explain your design choices and how you used CSS to realize those changes.

For this Weather App, we aimed for a clean and user-friendly design. To achieve this, we utilized Bootstrap, a popular CSS framework, for the styling. Here's how design choices were realized:

- **Bootstrap Framework**: Bootstrap provides a responsive grid system and pre-designed UI components, making it easy to create a visually appealing layout. We used Bootstrap classes for styling elements such as forms, buttons, and alerts.

- **Form and Input**: We used Bootstrap's form component for the input form. This provides consistent styling and responsiveness, making it easy for users to enter a city.

- **Alerts**: To display error messages and weather information, we used Bootstrap's alert component. These alerts provide clear visual feedback to the user.

- **Responsive Design**: Bootstrap ensures that the application is responsive, adapting to various screen sizes, from desktop to mobile. This design choice enhances the user experience.

- **Simplicity**: We aimed for a simple and clean design without excessive ornamentation. This helps users quickly understand the app's purpose and use it effectively.

- **Code Structure**: We kept the CSS code separate from the HTML and JavaScript for maintainability and readability.

In summary, the use of Bootstrap for styling helped achieve a professional and user-friendly design for the Weather App while ensuring a responsive layout that works well on different devices and screen sizes.
