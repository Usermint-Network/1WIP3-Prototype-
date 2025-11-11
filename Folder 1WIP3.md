1WIP3-Prototype/  
├─ README.md                ← start here (what/why/how)  
├─ .gitignore               ← keeps secrets & junk out of git  
├─ LICENSE                  ← MIT license  
├─ requirements.txt         ← Python deps for the API  
│  
├─ app/                     ← the running API (you’ll touch this often)  
│  ├─ app.py                ← main Flask server (endpoints)  
│  ├─ db\_utils.py           ← DB connection \+ commit/rollback  
│  ├─ sbt\_handler.py        ← SBT identity helpers (MVP)  
│  └─ utils/                ← small helpers (hashing/validation)  
│  
├─ docker/                  ← how we run locally and in containers  
│  ├─ Dockerfile            ← builds the API image  
│  ├─ docker-compose.yml    ← spins up API \+ Postgres together  
│  └─ entrypoint.sh         ← optional startup script  
│  
├─ infra/                   ← Terraform (cloud infra as code)  
│  ├─ main.tf               ← VPC/VM/etc  
│  ├─ variables.tf          ← knobs to configure  
│  ├─ outputs.tf            ← useful values after apply  
│  └─ terraform.tfvars.example  
│  
├─ docs/                    ← human-readable guides  
│  ├─ API\_REFERENCE.md      ← endpoint-by-endpoint  
│  ├─ CELESTIAL\_PROTOCOL.md ← weekly maintenance policy  
│  └─ ARCHITECTURE\_OVERVIEW.md  
│  
├─ sbt/                     ← identity/SBT extras (stubs now)  
│  └─ bridge/               ← Hedera/XRPL/EVM stubs  
│  
└─ tests/                   ← smoke tests & fixtures