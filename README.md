# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# mvp_starter

## Setup Instructions

### Prerequisites
- Ruby version 3.2.2
- PostgreSQL
- Node.js (version 16.0.0)
- Yarn (version 1.22.22)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/MuhammadAhsan252/mvp_starter.git
   cd mvp_starter
   ```

2. Install dependencies:
   ```sh
   bundle install
   yarn install
   ```

### Database Setup
1. Create and setup the database:
   ```sh
   rails db:create
   rails db:migrate
   ```

### Running the Application
1. Start the Rails server:
   ```sh
   rails server
   ```

2. Open your browser and navigate to `http://localhost:3000`
