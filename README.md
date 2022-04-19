# Roarum

Roarum is a web forum.

## Working with Docker

```sh
# Build the images
docker-compose build

# Run the containers in the background
docker-compose up -d

# Create the database
docker-compose run app rails db:create

# Migrate the database
docker-compose run app rails db:migrate

# Open the development url in a browser
open http://localhost:3000/

# Follow the app logs
docker-compose logs -f app

# Stop the containers
docker-compose stop
```