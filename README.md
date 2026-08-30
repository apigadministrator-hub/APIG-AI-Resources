# APIG AI Resources

This repository contains the canonical AI resource files for the **AP Investigative Group (APIG)** infrastructure project.

## Purpose

These resources define the architectural framework, specifications, workflows, rules, relationships, and decisions used to design, develop, review, and maintain the APIG system.

The repository is intended to provide AI systems and authorized human collaborators with a structured, persistent source of project requirements and institutional knowledge.

## Start Here

AI systems should begin with:

**`START-HERE.md`**

The START-HERE document explains the repository structure, identifies the appropriate resource areas, and directs an AI to the documents it should consult for a particular task.

## Repository Structure

### Specifications

The `Specifications/` folder contains the individual APIG specifications that define system requirements and architectural rules.

### PDF Resources

The `PDF-Resources/` folder contains source PDFs and other reference materials used during development and research.

Additional folders may be added as the project develops.

## Core Architectural Principle

The APIG website is a presentation layer over a structured database.

People, agencies, organizations, positions, meetings, documents, articles, photos, locations, sources, and relationships are represented as persistent entities with appropriate identifiers, histories, provenance, and relationships.

AI systems may assist with extraction, classification, matching, research, organization, and identification of gaps. Substantive publication and other consequential actions remain subject to the applicable human-review and authorization requirements defined by the project specifications.

## Repository Rules

1. `START-HERE.md` is the primary routing document for AI systems entering this repository.
2. Specifications should be treated as project requirements, not casual notes.
3. New specifications or resource categories should be added without unnecessarily duplicating existing requirements.
4. Changes to architectural requirements should be documented and reconciled with related specifications.
5. Conflicting or duplicated requirements should be identified and resolved rather than silently ignored.
6. Historical decisions and important project reasoning should be preserved in the appropriate project records.
7. The repository structure may evolve as APIG develops.

## Project Scope

The initial development target is the Illinois foundation, with **Wayne County** serving as the primary working example.

The architecture is intended to support expansion to additional jurisdictions without requiring a fundamental redesign of the underlying system.

## Status

This repository is an active development resource. Specifications and supporting materials may be revised as the APIG architecture is developed, tested, reviewed, and refined.
