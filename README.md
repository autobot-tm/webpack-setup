# Frontend Project Documentation

## 📦 Project Structure

```
/project-root
  ├── src/            # Source code
  ├── scripts/        # Deployment and utility scripts
  ├── public/         # Static assets
  ├── node_modules/   # Installed dependencies
  ├── package.json    # NPM configuration
  ├── webpack.config.js # Webpack configuration
  ├── .env           # Environment variables
  ├── .gitignore     # Git ignored files
  └── README.md      # Project documentation
```

## 🚀 Getting Started

### 1. Install Dependencies

```bash
npm install
```

### 2. Development Server

```bash
npm run start
```

Runs the app in development mode.

### 3. Build for Production

```bash
npm run build
```

Generates an optimized build in `/dist`.

### 4. Build for Development

```bash
npm run build:dev
```

Builds the project with development settings.

### 5. Analyze Bundle

```bash
npm run build:analyze
```

Analyzes the production build using bundle analyzer.

## 📚 Scripts Overview

- **start:** Launches the development server.
- **build:** Builds the project for production.
- **build:dev:** Builds the project for development.
- **build:analyze:** Analyzes the bundle size.

## 🛠️ Tools & Technologies

- **Webpack**: Module bundler
- **Node.js**: JavaScript runtime
- **NPM**: Package manager
- **Environment Variables**: Managed via `.env` files

## 🤝 Contribution

Feel free to fork this project and submit pull requests.

## 📄 License

This project is licensed under the MIT License.

---

Made with ❤️ by minh thanh
