# Drupal Modules
> Here lies a collection of Drupal 8 modules worth exploraing. 
> 
> Here are some of the [most used packages](https://www.drupal.org/project/usage)

The goal of this project is to develop an understanding of what drupal modules are, how to install using composer, and give a basic idea of what kind of functionality these modules add to a basic drupal instance. Each module is listed with it's machine name for reference when installing via the command line *(recommended)*

## module_filter
	composer require drupal/module_filter
	
[Module Filter](https://www.drupal.org/project/module_filter): quickly find the module you are looking for without having to rely on the browsers search feature... *why isn't this core?*

![Preview](https://www.drupal.org/files/project-images/module_filter-3.0-modules.png)

## webform 
	composer require drupal/webform

[Webform](https://www.drupal.org/project/webform): Webform is the module for making forms and surveys in Drupal. After a submission customizable e-mails can be sent to administrators and/or submitters. Results can be exported into Excel or other spreadsheet applications. Webform also provides some basic statistical review and has an extensive API for expanding its features.

This is a robust and actively maintained module. It's heavy and opinionated, but sometimes that's ok! 

![Preview](https://www.drupal.org/files/issues/2018-05-19/webfork-wizard-admin.png)

## honeypot
	composer require drupal/honeypot

[Honeypot](https://www.drupal.org/project/honeypot): Honeypot form protection means that an invisible field is added to a form. If this invisible field is filled out (bots will usually put in a value), then the form will return an error. Normal users (read: human beings) won't ever see the field, so they won't fill it out. Even if they do, the field is labeled in such a way as to indicate the human shouldn't fill out the field.

![Preview]()

## imce
	composer require drupal/imce
	
[IMCE](https://www.drupal.org/project/imce): IMCE is an image/file uploader and browser that supports personal directories and quota.

![Preview](https://www.drupal.org/files/images/imce-screenshot.jpg)
