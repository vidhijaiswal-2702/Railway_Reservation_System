# Railway Reservation System

Welcome to the Railway Reservation System project! This application is designed to manage train bookings, cancellations, and other administrative functions with ease. Built with Streamlit and SQLite, it provides an intuitive interface for both administrators and passengers.

## Features

- **Add Train**: Admins can add new train details, including train number, name, departure date, and destinations.
- **View Trains**: View all available trains in the database.
- **Search Train**: Search for trains by train number or by starting and ending destinations.
- **Delete Train**: Delete trains from the database.
- **Book Ticket**: Passengers can book tickets by selecting a seat type and providing their details.
- **Cancel Ticket**: Passengers can cancel their tickets.
- **View Seats**: Admins can view the seating arrangement and passenger details for a particular train.

## Installation

To get started with the Railway Reservation System, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory**:
    ```bash
    cd railway-reservation-system
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit application**:
    ```bash
    streamlit run app.py
    ```

## Database

The system uses an SQLite database to store the following information:

- **users**: Stores user credentials.
- **employees**: Stores employee details.
- **trains**: Stores train details such as train number, name, departure date, and destinations.
- **seats**: Each train has a dynamically created table to store seat details, including seat type, booking status, and passenger details.

## Usage

### Adding a Train

1. Select "Add Train" from the sidebar.
2. Fill in the train details.
3. Click "Add Train" to save the train in the database.

### Viewing Trains

1. Select "View Trains" from the sidebar.
2. A list of all available trains will be displayed.

### Searching for Trains

1. Select "Search Train" from the sidebar.
2. Search by either train number or starting and ending destinations.
3. Click the respective search button to view the results.

### Deleting a Train

1. Select "Delete Train" from the sidebar.
2. Enter the train number and departure date.
3. Click "Delete Train" to remove the train from the database.

### Booking a Ticket

1. Select "Book Ticket" from the sidebar.
2. Enter the train number, seat type, and passenger details.
3. Click "Book Ticket" to reserve a seat.

### Canceling a Ticket

1. Select "Cancel Ticket" from the sidebar.
2. Enter the train number and seat number.
3. Click "Cancel Ticket" to free up the seat.

### Viewing Seats

1. Select "View Seats" from the sidebar.
2. Enter the train number and click "Submit" to view the seating arrangement and passenger details.

## Screenshots

### Add Train

![Screenshot 2024-07-27 230630](https://github.com/user-attachments/assets/5561e4c4-bff7-40ca-8db1-705f0f086deb)

### View Trains
![Screenshot 2024-07-27 230646](https://github.com/user-attachments/assets/1c962b72-efa2-4f7e-bcdf-ad42c093ff99)

### Search Train
![Screenshot 2024-07-27 230705](https://github.com/user-attachments/assets/194a75f3-f0bc-40b7-b962-050ab0b569b5)

### Delete Train

![Screenshot 2024-07-27 230724](https://github.com/user-attachments/assets/878440e5-a17e-4502-863c-2835478593e0)

### Book Ticket

![Screenshot 2024-07-27 230807](https://github.com/user-attachments/assets/e0e1e75f-ce4e-4bef-939d-5deda5f3bc1c)

### View Seats

![Screenshot 2024-07-27 230826](https://github.com/user-attachments/assets/dac2dd8f-5f6a-4078-a1f2-0676350d334e)

---

Thank you for using the Railway Reservation System! We hope this application makes managing train reservations easier and more efficient. If you have any questions or feedback, please feel free to reach out.
