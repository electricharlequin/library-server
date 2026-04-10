# library-server
RAG app to host reference library


Steps:

# Spin her up:

docker compose up -d

# Pull required models for ollama:

# LLM for chat
docker exec -it ollama ollama pull llama3

# Embedding model for PDF indexing
docker exec -it ollama ollama pull nomic-embed-text