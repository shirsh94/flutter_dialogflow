# Flutter Chatbot with Dialogflow

## Overview

Welcome to the Flutter Chatbot with Dialogflow project! In this Flutter project, we'll be creating a simple chatbot using Dialogflow, a tool provided by Google. Dialogflow allows you to build chatbots without requiring extensive knowledge of machine learning or natural language processing (NLP). This README will guide you through the process of setting up your chatbot using Dialogflow and integrating it into a Flutter application.

## Table of Contents

- [Getting Started](#getting-started)
  - [Dialogflow Setup](#dialogflow-setup)
  - [Google Cloud Console Setup](#google-cloud-console-setup)
- [Flutter Project Setup](#flutter-project-setup)
  - [Dependencies](#dependencies)
  - [Assets Configuration](#assets-configuration)
  - [Code Implementation](#code-implementation)
- [Usage](#usage)
  - [Run the Flutter App](#run-the-flutter-app)
  - [Interacting with the Chatbot](#interacting-with-the-chatbot)
- [Contributing](#contributing)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## Getting Started

### Dialogflow Setup

1. Visit [Dialogflow Console](https://dialogflow.cloud.google.com/) and sign in with your Google account.

2. Create a new agent by clicking on "Create an agent" and provide a name, for example, "ShirshShuklaInfoBot."

3. Note the **Project ID** from the settings icon.

4. Create an intent for your chatbot. You can customize the training phrases and responses based on user inputs.

5. Navigate to the Google Cloud Console ([Google Cloud Console](https://console.cloud.google.com/)).

6. Log in with the same Google account used for Dialogflow.

7. In the Google Cloud Console, go to **APIs & Services > Credentials**.

8. Create a new service account, grant it access to the "Dialogflow API Admin," and download the JSON key.

### Flutter Project Setup

#### Dependencies

Add the Dialogflow Flutter package to your `pubspec.yaml` file:

```yaml
dependencies:
  dialog_flowtter: any
```

#### Assets Configuration

1. Create an `assets` folder in your Flutter project.

2. Rename the JSON key file downloaded from Google Cloud Console to `dialog_flow_auth.json` and place it inside the `assets` folder.

3. Update your `pubspec.yaml` to include the asset:

```yaml
assets:
  - assets/dialog_flow_auth.json
```

#### Code Implementation

Implement the Flutter chat screen using the provided code in `main.dart` and `message_view.dart`. Make sure to adjust the code according to your project structure.

## Usage

### Run the Flutter App

Run the Flutter app on an emulator or a physical device:

```bash
flutter run
```

### Interacting with the Chatbot

1. Open the app and start typing messages.

2. The chatbot will respond based on the predefined intents and responses set up in Dialogflow.

3. Explore the code to understand how messages are sent to Dialogflow and received responses are displayed.

## Contributing

If you find any issues or have suggestions for improvements, feel free to contribute. Create a pull request or open an issue on [GitHub](https://github.com/shirsh94/flutter_dialogflow).

## Contact

- Medium: [Shirsh Shukla]([https://www.linkedin.com/in/shirshshukla/](https://shirsh94.medium.com/))
- youtube: [Shirsh Shukla]([https://www.linkedin.com/in/shirshshukla/](https://www.youtube.com/channel/UCbBdLnqrcnTU4IN3QmkDdIw))
- Stack Overflow: [Shirsh Shukla]([https://www.linkedin.com/in/shirshshukla/](https://stackoverflow.com/users/13098417/shirsh-shukla))
- LinkedIn: [Shirsh Shukla]([https://www.linkedin.com/in/shirshshukla/](https://in.linkedin.com/in/shirsh-shukla-95b85786))
- Twitter: [@shirsh_shukla]([https://twitter.com/shirsh_shukla](https://twitter.com/shirsh94?lang=en))

## Acknowledgments

Special thanks to the Flutter and Dialogflow communities for their valuable contributions and support.


