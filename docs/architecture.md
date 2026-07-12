# Architecture

RelayWorks Document Processing Kit is presented as a self-hosted developer product built around a FastAPI backend and a Next.js frontend.

## Public architecture summary

```text
PDF upload
  -> local processing workflow
  -> generated document outputs
  -> review workspace
  -> downloadable package
```

## Backend

The paid product is described as using FastAPI for the API layer, background conversion workflow, job status, output generation, and download endpoints.

## Frontend

The paid product is described as using Next.js and React for the document workspace, goal selection, processing status, output review, and package download flow.

## Processing model

RelayWorks is local and self-hosted. Buyers run the backend and frontend in their own environment, keeping PDFs and generated outputs under their own control.

## Repository boundary

This public repository does not include backend modules, frontend source files, parser logic, export logic, job logic, or customer packages. It only documents the product for evaluation.
