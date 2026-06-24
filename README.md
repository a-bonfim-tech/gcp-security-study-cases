<p>
<a href="README.md">[EN]</a> <a href="README.de.md">[DE]</a> <a href="README.pt.md">[PT]</a>
</p>

# GCP Security Cases (Portfolio Evidence)

This repository contains 5 security-focused Google Cloud study cases, each backed by screenshots and audit-ready reasoning.

## Architecture overview
The relationship between the cases, the layered security model, and framework
alignment is documented in
[docs/architecture-overview.md](docs/architecture-overview.md).

## Cases
1. [Cloud Armor: Traffic Blocklisting (WAF at the Edge)](01-cloud-armor-blocklisting/README.md)
2. [Cloud NGFW: Workload Protection](02-cloud-ngfw-workload-protection/README.md)
3. [BeyondCorp Enterprise: Zero Trust Access to Compute Engine](03-beyondcorp-enterprise-ce-protection/README.md)
4. [CMEK with Cloud KMS for Cloud Storage (plus Secrets discipline)](04-cmek-kms-secret-manager/README.md)
5. [Cloud Logging + Monitoring + VPC Flow Logs (Observability for SecOps)](05-logging-monitoring-vpc-flow-logs/README.md)

## Evidence standard
Each case has an /evidence folder with named screenshots to prove configuration, enforcement, and logs.

## Security policy
Sensitive cloud identifiers, secrets, and unsafe evidence handling concerns are
covered in [SECURITY.md](SECURITY.md).
