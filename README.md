# S.L.A.V.K.O.™ Score 4.x  
Deterministic AI Evaluation Engine for Enterprise Governance

S.L.A.V.K.O.™ Score is a deterministic, auditable, and enterprise‑grade AI evaluation framework designed for high‑integrity environments.  
It provides a complete governance pipeline with strict reproducibility, multimodal extraction, and compliance‑ready scoring.

## Badges

![Deterministic](https://img.shields.io/badge/Deterministic-Yes-orange)
![Reproducibility](https://img.shields.io/badge/Reproducibility-Guaranteed-orange)
![Audit_Chain](https://img.shields.io/badge/Audit_Chain-Cryptographic-orange)
![Enterprise Ready](https://img.shields.io/badge/Enterprise_Ready-Yes-black)
![Governance Layer](https://img.shields.io/badge/Governance-Layer_v8-black)
![Zero Trust](https://img.shields.io/badge/Security-Zero_Trust-black)
![Multimodal](https://img.shields.io/badge/Multimodal-Supported-green)
![Compliance](https://img.shields.io/badge/Compliance-Ready-green)
![Plugins](https://img.shields.io/badge/Plugins-Hot_Reload-green)

## Overview

S.L.A.V.K.O.™ Score is part of the Formatdisc Integrity Stack — a suite of tools engineered for deterministic AI operations.  
The system enforces strict reproducibility, schema validation, and cryptographically verifiable audit trails.

### Architecture Components

| Component | Purpose | Stage |
|----------|---------|--------|
| SlavkoKernel v8 | Governance & Presentation Layer | Final Output |
| SlavkoShell 2.0 | Validation & Routing Layer | First Checkpoint |
| SlavkoFusion 1.0 | Multimodal Extraction Layer | Second Checkpoint |
| SlavkoScore 4.x | Evaluation & Compliance Layer | Third Checkpoint |

## Key Features

### Deterministic Execution
- Identical input always produces identical output  
- Temperature=0, top_p=0 enforced  
- Immutable audit chain with cryptographic signatures  
- Full reproducibility for compliance and regulatory audits  

### Multimodal Support
- Text, image, PDF, UI mock‑ups, and code analysis  
- Unified feature extraction pipeline  
- OCR and layout analysis  
- Vision model support (phi3‑vision, LLaVA, etc.)

### Enterprise Security
- Zero‑trust architecture  
- Schema validation at every stage  
- KernelBus v2 audit trail  
- Self‑hosted, no vendor lock‑in  

### Plugin System
- Custom scoring rules  
- Custom extractors for new modalities  
- Hot‑reloadable plugin architecture  
- Python‑based plugin development  

## Quick Start


git clone https://github.com/<your-org>/SlavkoScore
cd SlavkoScore

pip install -e .

python -m slavko_score.api


Dashboard:  
http://localhost:8000

## Ollama Integration

Pre‑configured Modelfiles are included for:

- deepseek-r1  
- phi3-vision  
- qwen2.5:14b  


ollama pull deepseek-r1
python -m slavko_score.cli --model deepseek-r1


## Documentation

- docs/README_SlavkoKernel_v8.md  
- docs/README_SlavkoShell_2_0.md  
- docs/README_SlavkoFusion_1_0.md  
- docs/README_SlavkoScore_4_x.md  
- docs/API_Reference.md  
- docs/Determinism_Guide.md  
- docs/Deployment_Guide.md  
- docs/Plugin_Development_Guide.md  

## Deployment

### Docker
```bash
docker-compose up -d
```

### Kubernetes

kubectl apply -f k8s/


## Benchmarks

| Model | Latency | RAM | Use Case |
|-------|---------|-----|----------|
| deepseek-r1 | 1.5–3s | 8–10GB | High‑precision evaluation |
| qwen2.5:14b | 1–2s | 6–8GB | Standard compliance |
| llama3.1:8b | 0.8–1.5s | 4–5GB | Fast screening |

## Security & Compliance

- SOC 2 Type II ready  
- GDPR compliant  
- HIPAA compatible (with proper configuration)  
- Full audit trail for every decision  
- Cryptographic signature support  

## License

MIT License.  
See LICENSE for details.

## Contact

Formatdisc — Computer Programming & Advanced Software Systems  
Founder & System Architect: **Mladen Gertner**  
Web: https://formatdisc.hr  
Email: mladen@formatdisc.hr  
Phone: +385 91 542 1014  
Location: Zagreb, Croatia  
OIB: 18915075854

From Code to Governance — One Score, One Audit Trail.
