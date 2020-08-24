<div align="center">
  <h1>fhg-test</h1>
  <p>Project Documentations & Deployment Scripts</p>

  <div>
    <a href="https://github.com/fhg-test/fhg-test/commits" aria-label="Commitizen Friendly">
      <img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square">
    </a>
    <a href="https://github.com/fhg-test/fhg-test" aria-label="Prettier Code Style">
      <img src="https://img.shields.io/badge/code_style-prettier-brightgreen?style=flat-square">
    </a>
    <a href="https://github.com/fhg-test/fhg-test/blob/master/LICENSE" aria-label="MIT License">
      <img src="https://img.shields.io/github/license/fhg-test/fhg-test?color=brightgreen&style=flat-square">
    </a>
  </div>
</div>

## Project Overview

Fullerton Healthcare Group is looking to build a wellness booking portal to facilitate information
transfer and booking of all activities and approval/rejection workflows.

More detailed information at [Developers Technical Test.pdf](/docs/developers-technical-test.pdf).

## Architectural Design

![Architectural Design](docs/architectural-design.png)

## Database Design

![Database Design](docs/database-design.png)

## UI Design

WIP

## Technologies

- Frontend
  - Web-based Application: React.js framework [Next.js](https://nextjs.org), global state management [Redux](https://redux.js.org), functional CSS (utility-first CSS) [TailwindCSS](https://tailwindcss.com), CSS in JS [Styled JSX](https://github.com/vercel/styled-jsx)
  - API Client: [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- Backend
  - API Service: Node.js framework [Express.js](https://expressjs.com), object schema validation [Yup](https://github.com/jquense/yup), session-based authentication [Passport.js](http://www.passportjs.org)
  - Database Access: [Mongoose ODM](https://mongoosejs.com)
- Database
  - Main Data: [MongoDB](https://www.mongodb.com)

Other tools using for local development:
- [TypeScript](https://www.typescriptlang.org)
- [ESLint](https://eslint.org)
- [Prettier](https://prettier.io)
- [Webpack](https://webpack.js.org)

## Repositories Organization

- [fhg-test](https://github.com/fhg-test/fhg-test) (this repo): main repo of the project that contains documentations & deployment scripts
- Frontend
  - [web](https://github.com/fhg-test/web): Web-based Application
- Backend
  - [api](https://github.com/fhg-test/api): API Service
- Shared Libraries
  - [core](https://github.com/fhg-test/core): Domain Entity type definitions, used in Web-based Application & API Service
  - [rest](https://github.com/fhg-test/rest): API Client, used in Web-based Application to communicate with API Service

## Development & Deployment Guides

WIP

## Authors

[Phat Pham](https://github.com/phatpham9)

## License

[MIT](https://github.com/fhg-test/fhg-test/blob/master/LICENSE)
