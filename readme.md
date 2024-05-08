# User Management System - IS601 Final Project

## Introduction
Under the guidance of Professor William Keith, the User Management System for the IS601 course demonstrates modern web technologies through practical use. This open-source project employs the 12-Factor App methodology and Agile principles, preparing students to develop scalable and maintainable applications.

### Key Methodologies
- **12-Factor App Methodology**: Covers key concepts like codebase management, dependency control, and consistent environments.
- **Agile Practices**: Promotes teamwork, iterative development, and ongoing customer interaction.
- **Industry Standards**: Emphasizes coding standards such as PEP 8 and essential practices like error handling and dependency injection.

## Features and Issues Addressed
- **Profile Picture Upload with Minio**: Enhances user profile management by allowing users to securely upload and store profile pictures using Minio. [More about this feature]
- **Issues solved**:
  - Code Update: Automatic Verification Email on User Registration [Issue Link](https://github.com/rk94407/final_project/tree/1-send-verification-email)
  - Update to User Response Model: Status Code 400 for Duplicate Nickname Registration [Issue Link](https://github.com/rk94407/final_project/tree/3-skipping-cannot-be-less-than-0)
  - Ensuring Non-Negative Skip and Positive Limit Parameters [Issue Link](https://github.com/rk94407/final_project/tree/4-password-validation)
  - Implementation of Password Validation [Issue Link](https://github.com/rk94407/final_project/tree/5-regex-updated)
  - Enhanced URL Validation with Updated Regex Pattern [Issue Link](https://github.com/NidhishVyas/user_management/pull/5)

## Test Cases
Included test cases cover a variety of functionality and validation scenarios:
- `test_email_verification_test`
- `test_create_user_duplicate_nickname`
- `test_user_base_nickname_valid`
- and more...

## Deployment and Repository Links
- [GitHub Commits](https://github.com/rk94407/final_project/commits/main/)
- [GitHub Deployments](https://github.com/rk94407/final_project/deployments)
- [GitHub Actions](https://github.com/rk94407/final_project/actions)
- [Docker Hub](https://hub.docker.com/repository/docker/rohankatkam1698/final_project/general)

## Technologies Integrated
- **FastAPI**: For high-performance API development.
- **SQLAlchemy**: For database management.
- **PostgreSQL**: For handling large-scale databases.
- **MinIO**: For managing large datasets efficiently.
- **OAuth2**: For secure user authentication.
- **Docker**: For containerization and consistent environments.
- **Alembic**: For database migrations and versioning.

## Conclusion
This project bridged theory and practice in software development, enhancing my skills in crucial technologies and best practices. It has prepared me for roles in software engineering, cybersecurity, and DevOps.
