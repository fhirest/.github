Coding rules
===============

* 64-bit architecture should be supported
* All code, scripts and application itself should use UTF-8 encoding
* Code should not store anything directly in server filesystem
* All configuration parameters should be meaningful
* Configuration parameters should be reused where possible. No duplications.
* Database connections should use connection pooling
* It should be possible to define different database users for database structure modifications and for basic usage 
* Database changes should be automated
* If any cryptographic algorithm is used, it should be configurable and replaceable
* All code, comments, scripts etc. should be written in English
* All variables, type and function names should be meaningful
* Unused code should be removed
* Dependencies used should not have EOL sooner, than 2 years
* Code should be runnable on high availability distributed environment with multiple instances
    * Application should be horizontally scalable
    * Application should be stateless
    * Application should be runnable on different domains and different environments
    * All configurations should be configurable at runtime
    * Environment specific variables should be configurable
    * Application should work with databases on remote server
    * Application should be scalable both in data size and user count
    * All api interfaces should be high availability capable
    * Application should run on infrastructure with load balancers
* Database rules
  * Table relations should use foreign keys
  * Foreign keys should be indexed
  * Parameter binding should be used in queries
  * Database object names should be meaningful
* Logging
  * Slf4j should be used for logging
  * One event per log
  * Empty parameters should be replaced with a placeholder
  * All errors should be logged

