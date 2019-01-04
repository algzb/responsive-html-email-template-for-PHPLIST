# Really Simple Free Responsive HTML Email Template for PhpList

This is a simple adaptation of the [Really Simple Free Responsive HTML by Lee Munroe](https://github.com/leemunroe/responsive-html-email-template). 
We added the following PhpList template placeholders:
```
[SUBJECT]
[LOGO]
[CONTENT]
[FORWARDURL]
[FOOTER]
```

[See live preview](https://algzb.github.io/responsive-html-email-template-for-PHPLIST/).

<img src="https://user-images.githubusercontent.com/15963/29055956-8dcca38e-7bb4-11e7-8a86-7b056ebf673d.png" alt="Simple HTML Email" width="500">

## How to use the Responsive HTML Email Template for PhpList

Check the documentation in PHPLIST - [Creating a Template](https://www.phplist.org/manual/ch022_creating-a-template.xhtml)

* Copy all of email.html
* Paste the HTML in PHPLIST (Campaigns > Manage Campaigns Templates > Add new template
* Create a new campaign and select your new template

## How to use the Text Preview / Preheader 

Copy / Paste the following code as the first line of your campaign in PhpList. (Composer -> Source)

```
<span class="preheader">This is preheader text. Some clients will show this text as a preview.</span>
```

## How to use the Call to Action Button 
Copy / Paste the following code into the Composer (Source) in PhPlist. 

```
<table role="presentation" border="0" cellpadding="0" cellspacing="0" class="btn btn-primary">
<tbody><tr><td align="center"><table role="presentation" border="0" cellpadding="0" cellspacing="0">
<tbody><tr><td>

<a href="https://example.com" target="_blank">Call To Action</a> </td>
                                    
</tr></tbody></table></td></tr></tbody></table>
```                        

## Tried and tested on all major email clients

Tested on mobile, desktop and web.

![Templates Tested on Email Clients](https://cloud.githubusercontent.com/assets/15963/17391543/bc289abe-59cb-11e6-9946-605a85f8c522.jpg)


