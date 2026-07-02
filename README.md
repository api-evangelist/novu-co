# Novu (novu-co)

Novu is open-source notification infrastructure that sends multi-channel messages - email, SMS, push, chat, and an in-app Inbox - from a single workflow trigger. One event API call fans a notification out across the channels defined in a workflow, with subscriber management, topics, layouts, digest/aggregation, 55+ provider integrations, and a real-time embeddable Inbox notification center powered by a WebSocket connection. Novu is self-hostable (MIT) and also available as Novu Cloud, with US (`api.novu.co`) and EU (`eu.api.novu.co`) regions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/novu-co/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/novu-co/refs/heads/main/apis.yml)

## Tags

- Notifications
- Multi-Channel
- Email
- SMS
- Push
- Chat
- In-App Inbox
- Open Source
- WebSocket

## Timestamps

- **Created:** 2026-07-02
- **Modified:** 2026-07-02

## APIs

### Novu Events API

Trigger notification workflows for one or many subscribers. A single event fans out across the channels defined in a workflow - in-app, email, SMS, push, and chat - with bulk trigger, broadcast to all subscribers, and cancel by transactionId.

- **Human URL:** [https://docs.novu.co/api-reference/events/trigger-event](https://docs.novu.co/api-reference/events/trigger-event)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Events
- Trigger
- Workflows

#### Properties

- [Documentation](https://docs.novu.co/api-reference/overview)
- [API Reference](https://docs.novu.co/api-reference/events/trigger-event)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Subscribers API

Create, retrieve, update, delete, and bulk-manage subscribers - the recipients of notifications - along with their channel credentials, online status, and subscriptions.

- **Human URL:** [https://docs.novu.co/api-reference/subscribers/create-a-subscriber](https://docs.novu.co/api-reference/subscribers/create-a-subscriber)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Subscribers
- Recipients
- CRM

#### Properties

- [API Reference](https://docs.novu.co/api-reference/subscribers/create-a-subscriber)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Topics API

Group subscribers into topics addressed by a topic key, then trigger a single event to notify the whole audience. Manage topic subscriptions - add, list, check, and remove subscribers.

- **Human URL:** [https://docs.novu.co/api-reference/topics/topic-creation](https://docs.novu.co/api-reference/topics/topic-creation)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Topics
- Audiences
- Broadcast

#### Properties

- [API Reference](https://docs.novu.co/api-reference/topics/topic-creation)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Inbox API

The in-app notification center feed for a subscriber - list feed items, read unseen/unread counts, and mark, read, unread, seen, archive, snooze, or delete notifications. Backs the embeddable Inbox component whose real-time updates arrive over the WebSocket described in the companion AsyncAPI document.

- **Human URL:** [https://docs.novu.co/platform/inbox/overview](https://docs.novu.co/platform/inbox/overview)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Inbox
- In-App
- Notification Center

#### Properties

- [Documentation](https://docs.novu.co/platform/inbox/overview)
- [API Reference](https://docs.novu.co/api-reference/subscribers/get-in-app-notification-feed-for-a-particular-subscriber)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/novu-co-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Messages API

List the individual channel messages generated by workflow executions, filter by channel/subscriber/transactionId, and delete messages individually or by transactionId.

- **Human URL:** [https://docs.novu.co/api-reference/messages/list-all-messages](https://docs.novu.co/api-reference/messages/list-all-messages)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Messages
- Delivery
- History

#### Properties

- [API Reference](https://docs.novu.co/api-reference/messages/list-all-messages)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Notifications API

Query the activity feed of triggered workflow executions (events) - list with filters and retrieve a single notification/event record with its per-step execution outcome for observability and debugging.

- **Human URL:** [https://docs.novu.co/api-reference/notifications/list-all-events](https://docs.novu.co/api-reference/notifications/list-all-events)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Notifications
- Activity Feed
- Analytics

#### Properties

- [API Reference](https://docs.novu.co/api-reference/notifications/list-all-events)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Workflows API

Create, list, retrieve, update, patch, delete, and sync notification workflows (formerly notification templates) - the multi-channel step definitions (in-app, email, SMS, push, chat, digest, delay) that a trigger event executes. Includes per-step retrieval and preview.

- **Human URL:** [https://docs.novu.co/api-reference/workflows/create-a-workflow](https://docs.novu.co/api-reference/workflows/create-a-workflow)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Workflows
- Notification Templates
- Orchestration

#### Properties

- [API Reference](https://docs.novu.co/api-reference/workflows/create-a-workflow)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Integrations API

Configure the delivery providers behind each channel - create, list (all and active), retrieve, update, and delete integrations across 55+ providers (SendGrid, Twilio, FCM, APNs, Slack, and more), set a primary integration, and auto-configure webhooks.

- **Human URL:** [https://docs.novu.co/api-reference/integrations/list-all-integrations](https://docs.novu.co/api-reference/integrations/list-all-integrations)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Integrations
- Providers
- Channels

#### Properties

- [API Reference](https://docs.novu.co/api-reference/integrations/list-all-integrations)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Layouts API

Manage reusable email layouts that wrap notification content - create, list, retrieve, update, delete, duplicate, preview, and inspect usage of the shared header/footer wrappers applied to email steps.

- **Human URL:** [https://docs.novu.co/api-reference/layouts/layout-creation](https://docs.novu.co/api-reference/layouts/layout-creation)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Layouts
- Email
- Templates

#### Properties

- [API Reference](https://docs.novu.co/api-reference/layouts/layout-creation)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Subscriber Preferences API

Read and update per-subscriber notification preferences - which workflows and channels a subscriber is opted into - including bulk preference updates that let end users control what they receive.

- **Human URL:** [https://docs.novu.co/api-reference/subscribers/get-subscriber-preferences](https://docs.novu.co/api-reference/subscribers/get-subscriber-preferences)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Preferences
- Opt-Out
- Channels

#### Properties

- [API Reference](https://docs.novu.co/api-reference/subscribers/get-subscriber-preferences)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Environments API

Manage Novu environments (Development, Production, and more) and promote resources between them - create, list, update, delete environments, list tags, compare, and publish changes to a target environment.

- **Human URL:** [https://docs.novu.co/api-reference/environments/list-all-environments](https://docs.novu.co/api-reference/environments/list-all-environments)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Environments
- Promotion
- Configuration

#### Properties

- [API Reference](https://docs.novu.co/api-reference/environments/list-all-environments)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Translations API

Localize notification content across locales - create, retrieve, and delete translations per resource and locale, manage translation groups, and import or upload master translation JSON and files.

- **Human URL:** [https://docs.novu.co/api-reference/overview](https://docs.novu.co/api-reference/overview)
- **Base URL:** `https://api.novu.co/v1`

#### Tags

- Translations
- Localization
- i18n

#### Properties

- [API Reference](https://docs.novu.co/api-reference/overview)
- [OpenAPI](openapi/novu-co-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novu-co.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novu-co.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novu Inbox Realtime API

Real-time WebSocket (Socket.IO) surface that pushes live Inbox updates to browser and mobile clients - `notification_received`, `unseen_count_changed`, and `unread_count_changed` events - authenticated by subscriberId, applicationIdentifier, and an HMAC subscriber hash. Powers the embeddable Inbox component's live bell, counts, and feed.

- **Human URL:** [https://docs.novu.co/platform/inbox/overview](https://docs.novu.co/platform/inbox/overview)
- **Base URL:** `https://ws.novu.co`

#### Tags

- WebSocket
- Realtime
- Inbox
- Socket.IO

#### Properties

- [Documentation](https://docs.novu.co/platform/inbox/overview)
- [AsyncAPI](asyncapi/novu-co-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/novuhq)
- [LinkedIn](https://www.linkedin.com/company/novuco)
- [Website](https://novu.co/)
- [Documentation](https://docs.novu.co)
- [Plans](plans/novu-co-plans-pricing.yml)
- [Rate Limits](rate-limits/novu-co-rate-limits.yml)
- [Fin Ops](finops/novu-co-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
