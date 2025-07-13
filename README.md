## 🚀 Xuple Starter Kit Pipeline

This is the foundation starter kit in our growing collection.

Future templates and extensions will be announced based on community feedback and demand.

### Xuple Laravel React Starter Kit

## Introduction

The Xuple Laravel React Starter Kit provides a production-ready foundation for building robust Laravel applications with a React frontend using [Inertia](https://inertiajs.com). This starter kit includes critical fixes that resolve the common installation and build issues found in the official Laravel React starter.

Inertia allows you to build modern, single-page React applications using classic server-side routing and controllers. This gives you the frontend power of React combined with Laravel's exceptional backend productivity and lightning-fast Vite compilation.

This starter kit utilises React 19, TypeScript, Tailwind CSS v4, and the [shadcn/ui](https://ui.shadcn.com) and [radix-ui](https://www.radix-ui.com) component libraries.

## ✨ What's Fixed

This starter kit resolves critical issues that prevent successful installation and development:

- ✅ **Dependency Conflicts**: Fixed npm ERESOLVE conflicts and mixed React versions
- ✅ **ESLint Configuration**: Updated to modern flat config approach  
- ✅ **Build System**: Resolved Tailwind v4 and PostCSS configuration issues
- ✅ **TypeScript**: Fixed compilation errors and case sensitivity problems
- ✅ **Missing Files**: Added required bootstrap file and proper configuration
- ✅ **Production Ready**: Tested and verified for production deployment

## Quick Start

```bash
# Clone the repository
git clone https://github.com/xuple/xuple-laravel-react-starter-kit.git my-app

# Install dependencies
composer install
npm install

# Set up environment
cp .env.example .env
php artisan key:generate

# Run migrations
php artisan migrate

# Start development
npm run dev
```

## 🚀 Xuple Starter Kit Pipeline

This is the foundation starter kit in our growing collection:

- **🔧 Xuple Laravel React Starter Kit** (this repo) - Clean, reliable foundation
- **🏛️  Xuple Laravel React Inertia Government Design System Starter** (coming soon) - Alternative government design patterns

Each starter kit builds on the reliability and fixes established in this foundation.

## Official Documentation

Documentation for all Laravel starter kits can be found on the [Laravel website](https://laravel.com/docs/starter-kits).

## Contributing

Thank you for considering contributing to the Xuple Laravel React Starter Kit! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## Acknowledgments

This starter kit is based on the official [Laravel React Starter Kit](https://github.com/laravel/laravel) with critical fixes and optimisations by [@xuple](https://github.com/xuple). Built with the UK developer community in mind.

## License

The Xuple Laravel React Starter Kit is open-sourced software licensed under the [MIT license](LICENSE).
