# C.elegans behavioural experiment encoding 

[![Join the chat at https://gitter.im/Si-elegans/behavioural_experiment_definition](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Si-elegans/behavioural_experiment_definition?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
A respository for the development of a Schema to define Behavioural Experiments that are conducted on C. elegans nematodes.

To validate files downloaded from Si elegans
==================

Change:	

```xml
<root>

by 

<root
    xmlns="http://www.w3schools.com"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://www.w3schools.com behav-exp-xsd1.0.xsd">  
```
	
To add xsd validated documents to Si elegans platform
=============================

Actually limited to admin users

Go to: https://platform.si-elegans.eu/restAPI/behaviouralExperiments_nested/

Makes sure that no description or about tag validated with the xsd is left empty, no <description/> or <about/> otherwise we will receive a "NULL not allowed" message

Select application/xml at the bottom, Ctrl+a (select all document), Ctrl+v (paste) on the Post section and click on POST
 
