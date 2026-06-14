# Mindbody GraphQL Schema

## Overview

This conceptual GraphQL schema represents the Mindbody Public API v6 domain model for fitness, wellness, and beauty business management. Mindbody exposes a REST API at `https://api.mindbodyonline.com`; this schema translates that domain into GraphQL types suitable for client-facing integrations, aggregator platforms, and studio management tooling.

## Source

- REST API: https://developers.mindbodyonline.com/PublicDocumentation/V6
- API Reference: https://developers.mindbodyonline.com/ui/documentation/public-api
- GitHub: https://github.com/mindbody

## Authentication

Mindbody uses a combination of:

- `Api-Key` header: Mindbody-issued key per partner application
- `SiteId` header: target site identifier
- `Authorization: Bearer <token>`: OAuth 2.0 token from Mindbody Identity Service (`signin.mindbodyonline.com`) for staff- and client-scoped operations

## Domain Coverage

The schema covers these primary domains from the Mindbody v6 API:

| Domain | Key Types |
|---|---|
| Sites and Locations | Site, Location, Room, Equipment, FacilityUse |
| Staff | Staff, StaffMember, StaffAvailability, StaffPermission, StaffScheduleItem |
| Classes | Class, ClassDescription, ClassSchedule, ClassSignUp, Enrollment |
| Appointments | Appointment, AppointmentAvailability, SessionType, Service |
| Clients | Client, ClientProfile, ClientMembership, ClientVisit, ClientContactLog |
| Sales | Sale, SaleItem, Product, PricingOption, Contract, GiftCard, Package |
| Payroll | PayrollDetail, ClassPayDetail, StaffPayDetail |
| Scheduling | Schedule, Availability, BookingStatus, Waitlist |
| Identity | APIKey, UserToken, OAuthConfig |
| Loyalty | RewardProgram, LoyaltyEvent, PromoCode |

## Schema File

See `mindbody-schema.graphql` for the full type definitions.

## Types Count

The schema defines 65 named GraphQL types including:

- 45 object types
- 8 input types
- 7 enum types
- 5 scalar types

## Usage Notes

- `SiteId` context is implicit in a GraphQL server implementation — pass it as a header or embed in the JWT claim.
- Pagination uses `offset`/`limit` pattern consistent with the Mindbody REST API.
- Webhook event payloads (from the Mindbody Push API) map to the same underlying types defined here.
