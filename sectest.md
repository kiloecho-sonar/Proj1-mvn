# Security Test File

This file is used to validate SonarQube secrets detection on .md files.
Do not commit real credentials.

## AWS

AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE
AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY

## Database

DATABASE_URL=postgresql://admin:SuperSecret123!@prod-db.internal:5432/appdb

## API Keys

STRIPE_SECRET_KEY=sk_live_51Hxample000000000EXAMPLEKEY12345678
GITHUB_TOKEN=ghp_exampleTOKENabcdefghijklmnopqrstuvwxyz12

## Private Key (PEM format)

-----BEGIN RSA PRIVATE KEY-----
MIIEowIBAAKCAQEA2a2rwplBQLF29amygykEMmYz0+Kcj3bKBp29P2rFj7dEBNGn
EEE5bxoB5B6EXAMPLE1234567890EXAMPLEKEY/NOTREAL==
-----END RSA PRIVATE KEY-----
