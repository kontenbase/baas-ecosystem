# Backend as a Service (BaaS) ecosystem

Let's discuss around BaaS ecosystem. Why we need, when to use, what are the options, and how they are comparing.

> 🎉 Feel free to do some casual discussion and QA (question/answer)

## Introduction

Why we need it and when to use it?

- Frontend and backend are well differentiated.
- Experimentation for new projects/products/features.
- Limitation factors related to business as well.
  - Team of developers, so need to maximize team effort. Want to outsource cloud infrastructure management to the most experienced.
  - Timeline, so need to speed up backend development. Reduce time to market.
  - Budget, so need to cust cost. Save money and decrease the cost of development.
- Need a lot of backend features quickly.
  - Database management
  - Hosting and deployment
  - REST API or GraphQL API
  - User authentication and authorization
  - Email verification
  - Files/assets storage
  - Push notifications
  - Serverless function
  - Geolocation
  - Security settings
  - Social account integration
- Trade-offs
  - 3rd party code and responsibility
  - Vendor lock-in
  - Unexpected long term cost

## Definition and scope

What is exactly a BaaS?

- Backend that we can use immediately without any prior development.
- Can expose the REST API or GraphQL.
- Can be cloud-hosted (available instantly) or self-hosted (usually open source or on-premise).
- Comparable to Headless CMS (Content Management System).

### References

- https://www.cloudflare.com/learning/serverless/glossary/backend-as-a-service-baas
- https://blog.back4app.com/backend-as-a-service-baas
- https://www.okta.com/identity-101/baas-backend-as-a-service
- https://bejamas.io/discovery/headless-cms

## API BaaS

Evaluating most popular BaaS options.

- [Firebase](https://firebase.google.com)
- [Supabase](https://supabase.com)
- [Nhost](https://nhost.io)
- [Strapi](https://strapi.io)
- [Payload CMS](https://payloadcms.com)
- [Hygraph](https://hygraph.com)
- [Kontenbase](https://kontenbase.com)
  - Kontenbase v1
  - Kontenbase v2 preview / Microgen v3

## Internal Tool BaaS

- [Retool](https://retool.com)
- [Budibase](https://budibase.com)
- [Metabase](https://metabase.com)
  - A backend written in Clojure which contains a REST API
