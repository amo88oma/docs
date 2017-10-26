---
seo:
  title: Securing Your Registration or Sign-Up Form
  description: Keeping Your Registration Form Secure
  keywords: double, opt-in, secure, sign, up, registration, form, captcha, bot, abuse, address
title: Securing Your Registration or Sign-Up Form
weight: 0
layout: page
zendesk_id: 200182928
navigation:
  show: true
---
Registration forms are a great way to follow up people’s interest in what you are offering on your website. 
Unfortunately, registration forms can be a source for collecting low quality and [Spam Trap]({{root_url}}/Classroom/Deliver/Undeliverable_Email/spam_trapped.html) 
email addresses. Which if sent to, will damage your sending and business reputation. Fortunately, there are many helpful 
techniques to avoid the issue that can be caused by registration forms.

1. Have your recipient enter their email twice. 
Sometimes in the registration process, a person may mistype their email address (person@domain.com or person@@domain.com). 
By entering the email address twice and having a system in place that checks that the addresses match up, there is a much 
smaller chance of accidentally entering an invalid address.
1. Use a [CAPTCHA](https://www.google.com/recaptcha/intro/) to protect your form against bots.  
    - Bots can exploit unprotected form by systematically using your registration form to send unwanted and malicious mail. 
    - A Captcha is a test to ensure that form is filled out by a human being as opposed to a bot. The task is not replicable by a bot but easily replicated by a human being.
1. Make sure the email addresses being registered exists. 
One common issue that arises with email registration forms is people registering false or fake addresses. To prevent this, the form can say that the service is not granted unless they confirm via email that they would like the service. 
This can be done with a Double [Opt-in]({{root_url}}/Glossary/opt_in_email.html) 
email, confirming that their address exists. A double opt-in email not only helps ensure that there is an actual 
human being registering but also validates that the recipient did indeed sign up for your registration. 
SendGrid has partnered with [BriteVerify](https://sendgrid.com/partners/briteverify/) to help ensure the validity of your email 
addresses by removing invalid, risky and inactive emails from existing lists inside of SendGrid right from the 
BriteVerify app.
https://www.screencast.com/t/AlQumJKHghttps://www.screencast.com/t/AlQumJKHg
Feel free to view our [Security Checklist]({{root_url}}/Classroom/Basics/Security/security_checklist.html)
for more security tips.