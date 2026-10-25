# helpdesk_mgmt

## Purpose

Helpdesk on Community: tickets (`helpdesk.ticket`) with stages, teams
(`helpdesk.ticket.team`), categories, tags (`helpdesk.ticket.tag`), channels,
priorities, portal access for customers and creation by mail alias.

## Notes for 20.0

- Migrated from 19.0 by the open OCA migration pull request; this fork carries it until
  upstream merges it.
- Model names differ from the Enterprise helpdesk: teams are `helpdesk.ticket.team`,
  tags `helpdesk.ticket.tag`; a ticket stores an anonymous requester in `partner_name`
  and `partner_email`.
- The pull request was written with AI assistance (stated in its description): review
  portal access checks and controllers with care.
