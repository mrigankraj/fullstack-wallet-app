# Full-Stack Wallet Application

## Project Overview
A comprehensive wallet management application with mobile, web, and admin interfaces.

## Features
- User Authentication
- Wallet Management
- Transaction Tracking
- Admin Control Panel

## Tech Stack
- Backend: Express, Prisma, tRPC
- Mobile: React Native
- Web Admin: Next.js
- Database: PostgreSQL
- Authentication: JWT

## Prerequisites
- Node.js (v18+)
- PostgreSQL
- Yarn or npm

## Quick Setup

### 1. Clone the Repository
```bash
git clone https://github.com/mrigankraj/wallet-app.git
cd wallet-app
```

### 2. Install Dependencies
```bash
yarn install
```

### 3. Setup Environment
- Copy `.env.example` to `.env` in each project directory
- Configure database connection

### 4. Database Setup
```bash
# Generate Prisma Client
yarn prisma generate

# Run Migrations
yarn prisma migrate dev
```

### 5. Run Applications
```bash
# Start Backend
yarn workspace backend dev

# Start Mobile App
yarn workspace mobile start

# Start Web Admin
yarn workspace web-admin dev
```

## Project Structure
- `backend/`: Express backend with Prisma ORM
- `mobile/`: React Native mobile application
- `web-admin/`: Next.js admin panel
- `docs/`: Project documentation

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
MIT License
