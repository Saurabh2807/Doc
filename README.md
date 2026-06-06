# 🩺 DocQueue — Find Doctors, Skip the Wait

**DocQueue** is an interactive, responsive web application designed to bridge the gap between patients and doctors by providing real-time clinic queue management. It helps patients discover doctors nearby, track live waiting times, and book appointments, while giving doctors a powerful dashboard to streamline their clinic operations.

Live Link: [saurabh2807.github.io/Doc](https://saurabh2807.github.io/Doc/)

---

## 🚀 Key Features

### 👤 For Patients
- **🔍 Doctor Discovery**: Browse a pre-populated database of qualified doctors across multiple specialties (General Physician, Dentist, Dermatologist, Cardiologist, Pediatrician, Orthopedic, ENT).
- **⏱ Live Queue Tracker**: See the exact number of patients currently waiting and the estimated waiting time before joining.
- **📅 Dynamic Slot Booking**: Book time slots in advance if you want to schedule a visit instead of joining the live queue.
- **🗺 Smart Navigation**: Stubbed map view displaying clinic locations and addresses with options to navigate.
- **🔔 Notification Center**: Access list of queue updates and reminders. Alerts notify patients when it is almost their turn.
- **💼 Patient Profile**: Manage health records, view past visit history, reviews, and configure account settings.

### 🥼 For Doctors
- **📊 Overview Dashboard**: Monitor active patients in queue, total served today, average rating, and adjust average consultation time slider.
- **👥 Live Queue Management**: Instantly serve next patient, add offline/walk-in patients, clear the queue, or manually edit waiting count.
- **📅 Appointments Panel**: View and manage booked slots for the day with one-click patient call options.
- **📈 Clinic Status Controller**: Toggle clinic availability status between `Open (🟢 Available)`, `Busy (🟡)`, and `Closed (🔴)`.
- **⚙️ Clinic Settings**: Edit timings, phone number, consultation fees, and profile details.

---

## 🛠️ Technology Stack

- **HTML5**: Responsive markup structuring patient and doctor screens.
- **Tailwind CSS & CSS3 Custom Variables**: Tailwind is used for quick grid layouts, and custom CSS handles smooth fade-in/fade-up animations, custom scrollbars, glassmorphism UI, status pills, and card transitions.
- **JavaScript (ES6)**: Pure client-side state management, real-time background queue tick simulation, location updater, and token generator.

---

## 📂 Project Structure

```text
├── index.html       # Clean HTML file with structured sections and links to style and script
├── styles.css       # Custom animations, transitions, scrollbars, and card stylings
├── script.js        # Core logic containing Doctor details, state management, and real-time simulator
└── README.md        # Project documentation
```

---

## 💻 How to run locally

1. Open the directory:
   ```bash
   cd doc_separated
   ```
2. Open `index.html` in any web browser to run the app.
