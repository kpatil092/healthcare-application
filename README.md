# Healthcare management application 
A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors, featuring administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications.

### Libraries and support
- Next.js
- Appwrite
- Typescript
- TailwindCSS
- ShadCN
- Twilio

### Features
- Users can sign up and create a personal profile as a patient.
- Patients can schedule appointments with doctors at their convenience and book multiple appointments.
- Admins can confirm and set appointment times to ensure they are properly scheduled.
- Patients receive SMS notifications to confirm their appointment details (using Twilio service).
- The application works seamlessly on all device types and screen sizes.
- The application uses Sentry to monitor and track its performance and detect any errors.

### Set-up
1. Clone to local machine
```
git clone https://github.com/kpatil092/healthcare-application.git
cd healthcare-application
```
2. Install modules
```
npm install
```
3. Set up environment variables
```
/.env.local

#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=123456
```
4. Run the project
```
npm dev run
```
