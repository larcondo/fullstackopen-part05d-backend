# Part 05 (d) - fullstackopen course

## End to end testing

Repository of backend

fullstackopen course: Part 05 - d ---> [Visit](https://fullstackopen.com/en/part5/end_to_end_testing)

Clone repository:

```console
$ git clone <repo url>
```

Install dependencies:

```console
$ npm install
```
## :warning: IMPORTANT!

After cloning the repository, create the **.env** file with the required variables.

The **.env** file looks like this:

```ini
MONGODB_URI=<text for mongodb_uri>
TEST_MONGODB_URI=<text for mongodb_uri>
PORT=3001
SECRET=<text for secret>
```

## Run the Backend

**OPTION 1:**
  - Run in production mode:
```console
$ npm run start
```
**OPTION 2:**
  - Run in development mode:
```console
$ npm run dev
```

**OPTION 3:**
  - Run in test mode (with frontend and cypress library)
```console
$ npm run start:test
```