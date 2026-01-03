orbitlink-enterprise-gateway/
├── README.md
├── architecture/
│   └── orbitlink-architecture.png
├── docs/
│   ├── onboarding.md
│   ├── api-reference.md
│   ├── partner-integration.md
│   └── sales-demo-script.md
├── telemetry-agent/
│   ├── agent.py
│   ├── config.yaml
│   └── Dockerfile
├── api-gateway/
│   ├── app/
│   │   ├── main.py
│   │   ├── auth.py
│   │   ├── routers/
│   │   │   ├── telemetry.py
│   │   │   ├── networks.py
│   │   │   └── partners.py
│   │   └── models.py
│   ├── Dockerfile
│   └── requirements.txt
├── sdk/
│   └── python/
│       ├── orbitlink/
│       │   ├── __init__.py
│       │   └── client.py
│       └── setup.py
├── postman/
│   └── orbitlink.postman_collection.json
├── docker-compose.yml
├── .gitignore
└── ci/
    └── pipeline.yml
