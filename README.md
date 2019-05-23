# Elections_Bot_Detection_pipeline

**As seen here in the [Independent](https://www.independent.co.uk/voices/european-elections-parliament-bots-social-media-matteo-salvini-far-right-a8924831.html) and the full version here on [Medium](https://medium.com/malicious-bots-actively-boosting-the-far-right/malicious-bots-actively-boosting-the-far-right-ahead-of-eu-elections-e651835a8782) .**

This code was designed to look at bot frequencies in the EU Parliament elections of 2019 and compare between nations and political groupings.

## Introduction
The 21st century has brought with it a wealth of new methods for data collection and analysis. Due to the convergence of digital trace data availability, more transparent data and code sharing norms, and relatively cheap and plentiful computer processing capabilities, researchers with a laptop and an internet connection can now access a large and growing set of tools and methods. The implications of the "computational revolution" is profound for the study of social and political processes, but the skills required to collect and harness these new sources of data are typically not taught to social scientists. This code is for anyone who is interested in studying phenomena that are of social and political importance using the growing set of computational methods that are being used to understand these phenomena in new ways. While these processes are reasonably accessible, it is also critical to understand their limits especially in an adversarial problem space such as bot-detection.

This code is designed to iterate over a table of hashtags and preserve what nation and political leaning each hashtag represents. The hashtags were acquired by looking at the Twitter pages of the parties that currently had MEPs in Parliament or otherwise seemed likely to.

## Authentication, Tweet Extraction, and Bot Detection
The first part of the code examines how researchers can extract data from Twitter, a popular online news and social networking platform. While Twitter provides more access to its data than many other platforms, extracting data from Twitter's servers requires using its Application Programming Interface (or API). This code will cover useful concepts when working with Twitter's API, including rate limiting and error handling, as well as methods for detecting whether Twitter users are humans or automated accounts (i.e. bots). This code is designed to run on Google's Colab for ease of access but you could just as easily run it locally on Jupyter notebooks.
