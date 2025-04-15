# create-repository
# M-Pesa E-commerce Website

A full-stack e-commerce website built with Node.js and MongoDB, featuring a user sign-up system and **M-Pesa STK Push** integration for first-time payments.

## Features

- User Sign-Up with Name, Email, and Phone
- First-Time Payment Required via M-Pesa
- M-Pesa Daraja API Integration (STK Push)
- MongoDB for storing user data and payment status
- Express.js API with environment config support
- Frontend using HTML5, CSS, and vanilla JavaScript

## Technologies Used

- **Frontend:** HTML5, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment:** Safaricom M-Pesa Daraja API

## Folder Structure
Easily set up a new github repository. Reads the name/description from the package.json file if it's present. Sets origin upstream if it's not already set.

```
npm install create-repository -g
```

## Usage

`create-repository` will try to read `package.json` and use the name and description properties.

```
$ create-repository
```

You can also pass values for name and description.

```
$ create-repository --name my-new-project --description "That's all I have to say about that"
```

## License

MIT