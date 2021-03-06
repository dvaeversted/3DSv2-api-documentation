# Clearhaus 3-D Secure v2 API Documentation

This is the documentation for the 3dsecure.io 3-D Secure Server.

## Status

The service, sandbox and documentation are all running in beta. Beta means functional, but needs
polish and/or minor changes.

## About

This documentation is meant to stand alone, so it is not necessary to refer to the specification.

Comments, pull requests and general feedback is welcome from anyone.

## Specification

The 3-D Secure v2 specification is defined by EMVCo, their list of 3-D Secure v2
documentation can be found [on their documentation
page](https://www.emvco.com/document-search/?action=search_documents&publish_date=&emvco_document_version=&emvco_document_book=&px_search=&emvco_document_technology%5B%5D=3-d-secure).

Specifically, the primary documentation can be found in [EMV® 3-D Secure
Protocol and Core Functions Specification.](https://www.emvco.com/wp-content/uploads/documents/EMVCo_3DS_Spec_v220_122018.pdf)

The spec is currently at version 2.2.0.

## Generate documentation locally

The documentation is currently generated by Sphinx. It can be generated locally by Makefile:
```
make
```

The generated documentation is then rooted in `build/html/index.html`.
