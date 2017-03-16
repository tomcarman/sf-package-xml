# Salesforce Reference package.xml 

Salesforce uses inconsistent syntax for referencing metadata in the package.xml.

For example 

```Some Things Have Spaces```

whilst 

```Other_Things_Use_Underscores``` 

and

```SomeUseTheObject__c.As_As_Prefix__c``` 

or even

```Folder_Name/With_Content```

This is a list of most metadata types, and their format in package.xml.


# Example

```xml
<?xml version="1.0" encoding="UTF-8"?>
<Package xmlns="http://soap.sforce.com/2006/04/metadata">
    <types>
        <members>Example</members>
        <name>ApexClass</name>
    </types>
    <types>
        <members>Example</members>
        <name>ApexComponent</name>
    </types>
    <types>
        <members>Example</members>
        <name>ApexPage</name>
    </types>
    <types>
        <members>Example</members>
        <name>ApexTrigger</name>
    </types>
    <types>
        <members>Example_Name</members>
        <name>AppMenu</name>
    </types>
    <types>
        <members>Object.Example_Name</members>
        <name>ApprovalProcess</name>
    </types>
