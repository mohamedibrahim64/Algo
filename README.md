# Algo

Algorithm implementation in Java.

## 📚 Documentation

JavaDoc documentation is automatically generated and deployed to GitHub Pages:
- **[View Documentation](https://mohamedibrahim64.github.io/Algo/)**

## 🔨 Building

### Prerequisites
- Java 11 or higher
- Maven 3.6 or higher

### Compile
```bash
mvn clean compile
```

### Generate JavaDoc
```bash
mvn clean javadoc:javadoc
```

The generated JavaDoc will be in the `docs/javadoc` directory.

## 📝 License

This project is open source and available under the MIT License.

## 🚀 Deployment

The project is automatically deployed to GitHub Pages on every push to the `main` branch using GitHub Actions. The workflow:

1. Checks out the code
2. Sets up Java 11
3. Compiles the project with Maven
4. Generates JavaDoc documentation
5. Deploys to GitHub Pages

Visit the [Actions tab](https://github.com/mohamedibrahim64/Algo/actions) to see deployment history.
