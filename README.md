# Hitachi Virtual Storage Platform (VSP) - Cisco Intersight Cloud Orchestrator (ICO) Custom Batch Workflows

This project repository serves as a hosting space for custom Cisco ICO workflows that enable batch operations on general VSP storage operations such as:

- Expanding Volume Capacities
- Creating Host Groups
- Adding LUN IDs (LUN Paths)
- Deleting Host Groups
- Deleting LUN IDs (LUN Paths)
- Deleting Volumes
- Creating Volumes

These workflows will allow users who utilze the Hitachi VSP within ICO enviroments to effciently utilize batch jobs within a single workflow for large scale enviroments,  negating the need to repetitively execute multiple workflows for common operations.
## Usage

These workflows are for personal usage within private lab enviroments only, end users assume all risks when utilizing this repository and shall not implement or distribute outside the usage outlined in this document. “Workflows are being provided to you “AS-IS”, without any warranties, express or implied including but not limited to warranties of merchantability, fitness for a particular purpose, non-infringement, or accuracy of information.   In no event will Hitachi Vantara be liable to for any damages, including direct, indirect,  special, incidental, punitive, or consequential damages arising from access or use of the Workflows. 


## Deployment

To deploy these custom workflows,  end users must download respective workflows in JSON format and import them within their ICO instance via the Import Workflow function.


## Documentation

To understand the best practices when utlizing ICO with the Hitachi VSP, including the custom workflows in this document please view the below best practices guide:
[Documentation](https://docs.hitachivantara.com/v/u/en-us/application-optimized-solutions/mk-sl-280)
