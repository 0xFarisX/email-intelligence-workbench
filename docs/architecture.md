# Architecture

The system uses a local SQLite evidence store behind a Python HTTP service and a
vanilla JavaScript workspace. Read-only Gmail indexing, structured form imports
and project enrichment feed unified client profiles. Research jobs attach cited
findings to those profiles. Campaign and email-studio workflows consume only
eligible, reviewed profiles and terminate at Gmail draft creation.

Key boundaries are separate Gmail read/compose authorization, local storage,
manual synchronization and explicit approval before drafting.

