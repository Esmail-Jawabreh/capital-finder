# capital-finder

## Lab: Class 16 - Serverless Functions
<br>

### Feature 
<br>

- Sign up with [Vercel](https://vercel.com/docs/concepts/get-started/deploy).
- Create a repository on Github and link it to Vercel account.
- Use [requests](https://requests.readthedocs.io/en/latest/) library to interact with [REST Countries API](https://restcountries.com/#rest-countries)
- Create a serverless function following Vercel’s get-started directions that handles two kinds of queries:
    - The serverless function should handle a `GET` http request with a given country name that responds with a string with the form `The capital of X is Y`
        - E.g. `/capital-finder?country=Chile` should generate an http response of `The capital of Chile is Santiago`.
        - The serverless function should handle a `GET` http request with a given capital that responds with a string with the form `The capital of X is Y`
            - E.g. `/capital-finder?capital=Santiago` should generate an http response of `Santiago is the capital of Chile`.

<br>

### Configuration
<br>

- Name your Github project `capital-finder`.
- Name your Vercel project starting with `capital-finder` then additional text as needed to give the project a unique name.
    - E.g. `capital-finder-ursula-lopez`
- File structure should match Vercel’s [Python requirements](https://vercel.com/docs/concepts/functions/serverless-functions/supported-languages#python).
    - Refer to demo for details.

<br>
<br>

---
<br>

### example urls:

#### Country:
- https://capital-finder-opal.vercel.app/api/country?name=italy
- https://capital-finder-opal.vercel.app/api/country?name=japan

#### Capital: 
- https://capital-finder-opal.vercel.app/api/capital?capital=amman
- https://capital-finder-opal.vercel.app/api/capital?capital=paris

<br>

---
<br>

**- Esmail Jawabreh**