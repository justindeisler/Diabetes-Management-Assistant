# Diabetes Tracking Platform 

## Objective

The DoT1 project aimed to create a comprehensive diabetes tracking and management platform that addresses the complex needs of individuals managing diabetes through technology. The primary focus was to integrate real-time continuous glucose monitoring (CGM) with advanced health analytics, providing users with actionable insights for better diabetes management. This hands-on healthcare technology project was designed to demonstrate proficiency in mobile development, medical device integration, self-hosted backend infrastructure, and AI-assisted development workflows while solving real-world healthcare challenges.

### Skills Learned

- Advanced cross-platform mobile development using Flutter and Dart with Clean Architecture principles.
- Healthcare technology integration including CGM device APIs (LibreLink) with secure credential management.
- Self-hosted backend infrastructure deployment and management using Ubuntu Server.
- Backend service orchestration with systemd for 24/7 automated CGM data collection.
- FastAPI REST API design and PostgreSQL database administration.
- Real-time data processing and synchronization for medical device integration.
- Advanced state management implementation using Riverpod with code generation.
- Secure authentication and encrypted healthcare data storage following HIPAA compliance principles.
- Python analytics integration for comprehensive health data analysis and correlation studies.
- AI-assisted development workflows using Claude Code while maintaining architectural ownership.
- Professional UI/UX design for healthcare applications with Material Design 3 and accessibility compliance.
- Medical device API integration with error handling and regional endpoint discovery.
- Advanced data visualization techniques for health metrics and trend analysis.

### Tools Used

- **Flutter/Dart**: Cross-platform mobile application framework for iOS, Android, Web, Windows, macOS, and Linux.
- **Riverpod with Code Generation**: Advanced state management with riverpod_generator for type-safe dependency injection.
- **LibreLink CGM API**: Real-time continuous glucose monitoring integration with secure credential storage.
- **FastAPI**: Modern Python web framework for building the backend REST API.
- **PostgreSQL**: Production database for persistent health data storage and user management.
- **Ubuntu Server**: Self-hosted backend infrastructure with systemd service management.
- **Material Design 3**: Modern UI framework with health-specific color schemes and accessibility features.
- **Python Integration**: Seamless data export for advanced analytics using pandas-compatible formats.
- **Claude Code**: AI-assisted development workflows for accelerated development while maintaining code quality.
- **Clean Architecture**: Domain/Data/Presentation layer separation with feature-based organization.
- **Freezed & JSON Serialization**: Immutable data classes with automatic code generation for robust data models.
- **Secure Storage**: Flutter Secure Storage for encrypted credential management and sensitive data protection.
- **FL Chart**: Advanced data visualization library for health metrics, trends, and correlation analysis.
- **Systemd**: Linux service management for automated startup and 24/7 background service operation.

## Steps

*The following screenshots demonstrate the key development milestones and features implemented throughout the project.*

### Architecture & Setup

*Ref 1: Project Architecture Overview*

<img width="326" height="621" alt="image" src="https://github.com/user-attachments/assets/fe3f6690-f31f-4180-8f67-6ebd5622b91f" />

This demonstrates the Clean Architecture implementation with feature-based organization. Each health tracking category (insulin, meals, activity, etc.) is self-contained with clear separation of concerns.

*Ref 2: Development Environment Setup*

<img width="685" height="123" alt="Screenshot_build" src="https://github.com/user-attachments/assets/e75f649b-c34e-426c-944e-4eb56cb369d2" />

Shows the modern development workflow with automated code generation for Riverpod providers, Freezed data classes, and JSON serialization, enabling type-safe development practices.

### Health Tracking Features

*Ref 3: Comprehensive Health Dashboard*
[Screenshot of the main dashboard showing health summary with multiple tracking categories and recent entries]

The home screen provides a comprehensive overview of all 11 health tracking categories with recent entries, quick access buttons, and health insights at a glance.

*Ref 4: Advanced Tracking Interface*
[Screenshot of the main tracking screen with categorized health entry options and intuitive UI]

Demonstrates the intuitive tracking interface with all health categories accessible through a clean, healthcare-optimized Material Design 3 interface.

*Ref 5: Insulin Tracking with Brand Memory*
[Screenshot showing insulin tracking form with dropdown for insulin types and dosage input]

Advanced insulin tracking feature with brand name memory, dosage tracking, and timing management for comprehensive diabetes management.

### CGM Integration & Real-Time Monitoring

*Ref 6: CGM Integration Setup*
[Screenshot of CGM credential entry form with secure storage and regional endpoint selection]

Secure CGM integration setup with encrypted credential storage and automatic regional endpoint discovery for global compatibility.

*Ref 7: Real-Time Glucose Monitoring*
[Screenshot of live CGM data display with glucose readings, trends, and time-in-range calculations]

Real-time continuous glucose monitoring with live data synchronization, trend analysis, and time-in-range calculations providing immediate health insights.

*Ref 8: CGM Data Visualization*
[Screenshot of advanced glucose charts with trend lines, target ranges, and statistical analysis]

Advanced data visualization showing glucose patterns, trend analysis, and statistical insights including time-in-range, glucose variability, and pattern recognition.

### Advanced Analytics & Correlation Analysis

*Ref 9: Health Analytics Dashboard*
[Screenshot of correlation analysis showing relationships between different health metrics]

