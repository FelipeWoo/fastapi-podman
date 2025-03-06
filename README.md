# FastAPI with Podman

This project containerizes a FastAPI application using Podman.

## Installation

### Clone the repository:
```bash
git clone https://github.com/FelipeWoo/fastapi-podman.git
cd fastapi-podman
```
### Install dependencies:
```bash
pip install -r requirements.txt
```
### Build and run the container:
```bash
podman build -t fastapi-app .
podman run -p 8000:8000 fastapi-app
```
## To-Do
- Add database integration
- Implement CI/CD pipeline