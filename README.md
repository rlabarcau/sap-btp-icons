# SAP BTP Icons

A public collection of SAP Business Technology Platform (BTP) service icons in SVG format, served via jsDelivr CDN for use in Mermaid diagrams, architecture documentation, and any web-based tooling.

---

## CDN base URL

```
https://cdn.jsdelivr.net/gh/rlabarcau/sap-btp-icons@main/
```

Individual file example:

```
https://cdn.jsdelivr.net/gh/rlabarcau/sap-btp-icons@main/10025-sap-datasphere_sd.svg
```

---

## Usage in Mermaid diagrams

These icons are designed for use with the Mermaid `img` node syntax (requires Mermaid v11+).

### Basic example

```mermaid
flowchart LR
    SAP_DS@{ img: "https://cdn.jsdelivr.net/gh/rlabarcau/sap-btp-icons@main/10025-sap-datasphere_sd.svg", label: "SAP Datasphere", pos: "t", w: 30, h: 30, constraint: "on" }
    SAP_HANA@{ img: "https://cdn.jsdelivr.net/gh/rlabarcau/sap-btp-icons@main/20083-sap-hana-cloud_sd.svg", label: "SAP HANA Cloud", pos: "t", w: 30, h: 30, constraint: "on" }
    SAP_IS@{ img: "https://cdn.jsdelivr.net/gh/rlabarcau/sap-btp-icons@main/32086-sap-integration-suite_sd.svg", label: "SAP Integration Suite", pos: "t", w: 30, h: 30, constraint: "on" }

    SAP_DS --> SAP_IS --> SAP_HANA
```

### Node definition pattern

```
NODE_ID@{ img: "ICON_URL", label: "Service Name", pos: "t", w: 30, h: 30, constraint: "on" }
```

| Parameter | Value | Description |
|---|---|---|
| `img` | Full jsDelivr URL | Path to the SVG icon |
| `label` | Service name | Text shown below the icon |
| `pos` | `"t"` | Label position: top |
| `w` / `h` | `30` | Icon size in pixels |
| `constraint` | `"on"` | Keeps node sizing consistent |

---

## Complete node reference

See [`sap-btp-icons-mermaid.md`](./sap-btp-icons-mermaid.md) for the full list of ready-to-use node definitions for all 130+ services.

---

## Icon index

