# My Microservice Demo

This is a demo service for Backstage catalog registration, showcasing a complete microservice setup with proper documentation and API specifications.

## Structure

```
backstage-svc-demo/
├── catalog-info.yaml    # Backstage catalog entities
├── openapi.yaml         # OpenAPI 3.0 specification
├── mkdocs.yml          # TechDocs configuration
├── docs/
│   └── index.md        # Main documentation
└── README.md           # This file
```

## Entities Included

- **Group**: platform-team (team type)
- **System**: user-management-system (owned by platform-team)
- **API**: my-microservice-api (OpenAPI spec, experimental lifecycle)
- **Component**: my-microservice (service type, provides API, has TechDocs)

## Features

- ✅ Complete Backstage catalog entities
- ✅ Valid OpenAPI 3.0 specification
- ✅ TechDocs integration with MkDocs
- ✅ Proper entity relationships and ownership
- ✅ Consistent naming (kebab-case)
- ✅ Default namespace usage

## Usage

This demo service is ready to be registered in Backstage via URL import. All entities are properly linked and follow Backstage best practices.

## Owner

Platform Team (platform-team@company.com)