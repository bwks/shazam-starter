# shazam-starter

Shazam is a Static Site Generator for Masochists.

The quickest way to get started is with Docker/Compose

## Clone the starter template
```
git clone --depth 1 git@github.com:bwks/shazam-starter.git <project-name>
```

## Move to project directory
```
cd <project-name>
```

## Update project variables in `bin/dev` file
```
APP_NAME="<UPDATE>";
APP_OWNER="<UPDATE>";
APP_OWNER_EMAIL="<UPDATE>";
```

## Initialize the project
```
bin/dev init
```

## Start the dev server
```
bin/dev up
```