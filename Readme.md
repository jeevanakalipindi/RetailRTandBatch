### Summary:
   `
    Working on Retail,Hospitality domain and seeing many recurring issues on same problem drove me to design a better and performance effective way to transfer data from and ERP to store or any Ecommerce application which includes faster XML/SAP/Raw file to JSON 
using hadoop map reduce. This design also use features of new NIO2 which is a well proven implementation for java asynchronous calls that uses call back for P2P messaging
   `
   
  `
   To process millions of trasactions I reaseach many tools that have better multi threaded libraries and I eventually end up using apache Storm
   which works perfectly with multi threade map reduce and aggregations
  `

### Components: 

*Batch*:
    
Storage File is uploaded to any storage service that has an online connect and can able to provide network 
access via FTP, HTTP protocols

*Real Time*:

Realtime apis are exposed through XML or REST.

*Messaging*: 

Every part of the communication between components are takes place through point to point messaging

*Apache storm*

``the meat of the application`` : Storm is a well developed and  approved parallel processing engine that helps 

*DB*:

Any nosql and sql database that has a proven integration with 
