# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

This is a Mintlify documentation site. Use these commands for development:

- **Local development**: `mint dev` - Preview docs locally at `http://localhost:3000`
- **Update CLI**: `mint update` - Ensure you have the latest Mintlify CLI version
- **Install CLI**: `npm i -g mint` - Install Mintlify CLI globally if not present

## Project Architecture

### Documentation Structure
- **Main config**: `docs.json` - Contains site configuration, navigation structure, and theming
- **Content**: `.mdx` files throughout the repository contain the actual documentation content
- **Navigation**: Two main tabs defined in `docs.json`:
  - "Ordinary Objects" - Core product documentation
  - "Learn" - Tutorials and educational content

### Key Directories
- `/editor/` - Editor-specific documentation (viewport navigation, keyboard shortcuts, assets)
- `/mirror/` - Platform-specific Mirror app documentation (Vision Pro, Quest, iOS)
- `/portal/` - Portal app documentation (team management)
- `/tutorials/` - Educational content organized by topic
- `/images/` - Static assets and screenshots
- `/logo/` - Brand assets (light/dark mode variants)

### Content Organization
The site uses a hierarchical structure defined in `docs.json` navigation:
- Get started section covers onboarding and basic setup
- Editor section covers core functionality
- Mirror section covers platform-specific features  
- Portal section covers collaboration features
- Learn tab provides tutorials and deep-dive content

### Key Features
- Dark/light mode support with separate logo variants
- Discord integration for community support
- External links to the main application portal
- Contextual toolbar with AI integrations (ChatGPT, Claude, Cursor, etc.)

## Important Context
This is documentation for "Ordinary Objects", a spatial computing app design tool. The documentation covers:
- Editor workflows for creating spatial prototypes
- Mirror apps for different platforms (Vision Pro, Quest, iOS)
- Portal for team management and collaboration
- Asset handling and animation workflows

When editing content, maintain consistency with the spatial computing and design tool context.