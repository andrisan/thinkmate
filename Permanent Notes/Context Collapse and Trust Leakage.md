# Context Collapse and Trust Leakage

Trust granted in one context can illegitimately leak into another, creating security vulnerabilities.

## Forms of Trust Failure

### Context Collapse
- Content reused outside its original context
- Verification semantics lost when media is extracted
- Original trust scope no longer applies

### Trust Transfer
- Trust from one platform assumed on another
- "Verified on X" treated as "verified everywhere"
- Cross-platform impersonation exploits this

### Implicit Trust Inheritance
- Systems assume prior verification remains valid
- No expiration or re-validation requirements
- Trust becomes stale and exploitable

## Example

A video verified as authentic in a secure video call is downloaded and reused on social media. The original verification (cryptographic, real-time) no longer applies, but viewers implicitly trust it based on appearance.

## Prevention

[[Zero Trust Persona]] addresses this through:
- **Contextual trust** — Trust is scoped to specific contexts
- **Temporal trust** — Trust decays over time
- **Revocable trust** — Trust can be withdrawn
- **Explicit signaling** — Trust status is visible, not assumed

## Related

- [[Zero Trust Persona]]
- [[Trust Through Verification Not Appearance]]
- [[Continuous and Revocable Trust]]

#zero-trust #trust #context #security #phd-research
