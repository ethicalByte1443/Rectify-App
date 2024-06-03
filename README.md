# Attendance Rectification Portal

## Overview

The **Attendance Rectification Portal** is a web application designed to streamline the process of requesting and processing attendance corrections for students. This platform allows students to lodge complaints and ensures quick response times from faculty and administrators for attendance-related issues.

![Attendance Rectification Portal]

---

## Features

- 📋 **Student Complaints**: Submit detailed rectification requests including class details, date, and reason for correction.
- 🧑‍🏫 **Faculty Review**: Faculty members can review, verify, and correct attendance records.
- 📊 **Dashboard**: Get an overview of pending and resolved requests through an intuitive dashboard.

---

## Task List

- [ ] Create a sleek user interface with an "Admin sign-in" button in the corner.
- [ ] Develop a login page and dashboard for admin users.
- [ ] Set up the server to handle login functions.
- [ ] Use MongoDB to store information securely.
- [ ] Implement robust data security measures.
- [ ] Enable user authentication via Firebase or WhatsApp OTP.

**Need more info? Call me up!**

---

## Getting Started

### Prerequisites

- **Node.js** and **npm** installed on your machine.

### Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/AshishJii/Rectify
    cd attendance-rectification-portal
    ```

2. **Install Dependencies**:

    ```bash
    npm install
    ```

3. **Run the Development Server**:

    ```bash
    npm run dev
    ```

---

## Tech Stack

- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: Firebase/WhatsApp OTP

---

## Contributing

We welcome contributions! Please follow our [contributing guidelines](https://github.com/AshishJii/Rectify/contributing-guidelines) to get started.

---

## License

This project is licensed under the [MIT License](https://github.com/AshishJii/Rectify/blob/main/LICENSE).

---

## Contact

For any questions or support, please contact:

- [Ayush Singh Bhadauria](mailto:2k22.cse.2213437@gmail.com)
- [Ashish Verma](mailto:2k22.cse.2213516@gmail.com)
- [Ashmit Kumar](mailto:2k22.cse.2211344@gmail.com)
- [Aseem Pradhan](mailto:2k22.cse.2213048@gmail.com)

---

## Additional Information

Feel free to customize this README to include additional details, such as technology stack, screenshots, deployment instructions, and any other relevant information for your project. Clear and comprehensive documentation helps users and contributors better understand and engage with your project.

---

## Enhancements

To improve the aesthetics of your project, you can add animations, custom fonts, and SVGs.

### Custom Fonts and Animations

Include the following CSS in your project to apply animations and custom fonts:

```html
<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

body {
    font-family: 'Montserrat', sans-serif;
}

button {
    transition: background-color 0.3s ease, transform 0.3s ease;
    font-family: 'Montserrat', sans-serif;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #007bff;
    color: white;
    transform: scale(1.05);
}

h2 {
    animation: fadeIn 2s ease-in-out;
}

@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}
</style>
