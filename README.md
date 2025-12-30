# homelab-docker-registry-cache

This repository contains a Docker Compose application for setting up a local Docker registry cache.

## Getting Started

To get started with this application, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/gromer/homelab-docker-registry-cache.git
   cd homelab-docker-registry-cache
   ```

2. **Build and run the application**:
   ```bash
   docker-compose up -d
   ```

3. **Access the registry**:
   The registry will be available at `http://localhost:5000`.

## Configuration

The configuration for the registry can be found in the `registry/config.yml` file. You can modify this file to customize the behavior of the registry.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.