# AI-Powered Customer & Purchase Explorer

**University of Utah | MSIS | IS 6490: AI for Business Process**

## Project Overview

This academic project explores how artificial intelligence can connect to enterprise systems through Model Context Protocol (MCP). I designed a read-only Customer & Purchase Explorer using Retool and a fictional HubSpot CRM to support natural-language customer and sales information queries.

## Technologies Used

- Retool AI App Builder
- HubSpot CRM
- Model Context Protocol (MCP)
- OAuth Authentication
- Generative AI

## Project Features

- Natural-language query interface
- Contacts and Deals/Purchases dashboard
- Fictional CRM records for testing
- Read-only access design
- Error handling for missing permissions
- Optional demonstration using sample data

## Architecture

User → Retool Application → HubSpot MCP Server → HubSpot CRM

## Implementation and Challenges

I created fictional customer and deal records in HubSpot, developed the Retool application interface, and configured OAuth connectivity through MCP.

During testing, the application encountered missing authorization scopes that prevented live CRM data retrieval. I documented the configuration, troubleshooting steps, and permission errors. My teaching assistant approved this documentation as an alternative to live retrieval.

## Business Value

The solution demonstrates how AI-assisted CRM exploration can reduce manual information searches and support customer service, sales, and business analysis.

## Responsible AI

The application was designed around least-privilege access, read-only permissions, data security, and human accountability. It does not intentionally expose tools that create, modify, or delete CRM records.

## Project Status

Academic prototype. Interface and OAuth configuration completed; live data retrieval remained blocked by authorization permissions.
