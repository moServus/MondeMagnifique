# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**Mein Wien** (My Vienna) is a search project for places to travel to Vienna, Austria. Without any source code just MD files for documentation purposes.

## Setup & Development

The project directory structure is as follows:
```
README.md
./wikiViennaAT
```
## Important Patterns & Conventions

- ViennaDE.md a growing list to relevant WikiPedia links in German
- Each WikiPedia link will be analysed with the / command "abstract"
- Ask in a prompt how this abstract should be called
- Write an abstract for tourists, history and fun facts
- After the main headline of the abstract MD add the Wikipedia link with the emoticon for each lingo
- The summary of each abstract in README.md will be generate by the / command "readme"

# Custom Commands

## /abstract
Summarize the current WikiPedia MD.
1. Ask in a prompt for the name of the abstract MD file
2. Download the WikiPedia Link into wikiSources
