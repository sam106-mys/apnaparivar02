# ApnaParivar

ApnaParivar is a secure family tree management platform where authenticated users can privately view family information while only administrators can update and manage the family tree.

## Core Features

- Secure JWT Authentication
- Role-Based Access Control
- Interactive Family Tree Visualization
- Admin-Only Family Updates
- Private Family Data Access
- Member Profiles
- Search Functionality
- Responsive Modern UI

## Tech Stack

### Frontend
- React
- Tailwind CSS
- React Flow
- Axios
- React Router

### Backend
- Node.js
- Express.js
- MongoDB
- JWT
- bcryptjs

## Planned Architecture

```txt
apnaparivar02/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── context/
│   │   └── utils/
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── config/
│   ├── services/
│   └── utils/
```

## Planned Features

- Interactive expandable family tree
- Relationship visualization
- Family timeline
- Member photos
- Search and filtering
- Invite-based access
- Export family tree
- Admin dashboard

## Security

- Password hashing using bcrypt
- JWT protected APIs
- Admin authorization middleware
- Secure environment variables
- Protected routes

## Future Goals

- Real-time updates
- Mobile responsive experience
- Dark mode
- PDF export
- Relationship auto-detection

## Getting Started

### Frontend

```bash
cd client
npm install
npm run dev
```

### Backend

```bash
cd server
npm install
npm run dev
```
