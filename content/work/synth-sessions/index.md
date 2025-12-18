+++
title = 'Synth Sessions'
position = 'Full Stack Web Developer'
location = 'New York City, USA'
image = "synth-sessions.png"
date = 2019-07-01T00:00:00-07:00
repo = 'https://github.com/sebastosh/synth-session'
tags = ['ReactJS','ToneJS','NexusUI','Rails API','JWTAuth']
+++

## Multi-synthesizer jamming sessions app

A web app designed for multi-synthesizer jamming. Users can create a session and choose to add one or more synthesizer modules (current choices, a Mono Synth, Duo Synth, and FM synth) to their sessions. They can play each synth with the on-screen keys or with a computer keyboard.

Key Technologies, Packages, and Gems:

Frontend:

- React
- Tone.js
- nexusUI
- react-select

Backend:

- Rails 5 API
- JWT token authentication
- BCrypt
- Postgres database
- fast_jsonapi serializer
  
Core Features:

- Unregistered users can jam solo with synths but will be prompted to signup when saving a session or synth parameters.
- A session show page displays a menu to add 1 to 3 different synthesizer modules at any time.
- Session and modules names can be edited inline.
- Module parameters (Gain, Envelopes, Harmonics, etc..) can be each be saved to backend server and restored in future sessions.