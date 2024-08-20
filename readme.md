# Handling Suspicious Sensitive Documents

Documents with sensitive information can lead to potential problems when it comes to malware analysis and triage. When documents can't be uploaded to open source tools such as virustotal to analyze samples manual triage is needed.

Most files handled containing sensitive data would be:

- Zip
- PDF
- Office Docs

The samples from the guide are available [here](https://github.com/obscur-ity/Document-Samples)

## Zip

Nothing much to say here but take into consideration that images / txt files inside could contain sensitive info. Although they should be separated before the analysis stage sometimes malware uses things like images / audio / text files and more to contain encrypted malware.

## PDFs

PDFs can contain simply just a phishing link inside to something as complex as range of scripts that will be ran when opened.

[This guide](./PDF/PDF.md) will run you through some simple ways to extract malicious IOCs from PDF documents.

## Office Docs

Microsoft office documents support a few ways an attacker could use. The common attacks done are phishing links, VBS macros, attached files.

[This guide](./Office/Office.md) will be a short outline of how to extract scripts / indicators from office documents without needing to open them.
