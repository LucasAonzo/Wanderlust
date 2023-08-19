# Wanderlust: A Travel Booking Web Application

Wanderlust is a web application designed for travelers. It streamlines the process of selecting and purchasing comprehensive travel packages, connecting travelers to ideal flight, accommodation, and activity options. With a rich and responsive UI, Wanderlust caters to both individual travelers and travel service providers.

![Wanderlust Screenshot](URL_TO_SCREENSHOT)

## Features

- **Comprehensive Travel Packages:** Easily find and book complete travel packages, including flights, accommodations, and activities.
- **Rich and Responsive UI:** A user-friendly interface that provides a seamless experience across devices.
- **Authentication:** Secure user authentication using Firebase.
- **Image Management:** Efficient image management with Cloudinary.
- **Emailing Functionalities:** Send and receive emails easily with Nodemailer.
- **Payment Processing:** Secure payment processing using PayPal.

## Technologies

- React
- Redux
- Express
- PostgreSQL
- Firebase (Authentication)
- Cloudinary (Image Management)
- TailwindCSS
- Axios
- Nodemailer (Emailing Functionalities)
- Vercel (Deployment)
- PayPal (Payment Processing)

## Getting Started

### Prerequisites

- Node.js
- PostgreSQL
- Firebase account
- Cloudinary account
- PayPal account

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/LucasAonzo/Wanderlust.git
    cd Wanderlust
    ```
2. Install the dependencies:
    ```bash
    npm install
    ```
3. Set up environment variables:

    Create a `.env` file in the root directory and configure the following variables:

    ```env
    FIREBASE_API_KEY=YOUR_FIREBASE_API_KEY
    CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY
    PAYPAL_CLIENT_ID=YOUR_PAYPAL_CLIENT_ID
    ```
4. Start the development server:
    ```bash
    npm start
    ```

    The application will be available at `http://localhost:3000`.

Contributing
We welcome contributions! Please see our contributing guide for more details.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Contact
Feel free to reach out to me at lucas.aonzo@example.com if you have any questions or feedback.
