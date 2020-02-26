# Python Powered Excel

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OddExtension5/Python-Powered-Excel/master)

This repo consist of four small project which based on real-life scenario.

Repo covers:

1. How to control Excel by writing Python code.
2. How to provide end report to companies which enrich in information.
3. How to present your report.


## Running Jupyter Locally via Docker

**Note**: You can run this repo via Docker(locally) or Binder(cloud) (binder button is added above just click on that)

You will need to have Docker installed on your system to create images and run containers. You can find the installation steps for all platforms on the company's [website](https://docs.docker.com/install/)
.

1) Clone the repository for the class either using the UI or your terminal (see above)..

2) Once you have Docker installed, type the following on your terminal to create a Docker image: `docker build -t NAME .` (replace `NAME`, here and in next step, with what you want to call it. Note the period)

3) That will take a little while to create a Docker image, but once completed, you can run your server with the following:
`docker run -p 8888:8888 NAME`

4) Head to `localhost:8888` in your browser and you will be able to access the Jupyter Notebooks.
