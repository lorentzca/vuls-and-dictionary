# vuls-and-dictionary

Run vuls, go-cve-dictionary, goval-dictionary.

## Usage

```
$ docker run -it --rm lorentzca/vuls-and-dictionary vuls
Usage: vuls <flags> <subcommand> <subcommand args>

Subcommands:
        commands         list all command names
        flags            describe all known top-level flags
        help             describe subcommands and their syntax

Subcommands for configtest:
        configtest       Test configuration

Subcommands for discover:
        discover         Host discovery in the CIDR

Subcommands for history:
        history          List history of scanning.

Subcommands for report:
        report           Reporting

Subcommands for scan:
        scan             Scan vulnerabilities

Subcommands for tui:
        tui              Run Tui view to analyze vulnerabilities


Use "vuls flags" for a list of top-level flags
```
