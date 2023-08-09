<br/>
<p align="center">
  <a href="https://github.com/Antovex/Automatic-S3-event-Trigger">
  </a>

  <h1 align="center">Automatic-S3-event-Trigger</h3>

  <p align="center">
    An event trigger within few clicks
    <br/>
    <br/>
<!---    <a href="https://github.com/Antovex/Automatic-S3-event-Trigger">View Demo</a>
    .
    --->
  </p>
</p>



## About The Project

This project is an application of the real life based scenario. This is a simple event based trigger, where when we upload a file in a specific/needed AWS S3 bucket, an email is sent to the mentioned email address.

## Architecture
<p align="center">
<img src="https://github.com/Antovex/Automatic-S3-event-trigger/blob/main/S3-event-triggering/S3-event-triggering-architecture.png" width="600" height="300">
</p>

## Getting Started

You just need a laptop with an internet connection and code editor for this project and it will be completed within just few clicks.

### Prerequisites

Make sure you have an active AWS account (logged in as root or administrative IAM user) and an unrestricted email, preferably gmail.

### Installation

1. Clone this repo in your local system.

2. Open the .py file and update the <REGION> and <ACCOUNT ID>

3. Open the .sh file and update the <REGION> and <EMAIL>

4. Open AWS console and log into your account.

5. Open Terminal of your account.

6. On the top right hand side corner, click on the options and then select upload files.

7. Upload all the files that you just cloned.

8. Then just paste the following command on the terminal and watch the project build itself.

```sh
./s3-notification-triggers.sh
```

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/Antovex/Automatic-S3-event-Trigger/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AddedFeature`)
3. Commit your Changes (`git commit -m 'Add some AddedFeature'`)
4. Push to the Branch (`git push origin feature/AddedFeature`)
5. Open a Pull Request

## Author

* **Antarin Ghosal** - *IT Student* - [Antarin Ghosal](https://github.com/Antovex)
