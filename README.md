# GCUI

This is a project to collect the bits of UI code that CDS creates into a single place, ready to be reused.

## Installation

In your project folder run either of the following commands:

```sh
yarn add @cdssnc/gcui
# or
npm i @cdssnc/gcui
```

## Usage

```javascript
import {
	WordMark
	EnerguideLogo,
	GoCSignature,
	DownwardChevron,
	UpwardChevron,
	PhaseBadge,
	PhaseBanner,
	Button,
	ErrorBoundary,
 } from '@cdssnc/gcui'

// Do something with <WordMark />
```

## Seeing the components

To explore the components and their documentation, run the following commands:

```sh
git clone https://github.com/cds-snc/gcui.git && cd gcui
npm i
npm run storybook
```

You can then explore the components visually in a React Storybook by going to [localhost:9001](http://localhost:9001/)

## Running the tests

```sh
npm t
```
