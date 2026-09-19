# STRATAON SNMP MIBs

Official SNMP Management Information Base (MIB) definitions for STRATAON devices.

This repository provides the official MIB files required to monitor and integrate STRATAON products with SNMP-compatible network management and monitoring systems.

## Supported Products

The current STRATAON MIB includes definitions for:

- miniPLC
- smartPDU
- miniENV
- sentiaMAN
- sentiaPRO
- sentiaLOK

Support may vary according to product model and firmware version.

## Enterprise OID

STRATAON uses the following IANA Private Enterprise Number (PEN):

```text
1.3.6.1.4.1.66204
```

## Integration

The STRATAON MIB can be used with SNMP-compatible monitoring and management systems, including:

- PRTG Network Monitor
- Zabbix
- Net-SNMP
- Other SNMP-compatible NMS platforms

## Repository Structure

```text
strataon-mibs/
├── README.md
├── CHANGELOG.md
├── LICENSE
└── mibs/
    └── STRATAON-MIB.mib
```

## MIB File

The current MIB is available at:

```text
mibs/STRATAON-MIB.mib
```

Version-specific MIB files are provided with GitHub Releases.

## SNMP

The STRATAON MIB provides a common enterprise tree for STRATAON devices, including common system and network information and product-specific branches.

The current MIB uses Product IDs for the supported product families:

| Product ID | Product |
| ---: | --- |
| 1 | miniPLC |
| 2 | smartPDU |
| 3 | miniENV |
| 4 | sentiaMAN |
| 5 | sentiaPRO |
| 6 | sentiaLOK |

## Compatibility

The STRATAON MIB structure has been validated with:

- Net-SNMP
  - `snmpwalk`
  - `snmpget`
  - `snmptranslate`
  - `smilint`
- PRTG Network Monitor
- Zabbix

## Version History

See [CHANGELOG.md](CHANGELOG.md) for the revision history.

Version-specific files and release notes are available in the repository's GitHub Releases.

## Support

For technical support and integration assistance:

- Website: https://strataon.com.br
- E-mail: suporte@strataon.com.br

## Security

If you believe you have found a security issue involving a STRATAON product, please contact STRATAON directly rather than opening a public GitHub issue.

## License

Use and redistribution of the integration resources in this repository are governed by the [LICENSE](LICENSE) file.

Copyright © 2026 STRATAON Equipamentos Eletrônicos Ltda.
