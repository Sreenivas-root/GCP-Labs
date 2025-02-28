## Developing Applications with Google Cloud: Storing Application Data

Running Code for the Google Cloud Lab:
    [Developing Applications with Google Cloud: Storing Application Data](https://www.cloudskillsboost.google/catalog_lab/30922)

App is written in Flask, run using Gunicorn (HTTP server on Linux), Cloud Logging, and Firestore database to store books data which uses Storage Bucket.

Use this cmd to run the code
> gunicorn -b :8080 main:app

Release [basic_flask_app](https://github.com/Sreenivas-root/GCP-Labs/tree/basic_flask_app) implements functionality for simple Flask server to run the application

Release [final_flask_app](https://github.com/Sreenivas-root/GCP-Labs/tree/final_flask_app) implements full setup as mentioned above