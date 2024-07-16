# GS1 Key Credential 

This is the Verifiable Credential that indicates that something has been identified. It contains no
data about what has been identified as that is done via the association process. This credential is
used only to indicate that the key that it contains exists and is valid. When the key is retired (e.g., a
product is withdrawn from the market or an asset is destroyed), the credential is revoked.

The credential subject ID must be a GS1 Digital Link URI. While preference should be given to the
canonical URI (based on id.gs1.org), this is not required. Using the GS1 Digital Link URI means that
the credential can support any level of granularity required (e.g., GTIN, GTIN+CPV, GTIN+lot,
GTIN+serial, GLN, GLN+extension, etc.).
