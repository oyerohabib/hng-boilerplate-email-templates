# HNG Boilerplate Email Templates

This repository contains the HNG 12 boilerplate email templates. These templates are part of the Email messaging/Template/SMS (using a background queue) task. You can view the design on [Figma](https://www.figma.com/design/VEItfX6St5NSAqqNHImcxD/HNG-Boilerplate-Designs?node-id=7-8277&m=dev). This project was developed by [@oyerohabib](https://github.com/oyerohabib/) and [@jane-jazzy](jane.ahone.eloundou@gmail.com). There are a total of 20 email templates, including:

- Account-Deactivation.html
- Account-Inactivity-Deactivation.html
- Activate-Account.html
- Activation-Link.html
- Active-Account.html
- Email-Complete.html
- Email-Verification.html
- Invoice.html
- New-Activation-Link.html
- New-Feature-Announcement.html
- Newsletter.html
- Password-Reset-Complete-Template.html
- Payment-Receipt.html
- README.md
- Reset-Password-Template.html
- Subscription-Cancellation-Confirmation.html
- Subscription-Confirmation.html
- Subscription-Renewal-Disabled.html
- Subscription-Renewal-Failed.html
- Subscription-Renewal-Reminder.html
- Welcome-Template.html

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

These templates are part of the general email functionality for the application. The email service, developed on the backend, can be used by various parts of the application such as signing in, signing up, password recovery, account deactivation, invoice generation, etc.

Templates are uploaded through an endpoint and stored on the backend. The backend developer can reference these templates by name. Additionally, the templates include dynamic fields like `{{name}}`, `{{email}}`, `{{token}}`, `{{link}}`, which are populated with values passed from the backend.

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

## License

This project is licensed under the [MIT License](LICENSE).
