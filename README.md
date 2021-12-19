# deephealthchecksystem
About Deep health check system
Building an open-source distributed deep health check system.

About the Project :- Health check is used to determine if a service can successfully handle a request. Most health check systems rely on a simple top level HTTP ping to determine if a service is up. These host failures however does not reflect the true health of the system or its ability to serve requests. For example, the service could have run out of database connections or the passwords for the message queue has changed in the background. The goal of this project is to build a system that can do deep health checks of a service.

The system should be able to integrate with a large variety of platforms and languages using plugins. The dependency checks have to originate within the application and should ideally use the same connections that are used by the application to contact the external dependency. For example, you could have a django-postgresql plugin that can use the django db connection to check if the service is up.

Resources

Resouces 1

Evaluation Criteria

-Create a proposal outlining your interest in working on above mentioned project. -Ability to write clean, well-documented code. -The proposal should include a link to your GitHub profile, and can also include a resume or CV if desired.
