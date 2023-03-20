---
title: Integrating ANVILL into an LMS (Learning Management System)
description: LTI integration
published: true
date: 2020-10-16T16:37:41.580Z
tags: lms, lti
editor: markdown
---

# Overview

ANVILL supports integration into an LMS using the LTI 1.3 specification. This allows an external LTI link that is created on the LMS to correspond to a single, unique lesson.

One caveat is that the LTI version of ANVILL is more restrictive than the stand-alone version. Because it depends on the LMS for authentication (anyone who is a member of the LMS can access the lesson), and also for organization, some features such as sharing, folders, etc are not available in the LTI version.

For more information on our security and privacy practices, see our [ANVILL Security & Privacy](/teachers/lti/security) help page.

# Supported LMS Platforms

- Canvas
- Moodle
- Blackboard
- Brightspace/D2L

# Integration Process

1) First apply for LTI access for your LMS via the application form at https://anvill.uoregon.edu/settings/lti/apply.
1) If possible, create ANVILL accounts using both the educational contact email and the technical contact email.
1) Once approved, LTI credentials will be available on your ANVILL settings page: https://anvill.uoregon.edu/settings/lti
1) Depending on your LMS type, have your LMS administrator follow the relevant guide below.

# Canvas Integration Guide

Integrating ANVILL into Canvas is fairly straighyforward. It requires that you have administrative access to the Canvas LMS and an existing account on ANVILL using your institutional email address.

## Installation 

1) Log in to Canvas as the account, sub-account or instructor, depending if you want ANVILL enabled for all courses within an account, sub-account, or just a single course.
1)  Go to the app settings page for the account: 
	- All courses in account or sub-account: /accounts/{accountId}/settings/configurations 
	- Single course: /courses/{courseId}/settings/configurations 
1)  Click the “+ App” button at the top of the page. 
1)  Fill in the form: 
	- Name: ANVILL (or whatever you  wish teachers to see the LTI tool as). 
	- Consumer Key: You can retrieve this from your ANVILL account at https://anvill.uoregon.edu/settings/lti in the public key column. 
	- Shared Secret: You can retrieve this from your ANVILL account at https://anvill.uoregon.edu/settings/lti in the secret key column. 
	- Launch URL: https://anvill.uoregon.edu/lti 
	- Domain: Leave blank. 
	- Privacy: Public (Note, ANVILL won’t work if this is not set to public). 
	- Custom Fields: Leave blank. 
	- Description: Leave blank or fill in a relevant description of what ANVILL will be used  for with your institution. 
1)  Click ‘Submit’ at the bottom of the form.
  
## Usage 

1) Log in as an instructor. 
1) Go to the course modules page: /courses/{courseId}/modules 
1) Create a new module. 
1) Click the “+” button for  the module. 
1) Select “External Tool” in the  “Add to module” drop down. 
1) Click “ANVILL”, which will populate the URL link with the correct LTI url. 
1) Click “Add Item”. 
1) Make sure to publish the module so students can see the lesson.
