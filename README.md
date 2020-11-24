# OpenAPI Presentation

This repository contains a small presentation about OpenAPI. It's purpose is to show a rather simplified view on why someone should consider using a API-Specification.

The presentation is written in german.

## Prerequisites

This presentation is written in markdown using [Marp](https://www.npmjs.com/package/@marp-team/marp-cli).
You can download the marp cli by executing:

```
pc> npm i @marp-team/marp-cli
```

### Development

You can start a development Server by executing:

```
pc> marp --server .
```

### Building

You can build a pdf(1) or a pptx(2) by executing one of the following commands:

```
pc> marp --pdf presentation.md
pc> marp --pptx presentation.md
```
