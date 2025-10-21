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

### User Interface 

*Ref 3: Home Screen and Data Overview*  
<img width="568" height="1084" alt="Home_Screen " src="https://github.com/user-attachments/assets/37a970ac-1848-4867-8d18-2577f8cb1709" />
<img width="568" height="1084" alt="Data_Screen" src="https://github.com/user-attachments/assets/984cb5ec-2269-4a91-a378-417a9b8e6584" />

*Ref 4: Quick Access Tracking Interface*  
<img width="568" height="1084" alt="Track_Screen" src="https://github.com/user-attachments/assets/1110bb7c-9fa9-4e5b-9ad2-ab876fa8bfe9" />

*Ref 5: Example: Insulin Tracking*  
<img width="568" height="1084" alt="InsulinTracking_Screen" src="https://github.com/user-attachments/assets/258a5655-2ec9-4514-a43e-112b84ae094d" />

### CGM Integration & Real-Time Monitoring

*Ref 6: CGM Integration Setup*  
<img width="568" height="1084" alt="Settings_Screen" src="https://github.com/user-attachments/assets/1540e2ea-2ea4-41db-944a-2a59794a39f9" />
<img width="568" height="1084" alt="Bildschirmfoto 2025-10-21 um 17 48 25" src="https://github.com/user-attachments/assets/bddef0e0-6ade-4948-b2c6-d3288f0d0043" />
<img width="568" height="1084" alt="Bildschirmfoto 2025-10-21 um 17 48 39" src="https://github.com/user-attachments/assets/536f8043-8592-4ff3-af74-403e21c195e3" />
<img width="568" height="1084" alt="Bildschirmfoto 2025-10-21 um 17 48 47" src="https://github.com/user-attachments/assets/c4f0a886-894e-4626-9bc1-8a5b634544da" />
<img width="568" height="1084" alt="Bildschirmfoto 2025-10-21 um 17 49 00" src="https://github.com/user-attachments/assets/0b78f8dc-9b98-4491-96c0-964109105d63" />
<img width="568" height="1084" alt="Bildschirmfoto 2025-10-21 um 17 49 12" src="https://github.com/user-attachments/assets/7ba8dfa2-1b37-4ba3-8987-508754b649b4" />
<img width="568" height="1084" alt="Patienten auswählen" src="https://github.com/user-attachments/assets/952a4232-5d10-4fb8-ad4c-b5432d3be25f" />
<img width="568" height="1084" alt="Bildschirmfoto 2025-10-21 um 17 49 43" src="https://github.com/user-attachments/assets/86b99437-8d0f-42d1-8e9d-a07803fca508" />
<img width="568" height="1084" alt="Bildschirmfoto 2025-10-21 um 17 54 49" src="https://github.com/user-attachments/assets/9dbad5ec-0a8a-43a7-8969-9ce13961514d" />

*Ref 7: Real-Time Glucose Monitoring*  
<img width="214" height="197" alt="image" src="https://github.com/user-attachments/assets/9349d74c-12d2-48b4-9d67-939eab1860cf" />

*Ref 8: Analysis Dashboard*  
<img width="568" height="1084" alt="Analysis_Screen" src="https://github.com/user-attachments/assets/ea82ce63-f97d-4b00-bf33-7b05b90b1fe3" />

### Backend Infrastructure & Deployment

*Ref 9: Ubuntu Server Configuration*
<img width="439" height="801" alt="server_setup" src="https://github.com/user-attachments/assets/ff6c93d7-15aa-400a-ab9f-f7b87e172381" />

*Ref 10: PostgreSQL Database Setup*
<img width="330" height="759" alt="db_setup" src="https://github.com/user-attachments/assets/f1953b1a-5c12-4cf6-a8cb-d03c92e6b60c" />

*Ref 11: Automated CGM Collection Service*
<img width="1462" height="575" alt="cgm_collection_log" src="https://github.com/user-attachments/assets/ddfdb1a6-99a4-40ae-b63b-4a6d61370ca2" />

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
