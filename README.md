1. clone this repo
2. from vs code's terminal, run: 
`docker-compose up --build --no-recreate -d`
3. build and start the application
`docker exec -ti webdevt_first sh`
4. then, while inside the container:
`npm i && npm run dev`