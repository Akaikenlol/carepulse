# Carepulse

Carepulse is a comprehensive healthcare appointment management app designed to streamline the booking process for patients and provide robust administrative tools for healthcare providers. The app ensures a smooth user experience with secure and efficient management of appointments, while offering advanced features like SMS notifications and access control for administrators.

## Features

- **Appointment Booking**: Users can book appointments with ease, selecting their preferred date and time.
- **Family Appointments**: Users can make appointments not only for themselves but also for their family members.
- **Admin Dashboard**: A secure admin dashboard with access control for managing appointments.
- **Rescheduling**: Admins can reschedule appointments upon patient request.
- **Cancellation with Notifications**: Admins can cancel appointments, with SMS notifications automatically sent to patients.

## Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) for a robust and scalable application foundation.
- **Styling**: [TailwindCSS](https://tailwindcss.com/) for modern, responsive design.
- **UI Components**: [shadcnui](https://shadcn.dev/) for pre-built, customizable UI components.
- **Database**: [AppwriteDB](https://appwrite.io/) for managing user and appointment data.
- **Type Safety**: [TypeScript](https://www.typescriptlang.org/), [React Hook Form](https://react-hook-form.com/), and [Zod](https://zod.dev/) for advanced form management and type safety.
- **SMS Notifications**: [Twilio](https://www.twilio.com/) for sending SMS notifications to patients.
- **Performance Monitoring**: [Sentry](https://sentry.io/) for monitoring performance and ensuring the security of the app.

## Getting Started

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/carepulse.git
2. Install dependencies:
    ```bash
    cd carepulse
    npm install
3. Configure environment variables for AppwriteDB, Twilio, and Sentry as needed.
4. Run the development server:
    ```bash
    npm run dev
5. Open http://localhost:3000 to view it in the browser.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.
