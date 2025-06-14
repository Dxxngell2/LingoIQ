# Built with

<p align="left">
<img src="https://ui-lib.com/blog/wp-content/uploads/2021/12/nextjs-boilerplate-logo.png" height="50px">&nbsp; &nbsp; &nbsp;
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/1024px-Typescript_logo_2020.svg.png?20221110153201" height="50px">&nbsp; &nbsp; &nbsp;
<img src="https://pbs.twimg.com/profile_images/1526251266862505985/KlWqqTp1_400x400.png" height="50px">&nbsp; &nbsp; &nbsp;
<img src="https://pbs.twimg.com/profile_images/1504919223168077836/RSsCSpKf_400x400.jpg" height="50px">&nbsp; &nbsp; &nbsp;
<img src="https://trpc.io/img/logo.svg" height="50px">&nbsp; &nbsp; &nbsp;
<img src="https://www.svgrepo.com/show/374002/prisma.svg" height="50px">
</p>

## LingoIQ
LingoIQ is a web application that allows users who speak different languages to converse with ease by translating the audio on the fly and speaking the translated audio in the native language of the user as well as provide them with translated captions. It also offers HD video and screen share, and can accommodate up to 100 concurrent users. The application also generates automatic meeting summaries and transcripts, making it easy for participants to review important details from the meeting.

## Use cases
- Startups and MNCs with international work culture.
- Freelancers with daily foreign communication.
- Content creators & live streamers to reach global range audience.
- Educational organizations to teach courses to multilingual students.

- [**Next JS**](https://nextjs.org/): React-based framework for building server-side rendered and statically exported web apps.
- [**Typescript**](https://www.typescriptlang.org/): Statically typed superset of JavaScript, adds type annotations to enhance code reliability & readability
- [**Livekit**](https://livekit.io/): End-to-end WebRTC infrastructure to build live video and audio applications.
- [**Pusher**](https://pusher.com/): WebSockets solution for Realtime updates and bidirectional communication.
- [**TailwindCSS**](https://tailwindcss.com/): Utility-first CSS framework
- [**Planetscale**](https://planetscale.com/): Highly scalable, globally distributed database
- [**tRPC**](https://trpc.io/): Provides a simple, type-safe way to build APIs for TS & JS
- [**Prisma ORM**](https://www.prisma.io/): Modern, type-safe ORM for Node.js and TS
- **APIs used**: Browser's [Webspeech](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) API for transcribing and tts/speech synthesis. [Google-translate-browser](https://www.npmjs.com/package/google-translate-api-browser) API for translating texts, OneAI's [Summarizer](https://www.oneai.com/summarize) for summarizations of meeting transcripts.

> **Note**
> This project was bootstrapped with [create-t3-app](https://create.t3.gg/). Check [package.json](https://github.com/swasthikshetty10/hackoverflow/blob/main/package.json) to know all the dependencies and tech stack we used.

## Features
- Multilingual Meeting Support
- Real-time Translation and Transcriptions
- Automatic Meeting Minutes generation
- Support to upto 100 concurrent users
- Supports HQ Video streaming

## Architecture
<img width="1073" alt="Screenshot 2023-03-18 at 11 09 44 AM" src="https://user-images.githubusercontent.com/83623339/226187854-03ec9559-1122-42a3-93c7-80614fdae396.png">

## Installation steps (windows)


1. Open Powershell as administrator and run `git clone https://github.com/Dxxngell2/LingoIQ.git`
   - Change current directory `cd hackoverflow`
2. Run the installtion script

```bash
./install.ps1
```


## Known Issues
- There is latency of around 5-6 seconds between the original time and the time when translated audio is spoken out. The latency issue can be tackled by following ways:
  - Use native models for faster transcriptions
  - Use paid APIs for quicker translations like Whisper AI, Google translate etc.
  - Develop a learning model to predict the next moves of the speaker, which is a replacement for WebSpeech API's final transcription boolean.
- As the app relies on browser's native Web Speech API for transcribing and tts, few browsers like Brave with known issues for this API and microphone functions tend to fail at running the app successfully.

## Future scope of development
- Use deepAI models to sync video/lip movements & translated audio.
- Resemble the spoken audio(translated) to source audio(speaker) pitch.

## Team Members

| <img src = "https://avatars.githubusercontent.com/u/83623339?v=4" width="50px"> | <img src = "https://avatars.githubusercontent.com/u/62538932?v=4" width="50px"> | <img src = "https://avatars.githubusercontent.com/u/74966490?v=4" width="50px"> |
| :-----------------------------------------------------------------------------: | :-----------------------------------------------------------------------------: | :------------------------------------------------------------------------------: |
|              [Nagaraj Pandith](https://github.com/nagarajpandith/)              |  [Swasthik Shetty](https://github.com/swasthikshetty10/](https://github.com/rudra246)>)  |                 [Tanishka Rao](https://github.com/tanishkarao16)                 |

## License
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This repository is licensed under [Apache License 2.0](https://github.com/swasthikshetty10/hackoverflow/blob/main/LICENSE)

## Attributions

- [Icon from - Flaticon](https://www.flaticon.com/free-icons/)
