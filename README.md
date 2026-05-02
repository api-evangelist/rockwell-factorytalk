# Rockwell FactoryTalk

Rockwell FactoryTalk is a portfolio of software products by Rockwell Automation that supports the design, operation, and maintenance of industrial control systems and connected manufacturing operations. The portfolio includes FactoryTalk Optix (HMI/SCADA), FactoryTalk Hub (cloud identity and connectivity), FactoryTalk DataMosaix (Industrial DataOps), and Logix Designer integration tools.

**Website:** [https://www.rockwellautomation.com/en-us/](https://www.rockwellautomation.com/en-us/)

**Portal:** [https://www.rockwellautomation.com/en-us/products/software/factorytalk.html](https://www.rockwellautomation.com/en-us/products/software/factorytalk.html)

**Documentation:** [https://docs.rockwellautomation.com/en/products/software/factorytalk/](https://docs.rockwellautomation.com/en/products/software/factorytalk/)

**GitHub:** [https://github.com/rockwellautomation](https://github.com/rockwellautomation)

## APIs

### FactoryTalk Optix REST API
Programmatic access to HMI and SCADA visualization applications: tag read/write, alarm management, recipe management, and historical trend data retrieval.

- **Documentation:** [https://docs.rockwellautomation.com/en/products/software/factorytalk/factorytalk-optix.html](https://docs.rockwellautomation.com/en/products/software/factorytalk/factorytalk-optix.html)
- **OpenAPI:** [openapi/rockwell-factorytalk-optix-openapi.yml](openapi/rockwell-factorytalk-optix-openapi.yml)

### FactoryTalk Hub API
Cloud-based industrial event streaming via webhooks for tag value changes, alarm activations, and device connectivity notifications.

- **Documentation:** [https://www.rockwellautomation.com/en-us/products/software/factorytalk.html](https://www.rockwellautomation.com/en-us/products/software/factorytalk.html)
- **AsyncAPI:** [asyncapi/rockwell-factorytalk-realtime-asyncapi.yml](asyncapi/rockwell-factorytalk-realtime-asyncapi.yml)

### Logix Designer API
Programmatic access to Logix controller programming for CI/CD pipeline automation and version control integration.

- **GitHub:** [https://github.com/rockwellautomation/ra-logix-designer-vcs-custom-tools](https://github.com/rockwellautomation/ra-logix-designer-vcs-custom-tools)

## Artifacts

### OpenAPI Specs
| File | Description |
|------|-------------|
| [openapi/rockwell-factorytalk-optix-openapi.yml](openapi/rockwell-factorytalk-optix-openapi.yml) | FactoryTalk Optix REST API specification |

### AsyncAPI Specs
| File | Description |
|------|-------------|
| [asyncapi/rockwell-factorytalk-realtime-asyncapi.yml](asyncapi/rockwell-factorytalk-realtime-asyncapi.yml) | FactoryTalk Hub real-time events AsyncAPI |

### Rules
| File | Description |
|------|-------------|
| [rules/rockwell-factorytalk-rules.yml](rules/rockwell-factorytalk-rules.yml) | Spectral ruleset for FactoryTalk API conventions |

### Capabilities
| File | Description |
|------|-------------|
| [capabilities/industrial-operations.yaml](capabilities/industrial-operations.yaml) | Unified industrial operations workflow capability |
| [capabilities/shared/factorytalk-optix.yaml](capabilities/shared/factorytalk-optix.yaml) | FactoryTalk Optix shared capability definition |

### JSON Schema
| File | Description |
|------|-------------|
| [json-schema/rockwell-factorytalk-tag-schema.json](json-schema/rockwell-factorytalk-tag-schema.json) | FactoryTalk tag (process variable) schema |

### JSON Structure
| File | Description |
|------|-------------|
| [json-structure/rockwell-factorytalk-structure.json](json-structure/rockwell-factorytalk-structure.json) | FactoryTalk data structure documentation |

### JSON-LD
| File | Description |
|------|-------------|
| [json-ld/rockwell-factorytalk-context.jsonld](json-ld/rockwell-factorytalk-context.jsonld) | JSON-LD context for FactoryTalk data semantics |

### Examples
| File | Description |
|------|-------------|
| [examples/factorytalk-read-tag-values-example.json](examples/factorytalk-read-tag-values-example.json) | Read multiple tag values example |
| [examples/factorytalk-list-alarms-example.json](examples/factorytalk-list-alarms-example.json) | List active alarms example |

### Vocabulary
| File | Description |
|------|-------------|
| [vocabulary/rockwell-factorytalk-vocabulary.yml](vocabulary/rockwell-factorytalk-vocabulary.yml) | FactoryTalk domain vocabulary |

## Capabilities

### Industrial Operations (`capabilities/industrial-operations.yaml`)
Unified workflow for industrial operations monitoring and control using FactoryTalk Optix REST API. Enables plant operators, process engineers, and maintenance teams to:
- Monitor real-time process variable tags
- Manage alarms and acknowledgments
- Analyze historical trend data
- Apply production recipes

**REST Port:** 8080 | **MCP Port:** 9080 | **Tools:** 10

## Maintainers

**Email:** kin@apievangelist.com
