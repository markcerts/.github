**markcerts** is an open-source ecosystem for managing and distributing trusted Mark Verifying Authority
(MVA) root certificates. It provides lightweight, language-friendly packages for securely embedding and
updating MVA root certificates in applications and tooling. 🔐

The primary use-case for **markcerts** is with **BIMI (Brand Indicators for Message Identification)**,
where **VMCs (Verified Mark Certificates)** and **CMCs (Certified Mark Certificates)** are used to prove
the authenticity of brand marks. In this model, markcerts acts as the root CA store that email providers
and MTAs can use to verify the full certificate chain behind a displayed logo.

## 📦 What's here?

### **mvarcs**
The [core `mvarcs` repo](https://github.com/markcerts/mvarcs) containing the canonical **`cacert.pem`** bundle.

### **Libraries**
Easy ways to consume the certificate bundle in your projects:

- [mvarcs-python](https://github.com/markcerts/mvarcs-python)
- [mvarcs-nodejs](https://github.com/markcerts/mvarcs-nodejs)
