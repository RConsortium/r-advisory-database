# RConsortium Advisory Database

This is a community owner repository of advisories for packages published on
[https://cran.r-project.org/](https://cran.r-project.org/) and
[https://www.bioconductor.org/](https://www.bioconductor.org/).

Advisories live in the [vulns](vulns/) directory and use a YAML encoding of the
[OSV format](https://ossf.github.io/osv-schema/).

## Contributing advisories

### Making a pull request

Existing entries can be edited by simply creating a pull request.

To introduce a new entry, create a pull request with a new file that has a name matching RSEC-<latest-id.txt + 1>-<anything>.yaml.

Increment the file `latest-id.txt` in your pull request.

### Triage process

Vulnerabilities should be pulled from a source like Github or the [NVD CVE](https://nvd.nist.gov/vuln/data-feeds) feeds.
These will be properly vetted, and approved.
