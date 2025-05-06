# Symfony Articles Project

This is a simple Symfony project that displays a list of articles.

## Setup Instructions

1. Make sure you have Docker and Docker Compose installed on your system.

2. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

3. Start the Docker containers:
```bash
docker-compose up -d
```

4. Install dependencies:
```bash
docker-compose exec php composer install
```

5. Access the application at http://localhost:8000

## Project Structure

- `templates/` - Contains all Twig templates
  - `base.html.twig` - Base template with Bootstrap integration
  - `inc/navbar.html.twig` - Navigation bar template
  - `articles/index.html.twig` - Articles list template
- `src/Controller/` - Contains the IndexController
- `docker/` - Contains Docker configuration files 