Comprehensive analytics engine demonstrating correlation analysis between health metrics, identifying patterns and relationships that support better diabetes management decisions.

*Ref 10: Trend Analysis & Insights*
[Screenshot showing long-term trend analysis with statistical insights and health recommendations]

Advanced trend analysis providing statistical insights, pattern recognition, and actionable health recommendations based on comprehensive data analysis.

### Data Management & Python Integration

*Ref 11: Data Export & Python Integration*
[Screenshot of data export interface showing CSV/JSON export options for Python analytics]

Demonstrates seamless Python integration with structured data export in pandas-compatible formats, enabling advanced external analytics and machine learning applications.

*Ref 12: Secure Data Storage*
[Screenshot showing data management interface with encryption status and backup options]

Secure healthcare data management with encryption, structured storage, and comprehensive backup options ensuring data integrity and privacy compliance.

### Backend Infrastructure & Deployment

*Ref 13: Ubuntu Server Configuration*
[Screenshot showing Ubuntu Server 24.04 terminal with systemd service configuration and status]

Self-hosted backend infrastructure running on Ubuntu Server 24.04 with systemd service management for automated startup, 24/7 reliability, and automatic restart on failure.

*Ref 14: PostgreSQL Database Setup*
[Screenshot of PostgreSQL database with health data tables, schema design, and optimized indexes]

Production PostgreSQL database with optimized schema for storing health metrics, user accounts, and CGM readings with proper relationships and indexing for fast queries.

*Ref 15: Automated CGM Collection Service*
[Screenshot showing systemd service logs and CGM data fetching process with timestamps]

Background service automatically fetching LibreLinkUp CGM data at configurable intervals, with comprehensive logging, error recovery, and retry logic for network failures.

*Ref 16: FastAPI Backend Documentation*
[Screenshot of FastAPI automatic OpenAPI documentation showing all REST endpoints]

FastAPI REST API with automatic interactive documentation, displaying all endpoints for health data management, user authentication, CGM integration, and data export.

*Ref 17: Frontend Backend Configuration*
[Screenshot of Flutter UI showing backend configuration panel with server settings and interval controls]

Flutter frontend interface for configuring backend settings including server connection details, authentication credentials, and CGM data collection intervals (1-60 minutes).

### Cross-Platform Deployment

*Ref 18: Multi-Platform Build Success*
[Screenshot of successful builds for iOS, Android, Web, Windows, macOS, and Linux platforms]

Demonstrates the cross-platform capability of the Flutter application, successfully building for all major platforms while maintaining consistent functionality and user experience.

### AI-Assisted Development Workflow

*Ref 19: Claude Code Development Integration*
[Screenshot showing Claude Code interface with code review and architectural guidance]

Professional AI-assisted development workflow using Claude Code for architectural guidance, code review, and accelerated development while maintaining technical ownership and decision-making authority.

*Ref 20: Code Quality & Architecture Validation*
[Screenshot of code analysis results showing Clean Architecture compliance and quality metrics]

Comprehensive code quality validation demonstrating Clean Architecture principles, type safety, security compliance, and maintainability standards achieved through AI-assisted development practices.

## Conclusion

This project demonstrates comprehensive full-stack development capabilities spanning mobile application development, backend infrastructure, database management, and medical device integration. The DoT1 Diabetes Management Assistant successfully combines modern development practices with real-world healthcare technology challenges to create a production-ready solution for diabetes management.

The implementation of Clean Architecture with 11 feature-based health tracking modules showcases strong software engineering principles, while the self-hosted backend with automated CGM data collection demonstrates DevOps and system administration capabilities. The successful integration of LibreLinkUp CGM API with secure credential management and 24/7 automated data fetching proves competency in medical device API integration and background service orchestration.

**Key Achievements:**
- Built scalable cross-platform application supporting 6 platforms from a single Flutter codebase
- Deployed production-ready self-hosted backend infrastructure with FastAPI and PostgreSQL
- Implemented HIPAA-compliant security practices including encrypted data storage and secure authentication
- Integrated medical device APIs with robust error handling and regional endpoint discovery
- Developed advanced analytics engine with correlation analysis across multiple health metrics
- Created intuitive Material Design 3 UI optimized for healthcare data visualization
- Achieved 24/7 automated CGM data collection with systemd service management
- Established seamless Python integration for advanced external analytics and machine learning

**AI-Assisted Development:** The integration of Claude Code as a development assistant accelerated the development process significantly, providing expert-level architectural guidance, code review, and comprehensive documentation. This project showcases how AI-assisted development can enhance productivity while maintaining high code quality standards and deepening technical understanding through AI-generated best practices and architectural recommendations.

The project successfully balances technical excellence with user experience, security compliance (HIPAA), and maintainability. It demonstrates the ability to architect and deploy complex healthcare technology solutions that bridge mobile applications, backend services, database management, and medical device integration—all critical competencies for building next-generation healthcare applications.

---

**Technologies**: Flutter • Dart • Riverpod • Material Design 3 • Python • FastAPI • PostgreSQL • Ubuntu Server • Systemd • LibreLinkUp API • FL Chart • Clean Architecture

**AI Development Tool**: Claude Code (claude.ai/code)

**Platforms**: iOS • Android • Web • Windows • macOS • Linux
