focusVoteServer
===============
a Microsoft-centric server for the [focusVote](https://bitbucket.org/nonnacm/focusvote) web app. i'm using this to compare and contrast with the original MEAN stack. some things likely to be demonstrated here:

* Web API (REST, AJAX)
* CQRS
 * SQL Server and EF for the write model
 * RavenDB and Dapper for the read model
* basic event sourcing

experimenting with event sourcing means that i'll probably be evaluating some of the following:

* Rx for .NET
* RabbitMQ
