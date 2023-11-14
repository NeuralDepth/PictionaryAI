# PictionaryAI
This project seeks to use computer vision to recreate a computer-based game of Pictionary, in which a human player draws an image and the computer attempts to guess the drawing.

Check out a demo of my project below!

https://user-images.githubusercontent.com/47067154/167285584-0c96468b-4442-4f87-98a8-76dd0d3fdfe2.mp4


## Development
The development environment is containerized, so both the server and client can be run with a single Docker command. After installing [Docker](https://docs.docker.com/get-docker/), simply run the following command:

```bash
docker-compose up --build
```

The client (React app) will be accessible at `localhost:3000`, and the server (FastAPI app) will be accessible at `localhost:5000`.

To stop the container from running, simply type `Ctrl+C` and then the following command:

```bash
docker-compose down
```
