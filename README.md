# Automatic Certificate Generator

## Introduction

![Image](github-readme-contents/banner.png)

This simple Python prototype tackles the age-old productivity challenge of automating mundane tasks by generating certificates automatically from a given list of names. By eliminating the need for manual entry of certificate holder names, this script streamlines the process and frees up valuable time for more meaningful work.

At its core, this script leverages Python and OpenCV to achieve its objective. The logic is straightforward: it utilizes a certificate template and dynamically populates it with names from the provided list, generating multiple certificates in a fraction of the time it would take to do so manually.

With its intuitive design and efficient execution, this script exemplifies the power of automation in enhancing productivity and efficiency in various domains. Whether used in educational institutions, corporate settings, or organizational events, this prototype offers a simple yet effective solution to a common productivity bottleneck.

## Technology and Framework

- Python 3.8
- OpenCV


### Why OpenCV?

We use OpenCV to write text on the certificate templates, OpenCV is a popular framework for computer vision.


## How to use it?

**Step 01:** Enter the name list of certificate holders in the "name-data.txt" file.

![Image](github-readme-contents/name-list.jpg)


**Step 02:** Choose a certificate template

![Image](github-readme-contents/certificate-template.jpg)

**Step 03:** Get the X1, Y1 coordinates, to get the X1, Y1 coordinates, use windows print application that is free and easy. To do that, open the print and load the template in it. An example is shown bellow.

![Image](github-readme-contents/xy-coordinates.gif)

**Note** In the bottom of the paint application, it will show the X1, Y1 coordinates.


**Step 04:** Enter the X1, Y1 coordinates in "run.py" script, to do that open the "run.py" in a text editor and, edit the X1, Y1 coordinates that is found on the code line number of 22.

![Image](github-readme-contents/code.jpg)


**Step 05:** Finally, execute the "run.py" script to get the outputs. In the "generated-certificates" folder all the generated certificates will be stored.

```
python run.py

```


#### Generated certificates

![Image](github-readme-contents/generated-certficiates.jpg)

#### Sample Certificate

![Image](github-readme-contents/sample-certificate.jpg)

## To execute the program run the following command. 

```
python run.py

```

# Contact

### 🌐 Website:
[![Visit](https://img.shields.io/badge/Visit%3A%20www.mpowerr.com-%23007ACC?style=flat&logo=google-chrome&logoColor=white&labelWidth=200)](https://www.mpowerr.com)

---

### 📱 Social Media:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/mpowerr-info)
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/mpowerr.info)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/mpowerr.info)
[![X (Twitter)](https://img.shields.io/badge/X-%231DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/MpowerrInfo)
[![TikTok](https://img.shields.io/badge/TikTok-%23000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@mpowerr.info)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@mpowerrinfo)

---
