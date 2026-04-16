# Salesforce REST Integration 
Developed a Node.js middleware service using Express.js to expose CPQ data via secure REST endpoints, implementing OAuth 2.0 JWT Bearer flow for server-to-server authentication with Salesforce.

Implemented service-layer Apex architecture (selector and domain classes) to handle request validation, trigger-based data consistency checks, and error logging to Custom Objects for monitoring.

Created retry logic and exponential backoff in Node.js to handle Salesforce API rate limits and connection timeouts, ensuring reliable data synchronization during peak operations. 
