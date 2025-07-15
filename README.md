# Event Manager

![Captura de pantalla](./assets/img/capture.png)

Event Manager is a web-based event management application with user roles (administrator and visitor) that allows you to create events, manage registrations, and view availability.

## Main features

- **User Authentication**: Registration and login with different roles
- **Event Management** (admin):
- Create, edit, and delete events
- Set maximum capacity per event
- **Event Registration** (visitor):
- View available events
- Register/unregister
- **Modern Interface**: Responsive design with visual components
- **Data Persistence**: Local storage with json-server

## Technologies Used

- **Frontend**:
- HTML5, CSS3 (Flexbox, Grid)
- Vanilla JavaScript (ES6+)
- **Mock Backend**: json-server
- **Dependencies**:
- Font Awesome (icons)
- Google Fonts (typography)


## Installation and Configuration

1. Clone the repository:
```bash
git clone https://github.com/Rwimike/event-manager.git
cd event-manager
```

2. Install dependencies:
```bash
npm install -g json-server
npm install
```

3. Start the database server (json-server):
```bash
json-server --watch db.json --port 3000
```

4. Open the application in the browser:
Open `index.html` in your favorite browser


## Estructura del proyecto

```
/miguelangelloperamunoz963 
│
├── index.html 
├── README.md
├── db.json
├── script.js
│ 
├── /css 
│ └── style.css 
│ 
├── /assets
  └── img 
      └── about.html 

```

## Usage

1. **User Registration**:
- Complete the registration form by selecting your role (admin or visitor)

2. **Event Management (admin)**:
- Create new events with a name, description, and capacity
- Edit or delete existing events

3. **Event Registration (visitor)**:
- View all available events
- Register for events with available space
- Cancel your registration whenever you need

## Future Enhancements

- Implement real JWT authentication
- Add event categories and filters
- Implement event calendar
- Add email notification system
- Integrate attendance charts (admin)
- Implement event search

## Licencia

Este proyecto está bajo la licencia [MikeRwi](LICENSE).
