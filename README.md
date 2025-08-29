# OCA Payroll

This repository contains **5** OCA packages for payroll.

## Packages Included (5 packages)

- **odoo-bringout-oca-payroll-hr_payroll_document** - From payroll: hr_payroll_document
- **odoo-bringout-oca-payroll-hr_payroll_period** - From payroll: hr_payroll_period
- **odoo-bringout-oca-payroll-payroll** - From payroll: payroll
- **odoo-bringout-oca-payroll-payroll_account** - From payroll: payroll_account
- **odoo-bringout-oca-payroll-payroll_contract_advantages** - From payroll: payroll_contract_advantages


## Installation

Install any package from this category:

```bash
# Install from local directory
pip install packages/oca-payroll/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/oca-payroll/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/oca-payroll/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
oca-payroll/
├── odoo-bringout-oca-PROJECT-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## Contributing

These packages are maintained as part of the [OCA (Odoo Community Association)](https://github.com/OCA) ecosystem.

## License

Each package maintains its original license as specified in the OCA repositories.
