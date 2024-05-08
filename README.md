<p align="center">
  <a>
    <img src="./assets/Header.jpg" alt="logo" width="100%" height="auto" />
  </a>
</p>
<p align="center">An Application used at Chick-Fil-A, Grandover VIllage to help improve efficiency, simplify processes, and provide seamless support for the day-to-day activities at the restaurant..</p>
</p>

# 👋 About

Initiated in October 2022, I began developing a full-stack application tailored to optimize the operations of Chick-Fil-A at Grandover Village. The main goal of this project is to enhance operational efficiency and simplify procedural complexities, thereby supporting the restaurant’s daily functions more effectively. By leveraging advanced technology, the "Grandover Project" seeks to transform Chick-Fil-A’s operational dynamics, ensuring a more efficient and smoother experience for both employees and patrons.

This Project was inspired from my smaller [project](https://github.com/RobbiDev/boil-out).

**NOTE:** This project will be open-sourced in the future, but as of right now. This repo will be used to show off and showcase my work done with [Chick-Fil-A Properties, Inc.](https://www.chick-fil-a.com/)

# 🛠️ Features

- Waste System: Used to Track and calculate all waste within the store
- Training System: A in-depth Training System that uses pathway to help efficently train new Team Members while being taught during store operations.
- Employee Directory: Simple Database Directory for all employyes.
- Kitchen Watch: An advanced version of my earlier project, Boil-Out, this timer-based tracker monitors maintenance tasks for items like fryers and floor drains on a daily or monthly basis, ensuring timely upkeep.

# 🏗️ Application Structure

This application boasts a deep yet intuitive design. To fully grasp how it functions, it’s important to first understand its underlying structure.

### Website Structure

```
Grandover Application
  ├── Waste System
  ├── Training System
  ├── Employee Directory
  └── Kitchen Watch
```

## Role-Based Access Structure

```
Owner (Ex: Operator/Corperate)
└── Admin Account (Ex: HR)
    ├── Trainer Account (Ex: Certified Trainer)
    │   └── Ipad Account (Ex: Strictly for Inputing Data)
    └── Manager Account (Ex: GM or Anyone else of Importance)
```

iPad accounts are strictly used for data entry. For instance, in the kitchen, you might find an iPad mounted in a convenient location for logging daily waste. These accounts have limited access and can only view specific information.

Trainer accounts are specifically designed to access the included training system and are limited to viewing only the trainees' information and the training materials. For example, a trainer might carry an iPad in a sling around their shoulder, dedicated solely to this function.

# 🔒 Security & Login

This application begins at the login page, which is strictly accessible only to users with Owner, Admin, or Manager accounts. No other roles have access, ensuring the protection of both company and employee information. The application places a strong emphasis on security and adherence to login protocols to safeguard sensitive data and maintain a secure and trusted environment.

<p align="center">
  <a>
    <img src="./assets/Login Page.jpg" alt="logo" width="100%" height="auto" />
  </a>
</p>

## User Roles and Access Permissions:

The task of adding and creating user accounts is exclusively handled by the owner account, ensuring tight control over the issuance of new user credentials. The operator predetermines the username and password when creating an account, adopting a standardized and secure method for account setup. Once a user is added, the operator is required to assign at least one of the specified roles, maintaining consistency and security across the application.

# 🤿 Diving Deeper
This is a general overview of the Grandover Application. For a more detailed exploration of each feature, please visit the respective feature's page.

- [Waste System](https://github.com/RobbiDev/grandover/blob/main/pages/waste.md).
- [Training System](https://github.com/RobbiDev/grandover/blob/main/pages/training.md)
- [Employee Directory](https://github.com/RobbiDev/grandover/blob/main/pages/directory.md)
- [Kitchen Watch](https://github.com/RobbiDev/grandover/blob/main/pages/kitchenwatch.md)

**If your feeling nerdy, Explore [How it was made](https://github.com/RobbiDev/grandover/blob/main/pages/howitwasmade.md) for a breakdown on this applications development**

# Notice

This project is currently in the production phase, and the release date has yet to be determined. Presently, this repository serves to showcase my work with [Chick-Fil-A Properties, Inc.](https://www.chick-fil-a.com/).

Please note, all icons used within the application are the property of CFA Pathway, and the Chick-Fil-A logo is also not owned by me. Chick-Fil-A reserves the right to deny any release of this application.
