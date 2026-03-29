# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This repo holds reusable AI agent configuration — primarily Claude Code skills — that can be shared across multiple projects. Skills defined here are things the user has found valuable in more than one context.

## Structure

Skills live under `skills/<skill-name>/SKILL.md`. Each skill file uses Claude Code's standard frontmatter (`name`, `description`) followed by the prompt. The goal is a single source of truth for skill definitions, symlinked or copied into individual project `.claude/skills/` directories.

## Working in This Repo

When adding or modifying a skill:
- Focus on reusability: skills here must generalize across projects, not encode project-specific logic
- Keep skill prompts concise and action-oriented; avoid verbose preamble
- If a skill only makes sense in one project, it belongs in that project's `.claude/` directory instead
