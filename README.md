# Integrating With HubSpot I: Foundations Practicum

This project demonstrates seamless integration with HubSpot's Custom Objects API, designed to manage and interact with custom data entities tailored to specific business needs within the HubSpot ecosystem.

## Overview

The practicum showcases the following functionalities:

1. **Homepage (List of Custom Objects):** Displays a comprehensive list of all custom objects (e.g., Assets). Each item in the list includes a link to its update form.
2. **Create New Custom Object:** Provides a form to create a new custom object (e.g., Assets). This form can be accessed via a button on the homepage.
3. **Update Custom Object:** Displays a form pre-filled with details of a specific custom object (e.g., Assets) for updating. Accessed by clicking on an item in the homepage list.

## Loom Video

For a complete explanation of the functionality, please refer to the [Loom video](https://www.loom.com/share/1899970080ac489babbe5d31e47692f2?sid=2aaced41-5bc5-44fe-af71-be86e44c8b8c).

## Custom Object List URL

You can view the list of custom objects by visiting the following URL: [HubSpot Custom Object List](https://app.hubspot.com/contacts/22802756/objects/2-17722902/views/all/list).

## Routes and Usage

This project implements the following routes to interact with HubSpot's Custom Objects API:

- **Homepage (List of Custom Objects):** Displays a list of all custom objects. Each item has a link to its update form.
- **Create New Custom Object:** Provides a form for creating a new custom object. Accessible via a button on the homepage.
- **Update Custom Object:** Displays a form pre-filled with details of a specific custom object for updating. Accessed by clicking on an item in the homepage list.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone [repository-url]
   cd [repository-directory]
   ```

2. **Install Dependencies:**
   ```sh
   npm install
   ```

3. **Run the Application:**
   ```sh
   npm start
   ```

## Technologies Used

- **Node.js** and **Express.js** for backend server and routing.
- **Pug** for template rendering.
- **jQuery** for handling DOM manipulations and AJAX requests.
- **CSS** for styling and responsive design.

## Contribution

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For further information, refer to the official [HubSpot API documentation](https://developers.hubspot.com/docs/api/overview).

---

Thank you for using the Integrating With HubSpot I: Foundations Practicum. We hope it enhances your experience with HubSpot's Custom Objects API!