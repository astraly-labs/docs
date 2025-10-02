# Deployment Guide

This monorepo contains two separate Mintlify documentation sites. Each site needs to be deployed separately.

## Mintlify Dashboard Setup

You'll need to configure two separate deployments in your Mintlify dashboard:

### 1. Pragma Oracle Documentation

**Configuration:**
- **Site Name**: Pragma Oracle
- **Repository**: Your GitHub repository URL
- **Branch**: `main` (or your default branch)
- **Root Directory**: `pragma`
- **Build Command**: (Leave default)
- **Output Directory**: (Leave default)

### 2. 0D Finance Documentation

**Configuration:**
- **Site Name**: 0D Finance
- **Repository**: Your GitHub repository URL
- **Branch**: `main` (or your default branch)
- **Root Directory**: `0d-finance`
- **Build Command**: (Leave default)
- **Output Directory**: (Leave default)

## Local Development

### Testing Pragma Docs
```bash
cd pragma
mintlify dev
```

### Testing 0D Finance Docs
```bash
cd 0d-finance
mintlify dev
```

## Custom Domains

In the Mintlify dashboard, you can configure custom domains for each site:
- Pragma: e.g., `docs.pragma.build`
- 0D Finance: e.g., `docs.0d.finance`

## Deployment Process

1. Push changes to your repository
2. Mintlify will automatically build and deploy both sites based on their root directories
3. Each site deploys independently - changes to `pragma/` only redeploy Pragma docs, changes to `0d-finance/` only redeploy 0D Finance docs

## Notes

- Both sites share the same Git repository but are completely separate Mintlify projects
- Each has its own `docs.json` configuration
- API specifications are stored in each project's `open-apis/` directory
- Assets (logos, favicons) are duplicated in each project for independence
