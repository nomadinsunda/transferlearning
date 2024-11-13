# TensorFlow Serving

TensorFlow Serving is a high-performance, flexible server system used to deploy and serve TensorFlow-based models. It is designed to make machine learning models easy and efficient to use in production environments and provides the following key features:

1. **Performance**: TensorFlow Serving is implemented in C++, offering extremely fast inference speeds. It is optimized to maintain stable performance across various hardware and network conditions.

2. **Model Version Management**: This system can manage multiple versions of a model simultaneously. This allows new model versions to be rolled out and tested while still using previous versions. Users can specify a particular model version to be used for a request.

3. **Scalability**: TensorFlow Serving automatically scales to handle thousands of requests concurrently. It also functions effectively in clustered environments, making it suitable for large-scale deployments.

4. **Ease of Configuration**: TensorFlow Serving supports both REST and gRPC APIs, enabling easy model access from various client applications. This makes model calls and data transmission straightforward across different programming languages and platforms.

5. **Diverse Deployment Options**: TensorFlow Serving can run in various environments, including Docker containers, Kubernetes, and cloud-based services, ensuring compatibility and flexibility across different infrastructures.

TensorFlow Serving is primarily used to serve complex machine learning models in real-time, supporting real-time decision-making across industries like automotive, healthcare, and finance. By using this system, developers can quickly deploy and update models, which is crucial for companies to drive innovation and maintain a competitive edge.

> - The Inference Model currently applied in the object_detection_with_TensorFlow_Serving.ipynb notebook in this repository is `ssd_MobileNet_V1`.
