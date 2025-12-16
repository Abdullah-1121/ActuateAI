# Docusaurus API Contracts

## Local Development Server API

### Start Development Server
- **Endpoint**: `POST /api/start-dev-server`
- **Purpose**: Start local development server with hot-reloading
- **Input**:
  - Configuration file path (optional, defaults to docusaurus.config.js)
  - Port number (optional, defaults to 3000)
- **Output**:
  - Server status (object)
    - url: Local server URL
    - status: Running/Failed
    - message: Status message

### Build Static Site
- **Endpoint**: `POST /api/build-site`
- **Purpose**: Generate static site for production
- **Input**:
  - Source directory (optional, defaults to current directory)
  - Output directory (optional, defaults to build/)
- **Output**:
  - Build status (object)
    - status: Success/Failed
    - outputPath: Path to built site
    - message: Build message
    - warnings: Build warnings (array)

### Deploy Site
- **Endpoint**: `POST /api/deploy-site`
- **Purpose**: Deploy to GitHub Pages
- **Input**:
  - Built site directory
  - GitHub repository details
- **Output**:
  - Deployment status (object)
    - status: Success/Failed
    - url: Deployed site URL
    - message: Deployment message

## Configuration API

### Get Configuration
- **Endpoint**: `GET /api/config`
- **Purpose**: Retrieve current Docusaurus configuration
- **Input**: None
- **Output**:
  - Configuration object (docusaurus.config.js content)

### Update Configuration
- **Endpoint**: `PUT /api/config`
- **Purpose**: Update Docusaurus configuration
- **Input**:
  - Configuration object with updates
- **Output**:
  - Updated configuration object
  - Validation results

## Documentation Management API

### Create Documentation
- **Endpoint**: `POST /api/docs`
- **Purpose**: Create new documentation file
- **Input**:
  - File path and content
  - Metadata (title, sidebar_label, etc.)
- **Output**:
  - Creation status
  - File path of created document

### Update Documentation
- **Endpoint**: `PUT /api/docs/{id}`
- **Purpose**: Update existing documentation file
- **Input**:
  - Document ID
  - Updated content and metadata
- **Output**:
  - Update status
  - Updated document information

### Delete Documentation
- **Endpoint**: `DELETE /api/docs/{id}`
- **Purpose**: Delete documentation file
- **Input**:
  - Document ID
- **Output**:
  - Deletion status