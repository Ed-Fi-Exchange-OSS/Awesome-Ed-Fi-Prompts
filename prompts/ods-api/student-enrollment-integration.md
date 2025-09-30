# Ed-Fi ODS/API Student Enrollment Integration

> **Disclaimer**: This prompt was written by GitHub Copilot Coding Agent as an example for the Awesome Ed-Fi Prompts repository.

## Prompt

Create a Python application that integrates with the Ed-Fi ODS/API to manage student enrollment data. The application should:

### Requirements:
1. **Authentication**: Implement OAuth 2.0 client credentials flow to authenticate with the Ed-Fi ODS/API
2. **Student Management**: 
   - Create new student records
   - Update existing student information
   - Retrieve student data by ID or search criteria
3. **Enrollment Management**:
   - Enroll students in schools and sections
   - Handle enrollment status changes (active, inactive, withdrawn)
   - Track enrollment effective dates
4. **Data Validation**:
   - Validate required fields according to Ed-Fi data standards
   - Handle API validation errors gracefully
   - Implement retry logic for transient failures
5. **Logging and Monitoring**:
   - Log all API interactions for auditing
   - Track sync statistics (records processed, errors, etc.)
   - Generate summary reports

### Technical Specifications:
- Use Python 3.8+ with requests library for HTTP calls
- Implement proper error handling and rate limiting
- Store configuration in environment variables
- Include unit tests for core functionality
- Follow Ed-Fi API versioning best practices
- Support both sandbox and production environments

### Sample Data Structure:
Include examples for:
- Student demographic data
- School and section information
- Enrollment records with proper relationships

The solution should be production-ready with proper documentation and deployment instructions.

## Expected Outcome:
A complete Python package that can be used as a reference implementation for Ed-Fi ODS/API integration patterns, particularly for student information systems.

## Ed-Fi Resources:
- Ed-Fi ODS/API Documentation
- Ed-Fi Data Model
- Authentication and Authorization Guide