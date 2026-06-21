### List of commands to get postgres running on docker

```
Steps

1. Install Docker -> https://www.docker.com/products/docker-desktop/
2. Launch Docker Desktop
3. Check if Docker is already installed -> docker --version
4. Create docker's compose.yaml
5. docker compose up -d
6. docker ps
7. Install Python dependencies if not installed
	pip install langgraph langgraph-checkpoint-postgres psycopg[binary,pool] langchain-openai langchain-deepseek

```