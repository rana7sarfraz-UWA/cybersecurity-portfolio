B20 — GitHub Project Security Enhancement

A small GitHub project was reviewed to identify insecure coding practices and improve its overall security.
The project contained hardcoded sensitive information which could expose credentials if publicly accessible.
The security enhancement involved removing hardcoded secrets from the source code and replacing them with environment variables stored in a .env file. 
File permissions for sensitive configuration files were also restricted to prevent unauthorised access.
This improvement demonstrated secure secret management practices and reduced the risk of credential exposure within publicly accessible repositories.
