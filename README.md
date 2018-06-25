Remote Pi
===========

The goal of this project is to control a Raspberry Pis IO pins from A Google Cloud Platform PubSub queue.

<img src="https://www.raspberrypi.org/app/uploads/2018/03/RPi-Logo-Reg-SCREEN.png" />

# Setup

## Setup account in GCP
- Create a project in GPC
- Enable the PubSub API
- Create a user with access to READ on PubSub in GCP. Download the credentials.json file.

## Setup project locally

- Clone the repo your local machine.
- Run `dep ensure --v`
- Replace `projectID`, `topicID` & `credentialsFile` variables
- Run `go run application.go`