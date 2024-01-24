# FlowRecordTypeUtils

THIS SOFTWARE IS COVERED BY [THIS DISCLAIMER](https://raw.githubusercontent.com/thedges/Disclaimer/master/disclaimer.txt).

Simple Apex class to provide a Flow action to retrieve the RecordType developer name for a given record id.

## Installation 
1. Install the package per this link

<a href="https://githubsfdeploy.herokuapp.com?owner=thedges&repo=FlowRecordTypeUtils&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

2. For your users needing access, provide access to the FlowRecordTypeUtils Apex class via profile or perm set.
   
3. Drag an Action step on your flow and search for "Get Record Type Name (apex-FlowRecordTypeUtils)"

4. Configure the Action step to pass in a record id for input and setup an output variable (Text) for the response. Here is example screenshot

<img src="/FlowRecordTypeUtils-1.png" alt="Configuration" height="350"/>

5. That's it! You can now use that output variable for decision logic within the flow.
