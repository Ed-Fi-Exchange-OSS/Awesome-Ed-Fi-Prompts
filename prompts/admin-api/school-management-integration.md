# Ed-Fi Admin API School Management Integration

> **Disclaimer**: This prompt was written by GitHub Copilot Coding Agent as an example for the Awesome Ed-Fi Prompts repository.

## Prompt

Develop a Node.js application that integrates with the Ed-Fi Admin API to manage educational organizations, applications, and API client configurations. The application should:

### Requirements:
1. **Admin API Authentication**: 
   - Implement authentication with the Ed-Fi Admin API
   - Handle API key management and token refresh
2. **Educational Organization Management**:
   - Create and manage Local Education Agencies (LEAs)
   - Set up schools and their organizational hierarchies
   - Configure education organization relationships
3. **Application and Vendor Management**:
   - Register applications in the Ed-Fi ecosystem
   - Manage vendor information and profiles
   - Handle application approval workflows
4. **API Client Configuration**:
   - Create and configure ODS/API client applications
   - Manage client secrets and security settings
   - Set up proper scopes and permissions
5. **Claims and Profile Management**:
   - Configure resource claims for applications
   - Set up claim sets for different user roles
   - Manage API profiles and their associations

### Technical Specifications:
- Use Node.js with Express.js framework
- Implement TypeScript for type safety
- Use axios for HTTP client with interceptors
- Include proper async/await error handling
- Implement configuration management with environment variables
- Add comprehensive logging with Winston
- Include integration tests using Jest
- Support for multiple Admin API environments

### Key Features:
- Bulk operations for setting up multiple schools
- Configuration validation and rollback capabilities
- Automated backup of configurations before changes
- CLI interface for common administrative tasks
- Web dashboard for monitoring and management

### Sample Workflows:
Include examples for:
- Setting up a new district with multiple schools
- Configuring a new SIS vendor application
- Managing API client lifecycle (create, update, disable, delete)
- Bulk permission updates across multiple clients

## Expected Outcome:
A robust Node.js application that simplifies Ed-Fi Admin API operations and can serve as a foundation for building administrative tools and automation scripts.

## Ed-Fi Resources:
- Ed-Fi Admin API Documentation
- Ed-Fi Security Configuration Guide
- ODS/API Client Management Best Practices