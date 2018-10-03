# Tools to assist in troubleshooting Kaspersky-issues on Windows
![My image](https://dha4w82d62smt.cloudfront.net/items/0s3r2T2h0V3z1I110S3v/Image%202018-07-24%20at%206.59.24%20PM.png)
## Intro

This repo is available for everyone who would like to use some tools to interact with troubleshooting Kaspersky home products on Windows PCs. Oftentimes troubleshooting issues, you'll need to perform a certain set of steps. These tools will aid in this (for automation).

## Reason of creation

Like any persistent software on a Windows PC, Kaspersky Lab products also leave remnants or things get broken. Here you can download the necessary tools to resolve the issue.

# Tool: KLeaner

Click [here](https://github.com/leoleogr/Kaspersky/raw/master/KLeaner/KLeaner.exe "Click here to download") to download KLeaner.

**KLeaner** performs the following actions

- It first elevates itself to get admin rights (this is to prevent for the user to right-click > run as admin).
- It then changes the HOSTS file to the default MS Windows one.
- It changes all the adapters to use DNS server 1.1.1.1 and backup 1.0.0.1
- It cleans your temp folders (Win + R > temp & Win + R > %temp%
- It then flushes your DNS and finally reboots your PC.




# Disclaimer

I have no affiliation with Kaspersky Lab, Mozilla Firefox or any of the mentioned other services or products. All rights belong to them. I'm still checking if a license is needed to distrubute these files. As this is a work in progress, many details are still missing. I'll be working on this as a side-project to update it with as much info as possible.
