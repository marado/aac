# Otsimo AAC PECS App

An app that helps kids with autism to compose phrases.

Otsimo AAC is an application that enables kids with autism who can not speak to compose phrases by tapping on the words. Otsimo AAC uses a picture exchange communication system.

This project was tested with the latest version of Node.js and npm. Please make sure you have atleast Node.js 5+ and npm 3+ installed.

## Usage & Development

- Clone or fork this repository
- run `npm install` to install dependencies
- run `npm run start` to fire up a dev server
- open browser to [`http://localhost:3001`](http://localhost:3001)

## Build

To create a ready to production distribution package of the project, please run:

```
npm run build
```

The generated files will be available at `/dist`.

## Testing

This seed has protractor and karma for end to end testing and unit testing respectively.

### Unit Testing

Make sure your tests are named with a `-test.js` suffix. To run karma simply run:

```
npm test
```

### End to end Testing

To start protractor tests please run:

```
npm run protractor
```

### Update Symbols

to update the symbols:

```
npm run update-symbols
```
