+++
draft = true
title = 'Teleprompter App'
position = 'Tech Project'
location = 'New York City, USA'
image = 'teleprompter-app.png'
date = 2019-03-01T00:00:00-07:00
github = 'https://github.com/sebastosh/teleprompter-app'
tags = ['JavaScript', 'QuillJS','Rails API']
+++


A web based teleprompter interface allowing a speaker to read scripts on camera or to a live audience.

Using Vanilla Javascript to create an interactive single page application through DOM manipulation, incorporating QuillJS library to invoke a WYSIWYG word processing editor with full CRUD capability. Ruby on Rails API backend used for document saving.

Built at [@flatiron-school](https://github.com/flatiron-school) with [@mmcgovern0](https://github.com/mmcgovern0) and [@jmhill91](https://github.com/jmhill91).

## Key Technologies, Packages, and Gems

- Front End

  - Javascript
  - QuillJS
  - HTML, CSS

- Back End
  - Rails 5 API
  - Postgres database

## Core Features

- User can access and perform full crud on all scripts from the database.
- A user can create a new script.
- Each script can be edited in a QuillJS WYSIWYG word processing editor module.
- Each script can switched to prompt mode.
- Scrolling currently is set at a fixed speed and is activated by pressing the "Return" key on the computer keyboard.
