<img width="2400" height="1040" alt="weaviate-cloud-flowchart-2811f1821d177be0f795b25ede864e18" src="https://github.com/user-attachments/assets/36e0230d-6c4a-4d52-ae5d-d1ed8123b01c" />


## Weaviate | Kubernetes ☸️
Weaviate is an open-source, cloud-native vector database that stores both objects and vectors, enabling semantic search at scale. It combines vector similarity search with keyword filtering, retrieval-augmented generation (RAG), and reranking in a single query interface. Common use cases include RAG systems, semantic and image search, recommendation engines, chatbots, and content classification.


#### 🎯 Key Features:

- **⚡ Fast Search Performance**: Fast Search Performance: Perform complex semantic searches over billions of vectors in milliseconds. Weaviate's architecture is built in Go for speed and reliability, ensuring your AI applications are highly responsive even under heavy load. See our ANN benchmarks for more info.
- **🔌 Flexible Vectorizatio**: Flexible Vectorization: Seamlessly vectorize data at import time with integrated vectorizers from OpenAI, Cohere, HuggingFace, Google, and more. Or you can import your own vector embeddings.
- **🔍 Advanced Hybrid & Image Search**: Combine the power of semantic search with traditional keyword (BM25) search, image search and advanced filtering to get the best results with a single API call.
- **🤖 Integrated RAG & Reranking**: Go beyond simple retrieval with built-in generative search (RAG) and reranking capabilities. Power sophisticated Q&A systems, chatbots, and summarizers directly from your database without additional tooling.
- **📈 Production-Ready & Scalable**: Weaviate is built for mission-critical applications. Go from rapid prototyping to production at scale with native support for horizontal scaling, multi-tenancy, replication, and fine-grained role-based access control (RBAC).
- **💰 Cost-Efficient Operations**: Radically lower resource consumption and operational costs with built-in vector compression. Vector quantization and multi-vector encoding reduce memory usage with minimal impact on search performance.


🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```





