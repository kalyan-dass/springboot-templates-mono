# Spring Boot Templates Monorepo

This monorepo contains ready-to-use Spring Boot template projects for rapid microservice and application development. Each template demonstrates best practices, common configurations, and a clean project structure.

## Repository Structure

```
springboot-templates-mono/
│
├── README.md
├── pom.xml
└── rest-api-basic/
    ├── README.md
    ├── pom.xml
    └── src/
```

- **pom.xml**: Monorepo Maven parent configuration.
- **rest-api-basic/**: Example Spring Boot REST API template.

## Getting Started

### Prerequisites

- Java 24 or higher
- Maven 3.8+ (Maven Wrapper included in submodules)
- Git

### Clone the Repository

```sh
git clone https://github.com/your-org/springboot-templates-mono.git
cd springboot-templates-mono
```

### Build All Modules

From the root directory:

```sh
mvn clean install
```

Or build a specific template:

```sh
cd rest-api-basic
./mvnw clean install
```

## Using a Template

1. Copy the desired template directory (e.g., `rest-api-basic`) to your new project location.
2. Update package names and project metadata as needed.
3. Follow the template's `README.md` for setup and usage.

## Contributing

1. Fork this repository.
2. Create a new branch for your feature or fix.
3. Make your changes and add tests if applicable.
4. Submit a pull request with a clear description.

## License

This repository is licensed under the MIT License.

## Support

For questions or issues, please open an issue in this repository.
