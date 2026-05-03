# SourceForge

SourceForge is a web-based platform for hosting, managing, and distributing open source software projects. Built on the Apache Allura platform, SourceForge provides project management tools including wiki, issue tracking, discussion forums, blogs, file releases, code repositories (Git, SVN, Mercurial), and a REST API for programmatic access to all project resources.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sourceforge/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Open Source, Developer Tools, Project Management, Code Hosting, Collaboration

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-02

## APIs

### SourceForge Allura API

The SourceForge REST API built on Apache Allura provides programmatic access to project management, wiki pages, issue trackers, discussion forums, blogs, and administrative functions including webhooks. All endpoints follow the `/rest/p/{project}/{tool}` path pattern.

**Human URL:** [https://sourceforge.net/p/forge/documentation/Allura%20API/](https://sourceforge.net/p/forge/documentation/Allura%20API/)
**Base URL:** `https://sourceforge.net`

#### Tags

Projects, Issues, Wiki, Discussions, Blogs, Webhooks

#### Properties

- [Documentation](https://sourceforge.net/p/forge/documentation/Allura%20API/)
- [Reference](https://sourceforge.net/api-docs/)
- [Release API](https://sourceforge.net/p/forge/documentation/Using%20the%20Release%20API/)
- [Download Stats API](https://sourceforge.net/p/forge/documentation/Download%20Stats%20API/)
- [OAuth](https://sourceforge.net/auth/oauth/)
- [OpenAPI](openapi/sourceforge-allura-openapi.yml)

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| SourceForge Allura API | [openapi/sourceforge-allura-openapi.yml](openapi/sourceforge-allura-openapi.yml) |

### Spectral Rules

| Ruleset | File |
|---------|------|
| SourceForge Rules | [rules/sourceforge-rules.yml](rules/sourceforge-rules.yml) |

### Naftiko Capabilities

**Shared Definitions:**

| API | File |
|-----|------|
| SourceForge Allura | [capabilities/shared/sourceforge-allura.yaml](capabilities/shared/sourceforge-allura.yaml) |

**Workflow Capabilities:**

| Workflow | File | Description |
|----------|------|-------------|
| Project Management | [capabilities/project-management.yaml](capabilities/project-management.yaml) | Open source project and issue management |

### JSON Schemas

| Schema | File |
|--------|------|
| Project | [json-schema/sourceforge-project-schema.json](json-schema/sourceforge-project-schema.json) |
| Ticket | [json-schema/sourceforge-ticket-schema.json](json-schema/sourceforge-ticket-schema.json) |

### JSON Structures

| Structure | File |
|-----------|------|
| Ticket | [json-structure/sourceforge-ticket-structure.json](json-structure/sourceforge-ticket-structure.json) |

### JSON-LD Contexts

| Context | File |
|---------|------|
| SourceForge | [json-ld/sourceforge-context.jsonld](json-ld/sourceforge-context.jsonld) |

### Examples

| Example | File |
|---------|------|
| List Tickets | [examples/sourceforge-list-tickets-example.json](examples/sourceforge-list-tickets-example.json) |

### Vocabulary

| Vocabulary | File |
|------------|------|
| SourceForge | [vocabulary/sourceforge-vocabulary.yml](vocabulary/sourceforge-vocabulary.yml) |

## Common Properties

- [Portal](https://sourceforge.net/p/forge/documentation/API/)
- [Documentation](https://sourceforge.net/p/forge/documentation/)
- [Website](https://sourceforge.net/)
- [API Documentation](https://sourceforge.net/api-docs/)
- [OAuth Portal](https://sourceforge.net/auth/oauth/)
- [Webhooks Documentation](https://forge-allura.apache.org/p/allura/wiki/Webhooks/)
- [Support](https://sourceforge.net/p/forge/site-support/)
- [Blog](https://sourceforge.net/blog/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
