# Architecture Overview

This is a high-level overview of the Prep Platform architecture. It intentionally excludes source code, private database structure, payment logic and implementation details.

## Main platform areas

### Public website layer

The public-facing sites were designed to present tutoring services, subject information, resource pathways and enquiry flows for students and parents.

The platform included state-specific education brands:

- HSCPrep
- QCEPrep
- VCEPrep

### Tutor/admin workflows

The private platform included tutor/admin workflows for managing tutoring operations, session-related processes and internal platform activity.

### Session workflows

The platform supported session-related workflows, including scheduling, tracking and operational coordination between students, tutors and internal processes.

### Payment-related workflows

The platform included payment-related workflow support as part of the tutoring operation.

Payment provider details, webhook handling and private implementation logic are intentionally excluded from this public case study.

### CRM and automation

The platform used CRM and automation workflows to support customer acquisition, response handling, scheduling processes and operational efficiency.

### API-driven features

The platform included API-driven features supporting practice-question generation, workflow automation and customer-response improvements.

## Design priorities

- Clear student-facing user experience
- Practical tutor/admin workflows
- Mobile-responsive layout
- Separation between public and private areas
- Backend-supported operations
- Multi-brand rollout structure
- Security-conscious handling of private workflows
