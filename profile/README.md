markcerts is a toolkit and ecosystem for handling mark certificates, along with a trusted root certificate store for Mark Verifying Authorities (MVAs). Its aim is to provide clean, language-friendly utilities for working with authenticated marks and their supporting certificate chains. 🔐

markcerts is designed to support use cases such as BIMI (Brand Indicators for Message Identification), where VMCs (Verified Mark Certificates) and CMCs (Certified Mark Certificates) enable email providers and MTAs to authenticate displayed brand logos.

The primary component, [**mvarcs**](https://github.com/markcerts/mvarcs) (Mark Verifying Authority Root Certificate Store), delivers the canonical [cacert.pem](https://raw.githubusercontent.com/markcerts/mvarcs/refs/heads/main/cacert.pem) bundle for verifying MVA-issued mark certificates. Future work may expand into higher-level tooling and BIMI-related libraries.

## 📦 What else is here?

### **mvarcs libraries**
Easy ways to consume the certificate bundle in your projects:

- [mvarcs-python](https://github.com/markcerts/mvarcs-python)
- [mvarcs-nodejs](https://github.com/markcerts/mvarcs-nodejs)

## 📚 References

- [**BIMI Group**](https://bimigroup.com)
- [**AuthIndicators GitHub**](https://github.com/authindicators)
- [**Fetching and Validating VMCs (IETF Draft)**](https://datatracker.ietf.org/doc/html/draft-fetch-validation-vmc-wchuang)
- [**BIMI (IETF Draft)**](https://datatracker.ietf.org/doc/html/draft-brand-indicators-for-message-identification)
