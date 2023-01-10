# Shazam Starter Template

The quickest way to get started is with Docker, Docker Compose and this template

> It is assumed that you already have Docker with Compose already installed.
> This template was tested against Docker CE - 20.10.21

## Clone the starter template
```
git clone --depth 1 git@github.com:bwks/shazam-starter.git <project-name>
```

## Move to project directory
```
cd <project-name>
```

## Remove Git History
```
rm -rf .git
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