# Scope

# Open Verification: Proof-of-Control of AI — Working Group Scope

The goal is open verification: the ability to trust that an AI system did only
what it was authorized to do, because an independent party can check it, not
because the operator asserts it. Open verification means the standard, the
method, and the tools used to check what a system did are themselves open,
independent, and inspectable, which is what turns a claim into checkable
evidence. (This concerns the openness of the verification system, not whether
any AI model is open-source.)

Proof-of-Control is the technical framework for open verification: the evidence
properties, the Domains of Verification, and the spectrum of verification by
which evidence is graded. This Working Group develops the Standard that defines
the cryptographic stage of that framework: independently verifiable evidence of
what an AI system did, the data it touched, the actions it took, and whether it
stayed within its authorized boundaries.

## In scope
- The definition of Proof-of-Control evidence and its required properties
  (contemporaneous, tamper-evident, attributable, independently checkable).
- The Domains of Verification: the categories of control boundary an AI system
  must demonstrate it honored. The specific domains are to be defined and
  maintained by the Working Group.
- The Proof-of-Control Spectrum, that defines the levels of trustworthiness depending on the level of verification
- A conformance model: the binary conformance threshold and a standardized
  trust-assumption disclosure.
- An assessment methodology by which an independent party can confirm a
  conformance claim (open verification in practice).
- Mappings to existing frameworks (e.g. NIST AI RMF, ISO/IEC 42001, CSA MAESTRO,
  OWASP) for interoperability.

## Out of scope
- Certification operations, accreditation, and any trust mark, which are
  governed separately.
- Insurance products, underwriting rules, and pricing.
- Requirements for what an AI model should do or how it is built; this Standard
  concerns evidence of what a system did, not model quality, safety, or
  correctness.
- Whether an AI model is open-source or proprietary; open verification concerns
  the verification system, not the model.
- Mandating any specific vendor, product, or service.
