# Portfolio: [Omkar Gaikwad](https://omkar04gaikwad.github.io/Omkar_Gaikwad/)

## Work Experience

<!--### Software Engineer, Ipser Labs – Remote (2025 – Present)
Built and deployed a distributed e-commerce platform using Spring Boot, React.js, and PostgreSQL, reducing onboarding time by 30% and securing transactions with JWT, MFA, and Stripe webhooks. Optimized database queries and implemented caching, improving system throughput by 25% while ensuring production-ready persistence for 100K+ users. Automated deployments with Terraform and AWS CDK, integrated CI/CD pipelines with GitHub Actions, and accelerated release cycles by 70%. Implemented unit and integration tests using Mockito to maintain 90%+ code coverage and ensure production reliability.-->

### Software Engineer, Humanitarians AI – Remote (Feb 2025 – Present)
Prototyped an AI-powered travel planner using FastAPI, Next.js, Cohere and Hugging Face that improved itinerary relevance by 37% in benchmarks and designed to scale to 10K monthly users. Developed a doctor recommendation engine trained on 520K+ profiles, improving match precision by 33% and reducing lookup time from 14 to 6 mins in controlled trials. Integrated 310K+ medical reports into Chroma DB with Groq API embeddings, cutting median query latency from 212ms to 117ms (45% faster) during load simulations. Designed an ER triage RAG App that categorized patients into 5 severity levels, lowering simulated prioritization delays by 24% in experimental evaluations.

### Software Engineer, Nuvera Fuel Cells – Boston, MA (July 2023 – Dec 2023)
Built a React.js dashboard integrated with Python, RabbitMQ, and Redis, enabling real-time monitoring of 50K daily telemetry events and reducing fault detection time from 9 to 2 minutes. Designed a Redis-backed Token Bucket rate limiter for APIs, sustaining 50K daily requests at 95ms latency and ensuring reliable performance under load. Developed a Python-based chatbot with LangChain and Vector DB integration, reducing analysis time by 83% and enabling adoption by 30 engineers for daily diagnostics.

### Software Engineer, Larsen & Toubro Infotech – Mumbai, India (Jan 2021 – Aug 2022)
Enhanced Spring Boot REST APIs with an ML-based duplicate detection system with 85% confidence, automating 90% of CRM reviews across 100K customer portals. Architected a microservices-based medical records platform with Spring Boot and MongoDB, managing 50M+ records with 99.9% uptime for 100K users. Adopted Agile and Test-Driven Development (TDD) with JUnit, integrating Jenkins into CI/CD pipelines to improve defect detection by 25% and ensure consistent release quality. Modernized a legacy authentication system by replacing ActiveX with a Java Servlet–based LDAP and JWT solution, enabling cross-browser compatibility and secure deployment on Oracle WebLogic Server. Built interactive dashboards with React.js and REST APIs, streamlining data access for 5K+ monthly users across healthcare workflows.

## Projects

### SIEM Intrusion Detection System
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/SIEM_Intrusion_Detection)**

**Technologies**: ELK Stack (Elasticsearch, Logstash, Kibana), Docker, AWS, Python

**Impact**: Processed 58,200+ security events with real-time threat detection and geographic attack visualization

**Key Features**: 
- Real-time network monitoring with 45% reduction in query latency (212ms → 117ms)
- Geographic heatmaps showing global attack distribution and top attacking IPs
- Automated threat detection with port scan analysis and anomaly identification
- Production-ready deployment with Docker containerization and AWS integration

### Automated Skin Lesion Classification System
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/Automated-Skin-Lesion-System)**

**Technologies**: TensorFlow, EfficientNet, ResNet-50, Python, Parallel Computing

**Impact**: Achieved 97.66% test accuracy for early skin cancer detection across 8 lesion categories

**Key Features**:
- Trained on 208,000+ dermoscopic images with parallel processing optimization (2.1x speedup)
- Implemented multiple deep learning architectures (EfficientNetB2/B3, ResNet-50)
- GPU-accelerated training with CUDA optimization and memory management
- Comprehensive evaluation with confusion matrix analysis and clinical validation

### ASL Detection and Real-Time Text Conversion System
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/ASL-Detection-and-Real-Time-Text-Conversion-System)**

**Technologies**: MediaPipe, TensorFlow, OpenCV, Streamlit, Python

**Impact**: 97.66% accuracy in real-time American Sign Language recognition with 208,000+ training images

**Key Features**:
- Real-time pose estimation with 21 hand landmarks and 42-dimensional feature vectors
- Live webcam processing with 2-second stability confirmation for gesture accuracy
- Dynamic text construction enabling word and sentence building
- Accessibility-focused design for deaf and hard-of-hearing communication

### UrbanCart - Secure E-Commerce Platform
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/UrbanCart)**

**Technologies**: React.js, Flask, PostgreSQL, Stripe API, Docker, AWS RDS

**Impact**: Production-ready e-commerce solution with comprehensive security implementation

