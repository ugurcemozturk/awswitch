# Change the default AWS profile, without hassle
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)


**awswitch** lets you change your default profile with another named AWS profile, with one single command. It's OS-independent. 
There will be an additional AWS profile after first usage of the **awswitch**. It'll be named as **[previous]** and it will store the latest changed profile to prevent unintended changes.

# Installation

    git clone https://github.com/ugurcemozturk/awswitch
    pip install -r requirements.txt


# Usage

Simply import your new IAM user credentials from **the latest downloaded CSV** to AWS config file, assumed at home folder, **~/.aws/credentials**
 
```
awswitch profile-1
```
or
```
awswitch previous
```
## Flow

```
sequenceDiagram
To
Be
Defined
```

