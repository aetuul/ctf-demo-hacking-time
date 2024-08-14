# ctf-demo-hacking-time
A simple Capture The Flag challenge where password reset tokens are generated based on the current time.
## Running the app locally
### Build the container
`sudo docker build -t time-hacking-demo .`
### Run the app
`sudo docker run -d -p 5000:5000 time-hacking-demo`