**Key Features**:
- JWT authentication with CSRF protection and Firebase OTP verification
- Secure payment processing with Stripe integration and webhook handling
- Docker containerization with Nginx reverse proxy for scalable deployment
- SQL injection prevention and XSS protection with comprehensive security testing

### URL Shortener Service (AWS Free Tier Optimized)
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/URL_Shortener_Service)**

**Technologies**: AWS Lambda, DynamoDB, API Gateway, Python, CloudFormation

**Impact**: Serverless URL shortening service optimized for AWS Free Tier with smart caching

**Key Features**:
- In-memory caching reducing DynamoDB calls by 80% for cost optimization
- Serverless architecture handling 1M+ requests/month within free tier limits
- RESTful API with URL validation, click analytics, and automatic cleanup
- Automated deployment with PowerShell scripts and CloudFormation templates

### Rate Limiter Service
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/rate_limiter_service)**

**Technologies**: Python, Redis, Docker, Token Bucket Algorithm, Distributed Systems

**Impact**: High-performance rate limiting service supporting 50K+ requests with 95ms latency

**Key Features**:
- Token bucket algorithm implementation with Redis backend for distributed rate limiting
- Configurable rate limits per user/IP with sliding window and burst handling
- Docker containerization with health checks and monitoring integration
- Production-ready with comprehensive testing and performance optimization

### Nomad AI - Personal AI Travel Planner
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/Nomad-AI)**

**Technologies**: Next.js, FastAPI, OpenAI/Anthropic LLMs, Sentence Transformers, FAISS, PostgreSQL

**Impact**: AI-powered travel planning with 37% improvement in itinerary relevance and conversational interface

**Key Features**:
- Natural language trip planning with constraint extraction and intent recognition
- Retrieval-augmented generation (RAG) for curated places and activities using embeddings
- Multimodal output with optional image generation for trip visualization
- Day-wise itinerary generation with maps, POIs, and time budgeting

### Patient Triage AI System
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/Patient_Triage_AI)**

**Technologies**: FastAPI, Cohere API, ChromaDB, Next.js, Python, Vector Embeddings

**Impact**: Emergency room triage system categorizing patients into 5 severity levels with 24% reduction in prioritization delays

**Key Features**:
- RAG-based patient assessment using 310K+ medical reports with ChromaDB vector storage
- Real-time symptom analysis and severity classification (Critical, High, Medium, Low, Minimal)
- Conversational interface for patient data collection and medical history analysis
- Integration with medical databases for evidence-based triage recommendations

### Swarm Intelligence Agent
**🔗 [GitHub Repository](https://github.com/omkar04gaikwad/Agents/tree/main/Swarm_Intelligence_Agent)**

**Technologies**: Python, Multi-Agent Systems, Swarm Algorithms, Distributed Computing

**Impact**: Advanced multi-agent system implementing swarm intelligence principles for collaborative problem-solving

**Key Features**:
- Distributed agent coordination with emergent behavior patterns
- Swarm optimization algorithms for complex problem-solving scenarios
- Real-time agent communication and decision-making protocols
- Scalable architecture supporting dynamic agent addition and removal

## Technical Skills

### Programming Languages
**Proficient**: Python, Java, JavaScript, SQL
**Familiar**: C++, TypeScript, Go, PowerShell

### Machine Learning & AI
**Frameworks**: TensorFlow, Keras, PyTorch, Scikit-learn
**Specializations**: Computer Vision, Natural Language Processing, Deep Learning, Transfer Learning
**Tools**: MediaPipe, OpenCV, Pandas, NumPy, Matplotlib

### Web Development
**Frontend**: React.js, Next.js, HTML5, CSS3, Material-UI, Streamlit
**Backend**: Flask, Spring Boot, FastAPI, Node.js, Express.js
**Databases**: PostgreSQL, MongoDB, Redis, DynamoDB, MySQL

### Cloud & DevOps
**Cloud Platforms**: AWS (EC2, RDS, Lambda, S3, CloudFormation), Google Cloud Platform
**Containerization**: Docker, Docker Compose, Kubernetes
**CI/CD**: GitHub Actions, Jenkins, GitLab CI
**Infrastructure**: Terraform, AWS CDK, Nginx, Load Balancing

### Security & Authentication
**Security**: JWT, OAuth2, CSRF Protection, SQL Injection Prevention, XSS Protection
**Authentication**: Firebase Auth, LDAP, Multi-Factor Authentication (MFA)
**Encryption**: SSL/TLS, bcrypt, AES-256, HTTPS

### Data & Analytics
**Databases**: Database design, query optimization, indexing, ACID compliance
**Analytics**: ELK Stack, Kibana dashboards, real-time monitoring, log analysis
**Processing**: ETL pipelines, data preprocessing, feature engineering

### Specialized Tools
**Payment Processing**: Stripe API, webhook handling, PCI compliance
**Monitoring**: CloudWatch, Prometheus, Grafana, Application Performance Monitoring
**Testing**: Unit testing, integration testing, load testing, security testing

