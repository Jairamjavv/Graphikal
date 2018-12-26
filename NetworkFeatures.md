__Network and Security Features__
* Triple DES for encryption and decryption.
* Load balancing using nginx in docker swarm
* To follow a secure upload of file:-
      > The application should use a whitelist of allowed file types. This list determines the types of files that can be uploaded, 
      and rejects all files that do not match approved types.
      > The application should use client- or server-side input validation to ensure evasion techniques have not been used to bypass
      the whitelist filter. These evasion techniques could include appending a second file type to the file name (e.g. image.jpg.php)
      or using trailing space or dots in the file name.
      > The application should set a maximum length for the file name, and a maximum size for the file itself.
      > The directory to which files are uploaded should be outside of the website root.
      > The application should not use the file name supplied by the user. Instead, the uploaded file should be renamed according to a
      predetermined convention.
* A tool for finding and exploiting all web application vulnerabilities. \<-W3AF> => web application attack and auditing framework   
