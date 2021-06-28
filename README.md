# Talk Time Analytics using Deepgram

[![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](#remix-on-glitch)

Analyzing the talk time of participants in a classroom, meeting, or phone call can help you improve participant engagement, sales presentations, and support response. This app aims to demonstrate how to use Deepgram API to compute
talk time per speaker. We then display the calculated talk time
in a pie chart.

## Prerequisites

You will need:

- A [free Deepgram account](https://console.deepgram.com/signup?utm_source=DEV_REL&utm_medium=github&utm_content=talk-time-analytics)
- A Deepgram [API key](https://developers.deepgram.com/api-reference/speech-recognition-api#tag/API-Keys)

## Getting Started

You can run this application by remixing it on Glitch or by running it on your
local computer.

### Remix on Glitch

Glitch comes with an online editor, so you'll have all the necessary tools
to explore your own app instance.

To remix this application on Glitch replace `YOUR_DEEPGRAM_API_KEY` in the
following URL with your Deepgram API Key:

> https://glitch.com/edit/#!/import/github/deepgram/talk-time-analytics?PORT=3000&DG_KEY=YOUR_DEEPGRAM_API_KEY

When accessing this URL in your browser, the project will be forked and deployed.

### Run on localhost

To run this project on your local computer:

#### Clone the repository

Either clone or download the repository to your local machine, in a new directory.

```bash
# Clone this repo
git clone https://github.com/deepgram/talk-time-analytics.git

# Move to the created directory
cd talk-time-analytics
```

#### Configure the settings

Your application will need to know more about you before it can run. Copy the
`.env-example` file into a new file named `.env` and edit this new file to
reflect the settings you want to use:

- `PORT`: The port you wish to run the application on. Leaving this as port 3000
is acceptable.
- `DG_KEY`: The Deepgram API key you created earlier in this tutorial.

#### Install the dependencies

In the directory where you downloaded the code, run the following command to
bring in the dependencies needed for this project.

```bash
npm install
```

#### Start the server

With the configuration done and the dependencies in place, your application
is ready to go! Run it with:

```bash
npm start
```

## Development and Contributing

Interested in contributing? We ❤️ pull requests!

To make sure our community is safe for all, be sure to review and agree to our
[Code of Conduct](./CODE_OF_CONDUCT.md). Then see the
[Contribution](./CONTRIBUTING.md) guidelines for more information.

## Getting Help

We love to hear from you so if you have questions, comments or find a bug in the
project, let us know! You can either:

- [Open an issue](https://github.com/deepgram/talk-time-analytics/issues/new) on this repository
- Tweet at us! We're [@DeepgramDevs on Twitter](https://twitter.com/DeepgramDevs)

## Further Reading

Check out the Developer Documentation at [https://developers.deepgram.com/](https://developers.deepgram.com/)
