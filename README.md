# Angular Source Reference

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

Angular - a web framework for modern web apps

## 🚀 Tech Stack

- TypeScript

## ✨ Features

- Modern and scalable architecture
- Type-safe development with TypeScript

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/amitdubeyup/angular-framework-source.git
cd angular-framework-source

# Install dependencies
npm install
```

## ⚙️ Configuration

Create a `.env` file in the root directory:

```bash
cp .env.example .env
```

Update the `.env` file with your configuration values.

## 🚀 Usage

```bash
```

## 📜 Available Scripts

- `npm run /` - 
- `npm run // 1` - Many developer of our checks/scripts/tools have moved to our ng-dev tool
- `npm run // 2` - Find the usage you are looking for with:
- `npm run // 3` - yarn ng-dev --help
- `npm run / ` - 
- `npm run postinstall` - node scripts/webdriver-manager-update.js && node --preserve-symlinks --preserve-symlinks-main ./tools/postinstall-patches.js
- `npm run prepare` - husky install
- `npm run test-ivy-aot` - bazelisk test --config=ivy --build_tag_filters=-no-ivy-aot,-fixme-ivy-aot --test_tag_filters=-no-ivy-aot,-fixme-ivy-aot
- `npm run test-non-ivy` - bazelisk test --build_tag_filters=-ivy-only --test_tag_filters=-ivy-only
- `npm run test-fixme-ivy-aot` - bazelisk test --config=ivy --build_tag_filters=-no-ivy-aot --test_tag_filters=-no-ivy-aot
- `npm run list-fixme-ivy-targets` - bazelisk query --output=label 'attr("tags", "\[.*fixme-ivy.*\]", //...) except kind("sh_binary", //...) except kind("devmode_js_sources", //...)' | sort
- `npm run lint` - yarn -s tslint && yarn -s ng-dev format changed --check
- `npm run tslint` - tsc -p tools/tsconfig.json && tslint -c tslint.json "+(dev-infra|packages|modules|scripts|tools)/**/*.+(js|ts)"
- `npm run public-api:check` - node goldens/public-api/manage.js test
- `npm run public-api:update` - node goldens/public-api/manage.js accept
- `npm run symbol-extractor:check` - node tools/symbol-extractor/run_all_symbols_extractor_tests.js test
- `npm run symbol-extractor:update` - node tools/symbol-extractor/run_all_symbols_extractor_tests.js accept
- `npm run ts-circular-deps:check` - yarn -s ng-dev ts-circular-deps check --config ./packages/circular-deps-test.conf.js
- `npm run ts-circular-deps:approve` - yarn -s ng-dev ts-circular-deps approve --config ./packages/circular-deps-test.conf.js
- `npm run ng-dev` - node dev-infra/ng-dev
- `npm run ng-dev:dev` - ts-node --transpile-only -- dev-infra/cli.ts

## 📁 Project Structure

```
angular-framework-source/
├── package.json
├── .env.example
├── README.md
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Amit Dubey**

- GitHub: [@amitdubeyup](https://github.com/amitdubeyup)
