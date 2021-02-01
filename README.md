# Introduction
The objective of this project is to perform and document the results of a prelimi-nary security analysis of a mobile application.  The application should have a sensitiverole impacting user privacy to motivate the security analysis. By sensitive role, it meansthat the application should handle user data of some sensitive nature (financial infor-mation of any kind, health records, location data, passwords and other authenticationinformation, etc).

# Method
Using the techniques and concepts you have learned in class, you should analyzethe application in four different aspects:

1. *Software security*:  decompile the application, look for keywords (such as crypto-graphic algorithms) or scan the source code using static analyzers
2. *Network security*:  document the TLS server configuration and attempt to MITMa connection to capture sensitive traffic.  Observe the exchanged traffic for sensi-tive data.
3. *Authentication*:  document what authentication mechanisms are used,  and howsecure they are.
4. *Privacy*:  observe relevant privacy characteristics (trackers and integration withsocial networks).

The application should have a sensitive role to motivate the security analysis. Candidate mobile applications can be of multiple types, for example:


- Financial (for banking and payments like MobilePay and local banks)
- Healthcare (like COVID apps for decentralized contact tracing)
- e-Government (nemID, eBoks and other digital government efforts)
- Transport (Midttrafik and Flixbus apps where you can buy tickets)
- Social Networks (TikTok, Tinder and similar, preferably a local one)
