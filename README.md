# Kittens API

A simple Ruby on Rails API to manage kitten records with basic CRUD functionality.

## Setup

1. Clone the repository:

   ```bash
   git clone git@github.com:arthur-goldenowl/odin-kittens.git
   ```

2. Navigate to the project directory:

   ```bash
   cd kittens-api
   ```

3. Install dependencies:

   ```bash
   bundle install
   ```

4. Set up the database:

   ```bash
   rails db:create db:migrate
   ```

## Usage

Start the Rails server:

```bash
rails server
```

## API Endpoints

- `GET /kittens`: Retrieve all kittens.
- `POST /kittens`: Create a new kitten.
- `GET /kittens/:id`: Retrieve a kitten by ID.
- `PUT/PATCH /kittens/:id`: Update a kitten by ID.
- `DELETE /kittens/:id`: Delete a kitten by ID.
