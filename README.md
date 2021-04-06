# Barista

Barista is the sign up process for Cold Brew. This code base will use the [beempy](https://beem.readthedocs.io/en/latest/) library. Cold Brew is built on the [HIVE blockchain](developers.hive.io) to store content and accounts. The current problem is on boarding users to the platform with a HIVE blockchain account. This web API will be used to create the keys needed to sign up a new user.

## Django

Beempy is a python library with a set of functions to create new accounts. Django will be used as the server for users to interact with and generate an account for Cold Brew.

This web app will have routes to generate a private and public key pair given a username. The flow will look like this.

## Beempy

To create a blockchain account on HIVE, users need to generate a public and private key pair to have access to their crypto earned from their content. Beempy has a keygen function that generates a master password and four public keys to have specific permissions on the app.

The keys and password is used to create an account with the beempy library.

## Thinking ahead

A database will need to be used to store keys. Hosting will also be another problem when it is finished.

### Conclusion

I could use help with initializing the django application and basic views for inputting information. I will handle the logic of generating keys and creating accounts. Development tasks will be under the project tab in GitHub.
