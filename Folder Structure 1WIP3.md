1WIP3-Prototype/  
│  
├── 📄 .gitignore  
├── 📄 LICENSE  
├── 📄 README.md  
├── 📄 requirements.txt  
│  
├── app/  
│   ├── \_\_init\_\_.py  
│   ├── app.py  
│   ├── db\_utils.py  
│   ├── sbt\_handler.py  
│   ├── config.py  
│   └── utils/  
│       ├── \_\_init\_\_.py  
│       ├── hashing.py  
│       └── validation.py  
│  
├── infra/  
│   ├── main.tf  
│   ├── variables.tf  
│   ├── outputs.tf  
│   ├── terraform.tfvars.example  
│   └── README.md  
│  
├── docker/  
│   ├── Dockerfile  
│   ├── docker-compose.yml  
│   ├── entrypoint.sh  
│   └── .dockerignore  
│  
├── data/  
│   ├── migrations/  
│   └── samples/  
│       └── test\_payload.json  
│  
├── docs/  
│   ├── API\_REFERENCE.md  
│   ├── ARCHITECTURE\_OVERVIEW.md  
│   ├── CELESTIAL\_PROTOCOL.md  
│   ├── CONTRIBUTING.md  
│   ├── SECURITY.md  
│   └── GOVERNANCE\_MODEL.md  
│  
├── sbt/  
│   ├── \_\_init\_\_.py  
│   ├── sbt\_schema.json  
│   ├── verifier.py  
│   ├── mint\_sbt.py  
│   └── bridge/  
│       ├── hedera\_bridge.py  
│       ├── xrpl\_bridge.py  
│       └── eth\_bridge.py  
│  
└── tests/  
    ├── \_\_init\_\_.py  
    ├── test\_api.py  
    ├── test\_sbt.py  
    ├── test\_db.py  
    └── fixtures/  
        ├── mock\_identity.json  
        └── mock\_tx.json