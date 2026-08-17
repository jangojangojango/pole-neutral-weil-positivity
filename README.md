# Pole-neutral Weil positivity through the first prime threshold

This repository contains the rigorous computer-assisted certificate
accompanying the paper

**Pole-neutral Weil positivity through the first prime threshold**.

## Proof artifact

The definitive proof certificate is

`first_prime_codim2_certificate.py`

with SHA-256

`716e4641f8b97d3e18921ae957d685651bc88ec8238d7dd2d351454d5c401175`

The certificate uses rigorous Arb ball arithmetic through `python-flint`,
together with exact rational arithmetic and exact rational LDL^T
factorizations.

## Running the certificate

Install the required package:

```bash
python -m pip install python-flint==0.6.0
```

Then run:

```bash
python first_prime_codim2_certificate.py
```

A successful execution terminates with:

```text
CORRECTED CODIMENSION-TWO FINITE CERTIFICATE PASSED
Odd finite Schur lower bound  > 0.003
Even finite Schur lower bound > 0.00018
```

## Provenance

The SHA-256 above identifies the exact frozen proof artifact.

The original successful execution established the certificate-pass condition
and the finite lower bounds stated above. The exact historical software
environment was not preserved. Reproduction runs are therefore documented
separately and do not alter the frozen proof artifact.

