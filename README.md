# Circular Fashion – Re-make and Mend

# Run with Docker (recommended)
1. Install Docker Desktop
2. In the project folder, run:
3. docker compose up --build
4. Open in browser: http://localhost:3000

The MySQL database runs on host port 3307 (container port is 3306).

The database schema and initial seed data are automatically loaded from db/init/.

# Run without Docker
1. Create a MySQL database named circular_fashion.
2. Run all SQL files located in db/init/ in the correct order.
3. Copy .env.example to .env and update the database configuration.
4. Install dependencies and start the application:

npm install

npm run dev

Open: http://localhost:3000
