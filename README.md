# Focal Agent Lab

[![CI](https://github.com/sjweiler/focal-agent-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/sjweiler/focal-agent-lab/actions/workflows/ci.yml)
[![CodeQL](https://github.com/sjweiler/focal-agent-lab/actions/workflows/codeql.yml/badge.svg)](https://github.com/sjweiler/focal-agent-lab/actions/workflows/codeql.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.12%20%7C%203.13-blue.svg)](pyproject.toml)

Experimental AI agent framework for FocalDesk.

## Overview

Focal Agent Lab is a research and prototyping project for evaluating
agentic AI frameworks such as LangChain, LangGraph, and CrewAI.

The goal is to prototype new capabilities before integrating them into
FocalDesk through its IPC interface.

## Goals

- Evaluate LangChain
- Evaluate LangGraph
- Evaluate LLamaIndex
- Evaluate LangSmith
- Evaluate CrewAI
- Experiment with local and cloud LLMs
- Prototype tool calling
- Prototype multi-agent workflows
- Develop safe desktop automation patterns

## Planned Features

- Local LLM support (Ollama)
- Cloud model support
- Tool registry
- Memory
- Permission-based desktop actions
- IPC integration with FocalDesk

## Relationship to FocalDesk

This project is intentionally separate from FocalDesk.

Successful experiments may later be integrated into FocalDesk through
its existing IPC architecture.

## Status

🚧 Early development
