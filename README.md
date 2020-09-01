# Django|Python Enviroment in Docker

- **Repository:**
	- A docker enviroment for your django application.
- **Stack:** Python, Django.
- **Services:** Django server.
- **Year:** 2020.

This repository provides a django development enviroment.

## Step 1. Clone the repository.

Open a Terminal, browse your projects location and run:

```bash
git clone https://github.com/diegoulloao/django-docker-startpoint.git project-name
```

## Step 2. Create the Django app.
Enter in your `project-name` folder, then create/copy your Django app in the `app` directory.

## Step 3. Build the dockerfile.

In `project-name` directory, run:
```
docker build .
```

```
docker-compose build
```

## Step 4. Run the service.

Finally run:

```
docker-compose up
```

Open up your browser to http://localhost:8080/ and you should see your django app running as intended.

--

**@diegoulloao · 2020**