| Node ID | Service name | File |
|---|---|---|
| `SAP_PH` | SAP BTP Services Placeholder | `10001-placeholder-icon-for-sap-btp-services_sd.svg` |
| `SAP_CIA` | Cloud Integration Automation | `10002-cloud-integration-automation_sd.svg` |
| `SAP_DIE` | Document Information Extraction | `10004-document-information-extraction_sd.svg` |
| `SAP_ISA` | Intelligent Situation Automation | `10007-intelligent-situation-automation_sd.svg` |
| `SAP_OBS` | Object Store on SAP BTP | `10009-object-store-on-sap-btp_sd.svg` |
| `SAP_PR` | Personalized Recommendation | `10010-personalized-recommendation_sd.svg` |
| `SAP_ACEE` | SAP Analytics Cloud Embedded Edition | `10013-sap-analytics-cloud-embedded-edition_sd.svg` |
| `SAP_ALS` | SAP Audit Log Service | `10014-sap-audit-log-service_sd.svg` |
| `SAP_CFR` | SAP BTP Cloud Foundry Runtime | `10017-sap-btp_cloud-foundry-runtime_sd.svg` |
| `SAP_CICD` | SAP Continuous Integration and Delivery | `10022-sap-continuous-integration-and-delivery_sd.svg` |
| `SAP_DPI` | SAP Data Privacy Integration | `10023-sap-data-privacy-integration_sd.svg` |
| `SAP_DS` | SAP Datasphere | `10025-sap-datasphere_sd.svg` |
| `SAP_FFS` | SAP Feature Flags Service | `10028-sap-feature-flags-service_sd.svg` |
| `SAP_HTML5` | SAP HTML5 Application Repository Service | `10030-sap-html5-application-repository-service-for-sap-btp_sd.svg` |
| `SAP_KS` | SAP Keystore Service | `10035-sap-keystore-service_sd.svg` |
| `SAP_MSS` | SAP Malware Scanning Service | `10037-sap-malware-scanning-service_sd.svg` |
| `SAP_MDI` | SAP Master Data Integration | `10039-sap-master-data-integration_sd.svg` |
| `SAP_PS` | SAP Print Service | `10041-sap-print-service_sd.svg` |
| `SAP_PLS` | SAP Private Link Service | `10042-sap-private-link-service_sd.svg` |
| `SAP_S4IR` | SAP S/4HANA Cloud Intelligent Intercompany Reconciliation | `10044-sap-s4hana-cloud-for-intelligent-intercompany-reconciliation_sd.svg` |
| `SAP_ABAP` | SAP BTP ABAP Environment | `20016-sap-btp_abap-environment_sd.svg` |
| `SAP_LMC` | SAP Landscape Management Cloud | `20036-sap-landscape-management-cloud_sd.svg` |
| `SAP_UI5FK` | UI5 Flexibility for Key Users | `20049-ui5-flexibility-for-key-users_sd.svg` |
| `SAP_AppAuto` | Application Autoscaler | `20051-application-autoscaler_sd.svg` |
| `SAP_CMS` | SAP Cloud Management Service | `20053-sap-cloud-management-service-for-sap-btp_sd.svg` |
| `SAP_DAR` | Data Attribute Recommendation | `20054-data-attribute-recommendation_sd.svg` |
| `SAP_DC` | Document Classification | `20056-document-classification_sd.svg` |
| `SAP_AIC` | SAP AI Core | `20058-sap-ai-core_sd.svg` |
| `SAP_AIL` | SAP AI Launchpad | `20059-sap-ai-launchpad_sd.svg` |
| `SAP_AC` | SAP Analytics Cloud | `20061-sap-analytics-cloud_sd.svg` |
| `SAP_AppLog` | SAP Application Logging Service | `20062-sap-application-logging-service-for-sap-btp_sd.svg` |
| `SAP_BW` | SAP BTP Bandwidth | `20064-sap-btp-bandwidth_sd.svg` |
| `SAP_KYMA` | SAP BTP Kyma Runtime | `20065-sap-btp_kyma-runtime_sd.svg` |
| `SAP_BAS` | SAP Business Application Studio | `20069-sap-business-application-studio_sd.svg` |
| `SAP_OAUTH` | OAuth 2.0 on SAP BTP | `20070-oauth-20-on-sap-btp_sd.svg` |
| `SAP_CDS` | SAP Custom Domain Service | `20074-sap-custom-domain-service_sd.svg` |
| `SAP_CTM` | SAP Cloud Transport Management | `20076-sap-cloud-transport-management_sd.svg` |
| `SAP_CS` | SAP Connectivity Service | `20077-sap-connectivity-service_sd.svg` |
| `SAP_DestS` | SAP Destination Service | `20080-sap-destination-service_sd.svg` |
| `SAP_HANA` | SAP HANA Cloud | `20083-sap-hana-cloud_sd.svg` |
| `SAP_JSS` | SAP Job Scheduling Service | `20090-sap-job-scheduling-service_sd.svg` |
| `SAP_MOBI` | SAP Mobile Services | `20091-sap-mobile-services_sd.svg` |
| `SAP_MON` | SAP Monitoring Service for SAP BTP | `20092-sap-monitoring-service-for-sap-btp_sd.svg` |
| `SAP_OPP` | SAP Omnichannel Promotion Pricing | `20093-sap-omnichannel-promotion-pricing_sd.svg` |
| `SAP_PersASE` | SAP Persistence Service ASE | `20094-sap-persistence-service-ase_sd.svg` |
| `SAP_TH` | SAP Translation Hub | `20095-sap-translation-hub_sd.svg` |
| `SAP_VCP` | SAP Variant Configuration and Pricing | `20096-sap-variant-configuration-and-pricing_sd.svg` |
| `SAP_SM` | SAP Service Manager | `20098-service-manager_sd.svg` |
| `SAP_STI` | Service Ticket Intelligence | `20099-service-ticket-intelligence_sd.svg` |
| `SAP_XSUAA` | SAP Authorization and Trust Management Service | `31015-sap-authorization-and-trust-management-service_sd.svg` |
| `SAP_BWZA` | SAP Build Work Zone Advanced Edition | `31018-sap-build-work-zone_advanced-edition_sd.svg` |
| `SAP_CAS` | SAP Content Agent Service | `31021-sap-content-agent-service_sd.svg` |
| `SAP_DRM` | SAP Data Retention Manager | `31024-sap-data-retention-manager_sd.svg` |
| `SAP_DRC` | SAP Document and Reporting Compliance | `31026-sap-document-and-reporting-compliance_sd.svg` |
| `SAP_DMS` | SAP Document Management Service | `31027-sap-document-management-service_sd.svg` |
| `SAP_CISEM` | SAP Integration Suite Event Mesh | `31037-sap-integration-suite_event-mesh_sd.svg` |
| `SAP_PDM` | SAP Personal Data Manager | `31040-sap-personal-data-manager_sd.svg` |
| `SAP_RMS` | SAP Responsibility Management Service | `31043-sap-responsibility-management-service_sd.svg` |
| `SAP_SLM` | SAP Solution Lifecycle Management | `31045-sap-solution-lifecycle-management-service-for-sap-btp_sd.svg` |
| `SAP_TC` | SAP Task Center | `31046-sap-task-center_sd.svg` |
| `SAP_UDM` | SAP Usage Data Management Service | `31047-sap-usage-data-management-service-for-sap-btp_sd.svg` |
| `SAP_BER` | Business Entity Recognition | `31052-business-entity-recognition_sd.svg` |
| `SAP_DQS` | Data Quality Services | `31055-data-quality-services_sd.svg` |
| `SAP_ANS` | SAP Alert Notification Service | `31060-sap-alert-notification-service-for-sap-btp_sd.svg` |
| `SAP_AP` | SAP Automation Pilot | `31063-sap-automation-pilot_sd.svg` |
| `SAP_BA` | SAP Build Apps | `31066-sap-build-apps_sd.svg` |
| `SAP_BPA` | SAP Build Process Automation | `31067-sap-build-process-automation_sd.svg` |
| `SAP_BWZ` | SAP Build Work Zone | `31068-sap-build-work-zone_sd.svg` |
| `SAP_CreS` | SAP Credential Store | `31073-sap-credential-store_sd.svg` |
| `SAP_CIDS` | SAP Cloud Integration for Data Services | `31075-sap-cloud-integration-for-data-services_sd.svg` |
| `SAP_HSS` | SAP HANA Spatial Services | `31085-sap-hana-spatial-services_sd.svg` |
| `SAP_IOR` | Invoice Object Recommendation | `31103-invoice-object-recommendation_sd.svg` |
| `SAP_LP` | Landscape Portal for SAP S/4HANA Cloud ABAP Environment | `31104-landscape-portal-for-sap-s4hana-cloud_abap-environment_sd.svg` |
| `SAP_BC` | SAP Build Code | `31109-sap-build-code_sd.svg` |
| `SAP_CL` | Cloud Logging | `31112-cloud-logging_sd.svg` |
| `SAP_DES` | SAP Data Enrichment Service | `31114-sap-data-enrichment-service_sd.svg` |
| `SAP_DA` | SAP Digital Assistant | `31115-sap-digital-assistant_sd.svg` |
| `SAP_GT` | SAP Green Token | `31117-sap-green-token_sd.svg` |
| `SAP_HDS` | SAP Health Data Services for FHIR | `31118-sap-health-data-services-for-fhir_sd.svg` |
| `SAP_MDG` | SAP Master Data Governance | `31119-sap-master-data-governance_sd.svg` |
| `SAP_SAAS` | SAP SaaS Provisioning Service | `31120-sap-software-as-a-service-provisioning-service_sd.svg` |
| `SAP_CAS2` | SAP Content Agent Service (v2) | `32021-sap-content-agent-service_sd.svg` |
| `SAP_AEM` | SAP Integration Suite Advanced Event Mesh | `32032-sap-integration-suite_advanced-event-mesh_sd.svg` |
| `SAP_IAS` | SAP Identity Authentication | `32071-identity-authentication_sd.svg` |
| `SAP_IPS` | SAP Identity Provisioning | `32072-identity-provisioning_sd.svg` |
| `SAP_EB` | SAP Event Broker for SAP Cloud Applications | `32082-sap-event-broker-for-sap-cloud-applications_sd.svg` |
| `SAP_IS` | SAP Integration Suite | `32086-sap-integration-suite_sd.svg` |
| `SAP_GRAPH` | Graph | `32087-graph_sd.svg` |
| `SAP_ISGRAPH` | SAP Integration Suite Graph | `32087-sap-integration-suite_graph_sd.svg` |
| `SAP_DG` | Document Grounding | `32124-document-grounding_sd.svg` |
| `SAP_AMS` | SAP Authorization Management Service | `32127-authorization-management.svg` |
| `SAP_IDS` | SAP Identity Directory | `32128-identity-directory.svg` |
| `SAP_CIS` | SAP Cloud Identity Services | `32129-sap-cloud-identity-services_sd.svg` |
| `SAP_SLS` | SAP Secure Login Service for SAP GUI | `32130-sap-secure-login-service-for-sap-gui_sd.svg` |
| `SAP_DM` | SAP Digital Manufacturing | `32131-sap-digital-manufacturing_sd.svg` |
| `SAP_APIM` | SAP Integration Suite API Management | `32133-sap-integration-suite_api-management_sd.svg` |
| `SAP_CI` | SAP Integration Suite Cloud Integration | `32134-sap-integration-suite_cloud-integration_sd.svg` |
| `SAP_DSI` | SAP Integration Suite Data Space Integration | `32135-sap-integration-suite_data-space-integration_sd.svg` |
| `SAP_EIC` | Edge Integration Cell | `32136-edge-integration-cell_sd.svg` |
| `SAP_IA` | SAP Integration Suite Integration Advisor | `32138-sap-integration-suite_integration-advisor_sd.svg` |
| `SAP_ISAS` | SAP Integration Suite Integration Assessment | `32139-sap-integration-suite_integration-assessment_sd.svg` |
| `SAP_MA` | SAP Integration Suite Migration Assessment | `32140-sap-integration-suite_migration-assessment_sd.svg` |
| `SAP_OC` | SAP Integration Suite Open Connectors | `32141-sap-integration-suite_open-connectors_sd.svg` |
| `SAP_TPM` | SAP Integration Suite Trading Partner Management | `32142-sap-integration-suite_trading-partner-management_sd.svg` |
| `SAP_SDE` | SAP Sustainability Data Exchange | `32146-sap-sustainability-data-exchange_sd.svg` |
| `SAP_UITD` | UI Theme Designer | `32147-ui-theme-designer_sd.svg` |
| `SAP_CC` | Cloud Connector | `32148-cloud-connector_sd.svg` |
| `SAP_CDCM` | SAP Collaborative Demand and Capacity Management | `32149-sap-collaborative-demand-and-capacity-management_sd.svg` |
| `SAP_DF` | SAP Dynamic Forms | `32150-sap-dynamic-forms_sd.svg` |
| `SAP_WLS` | SAP Watch List Screening | `32152-sap-watch-list-screening_sd.svg` |
| `SAP_BAH` | SAP Business Accelerator Hub | `32153-sap-business-accelerator-hub_sd.svg` |
| `SAP_ABHE` | API Business Hub Enterprise | `32154-api-business-hub-enterprise_sd.svg` |
| `SAP_PKI` | SAP PKI Certificate Service | `32156-sap-pki-certificate-service_sd.svg` |
| `SAP_EXT` | Extensibility Service for SAP BTP | `33122-extensibility-service-for-SAP-BTP_sd.svg` |
| `SAP_BPC` | Business Process Model Connector for SAP Signavio | `33123-business-process-model-connector-for-sap-signavio-solutions_sd.svg` |
| `SAP_APM` | SAP Asset Performance Management | `33126-sap-asset-performance-management_sd.svg` |
| `SAP_PVS` | SAP Process Visibility Service | `33145-sap-process-visibility-service_sd.svg` |
| `SAP_CAP` | SAP Cloud Application Programming Model | `33146-sap-cloud-application-programming-model_sd.svg` |
| `SAP_PRM` | SAP Project and Resource Management | `33147-sap-project-and-resource-management_sd.svg` |
| `SAP_S4MT` | SAP S/4HANA for Microsoft Teams | `33149-sap-s4hana-for-microsoft-teams_sd.svg` |
| `SAP_DIV` | Decentralized Identity Verification | `33150-decentralized-identity-verification_sd.svg` |
| `SAP_BDC` | SAP Business Data Cloud | `34152-sap-business-data-cloud_sd.svg` |
| `SAP_AVR` | Application Vulnerability Report | `34154-application-vulnerability-report_sd.svg` |
| `SAP_LOG` | SAP Logistics Management | `34155-sap-logistics-management_sd.svg` |
| `SAP_ALM` | SAP Cloud ALM | `34156-sap-cloud-alm_sd.svg` |
| `SAP_BUILD` | SAP Build | `34157-sap-build_sd.svg` |
| `SAP_AFS` | Application Frontend Service | `34158-application-frontend-service_sd.svg` |
| `SAP_CDC` | Customer Data Cloud | `34159-customer-data-cloud_sd.svg` |
| `SAP_JST` | Joule Studio | `35158-joule studio_sd.svg` |

---

## Versioning

Icons are currently served from the `main` branch. For production diagrams where stability is critical, pin to a release tag:

```
https://cdn.jsdelivr.net/gh/rlabarcau/sap-btp-icons@v1.0.0/filename.svg
```

To create a tag:

```bash
git tag v1.0.0
git push origin v1.0.0
```

---

## Icon source

Icons are sourced from the [SAP BTP Solution Diagram Design Guidelines](https://sap.github.io/btp-solution-diagrams/) and follow the SAP Fiori Horizon 2023 visual language.

---

## License

SVG icons are property of SAP SE and subject to SAP's terms of use. This repository redistributes them solely for use in technical architecture documentation.
