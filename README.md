To be able to authenticate with office 365, the plugin needs to be configured with an apiKey and an api secret that can be retrieved in the Microsoft azure panel by registering a new application. A redirect URL will also need to be provided. This URL needs to be your portal URL followed by /o/o365/login. Note that except for localhost tests, the URL is required to be HTTPS.

More info on the application registration is available on Microsoft documentation: https://docs.microsoft.com/fr-fr/graph/auth-register-app-v2

When targeting users in an organizational directory, the organization needs to approve the application for its users before they can be authorized to use it.

© Microsoft 2022