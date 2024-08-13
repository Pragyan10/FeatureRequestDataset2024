# FeatureRequestDataset2024

# Repository for web scrapped data from different open source projects - work in progress

## App included 
1. Mastodon - https://github.com/mastodon/mastodon-android
2. Signal - https://github.com/signalapp/Signal-Android

## Feature Request Counts 
1. Mastodon - Open Requests - 36
2. Mastodon - Closed Requests - 17
3. Signal - Closed Requests - 414

## Directory Details 
1. **Samples** - This directory contains samples pulled from the complete dataset. We have 3 files of sample size 5, 10, and 50 which all are pulled using stratified sampling.
2. **CombinedIntoSingleFile** - This directory contains the merged feature requets into single files - all requests from all apps, all closed requests from all the apps.
3. **Feature Request** - <u> **This is the main directory ** </u> In this directory you will find 3 files. 2 for Mastodon and 1 for Signal. 2 files for Mastodon include the open and closed feature request. 1 file for signal is the closed feature request since there are no open requests. Filename format is - (app name)_(status)_(date)_Final-(NumberOfFeatureRequestsInTheFile)


## Sampling technique in **Samples** 
- For pulling the samples out the complete dataset, we employ stratified sampling. 

