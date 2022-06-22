# PhotoAppConfiguration

configuration properties from Git repository will be of higher prioritu than application.properties file in local.

On configuration server, priorities (for microservice PhotoApp) will in order as: 
				PhotoApp-<profile>.properties  >   PhotoApp.properties   >   application.properties