# Kiro's personal documentation server setup

This is a quick manifestion of my personal document server I use for myself
for convenience.  It contains an image hosting service and a documentation
server which runs off of markdown formatting.

### Defaults
Image hosting service is ran on `localhost:9004`
Documentation hosting is ran on `localhost:9005`
Change them as you need in `docker-compose.yaml`

### Notes
All "useful" data store files are attached via bound volumes to the local file
file system for easy access.  These attached volumes are folders in the local
directory and are pretty obvious to which one is bound to which image.

## Usage
First run `./configure.sh` to create the volume bound directories,
initialize the requirements, and modify some permissions.
Then you may use the following to build and run the service
```
docker-compose up
```
or the following to run in detached mode
```
docker-compose -d up
```
