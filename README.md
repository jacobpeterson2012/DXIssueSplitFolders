# SFDX Issue example
When a object has fields split across mulitple pacakages force:source:push does not work.   You will recieve the following error:
**An object 'Account.TestField2__c' of type CustomField was named in package.xml, but was not found in zipped directory**

**Note**
sfdx-project.json has two packageDirectories defined which should be supported.

## Steps to recreate
1. Clone repo
2. Create new scratch org
3. Attempt to push sfdx:force:push
