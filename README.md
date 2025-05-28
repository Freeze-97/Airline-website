# ✈️ Airline_website

A web-based airline booking system created as part of Lab 4 in a web development course. The goal was to simulate a flight booking interface with interactive seat selection, class differentiation, and persistent session data.

## Project Overview
This project features an interactive seat booking system for an 18-seat airplane:
- **6 First Class seats** (Rows 1–2)
- **12 Economy Class seats** (Rows 3–6)
- **Seat layout:** 6 rows × 3 columns


Seats change color based on their state:
- 🟩 Available  
- 🟥 Booked

Once a booking is confirmed, a **boarding pass** is generated and displayed in a new tab.

## 🧠 Key Features

- **Session Storage:** Booked seat data is saved in session storage so it persists across all pages during the session.
- **Class-based Layout:** First and Economy classes are visually and functionally distinct.
- **Dynamic Seat Interaction:** Clicking seats updates their visual status and logic.
- **Boarding Pass Generation:** Booked passengers receive a boarding pass in a new browser tab.
- **Responsive and Styled Interface:** With images and CSS for improved UX.

## 🔧 How to Use

1. Open `index.html` in your browser.
2. Navigate to the **Booking** page to choose your seat.
3. Select a seat from either **First Class** or **Economy Class**.
4. Confirm the booking to generate a **boarding card** in a new tab.
5. Navigate between pages — your booking stays active thanks to **sessionStorage**.
