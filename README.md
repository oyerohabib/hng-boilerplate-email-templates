# 📧 HNG Boilerplate Email Templates

This repository contains the HNG 12 boilerplate email templates. These templates are part of the Email messaging/Template/SMS (using a background queue) task. You can view the design on [Figma](https://www.figma.com/design/VEItfX6St5NSAqqNHImcxD/HNG-Boilerplate-Designs?node-id=7-8277&m=dev). There are a total of 20 email templates.

## 🤝 Contributors

- [@oyerohabib](https://github.com/oyerohabib/)
- [@jane-jazzy](https://github.com/jane-ahone)

## 🔗 Relevant Links

- **Website Link**: [Website Link](https://hng-boilerplate-email-templates.netlify.app/)
- **Figma Design**: [Figma Design](https://www.figma.com/design/VEItfX6St5NSAqqNHImcxD/HNG-Boilerplate-Designs?node-id=7-8277&m=dev)
- **Frontend Repository**: [Boilerplate Frontend Repository](https://github.com/hngprojects/hng_boilerplate_nextjs)
- **Backend Repository**: [Boilerplate Backend Repository](https://github.com/hngprojects/hng_boilerplate_nestjs)
- **API Documentation**: [Boilerplate API Documentation](https://staging.api-nestjs.boilerplate.hng.tech/api/docs)

## 📸 Screenshots

|                                                   |                                                   |
| :-----------------------------------------------: | :-----------------------------------------------: |
| ![Screenshot 1](https://i.imgur.com/poBNEMH.jpeg) | ![Screenshot 2](https://i.imgur.com/GMW3VXn.jpeg) |
| ![Screenshot 3](https://i.imgur.com/zw9BXUn.jpeg) | ![Screenshot 4](https://i.imgur.com/S0zai60.jpeg) |
| ![Screenshot 5](https://i.imgur.com/PEVn1BC.jpeg) | ![Screenshot 6](https://i.imgur.com/zfy84d7.jpeg) |

## 📦 Technologies

- HTML
- CSS

## 🤔 How Does It Work?

These templates are part of the general email functionality for the application. The **Email Service**, developed on the backend, can be used by various parts of the application such as signing in, signing up, password recovery, account deactivation, invoice generation, etc.

Templates are uploaded through an endpoint and stored on the backend, this can be found in the API docs above. The backend developer can reference these templates by name. Additionally, the templates include dynamic fields like `{{name}}`, `{{email}}`, `{{token}}`, `{{link}}`, which are populated with values passed from the backend.

To learn more about this, you can reach out to the backend developer here - [KINGAJ](https://github.com/King-AJr)

## 🚦 Running the Project

To run the project in your local environment, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/oyerohabib/hng-boilerplate-email-templates.git email-templates
   ```

2. Navigate to the project directory:

   ```bash
   cd email-templates
   ```

3. Preview the templates by opening the respective files in any browser of your choice.

## ⭐ Support & Contributions

Thank you for considering contributing to the HNG Boilerplate Email Templates! We welcome contributions from the community to help improve and grow the project.

If you find this project helpful or interesting, please consider giving it a star! 🌟 Your support encourages future development and helps others discover the project. Contributions are also welcome—feel free to fork the repo, submit pull requests, or suggest features.

Please note that this project adheres to the [Contributor Covenant Code of Conduct](CONTRIBUTING.md). By participating, you are expected to uphold this code. Please report any unacceptable behavior.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
